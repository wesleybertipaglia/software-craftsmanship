# Software Craftsmanship - Redis

## Introduction

Build a simple in-memory key-value database server that accepts TCP connections and processes commands, inspired by Redis. This challenge explores server architecture, protocol design, and data structures.

### Objectives

- Understand client-server communication protocols
- Implement basic data structures (strings, hashes, lists)
- Handle concurrent connections and commands
- Learn about in-memory data storage and persistence

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, server components organized logically)

2. **Implementation Details**:
    - Implement Redis protocol (RESP) for command parsing
    - Support basic commands: SET, GET, DEL, EXISTS
    - Add data structures: strings, lists, hashes, sets
    - Handle multiple client connections concurrently
    - Implement expiration and TTL for keys

3. **Testing**:
    - Connect with redis-cli or custom client
    - Test concurrent operations and data consistency
    - Verify protocol compliance and error handling
    - Benchmark performance and memory usage

### Possible Improvements

- Add persistence with snapshotting or AOF
- Implement replication and clustering
- Add pub/sub messaging
- Create Lua scripting support

## Conclusion

By completing this challenge, you will understand how in-memory databases work and gain experience in building scalable server applications.

Happy coding!