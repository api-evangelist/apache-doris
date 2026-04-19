# Apache Doris (apache-doris)
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
