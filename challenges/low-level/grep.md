# Engineering Challenge - Grep

## Introduction

Build a command-line tool that searches for patterns in text files, similar to the Unix `grep` utility. This challenge will help you understand text processing, pattern matching algorithms, and command-line interface design.

### Objectives

- Implement basic pattern matching in files
- Handle command-line arguments for search patterns and file paths
- Support recursive directory searching
- Learn about efficient string searching algorithms

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, build scripts in the root or build/ directory)

2. **Implementation Details**:
    - Parse command-line arguments for pattern and file/directory paths
    - Implement string matching (start with simple substring search, then add regex)
    - Read files line by line and search for matches
    - Display matching lines with line numbers and file names
    - Add options for case-insensitive search, inverted matches, etc.

3. **Testing**:
    - Test with various text files and patterns
    - Compare output with system `grep` for correctness
    - Handle edge cases like binary files, large files, and special characters

### Possible Improvements

- Add regular expression support using a regex library
- Implement performance optimizations for large files
- Add context lines before/after matches
- Support multiple patterns and file types

## Conclusion

By completing this challenge, you will gain practical experience in text processing, algorithm implementation, and building robust command-line tools.

Happy coding!