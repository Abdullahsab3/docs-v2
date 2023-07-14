---
title: Execute SQL queries
seotitle: Execute SQL queries for data in InfluxDB Cloud Serverless
description: >
  Use tools and libraries to query data with SQL stored in InfluxDB Cloud Serverless.
weight: 103
menu:
  influxdb_cloud_serverless:
    name: Execute SQL queries
    parent: Query with SQL
influxdb/cloud-serverless/tags: [query]
aliases:
  - /influxdb/cloud-serverless/query-data/execute-queries/
  - /influxdb/cloud-serverless/query-data/tools/
---

The InfluxDB SQL implementation uses [Arrow DataFusion](https://arrow.apache.org/datafusion/)
and the [Apache Arrow Flight SQL](https://arrow.apache.org/) protocol to query
data stored in an InfluxDB database.

> Arrow Flight SQL is a protocol for interacting with SQL databases using the
> [Arrow in-memory format](https://arrow.apache.org/docs/format/Columnar.html)
> and the [Flight RPC](https://arrow.apache.org/docs/format/Flight.html) framework.
>
> {{% caption %}}[Apache Arrow Flight SQL documentation](https://arrow.apache.org/docs/format/FlightSql.html){{% /caption %}}

Data platforms and clients that support the Flight SQL protocol can query data
stored in an InfluxDB database.
Learn how to connect to InfluxDB and query your data using the following tools:

---

{{< children readmore=true hr=true hlevel="h2" >}}