# Google BigQuery (google-bigquery)

Google BigQuery is a fully managed, serverless data warehouse that enables scalable analysis over petabytes of data using SQL.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-bigquery/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-bigquery/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Analytics
- Big Data
- Cloud
- Data Warehouse
- Serverless
- SQL

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### BigQuery API

The BigQuery API provides programmatic access to Google BigQuery for creating, managing, and querying datasets, tables, jobs, and other BigQuery resources. Developers can use the API to load data, run queries, export results, and manage access control on BigQuery resources. The API supports SQL-based analytics over petabytes of data with serverless infrastructure.

- **Human URL:** [https://cloud.google.com/bigquery/docs](https://cloud.google.com/bigquery/docs)
- **Base URL:** `https://bigquery.googleapis.com`

#### Tags

- Analytics
- Data Warehouse
- Datasets
- Queries
- SQL

#### Properties

- [Documentation](https://cloud.google.com/bigquery/docs/reference/rest)
- [OpenAPI](openapi/bigquery-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bigquery-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigquery-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/google-bigquery-query-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/google-bigquery-table-schema.json) — [JSON Schema](https://json-schema.org/specification)

### BigQuery Connection API

The BigQuery Connection API enables developers to create and manage connections between BigQuery and external data sources such as Cloud SQL, Cloud Spanner, and other databases. These connections allow BigQuery to query data in external sources without moving or copying data. The API supports creating, updating, deleting, and listing connections as well as managing IAM policies on connections.

- **Human URL:** [https://cloud.google.com/bigquery/docs/reference/bigqueryconnection/rest](https://cloud.google.com/bigquery/docs/reference/bigqueryconnection/rest)
- **Base URL:** `https://bigqueryconnection.googleapis.com`

#### Tags

- Connections
- External Data
- Federation

#### Properties

- [Documentation](https://cloud.google.com/bigquery/docs/reference/bigqueryconnection/rest)
- [Postman Collection](collections/bigquery-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigquery-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BigQuery Migration API

The BigQuery Migration API provides tools for migrating data warehouse workloads to BigQuery from other platforms. It supports assessment and planning of migration tasks, translation of SQL dialects, and orchestration of migration workflows. The API helps enterprises move their analytics workloads to BigQuery with automated tooling and migration tracking.

- **Human URL:** [https://cloud.google.com/bigquery/docs/reference/migration/rest](https://cloud.google.com/bigquery/docs/reference/migration/rest)
- **Base URL:** `https://bigquerymigration.googleapis.com`

#### Tags

- Data Migration
- Migration
- SQL Translation

#### Properties

- [Documentation](https://cloud.google.com/bigquery/docs/reference/migration/rest)
- [Postman Collection](collections/bigquery-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigquery-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BigQuery Reservation API

The BigQuery Reservation API allows developers to manage slot reservations and capacity commitments for BigQuery compute resources. It provides programmatic control over how compute capacity is allocated across projects and organizations, enabling cost optimization and workload management. The API supports creating reservations, managing assignments, and purchasing capacity commitments.

- **Human URL:** [https://cloud.google.com/bigquery/docs/reference/reservations/rest](https://cloud.google.com/bigquery/docs/reference/reservations/rest)
- **Base URL:** `https://bigqueryreservation.googleapis.com`

#### Tags

- Capacity
- Compute
- Reservations

#### Properties

- [Documentation](https://cloud.google.com/bigquery/docs/reference/reservations/rest)
- [Postman Collection](collections/bigquery-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigquery-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BigQuery Storage API

The BigQuery Storage API provides high-throughput read and write access to BigQuery managed storage. It enables developers to read data from BigQuery tables using an efficient streaming protocol that is significantly faster than the traditional tabledata.list method. The API supports parallel reads, column filtering, and row filtering to optimize data transfer performance.

- **Human URL:** [https://cloud.google.com/bigquery/docs/reference/storage](https://cloud.google.com/bigquery/docs/reference/storage)
- **Base URL:** `https://bigquerystorage.googleapis.com`

#### Tags

- High Throughput
- Storage
- Streaming

#### Properties

- [Documentation](https://cloud.google.com/bigquery/docs/reference/storage)
- [Postman Collection](collections/bigquery-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigquery-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/googleapis)
- [Getting Started](https://cloud.google.com/bigquery/docs/quickstarts)
- [Pricing](https://cloud.google.com/bigquery/pricing)
- [Authentication](https://cloud.google.com/bigquery/docs/authentication)
- [Console](https://console.cloud.google.com/bigquery)
- [C L I](https://cloud.google.com/bigquery/docs/reference/bq-cli-reference)
- [S D Ks](https://cloud.google.com/bigquery/docs/reference/libraries)
- [Support](https://cloud.google.com/bigquery/docs/support)
- [Status Page](https://status.cloud.google.com)
- [JSON-LD](json-ld/google-bigquery-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://cloud.google.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
