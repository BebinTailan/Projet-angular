# Projet `Angular` / `demo`

Ce dépôt contient deux parties principales :

- **Backend Java (Spring Boot)** dans le dossier `demo/`
- **Frontend Angular** dans le dossier `front-books/`

---

## ⚙️ Backend (`demo/`)

Le backend est un projet Spring Boot (Java) qui expose une API REST (ex : `/api/books`).

### Installation

Il faut mvn npm et @angular.cli :

```sh

cd demo
.\mvnw.cmd spring-boot:run

puis pour lancer le front c'est:

cd front-books

dans un nouveau terminal
Puis ouvrir http://localhost:4200

npm ng serve
