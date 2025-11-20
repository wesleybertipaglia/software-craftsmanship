# Engineering Challenge - Shell

## Introduction

Implement a basic Unix-like shell that can execute commands, handle pipelines, redirection, and job control. This challenge explores process creation, inter-process communication, and command interpretation.

### Objectives

- Understand process lifecycle and fork/exec model
- Implement command parsing and execution
- Handle input/output redirection and pipelines
- Learn about job control and background processes

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, build scripts as appropriate)

2. **Implementation Details**:
    - Parse command lines with arguments and operators
    - Execute built-in commands (cd, exit) and external programs
    - Implement input/output redirection (<, >, >>)
    - Add pipeline support using pipes between processes
    - Handle background jobs and job control signals

3. **Testing**:
    - Test basic command execution and argument passing
    - Verify redirection and pipeline functionality
    - Check job control with background processes
    - Compare behavior with standard shells like bash

### Possible Improvements

- Add shell scripting language features
- Implement command history and tab completion
- Add environment variable support
- Create a configuration file system

## Conclusion

By completing this challenge, you will gain deep understanding of how shells work and experience in systems programming with processes and I/O.

Happy coding!