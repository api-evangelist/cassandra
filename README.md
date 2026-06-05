# Apache Cassandra (cassandra)

Apache Cassandra is a highly scalable, distributed open-source NoSQL database designed to handle massive amounts of data across many commodity servers, providing high availability with no single point of failure. It is governed by the Apache Software Foundation (ASF) under the Apache License 2.0 and is used in production by Netflix, Apple, Bloomberg, Backblaze, and many others. Cassandra exposes its CQL native protocol for clients and a family of HTTP, REST, GraphQL, Document, and gRPC APIs via the Stargate data gateway.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cassandra/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cassandra/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Apache
- Big Data
- Database
- Distributed
- NoSQL
- Open Source

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-23

## APIs

### Apache Cassandra CQL Native Protocol

Cassandra Query Language (CQL) is the primary interface to Apache Cassandra. Clients speak the binary CQL native protocol over TCP (default port 9042). Official drivers are maintained for Java, Python, Go, C/C++, C#, Node.js, Ruby, and Rust.

- **Human URL:** [https://cassandra.apache.org/doc/latest/cassandra/cql/](https://cassandra.apache.org/doc/latest/cassandra/cql/)

#### Tags

- CQL
- Database
- Native Protocol
- Query

#### Properties

- [Documentation](https://cassandra.apache.org/doc/latest/cassandra/cql/)
- [Specification](https://github.com/apache/cassandra/blob/trunk/doc/native_protocol_v5.spec)
- [Reference](https://cassandra.apache.org/doc/latest/cassandra/cql/ddl.html)
- [Postman Collection](collections/cassandra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cassandra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cassandra REST API (Stargate)

HTTP/JSON REST API for Cassandra provided by the Stargate data gateway. Enables CRUD operations and SQL-like query via REST without the CQL driver.

- **Human URL:** [https://stargate.io/docs/latest/develop/api-rest/](https://stargate.io/docs/latest/develop/api-rest/)

#### Tags

- Database
- REST
- Stargate

#### Properties

- [Documentation](https://stargate.io/docs/latest/develop/api-rest/)
- [Swagger](https://stargate.io/docs/latest/develop/api-rest/swagger.html)
- [Source Code](https://github.com/stargate/stargate)
- [Postman Collection](collections/cassandra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cassandra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cassandra GraphQL API (Stargate)

GraphQL endpoint for Cassandra, enabling flexible, typed queries and mutations against Cassandra tables through the Stargate gateway.

- **Human URL:** [https://stargate.io/docs/latest/develop/api-graphql/](https://stargate.io/docs/latest/develop/api-graphql/)

#### Tags

- Database
- GraphQL
- Stargate

#### Properties

- [Documentation](https://stargate.io/docs/latest/develop/api-graphql/)
- [Reference](https://stargate.io/docs/latest/develop/api-graphql/graphql-using.html)
- [Postman Collection](collections/cassandra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cassandra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cassandra Document API (Stargate)

Schemaless Document API that stores JSON documents in Cassandra, offering a MongoDB-like developer experience backed by Cassandra.

- **Human URL:** [https://stargate.io/docs/latest/develop/api-doc/](https://stargate.io/docs/latest/develop/api-doc/)

#### Tags

- Database
- Document
- JSON
- Stargate

#### Properties

- [Documentation](https://stargate.io/docs/latest/develop/api-doc/)
- [Reference](https://stargate.io/docs/latest/develop/api-doc/doc-using.html)
- [Postman Collection](collections/cassandra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cassandra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cassandra gRPC API (Stargate)

High-performance gRPC API for Cassandra through Stargate, designed for low-latency service-to-service communication.

- **Human URL:** [https://stargate.io/docs/latest/develop/api-grpc/](https://stargate.io/docs/latest/develop/api-grpc/)

#### Tags

- Database
- gRPC
- Stargate

#### Properties

- [Documentation](https://stargate.io/docs/latest/develop/api-grpc/)
- [Protocol](https://github.com/stargate/stargate/tree/main/grpc/proto)
- [Postman Collection](collections/cassandra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cassandra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cassandra JMX Management Interface

Java Management Extensions (JMX) interface for monitoring and administering Cassandra nodes, including metrics, compaction, repairs, and configuration.

- **Human URL:** [https://cassandra.apache.org/doc/latest/cassandra/operating/metrics.html](https://cassandra.apache.org/doc/latest/cassandra/operating/metrics.html)

#### Tags

- JMX
- Management
- Metrics
- Monitoring

#### Properties

- [Documentation](https://cassandra.apache.org/doc/latest/cassandra/operating/metrics.html)
- [Operations Guide](https://cassandra.apache.org/doc/latest/cassandra/operating/)
- [Postman Collection](collections/cassandra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cassandra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://cassandra.apache.org/)
- [Documentation](https://cassandra.apache.org/doc/latest/)
- [Getting Started](https://cassandra.apache.org/doc/latest/cassandra/getting_started/)
- [Download](https://cassandra.apache.org/download/)
- [Source Code](https://github.com/apache/cassandra)
- [Git Hub](https://github.com/apache/cassandra)
- [Issue Tracker](https://issues.apache.org/jira/projects/CASSANDRA)
- [Blog](https://cassandra.apache.org/blog/)
- [Community](https://cassandra.apache.org/community/)
- [Mailing List](https://cassandra.apache.org/community/#discussions)
- [Slack](https://cassandra.apache.org/community/#slack)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/cassandra)
- [X (Twitter)](https://twitter.com/cassandra)
- [LinkedIn](https://www.linkedin.com/company/apache-cassandra/)
- [YouTube](https://www.youtube.com/@PlanetCassandra)
- [Docker Hub](https://hub.docker.com/_/cassandra)
- [Package Registry](https://central.sonatype.com/artifact/org.apache.cassandra/cassandra-all)
- [License](https://www.apache.org/licenses/LICENSE-2.0)
- [Governance](https://www.apache.org/foundation/governance/)
- [Security Policy](https://cassandra.apache.org/_/security.html)
- [Privacy Policy](https://www.apache.org/privacy/)
- [Terms of Service](https://www.apache.org/foundation/license-faq.html)
- [Ecosystem](https://cassandra.apache.org/_/ecosystem.html)
- [Third Party](https://cassandra.apache.org/_/ecosystem.html)
- [Features](undefined)
- [Use Cases](undefined)

## Maintainers

**FN:** Apache Cassandra Community
**Email:** dev@cassandra.apache.org
