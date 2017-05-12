FROM maven

RUN git clone https://github.com/breddy604/devopstraining.git

RUN mvn clean package -f /devopstraining/LibraryApp/pom.xml

CMD ["java","-jar","/devopstraining/LibraryApp/target/library-app-fat.jar"]
