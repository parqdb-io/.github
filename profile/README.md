<div align="center">
  <a href="https://github.com/parqdb-io/parqdb">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/parqdb-io/parqdb/blob/main/assets/parqdb/logo-dark.svg">
      <img src="https://github.com/parqdb-io/parqdb/blob/main/assets/parqdb/logo.svg" alt="ParqDB" width="520">
    </picture>
  </a>
</div>

> Billion-scale embedded vector database built entirely on Parquet and Arrow.

ParqDB is an embedded vector database for larger-than-memory search and analytics
on billion-scale multimodal data, with Parquet storage and Arrow-native execution.

- **Billion-scale search in bounded memory.** Search 1B vectors at 90.3% recall with 63.05 ms median latency using just 2 CPU cores and 4 GB of memory.
- **Everything is Parquet.** Source data and vector indexes use standard Parquet rather than proprietary binary formats.
- **Multimodal data, SQL-native search.** Combine vector search with filters, joins, and aggregations in one execution plan.
- **Built for serving and analytics.** Parallelize across queries for throughput, or within one query for low-latency analytical and large-k search.
- **Scale from one core to thousands.** Run embedded on one machine, then use the same Parquet index with Spark or StarRocks at cluster scale.

## Quick start

```bash
python -m pip install parqdb
```

Continue with the [project repository](https://github.com/parqdb-io/parqdb),
[getting-started guide](https://github.com/parqdb-io/parqdb/blob/main/docs/getting-started.md),
or [open index specification](https://github.com/parqdb-io/parqdb/tree/main/spec).

ParqDB is open source under the [MIT and Apache-2.0 licenses](https://github.com/parqdb-io/parqdb/blob/main/LICENSE).
