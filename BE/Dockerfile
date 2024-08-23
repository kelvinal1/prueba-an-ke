# Usa una imagen base de OpenJDK para Spring Boot
FROM openjdk:17.0.1-jdk-slim

# Establece el directorio de trabajo
WORKDIR /app

# Copia el archivo JAR de la aplicación al contenedor
COPY demo.jar /app/demo.jar

# Expone el puerto en el que la aplicación escuchará (opcional, según el puerto que use tu aplicación)
EXPOSE 8080

# Comando para iniciar la aplicación, usando las variables de entorno
ENTRYPOINT ["java", "-jar", "/app/demo.jar"]





