# ⚡ Awesome Streaming Data API 🚀

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Streaming Data API Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Streaming-Data-API"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Streaming-Data-API?style=flat-square&color=gold" alt="GitHub Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Streaming-Data-API/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Streaming-Data-API?style=flat-square" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Streaming-Data-API/stargazers"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Streaming-Data-API?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 📌 Top Streaming Data API Ecosystem & Real-Time Event Architecture 📡

> **Curated List of SaaS Products & Open-Source GitHub Projects**  
> *Focused on Event Streaming, Real-Time Data Pipelines, Change Data Capture (CDC) & Self-Hosted Streaming Backends*  
> **Last updated: October 2026** 📅

This repository tracks notable **commercial streaming data APIs** and **open-source projects** that ingest, transport, and process continuous data streams — from cloud-native event buses to self-hosted Kafka-compatible backends and real-time pub/sub messaging platforms.

---

## 🗺️ Table of Contents
- [☁️ SaaS / Hosted Streaming Platforms](#-saas--hosted-streaming-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## ☁️ SaaS / Hosted Streaming Platforms

### 📊 Sector Market Size & Market Structure

The global **Streaming Data API and Event-Driven Architecture Market** is estimated at **$28.5 Billion (2026)** and is projected to expand at a CAGR of **21.4%**. 

The sector is **moderately fragmented**: 
- **Cloud Hyperscalers** (AWS, Google Cloud, Microsoft Azure) and mega enterprise platforms (Salesforce, Confluent) dominate enterprise infrastructure and baseline message transport.
- **Specialized Real-Time Platforms** (Ably, Pusher, Redpanda, Upstash, Decodable) capture developer-first, serverless, and niche high-performance pub/sub applications.

---

### 🏢 Hosted & Cloud Streaming Platform Matrix

*(Sorted by Company Size / Valuation / Revenue Descending)*

| Product / Platform 🚀 | Company Size / Valuation 📊 | Starting Tier Pricing 💰 | Free Tier / Free Trial Limits 🎁 | Description & Best Use Case 🎯 |
| :--- | :--- | :--- | :--- | :--- |
| **[Google Cloud Dataflow](https://cloud.google.com/dataflow)** | ~$2.4 Trillion Mkt Cap (Alphabet) | $0.056 / vCPU-hour + $0.009 / GB-hour | 90-day $300 free trial credits across GCP services | Fully managed stream & batch processing based on Apache Beam. Best for GCP-native unified streaming pipelines. |
| **[AWS Kinesis Data Streams](https://aws.amazon.com/kinesis/data-streams/)** | ~$2.0 Trillion Mkt Cap (Amazon) | $0.015 / shard-hour + $0.014 / GB payload | AWS Free Tier: 2 monthly free stream metrics & trial credits | Real-time streaming data service for large-scale ingestion. Best for AWS-native streaming architectures. |
| **[Azure Event Hubs](https://azure.microsoft.com/en-us/products/event-hubs/)** | ~$3.1 Trillion Mkt Cap (Microsoft) | $0.015 / Throughput Unit-hour ($11/mo Basic) | 12 months free services + $200 Azure free credit | High-throughput event ingestion with Kafka compatibility. Best for enterprise Azure ecosystem integration. |
| **[Salesforce Streaming API](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/intro_stream.htm)** | ~$280 Billion Mkt Cap | $25 / user / month (Salesforce Enterprise starting) | Developer Edition free forever account (10,000 events/day limit) | PushTopic, Platform Events & CDC streaming via CometD. Best for Salesforce-native real-time CRM updates. |
| **[Confluent Streaming API](https://www.confluent.io/)** | ~$7.5 Billion Mkt Cap / Valuation | $0.00 / mo base ($0.10 / GB ingress data) | $400 free cloud credits valid for 30 days | Enterprise managed Apache Kafka with schema registry & ksqlDB. Best for enterprise Kafka without ops overhead. |
| **[Pusher Channels](https://pusher.com/channels)** | ~$500 Million (Acquired by MessageBird / Bird) | $29 / month (Startup Tier) | Free Forever Sandbox: 200 concurrent connections & 200,000 msgs/day | WebSockets pub/sub messaging channels for web & mobile app features. Best for app notification & chat features. |
| **[Redpanda Cloud](https://redpanda.com/)** | ~$500 Million Valuation | $0.08 / GB ingested (Serverless Server) | $300 free trial credits for 14 days | C++ Kafka-compatible streaming engine with zero JVM dependencies. Best for high-performance low-latency streaming. |
| **[Ably](https://ably.com/)** | ~$350 Million Valuation | $29 / month (Pay-As-You-Go Plan) | Free Forever Developer Tier: 6M monthly messages & 200 peak connections | Serverless pub/sub infrastructure with guaranteed 99.999% SLA delivery. Best for mission-critical web/mobile messaging. |
| **[Upstash Kafka](https://upstash.com/kafka)** | ~$80 Million Valuation | $0.20 per 100K requests ($0.60/GB) | Free Forever Tier: 10,000 messages/day & 256MB storage | Serverless pay-per-request Kafka messaging with HTTP REST API access. Best for serverless functions & edge deployments. |
| **[Decodable](https://www.decodable.co/)** | ~$50 Million Valuation | $0.15 / Flink Task Unit hour | Free Trial: 14 days full feature access with 5 FTUs | Managed SQL-based stream processing platform powered by Apache Flink. Best for code-free real-time ETL pipelines. |

---

## 🔓 Open-Source GitHub Projects

Below is a curated collection of leading open-source projects for building, processing, and maintaining streaming data pipelines.

*(Sorted by GitHub Star Count Descending)*

| Repository 📦 | GitHub Stars ⭐ | License 📜 | Description & Key Capabilities 💡 |
| :--- | :--- | :--- | :--- |
| **[Apache Spark](https://github.com/apache/spark)** | [<img src="https://img.shields.io/github/stars/apache/spark?style=social&color=white" alt="Spark Stars"/>](https://github.com/apache/spark/stargazers) | Apache-2.0 | Unified analytics engine for large-scale data processing & Structured Streaming micro-batches. |
| **[Socket.IO](https://github.com/socketio/socket.io)** | [<img src="https://img.shields.io/github/stars/socketio/socket.io?style=social&color=white" alt="SocketIO Stars"/>](https://github.com/socketio/socket.io/stargazers) | MIT | Real-time, bidirectional, event-based communication framework with WebSocket fallbacks. |
| **[Apache Kafka](https://github.com/apache/kafka)** | [<img src="https://img.shields.io/github/stars/apache/kafka?style=social&color=white" alt="Kafka Stars"/>](https://github.com/apache/kafka/stargazers) | Apache-2.0 | De facto open-source standard for distributed event streaming, Kafka Connect & Kafka Streams. |
| **[Apache Flink](https://github.com/apache/flink)** | [<img src="https://img.shields.io/github/stars/apache/flink?style=social&color=white" alt="Flink Stars"/>](https://github.com/apache/flink/stargazers) | Apache-2.0 | Stateful stream processing engine with low latency, event-time semantics & exactly-once guarantees. |
| **[Vector](https://github.com/vectordotdev/vector)** | [<img src="https://img.shields.io/github/stars/vectordotdev/vector?style=social&color=white" alt="Vector Stars"/>](https://github.com/vectordotdev/vector/stargazers) | MPL-2.0 | Ultra-fast Rust-based observability data pipeline for collecting, transforming, and routing logs/events. |
| **[NATS Server](https://github.com/nats-io/nats-server)** | [<img src="https://img.shields.io/github/stars/nats-io/nats-server?style=social&color=white" alt="NATS Stars"/>](https://github.com/nats-io/nats-server/stargazers) | Apache-2.0 | Cloud-native, lightweight high-performance messaging system with JetStream persistence. |
| **[Apache Pulsar](https://github.com/apache/pulsar)** | [<img src="https://img.shields.io/github/stars/apache/pulsar?style=social&color=white" alt="Pulsar Stars"/>](https://github.com/apache/pulsar/stargazers) | Apache-2.0 | Distributed pub/sub messaging platform featuring multi-tenancy, geo-replication, and tiered storage. |
| **[Debezium](https://github.com/debezium/debezium)** | [<img src="https://img.shields.io/github/stars/debezium/debezium?style=social&color=white" alt="Debezium Stars"/>](https://github.com/debezium/debezium/stargazers) | Apache-2.0 | Log-based Change Data Capture (CDC) platform to stream database row changes in real time. |
| **[Redpanda](https://github.com/redpanda-data/redpanda)** | [<img src="https://img.shields.io/github/stars/redpanda-data/redpanda?style=social&color=white" alt="Redpanda Stars"/>](https://github.com/redpanda-data/redpanda/stargazers) | BSL | C++ implementation of Apache Kafka API with no JVM or Zookeeper required. |
| **[Centrifugo](https://github.com/centrifugal/centrifugo)** | [<img src="https://img.shields.io/github/stars/centrifugal/centrifugo?style=social&color=white" alt="Centrifugo Stars"/>](https://github.com/centrifugal/centrifugo/stargazers) | Apache-2.0 | Scalable real-time messaging server supporting WebSockets, gRPC, SSE, and HTTP streaming. |
| **[Redpanda Connect / Benthos](https://github.com/redpanda-data/connect)** | [<img src="https://img.shields.io/github/stars/redpanda-data/connect?style=social&color=white" alt="Connect Stars"/>](https://github.com/redpanda-data/connect/stargazers) | Apache-2.0 | High-performance declarative YAML stream processor for simple data integration and ETL. |
| **[Apache Beam](https://github.com/apache/beam)** | [<img src="https://img.shields.io/github/stars/apache/beam?style=social&color=white" alt="Beam Stars"/>](https://github.com/apache/beam/stargazers) | Apache-2.0 | Unified portable programming model for batch and stream processing across multiple runners. |
| **[Fluent Bit](https://github.com/fluent/fluent-bit)** | [<img src="https://img.shields.io/github/stars/fluent/fluent-bit?style=social&color=white" alt="FluentBit Stars"/>](https://github.com/fluent/fluent-bit/stargazers) | Apache-2.0 | Fast and lightweight log and metrics processor and forwarder for Linux, Embedded & K8s. |
| **[Fluentd](https://github.com/fluent/fluentd)** | [<img src="https://img.shields.io/github/stars/fluent/fluentd?style=social&color=white" alt="Fluentd Stars"/>](https://github.com/fluent/fluentd/stargazers) | Apache-2.0 | Unified logging layer for data collection, log aggregation, and real-time log streaming. |
| **[Logstash](https://github.com/elastic/logstash)** | [<img src="https://img.shields.io/github/stars/elastic/logstash?style=social&color=white" alt="Logstash Stars"/>](https://github.com/elastic/logstash/stargazers) | Elastic License | Server-side data processing pipeline that ingests data from multiple sources concurrently. |
| **[Apache NiFi](https://github.com/apache/nifi)** | [<img src="https://img.shields.io/github/stars/apache/nifi?style=social&color=white" alt="NiFi Stars"/>](https://github.com/apache/nifi/stargazers) | Apache-2.0 | Easy-to-use, powerful, and reliable system to process and distribute streaming data. |
| **[Apache SeaTunnel](https://github.com/apache/seatunnel)** | [<img src="https://img.shields.io/github/stars/apache/seatunnel?style=social&color=white" alt="SeaTunnel Stars"/>](https://github.com/apache/seatunnel/stargazers) | Apache-2.0 | Very high-performance, distributed, massive data integration tool for batch and streaming data. |
| **[ksqlDB](https://github.com/confluentinc/ksql)** | [<img src="https://img.shields.io/github/stars/confluentinc/ksql?style=social&color=white" alt="ksqlDB Stars"/>](https://github.com/confluentinc/ksql/stargazers) | Confluent License | Event streaming database purpose-built for stream processing applications on Kafka. |
| **[Mercure](https://github.com/dunglas/mercure)** | [<img src="https://img.shields.io/github/stars/dunglas/mercure?style=social&color=white" alt="Mercure Stars"/>](https://github.com/dunglas/mercure/stargazers) | AGPL-3.0 | Server-Sent Events (SSE) based real-time update protocol & hub for web applications. |
| **[Apache Samza](https://github.com/apache/samza)** | [<img src="https://img.shields.io/github/stars/apache/samza?style=social&color=white" alt="Samza Stars"/>](https://github.com/apache/samza/stargazers) | Apache-2.0 | Distributed stream processing framework built by LinkedIn to build stateful real-time applications. |
| **[Embulk](https://github.com/embulk/embulk)** | [<img src="https://img.shields.io/github/stars/embulk/embulk?style=social&color=white" alt="Embulk Stars"/>](https://github.com/embulk/embulk/stargazers) | Apache-2.0 | Open-source bulk data loader that helps data transfer between databases and cloud storage. |
| **[Apache Storm](https://github.com/apache/storm)** | [<img src="https://img.shields.io/github/stars/apache/storm?style=social&color=white" alt="Storm Stars"/>](https://github.com/apache/storm/stargazers) | Apache-2.0 | Distributed real-time computation system for processing unbounded streams of data. |
| **[Apache Flume](https://github.com/apache/flume)** | [<img src="https://img.shields.io/github/stars/apache/flume?style=social&color=white" alt="Flume Stars"/>](https://github.com/apache/flume/stargazers) | Apache-2.0 | Distributed service for efficiently collecting, aggregating, and moving log data. |

---

## 🛠️ Architectural Best Practices for Streaming Data APIs

When building event-driven architectures and selecting streaming data APIs:
- **Event Streaming Infrastructure**: Combine **Apache Kafka** or **Redpanda** for high-throughput, fault-tolerant message logs.
- **Stateful Stream Processing**: Use **Apache Flink** or **Apache Spark Structured Streaming** for complex aggregations, windowing, and exactly-once processing guarantees.
- **Database Replication & CDC**: Deploy **Debezium** to automatically stream database mutations without application code changes.
- **Declarative ETL & Pipelines**: Integrate **Vector** or **Redpanda Connect (Benthos)** for high-throughput routing, filtering, and transformation.
- **Client Pub/Sub & Web Push**: Leverage **Centrifugo**, **Ably**, or **Socket.IO** for WebSocket and SSE connections to browser clients.

---

## 🤝 How to Contribute

Contributions are welcome! Follow these steps to submit additions or updates:

1. **Fork the repository** on GitHub.
2. **Add or update entries** in `README.md` following the tabular format.
3. Ensure you include: Name, URL, exact pricing tier, free tier limits, and concise description.
4. Submit a **Pull Request (PR)** with a summary of changes.

Please refer to [Awesome-Awesome-Awesome](https://github.com/ishandutta2007/Awesome-Awesome-Awesome) for contribution guidelines across our curated awesome lists.

---

## 💖 Support & Sponsorship

If you find this repository helpful for evaluating real-time streaming architectures, please consider supporting the project:

- ⭐ **Star this repository** to help others discover it!
- 🔀 **Fork & Share** it with your data engineering team.
- ☕ **Buy me a coffee**: Support ongoing maintenance via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

Thank you for being part of the streaming data open-source community! ❤️

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Streaming-Data-API&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Streaming-Data-API&type=date&legend=top-left)

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Streaming data APIs handle high-volume data in motion and may process sensitive information. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **License considerations**: Redpanda uses BSL, ksqlDB uses Confluent Community License, and NATS uses Apache-2.0. Verify licensing against your use case before deploying to production.
- **Delivery Guarantees**: Kafka, Pulsar, and NATS JetStream handle delivery guarantees differently. Always design consumers for idempotency.

---

<p align="center">
  <b>Made with ❤️ for Data Engineers, Platform Teams &amp; Streaming Architects worldwide.</b>
</p>
