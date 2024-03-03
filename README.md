# Auth-Service

Auth-Service is a gRPC authentication service built with Go, designed to provide security and user authentication. In this repository, you will find the source code and instructions on how to deploy and integrate the service.

## Key Features

### gRPC Service

- Defined a simple gRPC service with authentication methods such as `Login` and `Register`.
- Service methods implemented in Go, handling user registration and login logic.

### Authentication

- Implemented basic authentication principles, such as generating and verifying JWT tokens.
- User credentials stored securely, using a hashing algorithm like bcrypt.

### Deployment

- Set up automatic deployment using GitHub Actions to a remote server.
- Configured the server to run the gRPC service and make it accessible to clients.

### URL Shortener Integration

- Integrated the gRPC service with the existing URL Shortener service as a client.
- Implemented functionality in the URL Shortener service to send authentication requests to the gRPC service and handle responses.

### Functional Tests

- Wrote comprehensive functional tests for the gRPC service to ensure that all methods work as expected.
- Tested edge cases and error handling to guarantee the stability and reliability of the service.

Join us and use Auth-Service to provide security and authentication in your projects!
