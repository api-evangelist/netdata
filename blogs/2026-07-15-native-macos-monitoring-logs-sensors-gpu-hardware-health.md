---
title: "Native macOS Monitoring: Logs, Sensors, GPU & Hardware Health"
url: "https://www.netdata.cloud/blog/macos-monitoring/"
date: "2026-07-15"
feed_url: "https://www.netdata.cloud/blog/index.xml"
---
We’ve overhauled macOS monitoring in the latest Netdata release. Netdata already collects system metrics on Macs at per-second resolution; this release completes the picture with logs and hardware telemetry, areas that previously required users to run CLI tools like log show and powermetrics . The new collectors read this data through Apple’s own frameworks, allowing users to trace application and OS errors and catch hardware issues early.
