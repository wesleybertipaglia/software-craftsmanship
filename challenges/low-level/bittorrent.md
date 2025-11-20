# Software Craftsmanship - BitTorrent

## Introduction

Implement a BitTorrent client that can download and share files using the peer-to-peer protocol. This challenge explores distributed systems, file chunking, and peer communication.

### Objectives

- Understand BitTorrent protocol and torrent files
- Implement peer wire protocol for communication
- Handle file piece downloading and verification
- Learn about distributed hash tables and peer discovery

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, downloads/ for temporary files)

2. **Implementation Details**:
    - Parse .torrent files and extract metadata
    - Implement peer handshake and communication protocol
    - Download file pieces from multiple peers
    - Verify piece integrity with hashes
    - Implement piece selection and rarest-first algorithm

3. **Testing**:
    - Test with existing torrent files
    - Verify download integrity and completion
    - Check peer communication and swarm behavior
    - Test with different file sizes and peer counts

### Possible Improvements

- Add torrent creation functionality
- Implement DHT for peer discovery
- Add encryption and obfuscation
- Create a web-based interface for torrent management

## Conclusion

By completing this challenge, you will understand peer-to-peer networks and distributed file sharing systems.

Happy coding!