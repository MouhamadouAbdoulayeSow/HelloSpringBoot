# HelloSpringBoot – Employee REST API

**Domains:** Software

Spring Boot exercise from the DIC2 course at École Polytechnique de Thiès: a REST API for employees and departments.

## Features
- JPA entities with inheritance: `Personne`, `Employe`, `Departement`.
- Repositories, a service layer and a REST controller with read and update endpoints.
- Data seeding at start-up.
- Spring profiles for `dev`, `ept` and `tests`.

## Stack
Java · Spring Boot · Spring Data JPA · MySQL · Lombok · Maven

## Run locally
```bash
./mvnw spring-boot:run -Dspring-boot.run.profiles=dev
```
