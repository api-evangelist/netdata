---
title: "Azure Monitor Collector: Monitor Azure Infrastructure"
url: "https://www.netdata.cloud/blog/azure-monitor/"
date: "2026-04-27"
feed_url: "https://www.netdata.cloud/blog/index.xml"
---
If you’re running infrastructure on Azure, you’ve probably dealt with the split between your Azure-native monitoring and the rest of your stack. Your VMs, databases, and Kubernetes clusters generate platform metrics through Azure Monitor, but those metrics live in a separate world from the OS-level, application, and on-prem metrics you’re already watching in Netdata. You end up checking two (or more) places during incidents, building mental bridges between dashboards that don’t talk to each other.
