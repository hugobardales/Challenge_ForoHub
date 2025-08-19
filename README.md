# Challenge ONE - Back End Java + Spring - Alura Forum API Rest.

## Project Description

This is the solution to the **Challenge - Alura Forum** using **Spring Boot** for creating the Rest API, **MySQL** for the databases, and **Java 17** for development with the help of the **IntelliJ** IDE and **Insomnia** for API testing. This is the fourth challenge of the **Oracle Next Education (ONE)** training from **Oracle + Alura LATAM**.

The challenge consists of creating an **API** by implementing the best practices of the **Rest** model with validations and a database implementation for data persistence.

### :hammer:Functionalities

- Create a new topic.
- Display all created topics.
- Display a specific topic.
- Update a topic.
- Delete a topic.
- API with routes implemented following the best practices of the Rest model.
- Validations performed according to business rules.
- Implementation of a database for data persistence.

## Getting Started 🚀

_These instructions will get you a copy of the project up and running on your local machine for development and testing purposes._

### Prerequisites 📋

_What things you need to install the software and how to install them._

- **Java Development Kit (JDK) 17**: Ensure you have JDK 17 installed on your system. You can download it from the official Oracle website or use a package manager like SDKMAN!
- **Maven or Gradle**: This project uses Maven for dependency management. If you don't have it, install it.
- **MySQL**: The project uses a MySQL database. Install MySQL server and a client.
- **IntelliJ IDEA**: Recommended IDE for this project.
- **Insomnia/Postman**: Recommended tool for testing the API endpoints.

### Installation 🔧

_A step-by-step series of examples that tell you how to get a development environment running._

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Configure MySQL**:
    * Create a new database for the project.
    * Update the `src/main/resources/application.properties` file with your MySQL credentials:
        ```properties
        spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
        spring.datasource.username=your_username
        spring.datasource.password=your_password
        spring.jpa.hibernate.ddl-auto=update
        ```

3.  **Run the application**:
    * Using Maven:
        ```bash
        ./mvnw spring-boot:run
        ```
    * Or, you can use your IDE (e.g., IntelliJ IDEA) to run the `main` method in the `ForoAluraApplication` class.

4.  **Test the API**:
    * The API will be running on `http://localhost:8080` by default.
    * Use Insomnia or Postman to test the endpoints. For example, to create a new topic, make a `POST` request to `http://localhost:8080/topics`.

## Built With 🛠️

_To develop the project, I used the following tools:_

* [Trello](https://trello.com/es) - Project management tool.
* [MySQL](https://www.mysql.com/) - Database management system.
* [Java 17](https://www.oracle.com/java/) - Programming language.
* [IntelliJ IDEA](https://www.jetbrains.com/idea/) - Integrated development environment for software development.
* [Spring Boot](https://start.spring.io/) - A tool that makes building web applications and microservices with the Spring Framework faster and easier.




