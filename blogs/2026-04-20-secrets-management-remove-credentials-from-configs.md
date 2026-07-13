---
title: "Secrets Management: Remove Credentials From Configs"
url: "https://www.netdata.cloud/blog/secrets-management/"
date: "2026-04-20"
feed_url: "https://www.netdata.cloud/blog/index.xml"
---
If you’re running Netdata collectors that connect to databases, APIs, or other authenticated services, there’s a good chance you have passwords sitting in plain-text configuration files right now. It works, but it’s the kind of thing that makes security teams nervous and makes credential rotation painful. Every password change means editing config files and restarting collectors.
