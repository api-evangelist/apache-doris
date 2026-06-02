---
title: "Apache Doris 4.1 Spill to Disk: Running Memory-Intensive Queries Without OOM"
url: "https://doris.apache.org/blog/apache-doris-4-1-spill-to-disk/"
date: "2026-05-08"
feed_url: "https://doris.apache.org/blog/rss"
---
Apache Doris 4.1 introduces mature spill-to-disk capabilities, enabling Hash Join, Aggregation, and Sort operators to write intermediate state to disk when memory pressure rises so that memory-intensive analytical queries complete without OOM errors.
