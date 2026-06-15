# NATS (nats)

A high-performance, cloud-native messaging system for microservices, IoT, and edge computing. Provides pub-sub, request-reply, and queue-based messaging patterns with at-most-once and at-least-once delivery guarantees.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nats/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nats/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cloud Native
- IoT
- Message Broker
- Microservices
- Pub Sub

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### NATS Monitoring API

HTTP monitoring API providing real-time server status, connection information, route details, subscription statistics, JetStream metrics, and health check endpoints for observability and operations.

- **Human URL:** [https://docs.nats.io/running-a-nats-service/nats_admin/monitoring](https://docs.nats.io/running-a-nats-service/nats_admin/monitoring)
- **Base URL:** `http://localhost:8222`

#### Tags

- Health
- Metrics
- Monitoring

#### Properties

- [Documentation](https://docs.nats.io/running-a-nats-service/nats_admin/monitoring)
- [OpenAPI](properties/nats-monitoring-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/nats-monitoring.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nats-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nats-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NATS Messaging API

Asynchronous messaging API supporting core pub-sub, request-reply, queue groups, and JetStream persistent messaging with streams, consumers, key-value stores, and object stores.

- **Human URL:** [https://docs.nats.io/nats-concepts/core-nats](https://docs.nats.io/nats-concepts/core-nats)

#### Tags

- JetStream
- Messaging
- Pub Sub
- Streaming

#### Properties

- [Documentation](https://docs.nats.io/nats-concepts/core-nats)
- [AsyncAPI](properties/nats-messaging-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [AsyncAPI](asyncapi/nats-messaging.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/nats-stream-config.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/nats-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nats-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NATS JetStream Management API

The JetStream wire API provides a protocol-level management interface for configuring and operating JetStream streams, consumers, key-value buckets, and object stores. Requests are made by publishing to well-known $JS.API.* subjects and responses are returned as typed JSON payloads. This API underlies all official NATS client SDKs and the nats CLI.

- **Human URL:** [https://docs.nats.io/reference/reference-protocols/nats_api_reference](https://docs.nats.io/reference/reference-protocols/nats_api_reference)

#### Tags

- JetStream
- Management
- Streaming

#### Properties

- [Documentation](https://docs.nats.io/reference/reference-protocols/nats_api_reference)
- [Reference](https://docs.nats.io/nats-concepts/jetstream)
- [AsyncAPI](properties/nats-jetstream-api-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](properties/nats-jetstream-config-json-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/nats-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nats-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NATS Key-Value Store API

The NATS Key-Value Store API is a JetStream-backed abstraction that provides immediately consistent, persistent associative array semantics. Clients can create buckets, get, put, delete, and watch keys, and receive real-time change notifications. Buckets are implemented as JetStream streams with the KV_ prefix.

- **Human URL:** [https://docs.nats.io/nats-concepts/jetstream/key-value-store](https://docs.nats.io/nats-concepts/jetstream/key-value-store)

#### Tags

- JetStream
- Key-Value
- Storage

#### Properties

- [Documentation](https://docs.nats.io/nats-concepts/jetstream/key-value-store)
- [Reference](https://docs.nats.io/using-nats/developer/develop_jetstream/kv)
- [JSON Schema](properties/nats-kv-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/nats-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nats-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NATS Object Store API

The NATS Object Store API is a JetStream-backed abstraction for storing and retrieving arbitrarily large binary objects using a chunking mechanism. Objects are identified by a bucket and a name, and the API supports put, get, delete, and watch operations for managing stored files and blobs.

- **Human URL:** [https://docs.nats.io/nats-concepts/jetstream/obj_store](https://docs.nats.io/nats-concepts/jetstream/obj_store)

#### Tags

- JetStream
- Object Store
- Storage

#### Properties

- [Documentation](https://docs.nats.io/nats-concepts/jetstream/obj_store)
- [Reference](https://docs.nats.io/using-nats/developer/develop_jetstream/object)
- [JSON Schema](properties/nats-object-store-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/nats-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nats-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://nats.io)
- [Documentation](https://docs.nats.io)
- [Getting Started](https://docs.nats.io/running-a-nats-service/introduction/installation)
- [GitHub Repository](https://github.com/nats-io/nats-server)
- [Blog](https://nats.io/blog/)
- [Slack](https://slack.nats.io)
- [Issues](https://github.com/nats-io/nats-server/issues)
- [Changelog](https://github.com/nats-io/nats-server/releases)
- [Examples](https://natsbyexample.com)
- [C L I](https://docs.nats.io/using-nats/nats-tools/nats_cli)
- [GitHub Organization](https://github.com/nats-io)
- [JSON Schema](properties/nats-server-config-json-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](properties/nats-jetstream-config-json-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](properties/nats-kv-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](properties/nats-object-store-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](properties/nats-context-jsonld.json) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Support](https://nats.io/support/)
- [Privacy Policy](https://nats.io/privacy/)
- [Community](https://nats.io/community/)
- [S D Ks](https://docs.nats.io/using-nats/developer)
- [Download](https://nats.io/download/)
- [L L Ms Txt](https://docs.nats.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
