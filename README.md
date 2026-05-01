# Google BigQuery (google-bigquery)
Google BigQuery is a fully managed, serverless data warehouse provided by Google Cloud that enables organizations to analyze massive datasets using SQL. Its developer platform offers REST APIs for managing datasets, tables, jobs, models, and routines, along with high-throughput storage APIs and tools for migrating workloads from other data platforms.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/google-bigquery/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Data Warehouse, Analytics, SQL, Big Data, Cloud, Serverless

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-04-28

## APIs

### BigQuery API
The BigQuery API provides programmatic access to Google BigQuery for creating, managing, and querying datasets, tables, jobs, and other BigQuery resources. Developers can use the API to load data, run queries, export results, and manage access control on BigQuery resources. The API supports SQL-based analytics over petabytes of data with serverless infrastructure.

**Human URL:** [https://cloud.google.com/bigquery/docs](https://cloud.google.com/bigquery/docs)


#### Tags:

 - Data Warehouse, SQL, Analytics, Queries, Datasets

#### Properties

- [Documentation](https://cloud.google.com/bigquery/docs/reference/rest)
- [OpenAPI](openapi/bigquery-api-openapi.yml)
- [JSONSchema](json-schema/google-bigquery-query-schema.json)
- [JSONSchema](json-schema/google-bigquery-table-schema.json)

### BigQuery Connection API
The BigQuery Connection API enables developers to create and manage connections between BigQuery and external data sources such as Cloud SQL, Cloud Spanner, and other databases. These connections allow BigQuery to query data in external sources without moving or copying data. The API supports creating, updating, deleting, and listing connections as well as managing IAM policies on connections.

**Human URL:** [https://cloud.google.com/bigquery/docs/reference/bigqueryconnection/rest](https://cloud.google.com/bigquery/docs/reference/bigqueryconnection/rest)


#### Tags:

 - Connections, External Data, Federation

#### Properties

- [Documentation](https://cloud.google.com/bigquery/docs/reference/bigqueryconnection/rest)

### BigQuery Migration API
The BigQuery Migration API provides tools for migrating data warehouse workloads to BigQuery from other platforms. It supports assessment and planning of migration tasks, translation of SQL dialects, and orchestration of migration workflows. The API helps enterprises move their analytics workloads to BigQuery with automated tooling and migration tracking.

**Human URL:** [https://cloud.google.com/bigquery/docs/reference/migration/rest](https://cloud.google.com/bigquery/docs/reference/migration/rest)


#### Tags:

 - Migration, Data Migration, SQL Translation

#### Properties

- [Documentation](https://cloud.google.com/bigquery/docs/reference/migration/rest)

### BigQuery Reservation API
The BigQuery Reservation API allows developers to manage slot reservations and capacity commitments for BigQuery compute resources. It provides programmatic control over how compute capacity is allocated across projects and organizations, enabling cost optimization and workload management. The API supports creating reservations, managing assignments, and purchasing capacity commitments.

**Human URL:** [https://cloud.google.com/bigquery/docs/reference/reservations/rest](https://cloud.google.com/bigquery/docs/reference/reservations/rest)


#### Tags:

 - Reservations, Capacity, Compute

#### Properties

- [Documentation](https://cloud.google.com/bigquery/docs/reference/reservations/rest)

### BigQuery Storage API
The BigQuery Storage API provides high-throughput read and write access to BigQuery managed storage. It enables developers to read data from BigQuery tables using an efficient streaming protocol that is significantly faster than the traditional tabledata.list method. The API supports parallel reads, column filtering, and row filtering to optimize data transfer performance.

**Human URL:** [https://cloud.google.com/bigquery/docs/reference/storage](https://cloud.google.com/bigquery/docs/reference/storage)


#### Tags:

 - Storage, Streaming, High Throughput

#### Properties

- [Documentation](https://cloud.google.com/bigquery/docs/reference/storage)

## Common Properties

- [GettingStarted](https://cloud.google.com/bigquery/docs/quickstarts)
- [Pricing](https://cloud.google.com/bigquery/pricing)
- [Authentication](https://cloud.google.com/bigquery/docs/authentication)
- [Console](https://console.cloud.google.com/bigquery)
- [CLI](https://cloud.google.com/bigquery/docs/reference/bq-cli-reference)
- [SDKs](https://cloud.google.com/bigquery/docs/reference/libraries)
- [Support](https://cloud.google.com/bigquery/docs/support)
- [Status](https://status.cloud.google.com)
- [JSON-LD](json-ld/google-bigquery-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
