# Use a imagem base do OpenJDK 17
FROM openjdk:17-jdk-slim

# Define o diretório de trabalho dentro do container
WORKDIR /app

# Copie o JAR gerado pelo Maven para o container
COPY target/demo-0.0.1-SNAPSHOT.jar app.jar

# Define o comando para executar a aplicação
ENTRYPOINT ["java","-jar","app.jar"]