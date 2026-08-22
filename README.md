# Apache Doris (apache-doris)

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

Apache Doris is a high-performance, real-time analytical database based on MPP (Massively Parallel Processing) architecture, governed by the Apache Software Foundation. It provides MySQL-protocol-compatible SQL queries, sub-second query latency on large-scale data, columnar storage with vectorized execution, real-time upsert via Stream Load and Routine Load APIs, and federated querying over data lakes (Hive, Iceberg, Hudi). It supports both shared-nothing and storage/compute-separated deployment modes.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Apache, Database, Lakehouse, MPP, OLAP, Open Source, Real-Time, SQL

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Doris
Apache Doris provides a MySQL-compatible protocol for SQL queries, a REST API for cluster management and monitoring, Stream Load HTTP API for real-time bulk data ingestion, Routine Load for continuous Kafka ingestion, and connectors for Flink, Spark, and Kafka. An MCP server is also available for AI-assisted analytics.

**Human URL:** [https://doris.apache.org/docs/dev/summary/basic-summary](https://doris.apache.org/docs/dev/summary/basic-summary)

#### Tags:

 - Analytics, Connectors, Data Ingestion, Flink, Kafka, MySQL, REST, SQL, Spark, Stream Load

#### Properties

- [Documentation](https://doris.apache.org/docs/dev/summary/basic-summary)
- [GettingStarted](https://doris.apache.org/docs/dev/install/)
- [APIReference](https://doris.apache.org/docs/dev/admin-manual/http-actions/)
- [GitHubRepository](https://github.com/apache/doris)
- [MCP Server](https://github.com/apache/doris-mcp-server)
- [Flink Connector](https://github.com/apache/doris-flink-connector)
- [Spark Connector](https://github.com/apache/doris-spark-connector)
- [Kafka Connector](https://github.com/apache/doris-kafka-connector)
- [Kubernetes Operator](https://github.com/apache/doris-operator)
- [Stream Loader CLI](https://github.com/apache/doris-streamloader)
- [Routine Load Job](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/json-schema/apache-doris-routine-load-job-schema.json)
- [Stream Load Response](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/json-schema/apache-doris-stream-load-response-schema.json)
- [Table Schema](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/json-schema/apache-doris-table-schema-schema.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/json-structure/apache-doris-routine-load-job-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/json-structure/apache-doris-stream-load-response-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/json-structure/apache-doris-table-schema-structure.json)
- [JSONLD](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/json-ld/apache-doris-context.jsonld)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/examples/apache-doris-routine-load-job-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/examples/apache-doris-stream-load-response-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/examples/apache-doris-table-schema-example.json)

## Common Properties

- [Portal](https://doris.apache.org/)
- [Documentation](https://doris.apache.org/docs/dev/)
- [GettingStarted](https://doris.apache.org/docs/dev/install/)
- [Blog](https://doris.apache.org/blog/)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/doris)
- [StackOverflow](https://stackoverflow.com/questions/tagged/apache-doris)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/vocabulary/apache-doris-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| MPP Columnar Analytics | Massively parallel processing with columnar storage and vectorized execution engine for high-concurrency sub-second analytical queries. |
| Stream Load API | HTTP-based bulk data ingestion API that loads CSV, JSON, and Parquet data in real time with transactional guarantees. |
| MySQL Protocol Compatibility | Fully MySQL-wire-protocol compatible, enabling use of standard MySQL clients, drivers, and BI tools without modification. |
| Federated Data Lakehouse Queries | Query external data in Hive, Iceberg, Hudi, and Delta Lake tables without data movement using Multi-Catalog. |
| Real-Time Upsert (Unique Key Model) | Primary key based upsert model supports real-time CDC data ingestion with micro-second latency row-level updates. |
| Routine Load from Kafka | Continuous data ingestion from Apache Kafka topics with automatic offset management and exactly-once semantics. |
| Tiered Storage | Hot/warm/cold data tiering with object storage (S3, HDFS) for cost-optimized storage at scale. |
| MCP Server | Model Context Protocol (MCP) server enabling AI agents to query Doris databases through natural language. |

## Use Cases

| Name | Description |
|------|-------------|
| Real-Time Dashboards and Reporting | Power business intelligence dashboards with sub-second query latency on live data updated continuously. |
| Log and Event Analytics | Ingest and analyze high-volume log, metric, and event data in real time using inverted indexes and full-text search. |
| Customer Data Platform | Consolidate customer behavioral and transactional data from multiple sources for real-time segmentation and analytics. |
| Data Lakehouse Analytics | Federate queries across data lake (Hive, Iceberg) and operational databases without ETL movement. |
| Ad-Hoc Analytics | Enable data analysts to run complex exploratory SQL queries on petabyte-scale datasets with fast response times. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Flink | Official Flink Connector for reading from and writing to Doris in real-time Flink streaming pipelines. |
| Apache Spark | Official Spark Connector for batch ETL and analytics workflows using Apache Spark. |
| Apache Kafka | Kafka Connector and Routine Load for continuous real-time data ingestion from Kafka topics. |
| Apache Iceberg / Hudi / Hive | Multi-Catalog feature enables federated queries over Iceberg, Hudi, and Hive Metastore data lakes. |
| Kubernetes | Official Kubernetes Operator for automated Doris cluster lifecycle management. |
| OpenTelemetry | OpenTelemetry demo integration for observability and tracing in Doris deployments. |

## Artifacts

Machine-readable schemas for Apache Doris data ingestion and table management models.

### JSON Schema

- [Routine Load Job](json-schema/apache-doris-routine-load-job-schema.json)
- [Stream Load Response](json-schema/apache-doris-stream-load-response-schema.json)
- [Table Schema](json-schema/apache-doris-table-schema-schema.json)

### JSON Structure

- [Routine Load Job](json-structure/apache-doris-routine-load-job-structure.json)
- [Stream Load Response](json-structure/apache-doris-stream-load-response-structure.json)
- [Table Schema](json-structure/apache-doris-table-schema-structure.json)

### JSON-LD

- [Apache Doris](json-ld/apache-doris-context.jsonld)

### Examples

- [Routine Load Job](examples/apache-doris-routine-load-job-example.json)
- [Stream Load Response](examples/apache-doris-stream-load-response-example.json)
- [Table Schema](examples/apache-doris-table-schema-example.json)

## Vocabulary

- [Apache Doris Vocabulary](vocabulary/apache-doris-vocabulary.yaml) — Taxonomy mapping 6 resources, 6 actions, and 3 personas across Apache Doris real-time analytics

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
