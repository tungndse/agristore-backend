# Agristore Backend

## Overview

The Agristore Backend is a Spring Boot application designed to support the Agristore platform. This backend handles various functionalities such as product management, order processing, user authentication, and integrates with PostgreSQL and OpenAI for advanced features.

## Features

- **Product Management**: CRUD operations for cattle food and rice products.
- **Order Processing**: Tracks and manages orders, including delivery details.
- **User Authentication**: Supports OAuth2 for secure user authentication.
- **Integration**: Utilizes PostgreSQL for relational data and OpenAI for AI-driven features.
- **WebSocket Support**: Enables real-time communication.
- **Database Migration**: Uses Liquibase for database versioning and migrations.

## Requirements

- Java 17 or later
- Maven 3.8.1 or later
- PostgreSQL 13 or later

## Getting Started

1. **Clone the Repository**

   ```bash
   git clone https://github.com/tungndse/agristore-backend.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd agristore-backend
   ```

3. **Build the Project**

   ```bash
   mvn clean install
   ```

4. **Run the Application**

   ```bash
   mvn spring-boot:run
   ```

5. **Access the Application**

   Open `http://localhost:8080` in your browser to access the API endpoints.

## Configuration

Configure the application by editing the `application.properties` or `application.yml` file located in `src/main/resources`.

## Dependencies

- Spring Boot 3.3.2
- PostgreSQL
- OpenAI
- Liquibase
- Spring Security
- Spring Data JPA
- Spring Data Redis
- Spring Data MongoDB

## Contributing

If you wish to contribute to this project, please follow the steps below:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please open an issue on GitHub or contact the project maintainer.
