# RWARegistry

A production-ready Clarity smart contract for managing and registering tokenized real-world assets (RWAs) on the Stacks blockchain.

## Overview

RWARegistry is a compact, secure smart contract that enables efficient registration, transfer, and valuation tracking of real-world assets. It provides cryptographic proof of asset ownership and maintains immutable history while supporting ownership transfers and valuation updates.

## Features

- **Asset Registration**: Register real-world assets with metadata hashing and initial valuation
- **Ownership Transfer**: Securely transfer asset ownership between principals
- **Valuation Management**: Update asset valuations with owner-level authorization
- **Asset Deactivation**: Deactivate assets while preserving full transaction history
- **Read-only Access**: Query asset details without modifying state
- **Comprehensive Error Handling**: 8 distinct error codes for precise fault diagnosis

## Getting Started

### Prerequisites

- [Clarinet](https://github.com/hirosystems/clarinet) - Clarity development environment
- Node.js 16+ (for running tests)
