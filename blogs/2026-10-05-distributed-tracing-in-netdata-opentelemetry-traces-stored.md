---
title: "Distributed Tracing in Netdata: OpenTelemetry Traces, Stored Where They Were Collected"
url: "https://www.netdata.cloud/blog/distributed-tracing-in-netdata/"
date: "2026-10-05"
feed_url: "https://www.netdata.cloud/blog/index.xml"
---
Back in 2020, when we laid out where Netdata was going , the plan listed anomaly detection, log collection and “application traces collection”. The first two shipped years ago. Traces took longer, because we wanted them to work the way the rest of Netdata works: collected and stored on your own nodes, with no separate backend to stand up.
