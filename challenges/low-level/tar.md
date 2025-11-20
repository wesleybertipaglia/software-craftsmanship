# Software Craftsmanship - Tar

## Introduction

Implement a simplified version of the Unix `tar` archiver, which combines multiple files into a single archive file. This challenge explores file system operations, data serialization, and archive formats.

### Objectives

- Understand archive file formats and metadata
- Implement file packing and unpacking operations
- Handle file permissions and timestamps
- Learn about binary data manipulation

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, data/ for test archives)

2. **Implementation Details**:
    - Design a simple archive format with file headers (name, size, permissions, timestamp)
    - Implement archive creation: read files and write to archive with headers
    - Implement archive extraction: read headers and recreate files
    - Handle directories and nested structures
    - Preserve file metadata where possible

3. **Testing**:
    - Create archives with various file types and sizes
    - Extract and verify file integrity
    - Test with nested directories and special files
    - Compare with standard tar for compatibility

### Possible Improvements

- Add compression support (gzip integration)
- Implement incremental backups
- Add encryption for archived files
- Support for sparse files and hard links

## Conclusion

By completing this challenge, you will gain experience in file system operations, data serialization, and building utility tools that manipulate files at a low level.

Happy coding!