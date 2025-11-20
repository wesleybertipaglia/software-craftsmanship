# Engineering Challenge - SQLite

## Introduction

Build a simplified relational database engine with SQL parsing, B-tree indexing, and basic query execution. This challenge explores database internals, data structures, and query processing.

### Objectives

- Understand database storage and indexing
- Implement B-tree data structure for efficient lookups
- Parse and execute basic SQL statements
- Learn about transaction management and persistence

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, data/ for database files)

2. **Implementation Details**:
    - Implement B-tree for indexing and storage
    - Parse SQL CREATE, INSERT, SELECT, UPDATE, DELETE statements
    - Execute queries with proper indexing
    - Handle table schemas and data types
    - Add basic transaction support with rollback

3. **Testing**:
    - Create tables and insert data
    - Execute various queries and verify results
    - Test indexing performance with large datasets
    - Check data persistence across sessions

### Possible Improvements

- Add JOIN operations and complex queries
- Implement query optimization and execution planning
- Add concurrency control with locking
- Create a SQL shell interface

## Conclusion

By completing this challenge, you will gain deep understanding of how relational databases work internally and experience in implementing complex data structures.

Happy coding!