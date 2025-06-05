# Awesome-DBGiant-Industry-Paper [![666](https://awesome.re/badge.svg)](https://awesome.re)

[![Awesome DBGiant Industry Paper](https://img.shields.io/static/v1?label=&message=Awesome+DBGiant+Industry+Paper&color=black&logo=awesomelists)](https://github.com/Wind-Gone/awesome-dbgiant-Industry-paper)
![](https://img.shields.io/github/last-commit/Wind-Gone/awesome-dbgiant-Industry-paper?color=green)
![visitor badge](https://visitor-badge.lithub.cc/badge?page_id=Wind-Gone.awesome-dbgiant-Industry-paper)
[![GitHub Repo stars](https://img.shields.io/github/stars/Wind-Gone/awesome-dbgiant-Industry-paper?style=social)](https://github.com/Wind-Gone/awesome-dbgiant-Industry-paper)
[![GitHub Repo forks](https://img.shields.io/github/forks/Wind-Gone/awesome-dbgiant-Industry-paper?style=social)](https://github.com/Wind-Gone/awesome-dbgiant-Industry-paper)
## Introduction

A curated paper list of awesome <b>industry papers from various giant database vendors</b> and other awesomeness, for database researchers/engineers.

## Contributing

The repository is under construction.  Welcome new PR, please conform to the committed rules: 

```bash
paperName(with pdf link) [MeetingName Year] Github link if it has open-sourced code (optional)
```
## Acknowledge
Thanks to all authors of the paper/repository I cite :D

## Table of Content

- [Awesome-DBGiant-Industry-Paper ](#awesome-dbgiant-industry-paper-)
  - [Introduction](#introduction)
  - [Contributing](#contributing)
  - [Acknowledge](#acknowledge)
  - [Table of Content](#table-of-content)
  - [Google](#google)
  - [Amazaon](#amazaon)
  - [Tencent](#tencent)
  - [Alibaba](#alibaba)
    - [OceanBase](#oceanbase)
    - [PolarDB](#polardb)
  - [Oracle](#oracle)
  - [Bytedance](#bytedance)
  - [Huawei](#huawei)
  - [Microsoft](#microsoft)
  - [Intel](#intel)
  - [Meta](#meta)
  - [Snowflake](#snowflake)
  - [Databrics](#databrics)
  - [SingleStore](#singlestore)
  - [ClickHouse](#clickhouse)
  - [Star History](#star-history)


## Google
1. [Progressive Partitioning for Parallelized Query Execution in Google’s Napa](https://www.vldb.org/pvldb/vol16/p3475-sankaranarayanan.pdf) [VLDB 23]
2. [Keep Your Distributed Data Warehouse Consistent at a Minimal Cost](https://dl.acm.org/doi/pdf/10.1145/3589770) [SIGMOD 23]

## Amazaon
1. [Amazon Redshift and the Case for Simpler Data Warehouses](https://15721.courses.cs.cmu.edu/spring2024/papers/22-redshift/p1917-gupta.pdf) [SIGMOD 15]
2. [Amazon Redshift Re-invented](https://15721.courses.cs.cmu.edu/spring2024/papers/22-redshift/redshift-sigmod2022.pdf) [SIGMOD 22]
3. [Amazon DynamoDB: A Scalable, Predictably Performant, and Fully Managed NoSQL Database Service](https://www.usenix.org/system/files/atc22-elhemali.pdf) [OSDI 22]
4. [The Story of AWS Glue](https://www.vldb.org/pvldb/vol16/p3557-saxena.pdf) [VLDB 23]
5. [Auto-WLM: ML-enhanced workload management in Amazon Redshift](https://dl.acm.org/doi/pdf/10.1145/3555041.3589677) [SIGMOD 23]
6. [Resource Management in Aurora Serverless](https://www.vldb.org/pvldb/vol17/p4038-urgaonkar.pdf) [VLDB 24]

## Tencent
1. [Angel-PTM: A Scalable and Economical Large-scale Pre-training System in Tencent](https://arxiv.org/pdf/2303.02868.pdf) [VLDB 23]
2. [EmbedX: A Versatile, Efficient and Scalable Platform to Embed Both Graphs and High-Dimensional Sparse Data](https://dl.acm.org/doi/pdf/10.14778/3611540.3611546) [VLDB 23]
3. [Towards General and Efficient Online Tuning for Spark](https://arxiv.org/pdf/2309.01901v1.pdf) [VLDB 23]
4. [TDSQL: Tencent Distributed Database System](https://www.vldb.org/pvldb/vol17/p3869-chen.pdf) [VLDB 24]


## Alibaba
1. [Eigen: End-to-end Resource Optimization for Large-Scale Databases on the Cloud](https://dl.acm.org/doi/pdf/10.14778/3611540.3611565) [VLDB 23]
2. [Anser: Adaptive Information Sharing Framework of AnalyticDB](https://dl.acm.org/doi/pdf/10.14778/3611540.3611553) [VLDB 23]
3. [Lindorm TSDB: A Cloud-native Time-series Database for Large-scale Monitoring Systems](https://dl.acm.org/doi/pdf/10.14778/3611540.3611559) [VLDB 23]
4. [Vineyard: Optimizing Data Sharing in Data-Intensive Analytics](https://dl.acm.org/doi/pdf/10.1145/3589780) [SIGMOD 23]
5. [Flux: Decoupled Auto-Scaling for Heterogeneous Query Workload in Alibaba AnalyticDB](https://dl.acm.org/doi/pdf/10.1145/3626246.3653381) [SIGMOD 24]
### OceanBase
1. [OceanBase Paetica: A Hybrid Shared-nothing/Shared-everything Database for Supporting Single Machine and Distributed Cluster](https://www.vldb.org/pvldb/vol16/p3728-xu.pdf) [VLDB 23]

### PolarDB
1. [PolarDB-SCC: A Cloud-Native Database Ensuring Low Latency for Strongly Consistent Reads](https://www.vldb.org/pvldb/vol16/p3754-chen.pdf) [VLDB 23]
2. [PolarDB-IMCI:A Cloud-Native HTAP Database System at Alibaba](https://arxiv.org/pdf/2305.08468.pdf) [SIGMOD 23]
3. [PolarDB-MP: A Multi-Primary Cloud-Native Database via Disaggregated Shared Memory](https://dl.acm.org/doi/10.1145/3626246.3653377) [SIGMOD 24]


## Oracle
1. [Automatic SQL Error Mitigation in Oracle](https://dl.acm.org/doi/pdf/10.14778/3611540.3611568) [VLDB 23]
2. [Grouping, Subsumption, and Disjunctive Join Optimizations in Oracle](https://www.vldb.org/pvldb/vol17/p4200-pasupuleti.pdf) [VLDB 24]

## Bytedance
1. [ByteHTAP: ByteDance’s HTAP System with High Data Freshness and Strong Data Consistency](https://www.vldb.org/pvldb/vol15/p3411-chen.pdf) [VLDB 22]
2. [Krypton: Real-time Serving and Analytical SQL Engine at ByteDance](https://www.vldb.org/pvldb/vol16/p3528-chen.pdf) [VLDB 23]
3. [VeDB: A Software and Hardware Enabled Trusted Relational Database](https://dl.acm.org/doi/pdf/10.1145/3589774) [SIGMOD 23]
4. [LavaStore: ByteDance's Purpose-built, High-performance, Cost-effective Local Storage Engine for Cloud Services](https://www.vldb.org/pvldb/vol17/p3799-jiao.pdf) [VLDB 24]

## Huawei
1. [Taurus MM: bringing multi-master to the cloud](https://www.vldb.org/pvldb/vol16/p3488-depoutovitch.pdf) [VLDB 23]
2. [GaussDB: A Cloud-Native Multi-Primary Database with Compute-Memory-Storage Disaggregation](https://www.vldb.org/pvldb/vol17/p3786-li.pdf) [VLDB 24]

## Microsoft
1. [POLARIS: The Distributed SQL Engine in Azure Synapse](https://15721.courses.cs.cmu.edu/spring2024/papers/23-synapse/p3204-saborit.pdf) [VLDB 20]
2. [Microsoft Purview: A System for Central Governance of Data](https://dl.acm.org/doi/pdf/10.14778/3611540.3611552) [VLDB 23]
3. [OneProvenance: Efficient Extraction of Dynamic Coarse-Grained Provenance From Database Query Event Logs](https://arxiv.org/pdf/2210.14047.pdf) [VLDB 23]
4. [Towards Building Autonomous Data Services on Azure](https://dl.acm.org/doi/pdf/10.1145/3555041.3589674) [SIGMOD 23]

## Intel
1. [Big Data Analytic Toolkit: A general-purpose, modular, and heterogeneous acceleration toolkit for data analytical engines](https://dl.acm.org/doi/pdf/10.14778/3611540.3611558) [VLDB 23]

## Meta
1. [Presto: A Decade of SQL Analytics at Meta](https://scontent.fbkk10-1.fna.fbcdn.net/v/t39.8562-6/338697424_1576642486169536_1067048833935401645_n.pdf?_nc_cat=110&ccb=1-7&_nc_sid=ad8a9d&_nc_ohc=DZpvN_qgbKYAX-CuZCe&_nc_ht=scontent.fbkk10-1.fna&oh=00_AfCbkBqoOtDXSp22jQBY4iKnzbV4DS_aYqPc1XumlWSKPg&oe=65047997) [SIGMOD 23]
2. [Disaggregating RocksDB: A Production Experience](https://scontent.fbkk10-1.fna.fbcdn.net/v/t39.8562-6/356990181_787184386211320_3255498706838241035_n.pdf?_nc_cat=106&ccb=1-7&_nc_sid=ad8a9d&_nc_ohc=8oLZBKS9wE4AX-oY4TG&_nc_ht=scontent.fbkk10-1.fna&oh=00_AfDOk7z_tBa89Hpz1HsslZNLrH8DrRsWRpCOrWC5a0b69w&oe=6504A5BC) [SIGMOD 23]

## Snowflake
1. [The Snowflake Elastic Data Warehouse](https://15721.courses.cs.cmu.edu/spring2024/papers/19-snowflake/p215-dageville-snowflake.pdf) [SIGMOD 16]
2. [Building An Elastic Query Engine on Disaggregated Storage](https://15721.courses.cs.cmu.edu/spring2024/papers/19-snowflake/vuppalapati-nsdi22.pdf) [OSDI 20]
3. [What’s the difference? Incremental processing with change queries in Snowflake](https://dl.acm.org/doi/pdf/10.1145/3589776) [SIGMOD 23]

## Databrics
1. [Photon: A Fast Query Engine for Lakehouse Systems](https://15721.courses.cs.cmu.edu/spring2024/papers/18-databricks/sigmod_photon.pdf) [SIGMOD 22]

## SingleStore
1. [Cloud-Native Transactions and Analytics in SingleStore](https://dl.acm.org/doi/pdf/10.1145/3514221.3526055) [SIGMOD 22]
2. [SingleStore-V: An Integrated Vector Database System in SingleStore](https://www.vldb.org/pvldb/vol17/p3772-chen.pdf) [VLDB 24]


## ClickHouse
1. [ClickHouse - Lightning Fast Analytics for Everyone](https://www.vldb.org/pvldb/vol17/p3731-schulze.pdf) [VLDB 24]


## Star History

<a href="https://star-history.com/#Wind-Gone/awesome-dbgiant-Industry-paper&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Wind-Gone/awesome-dbgiant-Industry-paper&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Wind-Gone/awesome-dbgiant-Industry-paper&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Wind-Gone/awesome-dbgiant-Industry-paper&type=Date" />
  </picture>
</a>