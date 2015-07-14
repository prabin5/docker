# docker
Dockerfile repo

Build:
docker build -t milkyway/java-hello-world 

Run:
docker run milkyway/java-hello-world

Docker Hub:
https://registry.hub.docker.com/u/milkyway/java-hello-world/

Build:
docker build -t milkyway/tomcat7-jre7 .

Run: (In detached mode)
docker run -it -d --name tomcat7 -p 8080:8080 milkyway/tomcat7-jre7

Docker Hub:
https://registry.hub.docker.com/u/milkyway/tomcat7-jre7/
