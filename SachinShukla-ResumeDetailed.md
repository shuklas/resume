# Sachin Shukla

**Principal Engineer** | AWS OpenSearch Service

---

## Summary

Principal Engineer with 25+ years of experience building large-scale distributed systems across Cloud (AWS), Advertising, E-commerce, Social Networking, and FinTech. Proven track record of modernizing monolithic systems, driving operational excellence, and mentoring engineers to promotion.

**Languages:** Golang, Java, Python, C#

---

## Education

B.Tech Computer Science — IIT Guwahati

---

## Experience

### Amazon Web Services — Principal Engineer

**AWS OpenSearch Service, Control Plane** | Jun 2017 – Present

Rebuilt the control plane to scale from 40K to 450K clusters across 44 regions while adding major capabilities — Rolling Blue/Green, Blue/Green Reduction (in-place updates), VPC Support, Security & Encryption (at rest & in transit), and High Availability. 99.99% API availability, 99.5% operation success rate. Grew the control plane team from 10 → 30+ engineers; mentored 10+ engineers.

---

### Flipkart — Tech Lead | Feb 2014 – Mar 2017

- **Retail Inventory Management** — Redesigned legacy system with no active developers; split into microservices. Feed processing: 30 min → seconds (1M records). Sustained Big Billion Day sales.
- **Auction-based Ad Pricing** — Designed and socialized Second Price auction for product listing ads. Built bid suggestion engine and auction data pipeline.
- **Full Funnel Attribution** — Built Hive pipeline computing campaign uplift across search, browse, purchase, and page views.
- **Ad Pricing Service** — Low-latency (<10ms) price serving at 15K QPS peak. Smart client + multi-layer caching. Grew ad revenue 3x.

**Tech:** Java, HBase, MySQL, Elasticsearch, Couchbase, RxJava, Hive, MapReduce, RabbitMQ

---

### Microsoft — SDE II | Jun 2013 – Feb 2014

- **Bing Ads (AdCenter)** — Built programmatic direct APIs for campaign product management. Migrated on-premise services to Azure. Designed Audience Insights portal for cross-device analytics.

**Tech:** C#, .NET, Azure, SQL Server

---

### Yahoo — Senior SDE | Dec 2009 – Jun 2013

- **Trending URL Pipeline** — Real-time extraction of trending URLs from Twitter Firehose using Storm + Kafka.
- **UGC Cloud Platform** — Distributed content platform (ratings, reviews, blogs) handling 4K read QPS. Designed data migration framework.

**Tech:** Java, Spring, Storm, Kafka, ActiveMQ, NoSQL

---

### HeadStrong (UBS, FINRA clients) — Senior Engineer | Dec 2004 – Nov 2009

- Built systems for derivatives processing across UBS and FINRA: parameter service (distributed, fault-tolerant), trade blotters, FX options auto-pricing, and regulatory (OATS) reporting.

**Tech:** Java, Spring, Hibernate, FIX Protocol, Oracle, RMI, Swing

---

### ADP India — Software Engineer | Jul 2001 – Dec 2004

- Maintained and enhanced IMPACT — a Straight Through Processing system for US Fixed Income used by JP Morgan, HSBC, UBS, Nomura. Led RPG → Java porting.

**Tech:** Java, RPG, DB2, IBM AS400

---

## Impact Highlights

| Metric | Before | After |
| --- | --- | --- |
| Sev2 tickets/month | 450+ | ~200 |
| RM release cycle | 1.5 months | 15 days |
| B/G failure rate | 1.6% | 0.6% |
| AMI build time | 12 hours | 30 min |
| Metering revenue recovered | — | +$30M/yr |
| Version upgrades/day | 0 | 750 |

---

## Appendix: System Scale

| Metric | Value |
| --- | --- |
| Clusters managed | 450K |
| Regions | 44 |
| ES/OS versions supported | 34 |
| API requests | 25M/hr (largest region: 2.5M/hr) |
| Cluster changes | 40K/hr (largest region: 7K/hr) |
| API latency | P50: 18ms, P99: 160ms |
| API availability | 99.99% |
| Operation success rate | 99.5% |

---

## Appendix: Architecture & Platform Modernization

- **Built next-gen workflow platform (Symphony)** — replaced monolithic Resource Manager with short-lived workflows, cellular architecture, and flow control. Used to host various features like pre-validation, self-healing, node replacement, and metering.
- **Defined CP Evolution vision** — proposed splitting the RM monolith into lifecycle workflows, config propagation, resource management, and deployment system. Spawned 3 new teams (Legos, SDPDS, Dysco).
- **Domain Change Processing Model** — diff-based data model enabling cross-system orchestration. Influenced roadmaps of 5 teams.

---

## Appendix: Deployment & Developer Velocity

- **CP/DP Deployment Decoupling (CICD)** — separated pipelines. Release cycle: 1.5 months → 15 days. AMI build: 12 hrs → 30 min.

---

## Appendix: Reliability & Operational Excellence

- **B/G Pre-validation** — catches 50% of config failures before Blue/Green. Eliminated unbalanced-cluster outages.
- **B/G Resiliency** — failure rate 1.6% → 0.6%. CDI failures ↓24%, DDI ↓26%.
- **Led first CP ORR and Security Review** post-launch.

---

## Appendix: Feature Delivery

- **Version Upgrades** — designed in-place upgrades (750/day). Critical for ES → OpenSearch rebrand.
- **B/G Reduction** — enabled in-place updates for master nodes, EBS, ALB (30%+ of changes previously needing B/G).
- **VPC Support** — built and launched Virtual Private Cloud connectivity for OpenSearch domains, enabling customers to communicate directly through their VPC without exposing traffic to the public internet.
- **Encryption at Rest & in Transit** — delivered end-to-end encryption capabilities for customer data protection.

