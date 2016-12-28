# Projeto Alfa Grupo 3 - Configuração e Execução
# GitHub
  - https://github.com/lucascorrei4/alfa-grupo-3.git

# Java Development Kit
  - Java 1.7: http://www.oracle.com/technetwork/pt/java/javase/downloads/jdk-7-netbeans-download-432126.html

# Instale o Servidor MySQL e baixe o MySQL Workbench 6.3
  - Server: http://dev.mysql.com/downloads/mysql/
  - MySQL Workbench: http://dev.mysql.com/downloads/workbench/6.3.html
  - Configure um usuário e um banco com as propriedades:

  - Usuário: root
  - Senha: 123456
  - Banco: grupo-3

# Configure variáveis de ambiente. Ex.:
  - JAVA_HOME: C:\Program Files\Java\jdk1.7.0_79
  - PLAY_FRAMEWORK: C:\Users\Lucas\Google Drive\Lucas\dev\play1.2.4
  - CATALINA_HOME = C:\Users\Lucas\Google Drive\Lucas\dev\apache-tomcat-7.0.42 
  - IMPORTANTE: Concatene tudo na variável Path: Ex.: %JAVA_HOME%\bin;%PLAY_FRAMEWORK%;%CATALINA_HOME%\bin;

# Baixe o Eclipse
  - http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/mars1

# Configuração Play Framework 1.2.4
  - Download: https://downloads.typesafe.com/releases/play-1.2.4.zip
  - Crie uma pasta /dev e descompacte o [play1.2.4] dentro dela
  - Dentro de /dev crie uma pasta /playapps dentro
  - Clone o projeto alfa-grupo-3.git dentro de /playapps
  - Ex.: /dev/playapps/alfa-grupo-3/

# Run alfa-grupo-3
  - Acesse a pasta /dev/playapps/alfa-grupo-3/ e digite os comandos:
  - play clean;
  - play deps;
  - play eclipsify (Gera o .project para abrir o projeto no Eclipse);
  - play run;
  - Se tudo estiver OK, acesse http://localhost:9000/ no navegador

# Abrir o projeto no Eclipse
  - File > Import > Existing projects into workspace