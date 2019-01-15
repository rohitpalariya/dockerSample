FROM openjdk:8
mvn clean install
ADD target/ForexService.jar ForexService.jar
EXPOSE 8000
ENTRYPOINT ["java", "-jar", "ForexService.jar"] 
