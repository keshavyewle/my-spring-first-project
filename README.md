# My Spring First Project

A simple Spring Boot Hello World application built with Maven.

## Prerequisites

- Java 17 or higher
- Maven 3.6 or higher

## Project Structure

```
my-spring-first-project/
├── pom.xml
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/myspringfirstproject/
│   │   │       ├── MySpringFirstProjectApplication.java
│   │   │       └── controller/
│   │   │           └── HelloWorldController.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/
│           └── com/example/myspringfirstproject/
│               └── MySpringFirstProjectApplicationTests.java
└── README.md
```

## How to Run

### Using Maven

1. Navigate to the project directory:
   ```bash
   cd my-spring-first-project
   ```

2. Run the application:
   ```bash
   mvn spring-boot:run
   ```

### Using Java

1. Build the project:
   ```bash
   mvn clean package
   ```

2. Run the JAR file:
   ```bash
   java -jar target/my-spring-first-project-1.0.0.jar
   ```

## Testing the Application

Once the application is running, you can test it by:

1. Opening your browser and navigating to:
   - http://localhost:8080/
   - http://localhost:8080/hello

2. Or using curl:
   ```bash
   curl http://localhost:8080/
   curl http://localhost:8080/hello
   ```

## Expected Output

- `GET /` returns: "Hello, World! Welcome to Spring Boot!"
- `GET /hello` returns: "Hello World from Spring Boot!"

## Technologies Used

- Spring Boot 3.2.0
- Java 17
- Maven


