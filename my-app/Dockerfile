FROM anapsix/alpine-java
MAINTAINER my-app 
RUN apk --no-cache add curl
RUN apk --no-cache add unzip
RUN curl  https://github.com/aviramboo/maven-hello-world/suites/3382002240/artifacts/79713671/github-actions-artifact.zip -O -J -L
RUN pwd && ls -la
RUN unzip github-actions-artifact.zip 
CMD ["java","-jar","my-app-1.0.0-SNAPSHOT.jar"]


