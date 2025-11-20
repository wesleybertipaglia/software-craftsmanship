# Engineering Challenge - DNS Server

## Introduction

Build a DNS server that can resolve domain names to IP addresses, with caching and recursive resolution. This challenge explores network protocols, caching strategies, and domain name system architecture.

### Objectives

- Understand DNS protocol and message formats
- Implement recursive DNS resolution
- Add caching for performance optimization
- Learn about network protocol implementation

### Instructions

1. **Environment Setup**: 
    - Choose your preferred programming language
    - Set up a project structure following common conventions for your chosen language (e.g., src/ for source files, tests/ for test files, include networking libraries)

2. **Implementation Details**:
    - Parse DNS query messages and extract domain names
    - Implement recursive resolution by querying root servers
    - Follow DNS hierarchy through TLD and authoritative servers
    - Cache responses to improve performance
    - Handle different record types (A, AAAA, CNAME, etc.)

3. **Testing**:
    - Test domain resolution against known DNS servers
    - Verify caching behavior and cache expiration
    - Check handling of different record types
    - Test with various domain names and edge cases

### Possible Improvements

- Add DNSSEC validation support
- Implement authoritative server functionality
- Add zone file parsing for local domains
- Create a DNS proxy with filtering capabilities

## Conclusion

By completing this challenge, you will understand how the Domain Name System works and gain experience in implementing network protocols.

Happy coding!