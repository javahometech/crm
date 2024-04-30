# Steps to Setup Project

This README provides steps to build and run a Java application using Maven.

## Prerequisites

Before you begin, ensure you have the following installed:

- Java Development Kit (JDK)
- Apache Maven

## Building the Application

To build the application, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the project directory containing the `pom.xml` file.
3. Run the following Maven command to clean and package the application:

    ```bash
    mvn clean package
    ```

   This command will compile the code, run tests, and package the application into an executable JAR file.

## Running the Application

Once the application is built, you can run it using the following command:

```bash
java -jar /path/to/your/application.jar
