<div align="center">
  <a href="https://github.com/parqdb-io/parqdb">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/parqdb-io/parqdb/docs/vision-centents/assets/parqdb/logo-dark.svg">
      <img src="https://raw.githubusercontent.com/parqdb-io/parqdb/docs/vision-centents/assets/parqdb/logo.svg" alt="ParqDB" width="520">
    </picture>
  </a>
</div>

> ParqDB 是一个把数据和索引都放进 Parquet 的嵌入式向量数据库。

向量索引不该是只有一套服务读得懂的黑盒。ParqDB 直接用 Parquet 存索引：
能做版本管理，能独立发布，也能在不同引擎之间共享。

- **小机器也能搜大数据**：用 2 个 CPU 核心、4 GB 内存搜索 10 亿向量，召回率 90.3%，中位延迟 63.05 ms
- **数据和索引都是 Parquet**：不用导入专有格式，也不用把整份索引塞进内存
- **向量搜索就是 SQL**：过滤、连接、聚合和 Top-K 在同一个执行计划中完成
- **一份索引，到处可用**：本地构建的索引，可以交给嵌入式或分布式计算引擎直接查询
- **既能在线服务，也能分析**：可以跨查询并行追求吞吐，也可以在单次查询内并行降低延迟

## ParqDB 是什么？

- 一个装进 Python 进程就能运行的向量数据库
- 一套开放、可移植的 Parquet 向量索引格式
- 一条从单机有限内存搜索走向集群计算的平滑路径

## 立即开始

```bash
python -m pip install parqdb
```

继续阅读：[项目主页](https://github.com/parqdb-io/parqdb) ·
[快速入门](https://github.com/parqdb-io/parqdb/blob/main/docs/getting-started.md) ·
[索引格式](https://github.com/parqdb-io/parqdb/tree/main/spec) ·
[English README](https://github.com/parqdb-io/parqdb/blob/main/README.md)

ParqDB 采用 [MIT 与 Apache-2.0 双许可证](https://github.com/parqdb-io/parqdb/blob/main/LICENSE)开源。
