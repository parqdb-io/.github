<div align="center">
  <a href="https://github.com/parqdb-io/parqdb">
    <img src="https://raw.githubusercontent.com/parqdb-io/parqdb/main/assets/parqdb-header.svg" alt="ParqDB" width="760">
  </a>
</div>

> ParqDB is a billion-scale embedded vector database built entirely on Parquet and Arrow.

### Why ParqDB

- **Billion-scale search in bounded memory.** Search larger-than-memory vector datasets on modest hardware.
- **Everything is Parquet.** Source data and vector indexes use an open, portable storage format that can be versioned, published, and shared.
- **SQL-native vector search.** Combine similarity search with filters, joins, projections, and aggregations in one relational plan.
- **Serving and analytics.** Parallelize across queries for throughput or within a query for low-latency analytical and large-k search.
- **One index, multiple engines.** Build locally and use the same Parquet index across embedded and distributed execution environments.

### Get started

```bash
python -m pip install parqdb
```

Explore the [ParqDB repository](https://github.com/parqdb-io/parqdb), follow the
[getting-started guide](https://github.com/parqdb-io/parqdb/blob/main/docs/getting-started.md),
or read the [open index specification](https://github.com/parqdb-io/parqdb/tree/main/spec).

ParqDB is open source under the [MIT and Apache-2.0 licenses](https://github.com/parqdb-io/parqdb/blob/main/LICENSE).
