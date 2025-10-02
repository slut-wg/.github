# 🌸 SLUT Working Group

Welcome to the SLUT (Simple LLM Unified Transmission) working group! We're a cute subproject of [allura.moe](https://allura.moe/) focused on creating standardized protocols for LLM communication.

## About SLUT

SLUT is an open protocol specification designed to unify how applications interact with Large Language Models. Our goal is to create a simple, elegant, and standardized way to transmit requests and receive responses from different LLM providers through a consistent API interface.

## What We Do

- **Protocol Design**: Define and maintain the SLUT protocol specification
- **Reference Implementation**: Provide official server and client implementations
- **Provider Integration**: Support multiple LLM providers through a unified interface
- **Community Standards**: Foster adoption and compatibility across the ecosystem

## Key Features
- **Unified API**: Single interface for multiple LLM providers
- **Streaming Support**: Real-time text generation with Server-Sent Events
- **Extensible Design**: Easy to add new providers and features
- **Authentication**: Built-in API key management and access control

## Projects

### [proxy/](./proxy/) - Reference Server
A Python-based reference implementation of the SLUT protocol (as well as an OpenAI-compatible layer) that acts as a proxy between clients and various LLM providers.

### [spec/](./spec/) - Protocol Specification
The official TypeSpec specification for the SLUT protocol. This defines the core API structure, request/response formats, and extension points for providers. It also includes an (attempted) formalization of the OpenAI protocol.

## Getting Started

1. Check out our [protocol specification](./spec/) to understand the SLUT API
2. Try our [reference server](./proxy/) for a quick start
3. Join our community discussions at allura.moe

## License

SLUT projects are licensed under permissive open source licenses. See individual project directories for specific licensing information.

## Contact

Find us at [allura.moe](https://allura.moe/) for discussions, support, and contributions! ✨

---

*Made with 💕 by allura (The docs were written by GLM-4.6, blame Zhipu if they're slop)*
