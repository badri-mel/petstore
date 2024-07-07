# Pet Store API

This project is a Spring Boot application that provides a REST API 
for managing a pet store. 

* The API is generated using Swagger Generator based on the `api.yaml` specification.
* The project aims to write a template to generate builder for all the generated classes automatically.

## Project Structure

- **src/main/resources/api.yaml**: OpenAPI specification file.
- **build.gradle**: Gradle build configuration.
- **generated/**: Directory where the Swagger Generator outputs the generated code.

## Getting Started

### Prerequisites

- Java 21 or higher
- Gradle 7.0 or higher

### Building the Project

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/petstore-api.git
   cd petstore-api
   ```

2. Generate the models 
   ```sh
   ./gradlew generateSwaggerCode
   ```