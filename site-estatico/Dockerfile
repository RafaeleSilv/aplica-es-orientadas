# Usar uma imagem base do Java 11
FROM openjdk:21-jre-slim

# Definir o diretório de trabalho dentro do contêiner
WORKDIR /app

# Copiar o arquivo JAR gerado para dentro do contêiner
COPY target/*.jar app.jar

# Informar ao contêiner qual comando deve ser executado para rodar a aplicação
ENTRYPOINT ["java", "-jar", "app.jar"]
