# Engineering Challenge - HTTP Server

## Introduction

Implement a basic HTTP web server that can handle requests, parse headers, and route to different handlers. This challenge explores web protocols, server architecture, and request processing.

### Objectives

- Understand HTTP protocol and request/response cycle
- Implement request parsing and routing
- Handle static file serving and dynamic content
- Learn about server performance and concurrency

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, static/ for web assets)

2. **Implementation Details**:
    - Parse HTTP requests including method, path, headers, and body
    - Implement routing for different endpoints
    - Serve static files with proper MIME types
    - Handle different HTTP methods (GET, POST, etc.)
    - Add support for query parameters and form data

3. **Testing**:
    - Test with web browsers and curl commands
    - Verify correct header handling and status codes
    - Check concurrent request handling
    - Test with various file types and sizes

### Possible Improvements

- Add HTTPS support with TLS
- Implement middleware for logging and authentication
- Add template engine for dynamic content
- Create REST API endpoints with JSON responses

## Conclusion

By completing this challenge, you will gain experience in web server development and understand the fundamentals of client-server web communication.

Happy coding!