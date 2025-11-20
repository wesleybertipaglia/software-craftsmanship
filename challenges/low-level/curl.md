# Engineering Challenge - Curl

## Introduction

Implement a basic HTTP client that can make requests to web servers using raw TCP connections, similar to curl. This challenge explores network programming, HTTP protocol, and client-server communication.

### Objectives

- Understand HTTP protocol and request/response format
- Implement TCP socket communication
- Handle HTTP headers and body parsing
- Learn about network programming fundamentals

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, include networking libraries)

2. **Implementation Details**:
    - Resolve hostnames to IP addresses
    - Establish TCP connections to servers
    - Send HTTP GET/POST requests with proper formatting
    - Parse HTTP responses including status codes and headers
    - Handle different content types and encodings

3. **Testing**:
    - Test with various websites and endpoints
    - Verify correct handling of redirects and errors
    - Check compatibility with different servers
    - Test with HTTPS (may require TLS library)

### Possible Improvements

- Add HTTPS support with TLS encryption
- Implement HTTP methods beyond GET/POST
- Add cookie and session management
- Create a more user-friendly command-line interface

## Conclusion

By completing this challenge, you will gain experience in network programming and understand how HTTP clients communicate with web servers.

Happy coding!