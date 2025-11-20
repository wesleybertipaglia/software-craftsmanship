# Software Craftsmanship - Git

## Introduction

Build a simplified version control system inspired by Git, focusing on the core concepts of object storage, commits, and basic repository management. This challenge explores data structures and algorithms for version control.

### Objectives

- Understand Git's object model and storage format
- Implement content-addressable storage
- Create commit history and branching concepts
- Learn about cryptographic hashing for data integrity

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, include crypto libraries as needed)

2. **Implementation Details**:
    - Implement object storage with SHA-1 hashing
    - Create blob objects for file contents and tree objects for directories
    - Build commit objects with metadata and parent references
    - Add basic commands: init, add, commit, log
    - Handle staging area (index) for pending changes

3. **Testing**:
    - Create repositories and make commits
    - Verify object integrity and hash consistency
    - Test branching and merging concepts
    - Compare with Git for basic operations

### Possible Improvements

- Add remote repository support
- Implement diff and patch generation
- Add merge conflict resolution
- Create a network protocol for distributed operations

## Conclusion

By completing this challenge, you will understand how distributed version control systems work at their core and gain experience in data structures for version control.

Happy coding!