# Spring-Security-JWT-Authentication
This repository showcases a sample Spring Boot web application integrated with Spring Security for role-based authentication and JWT (JSON Web Token) authorization. The application uses an H2 in-memory database for storing user credentials and demonstrates secure access to API endpoints using JWT tokens.

The project showcases a robust security setup suitable for enterprise-grade applications, leveraging Spring Security's powerful features to protect endpoints and manage user roles efficiently. JWT tokens are used for stateless authentication, ensuring scalability and security.

## Features

- **JWT Authentication**: Implements stateless authentication using JWT tokens, enhancing security and scalability.
- **Role-Based Authorization**: Defines access levels based on user roles (`ROLE_USER`, `ROLE_ADMIN`) using Spring Security annotations.
- **H2 Database Integration**: Uses H2 in-memory database for storing user credentials and authorization details.
- **RESTful API Protection**: Secures RESTful APIs with JWT-based authentication to control access based on user roles.
- **Customizable Security Configuration**: Demonstrates how to customize security configurations in Spring Boot for different authentication and authorization requirements.
