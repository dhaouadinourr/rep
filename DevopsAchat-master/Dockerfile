# Utilisez une image de base adaptée à Java
FROM openjdk:11-jre-slim

# Définissez le répertoire de travail dans le conteneur
WORKDIR /app

# Copiez le fichier JAR de votre application Spring Boot dans le conteneur
COPY target/achat-1.0.jar /app/achat-1.0.jar

# Exposez le port sur lequel votre application Spring Boot écoute (par défaut 8080)
EXPOSE 8089

# Commande pour exécuter l'application Spring Boot
CMD ["java", "-jar", "achat-1.0.jar"]
