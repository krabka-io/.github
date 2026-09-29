# Krabka

An Apache Kafka-compatible streaming ecosystem. Website: [krabka.io](https://krabka.io)

## Repositories

**Core**
- [krabka-broker](https://github.com/krabka-io/krabka-broker) — Kafka-compatible broker with a KRaft consensus engine and tiered storage
- [krabka-protocol](https://github.com/krabka-io/krabka-protocol) — the Kafka wire layer: API codecs, KRaft metadata records, SASL/TLS
- [krabka-schema-registry](https://github.com/krabka-io/krabka-schema-registry) — Confluent Schema Registry-compatible service, plus client serdes
- [krabka-gateway](https://github.com/krabka-io/krabka-gateway) — gRPC / Connect-RPC and HTTP front end to Kafka topics, with app SDKs
- [krabka-connect](https://github.com/krabka-io/krabka-connect) — connector framework, connectors, and worker

**Clients and stream processing**
- [krabka-client-rs](https://github.com/krabka-io/krabka-client-rs) — Rust producer, consumer, and admin client
- [krabka-streams-rs](https://github.com/krabka-io/krabka-streams-rs) · [krabka-streams-java](https://github.com/krabka-io/krabka-streams-java) · [krabka-streams-go](https://github.com/krabka-io/krabka-streams-go) — Kafka Streams-style libraries

**Operations**
- [krabka-operator](https://github.com/krabka-io/krabka-operator) — Kubernetes operator that reconciles clusters from custom resources
- [krabka-cli](https://github.com/krabka-io/krabka-cli) — the `krabka` operator CLI
- [krabka-rebalancer](https://github.com/krabka-io/krabka-rebalancer) — partition rebalancing
- [krabka-o11y](https://github.com/krabka-io/krabka-o11y) — metrics, traces, profiles, and logs · [demo](https://github.com/krabka-io/krabka-o11y-demo)

**Other**
- [gres](https://github.com/krabka-io/gres) · [tooling](https://github.com/krabka-io/tooling) — shared build and release inputs · [krabka-io.github.io](https://github.com/krabka-io/krabka-io.github.io) — the website

## Contributing

Issues and pull requests are welcome in any repository; each one's README and `CONTRIBUTING.md` (where present) have the details.
