# config-server

Application.properties : contains the git repo uri which contains config files (here we used same repo)
* @EnableConfigServer : annotation Plays vital role

run the app with below commands :

* $cd config-server
* $mvn package
* $java -jar target/config-server-0.0.1-SNAPSHOT.jar


Browse : http://localhost:8888/config-client-production.properties


# SECURITY :
TBD

