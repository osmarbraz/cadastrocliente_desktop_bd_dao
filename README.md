# Sistema de Cadastro de Clientes para Desktop em Banco de Dados Oracle ou MySQL utilizando o padr�o Abstract Factory.
 - Este programa possui diversas classes organizada nos pacotes vis�o, modelo e dao.<br>
 - 
 - Toda itera��o com banco de dados � tratada diretamente pelo DAO(Data Access Object).<br>
 - Os dados de configura��o(Servidor, Database, Usuario, Senha) da integra��o do java com o banco de dados est�o no arquivo src/DadosBanco.java.<br>
 - Crie o banco de dados antes de executar o projeto, as especifica��es das tabelas est�o no arquivo banco_mysql.sql e banco_oracle.sql.<br>
 - A pasta src cont�m os fontes do projeto e na pasta  lib o driver jdbc para Oracle e MySQL.<br>