# System Design Resources Collection

[![GitHub Stars](https://img.shields.io/github/stars/sandeepkumar-24/system-design-resources?style=social)](https://github.com/sandeepkumar-24/system-design-resources/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/sandeepkumar-24/system-design-resources?style=social)](https://github.com/sandeepkumar-24/system-design-resources/network/members)

> Comprehensive system design learning materials organized into categories for easy reference and speed reading.

This repository contains detailed explanations of system design concepts and real-world problems, designed to help you prepare for system design interviews and build scalable distributed systems.

---

## 📚 Contents

### [Concepts](./concepts/)

Fundamental system design concepts and principles that form the foundation of distributed systems design.

#### Core Concepts
| Topic | Description |
|-------|-------------|
| [Scalability](./concepts/scalability.md) | Vertical vs horizontal scaling, scaling strategies, challenges |
| [Availability](./concepts/availability.md) | High availability, redundancy, failover, uptime calculations |
| [Reliability](./concepts/reliability.md) | Fault tolerance, error handling, monitoring |
| [Fault Tolerance](./concepts/core/fault-tolerance.md) | Designing resilient systems |
| [Failover](./concepts/core/failover.md) | Automatic failure recovery |
| [Single Point of Failure (SPOF)](./concepts/core/spof.md) | Identifying and eliminating SPOF |

#### Distributed Systems
| Topic | Description |
|-------|-------------|
| [CAP Theorem](./concepts/cap-theorem.md) | Consistency, Availability, Partition Tolerance tradeoffs |
| [Consistent Hashing](./concepts/consistent-hashing.md) | Distributed hashing, virtual nodes, load distribution |
| [Distributed Locking](./concepts/distributed/distributed-locking.md) | Managing distributed concurrency |
| [Consensus Algorithms](./concepts/distributed/consensus-algorithms.md) | Raft, Paxos, and leader election |
| [Circuit Breaker](./concepts/distributed/circuit-breaker.md) | Preventing cascading failures |
| [Service Discovery](./concepts/distributed/service-discovery.md) | Locating services in distributed systems |
| [Gossip Protocol](./concepts/distributed/gossip-protocol.md) | Epidemic broadcast protocols |
| [Heartbeats](./concepts/distributed/heartbeats.md) | Health monitoring in distributed systems |
| [Distributed Tracing](./concepts/distributed/distributed-tracing.md) | Observability across services |
| [Disaster Recovery](./concepts/distributed/disaster-recovery.md) | Business continuity planning |

#### Networking
| Topic | Description |
|-------|-------------|
| [DNS](./concepts/dns.md) | Domain name resolution, DNS hierarchy, caching, security |
| [Load Balancing](./concepts/load-balancing.md) | Algorithms, Layer 4 vs Layer 7, health checks |
| [TCP vs UDP](./concepts/networking/tcp-vs-udp.md) | Transport layer protocols comparison |
| [HTTP vs HTTPS](./concepts/networking/http-https.md) | Web protocols and security |
| [Proxy vs Reverse Proxy](./concepts/networking/proxy-vs-reverse-proxy.md) | Understanding proxy patterns |
| [IP Addresses](./concepts/networking/ip-addresses.md) | Networking fundamentals |
| [Checksums](./concepts/networking/checksums.md) | Data integrity verification |
| [OSI Model](./concepts/osi-model.md) | Network architecture layers |

#### Caching
| Topic | Description |
|-------|-------------|
| [Caching Overview](./concepts/caching.md) | Cache strategies, eviction policies, CDN |
| [Caching Strategies](./concepts/caching/caching-strategies.md) | Cache-aside, read-through, write-through |
| [Cache Eviction Policies](./concepts/caching/cache-eviction-policies.md) | LRU, LFU, FIFO strategies |
| [Distributed Caching](./concepts/caching/distributed-caching.md) | Scaling cache across nodes |

#### Database
| Topic | Description |
|-------|-------------|
| [Database Sharding](./concepts/database-sharding.md) | Horizontal partitioning, shard keys |
| [Database Indexing](./concepts/database-indexing.md) | B-tree, hash, composite indexes |
| [SQL vs NoSQL](./concepts/database/sql-vs-nosql.md) | Database type comparison |
| [Database Scaling](./concepts/database/database-scaling.md) | Read replicas, federation |
| [ACID Transactions](./concepts/database/acid-transactions.md) | Transaction properties |
| [Data Replication](./concepts/database/data-replication.md) | Master-slave, master-master |
| [Database Types](./concepts/database/database-types.md) | Relational, document, graph, columnar |
| [Database Architectures](./concepts/database/database-architectures.md) | Storage engines and design |
| [Bloom Filters](./concepts/database/bloom-filters.md) | Probabilistic data structures |

#### Architecture Patterns
| Topic | Description |
|-------|-------------|
| [Microservices](./concepts/microservices.md) | Service decomposition, communication patterns |
| [Client-Server Architecture](./concepts/architecture/client-server-architecture.md) | Classic distributed pattern |
| [Event-Driven Architecture](./concepts/architecture/event-driven-architecture.md) | Async event processing |
| [P2P Architecture](./concepts/architecture/p2p-architecture.md) | Peer-to-peer systems |
| [Serverless Architecture](./concepts/architecture/serverless-architecture.md) | Function-as-a-Service |

#### Messaging & Async
| Topic | Description |
|-------|-------------|
| [Message Queues](./concepts/message-queues.md) | Async communication, delivery semantics |
| [Pub/Sub](./concepts/async/pub-sub.md) | Publish-subscribe patterns |
| [Change Data Capture](./concepts/async/change-data-capture.md) | Data synchronization |
| [WebSockets](./concepts/websockets.md) | Real-time bidirectional communication |

#### API Design
| Topic | Description |
|-------|-------------|
| [API Design](./concepts/api-design.md) | REST vs GraphQL, versioning, authentication |
| [REST vs GraphQL](./concepts/api/rest-vs-graphql.md) | API paradigm comparison |
| [API Gateway](./concepts/api/api-gateway.md) | API management layer |
| [Rate Limiting](./concepts/api/rate-limiting.md) | Throttling strategies |
| [Idempotency](./concepts/api/idempotency.md) | Safe retry semantics |
| [Webhooks](./concepts/api/webhooks.md) | Event callbacks |
| [API Basics](./concepts/api/apis-basics.md) | Fundamentals of API design |

#### Tradeoffs
| Topic | Description |
|-------|-------------|
| [Latency vs Throughput](./concepts/tradeoffs/latency-vs-throughput.md) | Performance tradeoffs |
| [Strong vs Eventual Consistency](./concepts/tradeoffs/strong-vs-eventual-consistency.md) | Consistency models |
| [Stateful vs Stateless](./concepts/tradeoffs/stateful-vs-stateless.md) | Architecture patterns |
| [Sync vs Async](./concepts/tradeoffs/sync-vs-async.md) | Communication patterns |
| [REST vs RPC](./concepts/tradeoffs/rest-vs-rpc.md) | API style comparison |
| [Push vs Pull](./concepts/tradeoffs/push-vs-pull.md) | Data flow patterns |
| [Batch vs Stream Processing](./concepts/tradeoffs/batch-vs-stream-processing.md) | Processing paradigms |
| [Read-Through vs Write-Through Cache](./concepts/tradeoffs/read-through-vs-write-through-cache.md) | Caching patterns |
| [Long Polling vs WebSockets](./concepts/tradeoffs/long-polling-vs-websockets.md) | Real-time strategies |
| [Concurrency vs Parallelism](./concepts/tradeoffs/concurrency-vs-parallelism.md) | Execution models |

---

### [Easy Problems](./problems-easy/)

System design problems suitable for beginners. These introduce core concepts with manageable complexity.

| Problem | Description |
|---------|-------------|
| [URL Shortener](./problems-easy/url-shortener.md) | Short URL generation, base62 encoding, redirect handling |
| [Parking Garage](./problems-easy/parking-garage.md) | Spot management, entry/exit flow, fee calculation |
| [CDN Design](./problems-easy/cdn-design.md) | Edge servers, content caching, routing |
| [Load Balancer](./problems-easy/load-balancer.md) | Traffic distribution system |
| [Distributed Cache](./problems-easy/distributed-cache.md) | Scalable caching layer |
| [Distributed Key-Value Store](./problems-easy/distributed-key-value-store.md) | Simple KV storage |
| [Autocomplete](./problems-easy/autocomplete.md) | Type-ahead search system |
| [Vending Machine](./problems-easy/vending-machine.md) | State machine design |
| [Authentication System](./problems-easy/authentication-system.md) | User auth & sessions |
| [UPI Payment](./problems-easy/upi.md) | Payment processing system |

---

### [Medium Problems](./problems-medium/)

Intermediate level problems requiring understanding of multiple concepts and their interactions.

| Problem | Description |
|---------|-------------|
| [WhatsApp](./problems-medium/whatsapp.md) | Real-time messaging, group chats, encryption |
| [Instagram](./problems-medium/instagram.md) | Photo sharing, feed generation, stories |
| [Netflix](./problems-medium/netflix.md) | Video streaming, CDN, encoding, recommendations |
| [Twitter/X](./problems-medium/twitter.md) | Microblogging, timeline, fan-out strategies |
| [Rate Limiter](./problems-medium/rate-limiter.md) | Token bucket, leaky bucket, sliding window |
| [Notification Service](./problems-medium/notification-service.md) | Push, email, SMS delivery |
| [YouTube](./problems-medium/youtube.md) | Video platform at scale |
| [Spotify](./problems-medium/spotify.md) | Music streaming service |
| [Facebook](./problems-medium/facebook.md) | Social network platform |
| [Tinder](./problems-medium/tinder.md) | Dating app with geolocation |
| [Airbnb](./problems-medium/airbnb.md) | Marketplace platform |
| [Amazon](./problems-medium/amazon.md) | E-commerce platform |
| [Reddit](./problems-medium/reddit.md) | Forum and content aggregation |
| [TikTok](./problems-medium/tiktok.md) | Short video platform |
| [Shopify](./problems-medium/shopify.md) | E-commerce SaaS platform |
| [Kafka](./problems-medium/kafka.md) | Distributed event streaming |
| [Google Search](./problems-medium/google-search.md) | Search engine design |
| [Distributed Job Scheduler](./problems-medium/distributed-job-scheduler.md) | Job queue management |
| [Digital Wallet](./problems-medium/digital-wallet.md) | Wallet & payment system |
| [Online Code Editor](./problems-medium/online-code-editor.md) | Cloud IDE platform |
| [Payment System](./problems-medium/payment-system.md) | Payment processing |
| [Flight Booking](./problems-medium/flight-booking.md) | Reservation system |
| [Analytics Platform](./problems-medium/analytics-platform.md) | Data analytics service |

---

### [Hard Problems](./problems-hard/)

Advanced problems involving complex distributed systems with multiple challenging requirements.

| Problem | Description |
|---------|-------------|
| [Uber](./problems-hard/uber.md) | Location tracking, ride matching, geospatial indexing |
| [Google Docs](./problems-hard/google-docs.md) | Collaborative editing, operational transformation |
| [Dropbox](./problems-hard/dropbox.md) | File sync, chunking, deduplication |
| [Google Maps](./problems-hard/google-maps.md) | Map and navigation service |
| [DoorDash](./problems-hard/doordash.md) | Food delivery platform |
| [Yelp](./problems-hard/yelp.md) | Local business reviews |
| [Zoom](./problems-hard/zoom.md) | Video conferencing platform |
| [Slack](./problems-hard/slack.md) | Team communication platform |
| [S3 (Object Storage)](./problems-hard/s3.md) | Distributed object storage |
| [Web Crawler](./problems-hard/web-crawler.md) | Search engine crawler |
| [BookMyShow](./problems-hard/bookmyshow.md) | Ticket booking system |
| [Code Deployment](./problems-hard/code-deployment.md) | CI/CD pipeline system |
| [Distributed Counter](./problems-hard/distributed-counter.md) | Global counter service |
| [Distributed Locking Service](./problems-hard/distributed-locking-service.md) | Lock management service |
| [Live Comments](./problems-hard/live-comments.md) | Real-time commenting system |

---

## 🎓 Learning Path

### For Beginners
Start with these concepts, then attempt the easy problems:
1. [Scalability](./concepts/scalability.md)
2. [Availability](./concepts/availability.md)
3. [Load Balancing](./concepts/load-balancing.md)
4. [Caching](./concepts/caching.md)
5. [API Design](./concepts/api-design.md)

Then practice with:
- [URL Shortener](./problems-easy/url-shortener.md)
- [Parking Garage](./problems-easy/parking-garage.md)
- [Load Balancer](./problems-easy/load-balancer.md)

### For Intermediate Learners
Study these concepts, then attempt medium problems:
1. [CAP Theorem](./concepts/cap-theorem.md)
2. [Database Sharding](./concepts/database-sharding.md)
3. [Microservices](./concepts/microservices.md)
4. [Message Queues](./concepts/message-queues.md)
5. [Consistent Hashing](./concepts/consistent-hashing.md)

Then practice with:
- [Rate Limiter](./problems-medium/rate-limiter.md)
- [Notification Service](./problems-medium/notification-service.md)
- [Twitter](./problems-medium/twitter.md)

### For Advanced Learners
Master these concepts, then tackle hard problems:
1. [Distributed Locking](./concepts/distributed/distributed-locking.md)
2. [Consensus Algorithms](./concepts/distributed/consensus-algorithms.md)
3. [WebSockets](./concepts/websockets.md)
4. [Database Indexing](./concepts/database-indexing.md)

Then practice with:
- [Uber](./problems-hard/uber.md)
- [Google Docs](./problems-hard/google-docs.md)
- [Dropbox](./problems-hard/dropbox.md)

---

## 💡 System Design Interview Tips

1. **Understand Requirements** - Ask clarifying questions about scale, performance, and features
2. **High-Level Architecture** - Identify major components and their interactions
3. **Data Model** - Choose appropriate databases and schema design
4. **Scalability** - Address through sharding, caching, and load balancing
5. **Reliability** - Consider replication, failover, and monitoring
6. **Security** - Authentication, authorization, and encryption
7. **Tradeoffs** - Discuss consistency, availability, latency, and cost
8. **Capacity Estimation** - Provide rough estimates for storage, bandwidth, and traffic
9. **Visualize** - Draw diagrams for architecture and data flow
10. **Deep Dive** - Be prepared to explain any component in detail

---

## 📖 Additional Resources

- **Books**: [Designing Data-Intensive Applications](https://dataintensive.net/) by Martin Kleppmann
- **YouTube**: [ByteByteGo](https://www.youtube.com/@ByteByteGo) - System Design videos
- **GitHub**: [System Design Primer](https://github.com/donnemartin/system-design-primer)
- **Blogs**: Engineering blogs from Netflix, Uber, Airbnb, and other tech companies

---

## 📄 File Index

See [FILE-INDEX.md](./FILE-INDEX.md) for a complete listing of all topics covered.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to add new topics or improve existing content:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

## 📜 License

This collection is based on the awesome-system-design-resources by [ashishps1](https://github.com/ashishps1). 

---

<p align="center">
  ⭐ Star this repository if you find it helpful!
</p>
