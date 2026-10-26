# Apache Cassandra (cassandra)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
