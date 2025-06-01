### Elastic Cache
```
https://aws.amazon.com/elasticache/
```
```
https://docs.aws.amazon.com/AmazonElastiCache/latest/dg/WhatIs.html
```
```
https://www.amazonaws.cn/en/elasticache/redis/
```
### Reference
```
https://www.scaler.com/topics/aws/aws-redis/
```
```
https://www.cloudzero.com/blog/elasticache-vs-redis/
```


- Amazon ElastiCache is a fully managed caching service that helps improve application performance by storing frequently accessed 
  data in memory for microsecond response times. 
- command usage:
  - Real-time application data caching: Speeds up databases, analytics, and AI applications by reducing latency.
  - Session storage: Stores ephemeral session data for gaming, e-commerce, and social media platforms.
  - Leaderboards: Helps manage and update leaderboards in gaming applications.
  - Messaging platforms: Supports real-time message processing and relaying.
  - Geospatial processing: Enhances location-based services.
  - Serverless caching: Offers automatic scaling and eliminates infrastructure

Engine Types
  - Memcached
    - Best for: Simple caching needs.
    - Strengths: Lightweight, easy to use, and highly scalable.
    - Limitations: Lacks advanced data structures and persistence.
    - Use cases: Web session caching, database query caching, and object caching.
  - Redis OSS
    - Best for: High-performance applications needing complex data structures.
    - Strengths: Supports lists, sets, sorted sets, and more. Offers persistence and replication.
    - Limitations: Single-threaded for most operations.
    - Use cases: Real-time analytics, leaderboards, messaging queues, and session storage.
  - Valkey
    - Best for: Open-source alternative to Redis with enhanced scalability.
    - Strengths: Multi-threaded architecture, automatic cluster failover, and improved memory efficiency.
    - Limitations: Newer technology, still evolving.
    - Use cases: High-throughput caching, real-time data processing, and distributed applications.