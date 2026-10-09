# Awesome-Streaming-Data-API

# Top Streaming Data API Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Event Streaming, Real-Time Data Pipelines & Self-Hosted Streaming Backends*  
**Last updated: October 2026**

This repository tracks notable **commercial streaming data APIs** and **open-source projects** that ingest, transport, and process continuous data streams — from cloud-native event buses to self-hosted Kafka-compatible backends and real-time pub/sub messaging platforms.

**Examples** include Salesforce Streaming API, AWS Kinesis Data Streams, Google Cloud Dataflow, Confluent Streaming API, Ably, Pusher Channels, Azure Event Hubs, Redpanda, Upstash Kafka, and Decodable (the category leaders).

**Open-source emphasis**: Streaming data APIs are one of the strongest open-source domains. **Apache Kafka** remains the de facto standard for event streaming, with **Redpanda** delivering C++ performance and **Apache Pulsar** adding multi-tenancy. **Apache Flink** dominates stateful stream processing, **Debezium** powers change data capture, and **Benthos/Redpanda Connect** enables declarative pipelines. **NATS** and **Centrifugo** provide lightweight real-time messaging, while **Apache Beam** offers portable stream processing. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Streaming API](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/intro_stream.htm)**  
  **Salesforce's real-time event streaming** — PushTopic, Platform Events, and Change Data Capture for real-time updates within Salesforce. **CometD-based with replay and durable subscriptions** . **Best for Salesforce-native real-time integrations**.

- **[AWS Kinesis Data Streams](https://aws.amazon.com/kinesis/data-streams/)**  
  **AWS's real-time streaming data service** — ingest and process data streams at scale . **Kinesis Client Library (KCL) for consumers** . **Best for AWS-native streaming** .

- **[Google Cloud Dataflow](https://cloud.google.com/dataflow)**  
  **Google's fully managed stream and batch processing** based on Apache Beam . **Unified programming model** — same code for batch and stream . **Best for GCP-native streaming** .

- **[Confluent Streaming API](https://www.confluent.io/)**  
  **The leading managed Kafka platform** — fully managed Kafka, ksqlDB, Flink, connectors, and schema registry . **The enterprise standard for event streaming** . **Best for organizations wanting Kafka without operational burden** .

- **[Ably](https://ably.com/)**  
  **Real-time messaging infrastructure** — pub/sub with guaranteed delivery at scale . **Best for mission-critical real-time messaging** .

- **[Pusher Channels](https://pusher.com/channels)**  
  **Real-time messaging platform** — WebSocket-based pub/sub channels for applications . **Best for real-time features** .

- **[Azure Event Hubs](https://azure.microsoft.com/en-us/products/event-hubs/)**  
  **Azure's big data streaming platform** — Kafka-compatible endpoint, millions of events per second . **Event Hubs Capture** for automatic data loading . **Best for Azure-native streaming** .

- **[Redpanda Cloud](https://redpanda.com/)**  
  **Kafka-compatible streaming platform in C++** — no Zookeeper, no JVM . **10x faster than Kafka** in some benchmarks . **Best for high-performance streaming** .

- **[Upstash Kafka](https://upstash.com/kafka)**  
  **Serverless Kafka** — pay-per-request messaging with REST API . **Best for serverless streaming** .

- **[Decodable](https://www.decodable.co/)**  
  **Managed stream processing** — SQL-based pipelines on Apache Flink . **Best for simple streaming ETL** .

## Open-Source GitHub Projects

### Event Streaming Platforms

- **[Apache Kafka](https://github.com/apache/kafka)**  
  **The de facto standard for event streaming**, Apache-2.0 licensed with **28,000+ GitHub stars** . **Distributed, fault-tolerant, high-throughput pub/sub messaging** . **Kafka Connect for source/sink connectors** and **Kafka Streams for stream processing** . **The foundation for most streaming data architectures** . **Best for enterprise event streaming at scale** .

- **[Redpanda](https://github.com/redpanda-data/redpanda)**  
  **Kafka-compatible streaming platform in C++**, BSL licensed (free for most uses) . **No Zookeeper, no JVM** — simpler operations . **10x faster than Kafka** in some benchmarks . **Best for teams wanting Kafka compatibility with better performance** .

- **[Apache Pulsar](https://github.com/apache/pulsar)**  
  **Distributed messaging and streaming platform**, Apache-2.0 licensed with **14,000+ GitHub stars** . **Multi-tenancy, geo-replication, and tiered storage** . **The main alternative to Kafka** . **Best for multi-tenant and geo-distributed streaming** .

- **[NATS](https://github.com/nats-io/nats-server)**  
  **Cloud-native messaging system**, Apache-2.0 licensed with **15,000+ GitHub stars** . **Lightweight, high-performance pub/sub** with JetStream for persistence . **Best for IoT and edge streaming** .

### Stream Processing

- **[Apache Flink](https://github.com/apache/flink)**  
  **The de facto standard for stateful stream processing**, Apache-2.0 licensed with **24,000+ GitHub stars** . **Exactly-once semantics, event-time processing, and savepoints** . **Best for mission-critical stream processing** .

- **[Kafka Streams](https://github.com/apache/kafka)**  
  **Stream processing library for Kafka**, Apache-2.0 licensed . **No separate cluster** — runs in your application . **Exactly-once semantics and interactive queries** . **Best for Kafka-native stream processing** .

- **[ksqlDB](https://github.com/confluentinc/ksql)**  
  **Streaming SQL for Kafka**, Confluent Community License . **SQL interface for Kafka Streams** . **Continuous queries, materialized views, and pull queries** . **Best for SQL-proficient teams** .

- **[Apache Beam](https://github.com/apache/beam)**  
  **Unified programming model for batch and stream**, Apache-2.0 licensed . **Portable across Flink, Spark, and Dataflow** . **Best for portable pipelines** .

- **[Apache Spark Structured Streaming](https://github.com/apache/spark)**  
  **Unified batch and stream processing**, Apache-2.0 licensed . **Micro-batch with exactly-once semantics** . **Best for teams already using Spark** .

### Data Movement & CDC

- **[Debezium](https://github.com/debezium/debezium)**  
  **The leading open-source CDC platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Captures row-level changes from databases** . **Kafka Connect-based** . **Best for database replication** .

- **[Benthos (Redpanda Connect)](https://github.com/redpanda-data/connect)**  
  **Stream processing without code**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Declarative YAML configuration for streaming ETL** . **Hundreds of connectors** . **Best for code-free stream pipelines** .

- **[Vector](https://github.com/vectordotdev/vector)**  
  **High-performance observability data pipeline**, MPL-2.0 licensed with **18,000+ GitHub stars** . **Collect, transform, and route logs and events** . **Best for observability data** .

### Real-Time Messaging & Pub/Sub

- **[Centrifugo](https://github.com/centrifugal/centrifugo)**  
  **Scalable real-time messaging server**, Apache-2.0 licensed with **8,000+ GitHub stars** . **WebSocket, HTTP-streaming, SSE, and GRPC** . **Pub/sub channels with presence and history** . **Best for real-time pub/sub messaging** .

- **[Mercure](https://github.com/dunglas/mercure)**  
  **Open-source protocol for real-time updates**, AGPL-3.0 licensed . **Server-sent events (SSE) based** . **Best for real-time web updates** .

- **[Socket.IO](https://github.com/socketio/socket.io)**  
  **Bidirectional event-based communication**, MIT licensed with **60,000+ GitHub stars** . **WebSocket with fallback to HTTP long-polling** . **Best for real-time web applications** .

### Additional Strong Open-Source Options

- **Apache Samza** — Stream processing on Kafka .
- **Apache Storm** — Real-time computation (legacy) .
- **Apache Heron** — Twitter's stream processing (retired) .
- **Apache Flume** — Log aggregation (legacy) .
- **Logstash** — Data collection and transformation .
- **Fluentd** — Unified logging layer .
- **Fluent Bit** — Lightweight log processor .
- **Apache SeaTunnel** — High-performance data integration .
- **Apache NiFi** — Data flow automation .
- **Embulk** — Pluggable bulk data loader .
- **Kafka Connect** — Source/sink connectors for Kafka .

**Frameworks for building custom streaming data API solutions**: Combine **Apache Kafka** or **Redpanda** for high-throughput event streaming . Use **Apache Flink** for stateful stream processing with exactly-once semantics . Deploy **Debezium** for CDC from databases . Integrate **Benthos** or **Vector** for code-free pipelines and observability data . Choose **ksqlDB** for SQL-based stream processing . Use **Centrifugo** for real-time pub/sub messaging . Note that true managed streaming data APIs with global infrastructure, automatic scaling, and vendor-supported SLAs (Kinesis, Confluent Cloud, Azure Event Hubs) remain primarily commercial territory; open-source stacks provide strong event streaming, stream processing, and data movement foundations that require integration for complete streaming data APIs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Streaming data APIs handle high-volume data in motion and may process sensitive information. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **License considerations**: Redpanda uses BSL (free for most uses but not OSI), ksqlDB uses Confluent Community License, and NATS uses Apache-2.0. Verify licensing against your use case before committing .
- **Exactly-once semantics are hard** — Kafka, Pulsar, and NATS JetStream each handle delivery guarantees differently. Understand your requirements before choosing .
- **Event ordering matters** — Kafka guarantees order per partition; other systems may not. Design for idempotency and handle out-of-order events .
- The open-source ecosystem provides strong event streaming, stream processing, and data movement foundations, but **managed infrastructure, global scale, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for data engineers, platform teams, and organizations seeking streaming data API sovereignty.**  
Let's make streaming data APIs more open, transparent, and reliable.
