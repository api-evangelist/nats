# NATS (nats)
A high-performance, cloud-native messaging system for microservices, IoT, and edge computing. Provides pub-sub, request-reply, and queue-based messaging patterns with at-most-once and at-least-once delivery guarantees.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/nats/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Message Broker, Pub Sub, Microservices, Cloud Native, IoT

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-18 

## APIs

### NATS Monitoring API
HTTP monitoring API providing real-time server status, connection information, route details, subscription statistics, JetStream metrics, and health check endpoints for observability and operations.

**Human URL:** [https://docs.nats.io/running-a-nats-service/nats_admin/monitoring](https://docs.nats.io/running-a-nats-service/nats_admin/monitoring)


#### Tags:

 - Monitoring, Health, Metrics

#### Properties

- [Documentation](https://docs.nats.io/running-a-nats-service/nats_admin/monitoring)
- [OpenAPI](properties/nats-monitoring-api-openapi.yml)

### NATS Messaging API
Asynchronous messaging API supporting core pub-sub, request-reply, queue groups, and JetStream persistent messaging with streams, consumers, key-value stores, and object stores.

**Human URL:** [https://docs.nats.io/nats-concepts/core-nats](https://docs.nats.io/nats-concepts/core-nats)


#### Tags:

 - Messaging, Pub Sub, JetStream, Streaming

#### Properties

- [Documentation](https://docs.nats.io/nats-concepts/core-nats)
- [AsyncAPI](properties/nats-messaging-asyncapi.yml)

### NATS JetStream Management API
The JetStream wire API provides a protocol-level management interface for configuring and operating JetStream streams, consumers, key-value buckets, and object stores. Requests are made by publishing to well-known $JS.API.* subjects and responses are returned as typed JSON payloads. This API underlies all official NATS client SDKs and the nats CLI.

**Human URL:** [https://docs.nats.io/reference/reference-protocols/nats_api_reference](https://docs.nats.io/reference/reference-protocols/nats_api_reference)


#### Tags:

 - JetStream, Management, Streaming

#### Properties

- [Documentation](https://docs.nats.io/reference/reference-protocols/nats_api_reference)
- [Reference](https://docs.nats.io/nats-concepts/jetstream)
- [AsyncAPI](properties/nats-jetstream-api-asyncapi.yml)
- [JSONSchema](properties/nats-jetstream-config-json-schema.json)

### NATS Key-Value Store API
The NATS Key-Value Store API is a JetStream-backed abstraction that provides immediately consistent, persistent associative array semantics. Clients can create buckets, get, put, delete, and watch keys, and receive real-time change notifications. Buckets are implemented as JetStream streams with the KV_ prefix.

**Human URL:** [https://docs.nats.io/nats-concepts/jetstream/key-value-store](https://docs.nats.io/nats-concepts/jetstream/key-value-store)


#### Tags:

 - Key-Value, JetStream, Storage

#### Properties

- [Documentation](https://docs.nats.io/nats-concepts/jetstream/key-value-store)
- [Reference](https://docs.nats.io/using-nats/developer/develop_jetstream/kv)
- [JSONSchema](properties/nats-kv-schema.json)

### NATS Object Store API
The NATS Object Store API is a JetStream-backed abstraction for storing and retrieving arbitrarily large binary objects using a chunking mechanism. Objects are identified by a bucket and a name, and the API supports put, get, delete, and watch operations for managing stored files and blobs.

**Human URL:** [https://docs.nats.io/nats-concepts/jetstream/obj_store](https://docs.nats.io/nats-concepts/jetstream/obj_store)


#### Tags:

 - Object Store, JetStream, Storage

#### Properties

- [Documentation](https://docs.nats.io/nats-concepts/jetstream/obj_store)
- [Reference](https://docs.nats.io/using-nats/developer/develop_jetstream/object)
- [JSONSchema](properties/nats-object-store-schema.json)

## Common Properties

- [Website](https://nats.io)
- [Documentation](https://docs.nats.io)
- [Getting Started](https://docs.nats.io/running-a-nats-service/introduction/installation)
- [GitHub Repository](https://github.com/nats-io/nats-server)
- [Blog](https://nats.io/blog/)
- [Slack](https://slack.nats.io)
- [Issues](https://github.com/nats-io/nats-server/issues)
- [Change Log](https://github.com/nats-io/nats-server/releases)
- [Examples](https://natsbyexample.com)
- [CLI](https://docs.nats.io/using-nats/nats-tools/nats_cli)
- [GitHub Organization](https://github.com/nats-io)
- [JSONSchema](properties/nats-server-config-json-schema.json)
- [JSONSchema](properties/nats-jetstream-config-json-schema.json)
- [JSONSchema](properties/nats-kv-schema.json)
- [JSONSchema](properties/nats-object-store-schema.json)
- [JSON-LD](properties/nats-context-jsonld.json)
- [Support](https://nats.io/support/)
- [Privacy Policy](https://nats.io/privacy/)
- [Community](https://nats.io/community/)
- [SDKs](https://docs.nats.io/using-nats/developer)
- [Download](https://nats.io/download/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
