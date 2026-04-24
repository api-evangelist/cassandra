# Apache Cassandra (cassandra)
Apache Cassandra is a highly scalable, distributed open-source NoSQL database designed to handle massive amounts of data across many commodity servers, providing high availability with no single point of failure. It is governed by the Apache Software Foundation (ASF) under the Apache License 2.0 and is used in production by Netflix, Apple, Bloomberg, Backblaze, and many others. Cassandra exposes its CQL native protocol for clients and a family of HTTP, REST, GraphQL, Document, and gRPC APIs via the Stargate data gateway.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cassandra/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Database, NoSQL, Distributed, Big Data, Apache, Open Source

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-23

## APIs

### Apache Cassandra CQL Native Protocol
Cassandra Query Language (CQL) is the primary interface to Apache Cassandra. Clients speak the binary CQL native protocol over TCP (default port 9042). Official drivers are maintained for Java, Python, Go, C/C++, C#, Node.js, Ruby, and Rust.

**Human URL:** [https://cassandra.apache.org/doc/latest/cassandra/cql/](https://cassandra.apache.org/doc/latest/cassandra/cql/)

#### Tags:

 - CQL, Query, Database, Native Protocol

#### Properties

- [Documentation](https://cassandra.apache.org/doc/latest/cassandra/cql/)
- [Specification](https://github.com/apache/cassandra/blob/trunk/doc/native_protocol_v5.spec)
- [Reference](https://cassandra.apache.org/doc/latest/cassandra/cql/ddl.html)

### Cassandra REST API (Stargate)
HTTP/JSON REST API for Cassandra provided by the Stargate data gateway. Enables CRUD operations and SQL-like query via REST without the CQL driver.

**Human URL:** [https://stargate.io/docs/latest/develop/api-rest/](https://stargate.io/docs/latest/develop/api-rest/)

#### Tags:

 - REST, Stargate, Database

#### Properties

- [Documentation](https://stargate.io/docs/latest/develop/api-rest/)
- [Swagger](https://stargate.io/docs/latest/develop/api-rest/swagger.html)
- [SourceCode](https://github.com/stargate/stargate)

### Cassandra GraphQL API (Stargate)
GraphQL endpoint for Cassandra, enabling flexible, typed queries and mutations against Cassandra tables through the Stargate gateway.

**Human URL:** [https://stargate.io/docs/latest/develop/api-graphql/](https://stargate.io/docs/latest/develop/api-graphql/)

#### Tags:

 - GraphQL, Stargate, Database

#### Properties

- [Documentation](https://stargate.io/docs/latest/develop/api-graphql/)
- [Reference](https://stargate.io/docs/latest/develop/api-graphql/graphql-using.html)

### Cassandra Document API (Stargate)
Schemaless Document API that stores JSON documents in Cassandra, offering a MongoDB-like developer experience backed by Cassandra.

**Human URL:** [https://stargate.io/docs/latest/develop/api-doc/](https://stargate.io/docs/latest/develop/api-doc/)

#### Tags:

 - Document, JSON, Stargate, Database

#### Properties

- [Documentation](https://stargate.io/docs/latest/develop/api-doc/)
- [Reference](https://stargate.io/docs/latest/develop/api-doc/doc-using.html)

### Cassandra gRPC API (Stargate)
High-performance gRPC API for Cassandra through Stargate, designed for low-latency service-to-service communication.

**Human URL:** [https://stargate.io/docs/latest/develop/api-grpc/](https://stargate.io/docs/latest/develop/api-grpc/)

#### Tags:

 - gRPC, Stargate, Database

#### Properties

- [Documentation](https://stargate.io/docs/latest/develop/api-grpc/)
- [Protocol](https://github.com/stargate/stargate/tree/main/grpc/proto)

### Cassandra JMX Management Interface
Java Management Extensions (JMX) interface for monitoring and administering Cassandra nodes, including metrics, compaction, repairs, and configuration.

**Human URL:** [https://cassandra.apache.org/doc/latest/cassandra/operating/metrics.html](https://cassandra.apache.org/doc/latest/cassandra/operating/metrics.html)

#### Tags:

 - JMX, Management, Metrics, Monitoring

#### Properties

- [Documentation](https://cassandra.apache.org/doc/latest/cassandra/operating/metrics.html)
- [OperationsGuide](https://cassandra.apache.org/doc/latest/cassandra/operating/)

## Common Properties

- [Website](https://cassandra.apache.org/)
- [Documentation](https://cassandra.apache.org/doc/latest/)
- [GettingStarted](https://cassandra.apache.org/doc/latest/cassandra/getting_started/)
- [Download](https://cassandra.apache.org/download/)
- [SourceCode](https://github.com/apache/cassandra)
- [GitHub](https://github.com/apache/cassandra)
- [IssueTracker](https://issues.apache.org/jira/projects/CASSANDRA)
- [Blog](https://cassandra.apache.org/blog/)
- [Community](https://cassandra.apache.org/community/)
- [MailingList](https://cassandra.apache.org/community/#discussions)
- [Slack](https://cassandra.apache.org/community/#slack)
- [StackOverflow](https://stackoverflow.com/questions/tagged/cassandra)
- [X](https://twitter.com/cassandra)
- [LinkedIn](https://www.linkedin.com/company/apache-cassandra/)
- [YouTube](https://www.youtube.com/@PlanetCassandra)
- [DockerHub](https://hub.docker.com/_/cassandra)
- [PackageRegistry](https://central.sonatype.com/artifact/org.apache.cassandra/cassandra-all)
- [License](https://www.apache.org/licenses/LICENSE-2.0)
- [Governance](https://www.apache.org/foundation/governance/)
- [SecurityPolicy](https://cassandra.apache.org/_/security.html)
- [PrivacyPolicy](https://www.apache.org/privacy/)
- [TermsOfService](https://www.apache.org/foundation/license-faq.html)
- [Ecosystem](https://cassandra.apache.org/_/ecosystem.html)

## Maintainers

**FN:** Apache Cassandra Community

**Email:** dev@cassandra.apache.org
