# Complete File Index

## Concepts (14 + 35 subtopic files)

### Core Concepts
| # | File | Description |
|---|------|-------------|
| 1 | [scalability.md](./concepts/scalability.md) | Vertical vs horizontal scaling, scaling strategies, challenges |
| 2 | [availability.md](./concepts/availability.md) | High availability, redundancy, failover, uptime calculations |
| 3 | [reliability.md](./concepts/reliability.md) | Fault tolerance, error handling, monitoring |
| 4 | [fault-tolerance.md](./concepts/core/fault-tolerance.md) | Designing resilient systems |
| 5 | [failover.md](./concepts/core/failover.md) | Automatic failure recovery |
| 6 | [spof.md](./concepts/core/spof.md) | Single Point of Failure |

### Distributed Systems
| # | File | Description |
|---|------|-------------|
| 7 | [cap-theorem.md](./concepts/cap-theorem.md) | Consistency, Availability, Partition Tolerance tradeoffs |
| 8 | [consistent-hashing.md](./concepts/consistent-hashing.md) | Distributed hashing, virtual nodes, load distribution |
| 9 | [distributed-locking.md](./concepts/distributed/distributed-locking.md) | Distributed concurrency control |
| 10 | [consensus-algorithms.md](./concepts/distributed/consensus-algorithms.md) | Raft, Paxos, leader election |
| 11 | [circuit-breaker.md](./concepts/distributed/circuit-breaker.md) | Preventing cascading failures |
| 12 | [service-discovery.md](./concepts/distributed/service-discovery.md) | Service location in distributed systems |
| 13 | [gossip-protocol.md](./concepts/distributed/gossip-protocol.md) | Epidemic broadcast protocols |
| 14 | [heartbeats.md](./concepts/distributed/heartbeats.md) | Health monitoring |
| 15 | [distributed-tracing.md](./concepts/distributed/distributed-tracing.md) | Observability |
| 16 | [disaster-recovery.md](./concepts/distributed/disaster-recovery.md) | Business continuity |

### Networking
| # | File | Description |
|---|------|-------------|
| 17 | [load-balancing.md](./concepts/load-balancing.md) | Algorithms, Layer 4 vs Layer 7, health checks |
| 18 | [dns.md](./concepts/dns.md) | Domain name resolution, DNS hierarchy |
| 19 | [tcp-vs-udp.md](./concepts/networking/tcp-vs-udp.md) | Transport protocols |
| 20 | [http-https.md](./concepts/networking/http-https.md) | Web protocols |
| 21 | [proxy-vs-reverse-proxy.md](./concepts/networking/proxy-vs-reverse-proxy.md) | Proxy patterns |
| 22 | [ip-addresses.md](./concepts/networking/ip-addresses.md) | Networking fundamentals |
| 23 | [checksums.md](./concepts/networking/checksums.md) | Data integrity |
| 24 | [osi-model.md](./concepts/osi-model.md) | Network layers |

### Caching
| # | File | Description |
|---|------|-------------|
| 25 | [caching.md](./concepts/caching.md) | Cache strategies, eviction policies, CDN |
| 26 | [caching-strategies.md](./concepts/caching/caching-strategies.md) | Cache-aside, read-through, write-through |
| 27 | [cache-eviction-policies.md](./concepts/caching/cache-eviction-policies.md) | LRU, LFU, FIFO |
| 28 | [distributed-caching.md](./concepts/caching/distributed-caching.md) | Scaling cache |

### Database
| # | File | Description |
|---|------|-------------|
| 29 | [database-sharding.md](./concepts/database-sharding.md) | Horizontal partitioning |
| 30 | [database-indexing.md](./concepts/database-indexing.md) | B-tree, hash indexes |
| 31 | [sql-vs-nosql.md](./concepts/database/sql-vs-nosql.md) | Database comparison |
| 32 | [database-scaling.md](./concepts/database/database-scaling.md) | Read replicas |
| 33 | [acid-transactions.md](./concepts/database/acid-transactions.md) | Transaction properties |
| 34 | [data-replication.md](./concepts/database/data-replication.md) | Replication strategies |
| 35 | [database-types.md](./concepts/database/database-types.md) | Relational, document, graph |
| 36 | [database-architectures.md](./concepts/database/database-architectures.md) | Storage engines |
| 37 | [bloom-filters.md](./concepts/database/bloom-filters.md) | Probabilistic data structures |

### Architecture
| # | File | Description |
|---|------|-------------|
| 38 | [microservices.md](./concepts/microservices.md) | Service decomposition |
| 39 | [client-server-architecture.md](./concepts/architecture/client-server-architecture.md) | Classic pattern |
| 40 | [event-driven-architecture.md](./concepts/architecture/event-driven-architecture.md) | Event processing |
| 41 | [p2p-architecture.md](./concepts/architecture/p2p-architecture.md) | Peer-to-peer |
| 42 | [serverless-architecture.md](./concepts/architecture/serverless-architecture.md) | FaaS |

### Messaging & Async
| # | File | Description |
|---|------|-------------|
| 43 | [message-queues.md](./concepts/message-queues.md) | Async communication |
| 44 | [pub-sub.md](./concepts/async/pub-sub.md) | Publish-subscribe |
| 45 | [change-data-capture.md](./concepts/async/change-data-capture.md) | Data sync |
| 46 | [websockets.md](./concepts/websockets.md) | Real-time communication |

### API Design
| # | File | Description |
|---|------|-------------|
| 47 | [api-design.md](./concepts/api-design.md) | REST vs GraphQL |
| 48 | [rest-vs-graphql.md](./concepts/api/rest-vs-graphql.md) | API paradigms |
| 49 | [api-gateway.md](./concepts/api/api-gateway.md) | API management |
| 50 | [rate-limiting.md](./concepts/api/rate-limiting.md) | Throttling |
| 51 | [idempotency.md](./concepts/api/idempotency.md) | Safe retries |
| 52 | [webhooks.md](./concepts/api/webhooks.md) | Event callbacks |
| 53 | [apis-basics.md](./concepts/api/apis-basics.md) | API fundamentals |

### Tradeoffs
| # | File | Description |
|---|------|-------------|
| 54 | [latency-vs-throughput.md](./concepts/tradeoffs/latency-vs-throughput.md) | Performance tradeoffs |
| 55 | [strong-vs-eventual-consistency.md](./concepts/tradeoffs/strong-vs-eventual-consistency.md) | Consistency models |
| 56 | [stateful-vs-stateless.md](./concepts/tradeoffs/stateful-vs-stateless.md) | Architecture patterns |
| 57 | [sync-vs-async.md](./concepts/tradeoffs/sync-vs-async.md) | Communication patterns |
| 58 | [rest-vs-rpc.md](./concepts/tradeoffs/rest-vs-rpc.md) | API styles |
| 59 | [push-vs-pull.md](./concepts/tradeoffs/push-vs-pull.md) | Data flow |
| 60 | [batch-vs-stream-processing.md](./concepts/tradeoffs/batch-vs-stream-processing.md) | Processing paradigms |
| 61 | [read-through-vs-write-through-cache.md](./concepts/tradeoffs/read-through-vs-write-through-cache.md) | Caching |
| 62 | [long-polling-vs-websockets.md](./concepts/tradeoffs/long-polling-vs-websockets.md) | Real-time |
| 63 | [concurrency-vs-parallelism.md](./concepts/tradeoffs/concurrency-vs-parallelism.md) | Execution models |

---

## Easy Problems (10 files)

| # | File | Description |
|---|------|-------------|
| 1 | [url-shortener.md](./problems-easy/url-shortener.md) | Short URL generation, base62 encoding |
| 2 | [parking-garage.md](./problems-easy/parking-garage.md) | Spot management, entry/exit flow |
| 3 | [cdn-design.md](./problems-easy/cdn-design.md) | Edge servers, content caching |
| 4 | [load-balancer.md](./problems-easy/load-balancer.md) | Traffic distribution |
| 5 | [distributed-cache.md](./problems-easy/distributed-cache.md) | Scalable caching |
| 6 | [distributed-key-value-store.md](./problems-easy/distributed-key-value-store.md) | KV storage |
| 7 | [autocomplete.md](./problems-easy/autocomplete.md) | Type-ahead search |
| 8 | [vending-machine.md](./problems-easy/vending-machine.md) | State machine |
| 9 | [authentication-system.md](./problems-easy/authentication-system.md) | User auth |
| 10 | [upi.md](./problems-easy/upi.md) | Payment processing |

---

## Medium Problems (23 files)

| # | File | Description |
|---|------|-------------|
| 1 | [whatsapp.md](./problems-medium/whatsapp.md) | Real-time messaging |
| 2 | [instagram.md](./problems-medium/instagram.md) | Photo sharing |
| 3 | [netflix.md](./problems-medium/netflix.md) | Video streaming |
| 4 | [twitter.md](./problems-medium/twitter.md) | Microblogging |
| 5 | [rate-limiter.md](./problems-medium/rate-limiter.md) | Rate limiting algorithms |
| 6 | [notification-service.md](./problems-medium/notification-service.md) | Push/email/SMS |
| 7 | [youtube.md](./problems-medium/youtube.md) | Video platform |
| 8 | [spotify.md](./problems-medium/spotify.md) | Music streaming |
| 9 | [facebook.md](./problems-medium/facebook.md) | Social network |
| 10 | [tinder.md](./problems-medium/tinder.md) | Dating app |
| 11 | [airbnb.md](./problems-medium/airbnb.md) | Marketplace |
| 12 | [amazon.md](./problems-medium/amazon.md) | E-commerce |
| 13 | [reddit.md](./problems-medium/reddit.md) | Forum platform |
| 14 | [tiktok.md](./problems-medium/tiktok.md) | Short video |
| 15 | [shopify.md](./problems-medium/shopify.md) | E-commerce SaaS |
| 16 | [kafka.md](./problems-medium/kafka.md) | Event streaming |
| 17 | [google-search.md](./problems-medium/google-search.md) | Search engine |
| 18 | [distributed-job-scheduler.md](./problems-medium/distributed-job-scheduler.md) | Job queue |
| 19 | [digital-wallet.md](./problems-medium/digital-wallet.md) | Wallet system |
| 20 | [online-code-editor.md](./problems-medium/online-code-editor.md) | Cloud IDE |
| 21 | [payment-system.md](./problems-medium/payment-system.md) | Payment processing |
| 22 | [flight-booking.md](./problems-medium/flight-booking.md) | Reservation system |
| 23 | [analytics-platform.md](./problems-medium/analytics-platform.md) | Data analytics |

---

## Hard Problems (15 files)

| # | File | Description |
|---|------|-------------|
| 1 | [uber.md](./problems-hard/uber.md) | Ride sharing |
| 2 | [google-docs.md](./problems-hard/google-docs.md) | Collaborative editing |
| 3 | [dropbox.md](./problems-hard/dropbox.md) | File sync |
| 4 | [google-maps.md](./problems-hard/google-maps.md) | Maps service |
| 5 | [doordash.md](./problems-hard/doordash.md) | Food delivery |
| 6 | [yelp.md](./problems-hard/yelp.md) | Business reviews |
| 7 | [zoom.md](./problems-hard/zoom.md) | Video conferencing |
| 8 | [slack.md](./problems-hard/slack.md) | Team communication |
| 9 | [s3.md](./problems-hard/s3.md) | Object storage |
| 10 | [web-crawler.md](./problems-hard/web-crawler.md) | Search crawler |
| 11 | [bookmyshow.md](./problems-hard/bookmyshow.md) | Ticketing system |
| 12 | [code-deployment.md](./problems-hard/code-deployment.md) | CI/CD pipeline |
| 13 | [distributed-counter.md](./problems-hard/distributed-counter.md) | Global counter |
| 14 | [distributed-locking-service.md](./problems-hard/distributed-locking-service.md) | Lock service |
| 15 | [live-comments.md](./problems-hard/live-comments.md) | Real-time comments |

---

**Total: 111 detailed system design files covering concepts and real-world problems**
