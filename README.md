# OpenAPI Specification for Nanograph API

This repository contains the OpenAPI specification for the Nanograph API, which currently supports the Farcaster protocol.

## Getting Started

To generate an API client library for your preferred programming language, you can use the OpenAPI definition file (`farcaster-api.yaml`) in conjunction with the [OpenAPI Generator](https://openapi-generator.tech/docs/installation/).

## Example

Follow these steps to generate a TypeScript client library:

1. Install the OpenAPI TypeScript codegen CLI:
   ```
   npm install @openapitools/openapi-generator-cli -g
   ```

2. Ensure that you have Java runtime installed (minimum required version is 11 or higher). For example, to install OpenJDK 17 on macOS, run:
   ```
   brew install openjdk@17
   ```
   
3. Generate the client library:
   ```
   openapi-generator-cli generate -i farcaster-api.yaml -g typescript-fetch -o ./build/farcaster-ts
   ```
   This command will generate a client library in the `build/farcaster-ts` directory.


## API Documentation

For more information about the usage of the Nanograph API, please refer to our [API documentation](https://docs.nanograph.xyz).