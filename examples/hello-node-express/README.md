# Hello World Express Example

## Overview

This example illustrates a simple hello world using a local dependency and express.

## Usage

### Install and setup

```bash
npm run setup
```

### Running the main application

```bash
HONEYCOMB_API_KEY={apikey} OTEL_SERVICE_NAME="hello-node-express" npm start
```

Alternatively, to export telemetry using `gRPC` instead of `http/protobuf`:

```bash
HONEYCOMB_API_KEY={apikey} OTEL_SERVICE_NAME="hello-node-express" OTEL_EXPORTER_OTLP_PROTOCOL=grpc npm start
```
