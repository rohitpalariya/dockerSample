FROM openjdk:8
RUN apt-get install mvn
RUN mvn clean install
ADD target/ForexService.jar ForexService.jar
EXPOSE 8000
ENTRYPOINT ["java", "-jar", "ForexService.jar"] 
