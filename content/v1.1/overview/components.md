---
title: "Components"
weight: 1
---

## M3 Coordinator

M3 Coordinator is a service that coordinates reads and writes between upstream systems, such as Prometheus, and M3DB. It is a bridge that users can deploy to access the benefits of M3DB such as long term storage and multi-DC setup with other monitoring systems, such as Prometheus.

## M3DB

M3DB is a distributed time series database that provides scalable storage and a reverse index of time series. It is optimized as a cost effective and reliable realtime and long term retention metrics store and index.  For more details, see the [M3DB documentation](/docs/v1.1/reference/m3db/).

## M3 Query

{{< fileinclude file="m3query_intro.md" >}}

## M3 Aggregator

{{< fileinclude file="m3aggregator_intro.md" >}}
