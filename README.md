# BookStrore-crud-app
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

# Backend - Spring Boot Setup <br>
## 1.Create the Spring Boot project using Spring Initializr:
`mvn archetype:generate -DgroupId=com.bookstore -DartifactId=backend -Dversion=1.0-SNAPSHOT  `
## 2.Add necessary dependencies to `pom.xml`:
- Spring Web
- Spring Data JPA
- H2 Database (for development)
- Spring Boot DevTools (optional)
- Create a controller, service, and repository:

## 3.Define your BooksStoreApplication.java file under com/bookstore.
- Set up your entity classes in the model folder.
- Define JPA repositories in the repository folder.
- Implement business logic in the service folder.
- Create endpoints using RestController in the controller folder.
## 4.Run the application:
`mvn spring-boot:run`

# Frontend - ReactJS Setup 

1. Navigate to the frontend folder:<br>
  ` cd frontend `
2. Create a new React application:<br>
   ` npx create-react-app . `
3. Install additional packages (if needed):<br>
  ` npm install axios react-router-dom `
4. Create necessary components under the components folder:<br>
  - Example: `BooksList.js`, `AddBook.js`, etc.

5. Start the React application:<br>
  ` npm start `


