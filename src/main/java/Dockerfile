FROM ubuntu:latest
LABEL authors="kamoh"
EXPOSE 8080
ADD target/docker-jenkins-intergration-sample.jar docker-jenkins-intergration-sampler.jar
ENTRYPOINT ["java", "-jar","/docker-jenkins-intergration-sample.jar"]