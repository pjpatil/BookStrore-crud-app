## BookStrore-crud-app
using Spring boot and React Js.

Folder Structure

#code \
BooksStore/  \
├── backend/ \
│   ├── src/ \
│   │   ├── main/ \
│   │   │   ├── java/ \
│   │   │   │   └── com/ \
│   │   │   │       └── bookstore/ \
│   │   │   │           ├── BooksStoreApplication.java \
│   │   │   │           ├── controller/ \
│   │   │   │           ├── model/ \
│   │   │   │           ├── repository/ \
│   │   │   │           └── service/ \
│   │   │   └── resources/  \
│   │   │       ├── application.properties \
│   │   │       └── static/ \
│   │   └── test/ \
│   │       └── java/ \
│   ├── pom.xml \
│   └── README.md \
│ \
├── frontend/ \
│   ├── public/ \
│   ├── src/ \
│   │   ├── components/ \
│   │   ├── App.js \
│   │   ├── index.js \
│   │   └── styles/ \
│   ├── package.json \
│   └── README.md \
│ \
└── README.md 

## Backend - Spring Boot Setup <br>
# 1.Create the Spring Boot project using Spring Initializr:

`in`
Add necessary dependencies to `pom.xml`:

# 2.Spring Web
-Spring Data JPA
-H2 Database (for development)
-Spring Boot DevTools (optional)
-Create a controller, service, and repository:

# 3.Define your BooksStoreApplication.java file under com/bookstore.
Set up your entity classes in the model folder.
Define JPA repositories in the repository folder.
Implement business logic in the service folder.
Create endpoints using RestController in the controller folder.
Run the application:

