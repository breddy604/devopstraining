FROM maven

COPY ./../LibraryApp /

RUN mvn clean package -f /LibraryApp/pom.xml

CMD ["java","-jar","/devopstraining/LibraryApp/target/library-app-fat.jar"]
