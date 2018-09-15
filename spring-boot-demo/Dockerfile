FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
VOLUME /log
ADD target/spring-boot-demo*.jar app.jar
EXPOSE 8080
ENTRYPOINT [ "sh", "-c", "java -jar /app.jar" ]