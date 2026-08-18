<div align="center">
  <a href="https://github.com/parqdb-io/parqdb">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/parqdb-io/parqdb/docs/vision-centents/assets/parqdb/logo-dark.svg">
      <img src="https://raw.githubusercontent.com/parqdb-io/parqdb/docs/vision-centents/assets/parqdb/logo.svg" alt="ParqDB" width="520">
    </picture>
  </a>
</div>

> ParqDB is an embedded vector database that stores both data and indexes in Parquet.

Vector indexes should not be opaque files understood by only one service.
ParqDB makes indexes portable: version them, publish them, and query them from
different engines without changing formats.

- **Billion-scale search on modest hardware:** 1B vectors, 90.3% recall, and 63.05 ms median latency with 2 CPU cores and 4 GB of memory
- **Parquet all the way down:** no proprietary import format and no requirement to keep the full index in memory
- **Vector search is SQL:** filters, joins, aggregations, and Top-K stay in one execution plan
- **Build once, query anywhere:** use the same index from embedded and distributed compute engines
- **Serving and analytics:** parallelize across queries for throughput or within one query for low latency

## What is ParqDB?

- A vector database that runs inside your Python process
- An open, portable vector-index format built on Parquet
- A path from bounded-memory search on one machine to cluster-scale execution

## Quick start

```bash
python -m pip install parqdb
```

Continue with the [project repository](https://github.com/parqdb-io/parqdb),
[getting-started guide](https://github.com/parqdb-io/parqdb/blob/main/docs/getting-started.md),
or [open index specification](https://github.com/parqdb-io/parqdb/tree/main/spec).

ParqDB is open source under the [MIT and Apache-2.0 licenses](https://github.com/parqdb-io/parqdb/blob/main/LICENSE).
