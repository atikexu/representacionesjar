# Usa una imagen de Java 17 (puedes cambiar según tu versión)
FROM eclipse-temurin:17-jdk

# Establece el directorio de trabajo
WORKDIR /app

# Copia tu jar al contenedor
COPY miapp/representacionesdelsur-1.0.0-SNAPSHOT.jar .

# Puerto expuesto por Render (Render asigna $PORT dinámicamente)
ENV PORT 8080

# Comando para ejecutar tu app
CMD ["java", "-jar", "representacionesdelsur-1.0.0-SNAPSHOT.jar"]