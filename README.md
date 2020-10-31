# on7-porto-s12-db


<h1>MongoDB</h1>

<center><img src="./image1.jpg" width="400" height="400"></center>

<h2>Introdução ao Banco de Dados MongoDB</h2>

Diferente dos Bancos de dados tradicionais que seguem o modelo relacional, o MongoDB é um Banco de Dados Orientado a Documentos, utilizando conceito de dados e documentos autocontidos e auto descritivos, implicando que o documento em si já define como ele deve ser apresentado e qual é o significado dos dados armazenados na sua estrutura. Tem como característica conter todas as informações importantes em um único documento, ser livre de esquemas, possuir identificadores únicos universais (UUID), possibilitar a consulta de documentos através de métodos avançados de agrupamento e filtragem (MapReduce) e permitir redundância e inconsistência.

<img src="./imagens2.jpg" width="200" height="150">


Este Banco de Dados tem como característica ser código-fonte aberto licenciado pela GNU AGPL (Affero General Public License), possuir alta performance, não possuir esquemas, ser escrito em C++, multiplataforma e ser formado por um conjunto de aplicativos JSON. Apesar do projeto MongoDB ter iniciado em 2007 o Banco de Dados somente foi concluído em 2009 lançando assim a primeira versão do MongoDB. Diversas linguagens e plataforma já possuem drivers para o MongoDB, entre elas destacam-se: C, C#, C++, Haskell, Java, JavaScript, Perl, PHP, Python, Ruby e Scala. Além disso, o MongoDB possui binários para diversas plataformas como Windows, Mac OS X, Linux e Solaris.

<h2>Principais Comandos</h2>

**use nomeDoBanco** Para criar um banco de dados novo
**db.current** Mostra o banco de dados atual
**show databases** Listar todos os bancos de dados
**db.createCollection("collectionNomedaColeção")** Cria uma coleção
**show collections** Lista todas coleções
**db.nomeDaColeção.find()** Busca todos os registros de uma coleção
**db.nomeDaCollection.findOne()** Retorna apenas um registro
**db.nomeDaCollection.insertOne({Atributos})** Inclui o registro dentro de uma coleção
**db.nomeDaCollection.insertMany()** Inclui vários registros
**db.collection.drop()** Apagar uma coleção
**db.dropDatabase()** Remover um banco de dados
**db.nomeDaColeção.find().pretty()** Retorna a coleção com o formato mais legível, do tipo JSON