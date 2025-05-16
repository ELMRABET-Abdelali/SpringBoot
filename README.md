# SpringBoot
n'oubli pas de telecharger la bonne version de java JDK celle de pom.xml : ex JDK17 

il faut voir la version utilisé par defaut dans le terminal avec : java -version

pour mettre a jour la version par defaut : setx JAVA_HOME "C:\Program Files\Java\jdk-17" cas de JDK17

aussi voir variables d'envirenements dans windows pour enlever les anciens path de jdk et de mettre %JAVA_HOME%\bin en haut dans variable utilisateur et systeme !!!

commande a mettre dans le terminal pour executer maven :
.\mvnw clean compile

mvnw  [default] compile -> test -> package -> verify

on peut lancer l'application après compilation

.\mvnw clean package 

cd target 

java -jar myCompiledFile.jar

on peut aussi executer l'application via spring boot plugin:

.\mvnw spring-boot:run






