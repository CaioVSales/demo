# Java Spring Boot Study Project

![Java Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.6.3-brightgreen) ![Java](https://img.shields.io/badge/Java-17-blue)

This is a study project created with Java 21 and the latest version of Spring Boot. The purpose of this project is to serve as an initial exploration, setting the groundwork for a more extensive project.

## Project Overview

- **Spring Boot Version:** 2.6.3
- **Java Version:** 21

## Getting Started

Follow these steps to set up and run the project locally:

### Prerequisites

- [Java Development Kit (JDK)](https://adoptopenjdk.net/) 17 or later
- [Maven](https://maven.apache.org/) (latest version recommended)

### Clone the Repository

```bash
git clone https://github.com/CaioVSales/demo.git
cd demo
```

### Build and Run

```bash
mvn spring-boot:run
```

The application will be accessible at `http://localhost:8080`. 

## Project Structure

Briefly explain the main structure of your project, such as key packages and their roles.

```plaintext
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── com.example.project
│   │   │   │   ├── controller    # RESTful API controllers
│   │   │   │   ├── service       # Business logic
│   │   │   │   ├── repository    # Data access layer
│   │   │   │   └── ...
│   │   │   └── ...
│   │   └── resources
│   │       ├── application.yml   # Application configuration
│   │       └── ...
│   └── test
│       └── ...
└── ...
```

## Contributing

If you'd like to contribute to this project or have suggestions, feel free to open an issue or create a pull request.

## License
No license
