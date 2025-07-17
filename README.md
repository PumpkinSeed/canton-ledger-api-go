# Canton Ledger API Go Client

This repository contains a Go client for the Canton Ledger API, generated from the OpenAPI specification using [oapi-codegen](https://github.com/oapi-codegen/oapi-codegen).

## Features

- Auto-generated Go client from OpenAPI 3.0.3 specification
- Type-safe API calls with proper error handling
- Support for both synchronous and asynchronous command submission
- Authentication support (HTTP Basic Auth and API Key)
- Comprehensive model definitions

## Quick Start

### Prerequisites

- Go 1.24.5 or later

### Generating the Client

You have two options to generate the Go client:

#### Option 1: Using the Custom Generator (Recommended)

```bash
go generate
```
