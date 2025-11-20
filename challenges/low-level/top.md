# Software Craftsmanship - Top

## Introduction

Build a system monitoring tool that displays real-time information about running processes, similar to the Unix `top` command. This challenge involves interacting with the operating system to gather process and system statistics.

### Objectives

- Learn about process management and system calls
- Implement real-time data collection and display
- Handle asynchronous updates and user input
- Understand system performance metrics

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, consider cross-platform libraries if needed)

2. **Implementation Details**:
    - Gather process information (PID, CPU usage, memory, command)
    - Collect system-wide statistics (total CPU, memory usage)
    - Create a real-time updating display with sorting options
    - Handle user input for sorting, filtering, and quitting
    - Implement efficient data collection to minimize system impact

3. **Testing**:
    - Monitor various system loads and process behaviors
    - Verify accuracy against system tools like `ps` and `top`
    - Test on different operating systems if cross-platform
    - Check performance impact of your monitoring tool

### Possible Improvements

- Add graphical interface or web-based display
- Implement historical data and trend analysis
- Add alerting for high resource usage
- Support for container and virtual machine monitoring

## Conclusion

By completing this challenge, you will understand how system monitoring tools work and gain experience in real-time data processing and user interface design.

Happy coding!