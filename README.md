# Cadastro de Aluno 

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN)


## Resumo do projeto

Aplicação Java utilizando Maven e MongoDB

alura = student
principal = main


https://github.com/mongodb/mongo-java-driver

pom.xml:

<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>
  <groupId>br.com.student</groupId>
  <artifactId>JavaMongo</artifactId>
  <version>0.0.1-SNAPSHOT</version>
  <dependencies>
  <dependency>
        <groupId>org.mongodb</groupId>
        <artifactId>mongodb-driver-sync</artifactId>
        <version>4.7.1</version>
    </dependency>
  </dependencies>
</project>


Main.java:

import com.mongodb.MongoClient;

public class Main {
	public static void main(String[] args) {
		MongoClient client = new MongoClient();
	}
}