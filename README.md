# Projet Gestion de Bibliotheque
Ce projet est une application web complete composee d'un backend Spring Boot et d'un frontend Angular.
Il suit une architecture de separation claire entre le client et le serveur.
Prerequis:
Java JDK 17 ou superieur 
Node.js
Angular CLI (installation : npm install -g @angular/cli)

# Installation et Lancement1. 
Backend (Spring Boot)Le backend est situe dans le dossier demo/. 
Il utilise Spring Data JPA pour la gestion des donnees et expose une API REST.Bash# Aller dans le dossier backend

cd demo

# Installer les dependances et compiler le projet

./mvnw clean install

# Lancer l'application

./mvnw spring-boot:run
Le serveur sera accessible sur : http://localhost:80802. Frontend (Angular)Le frontend est situe dans le dossier front-books/. Il s'agit d'une Single Page Application (SPA).Bash# Aller dans le dossier frontend
cd front-books

# Installer les dependances Node.js

npm install

# Lancer le serveur de developpement

npx ng serve

L'interface sera accessible sur : http://localhost:4200

# Requete http:

GET /api/books : Recupere la liste des livres.

POST /api/books : Cree un nouveau livre.

PUT /api/books/{id} : Met a jour un livre existant.

DELETE /api/books/{id} : Supprime un livre.
