---
title: Supported Service Inputs

menu:
  telegraf_011:
    name: Service Inputs
    identifier: services
    weight: 30
---

Telegraf is entirely input driven. It gathers all metrics from the inputs specified in the configuration file.

## Usage Instructions

View usage instructions for each service input by running `telegraf -usage <service-input-name>`.

## Supported Service Plugin List

* [Kafka Consumer](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/kafka_consumer)
* [GitHub Webhooks](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/github_webhooks)
* [MQTT Consumer](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/mqtt_consumer)
* [NATS Consumer](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/nats_consumer)
* [StatsD](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/statsd)
* [TCP Listener](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/tcp_listener)
* [UDP Listener](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/udp_listener)
