# spring-boot-crud

Students CRUD made in Spring Boot using Java 17. I used PostgreSQL database and JPA to map the only entity named Student.
Maven was used to manage dependencies.

## Layers

- Controller: Manage HTTP requests.
- Service: Implements the bussiness logic and throws exceptions.
- Repository: Access the data.
- Entities: just one class named Student. It also has StundentConfig in order to create 2 objects when the server sets up, thats because I used this configuration: spring.jpa.hibernate.ddl-auto=create-drop.
