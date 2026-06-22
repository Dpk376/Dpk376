<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0908,100:6b4f3a&height=180&section=header&text=Deepak%20Kumar%20S%20S&fontColor=D4B896&fontSize=48&fontAlignY=38&desc=Senior%20Backend%20Engineer%20%7C%20Distributed%20Systems&descAlignY=58&descSize=18" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=F6C517&center=true&vCenter=true&width=760&lines=SDE-2+%40+Flipkart+%F0%9F%9B%92;Java+21+%7C+Spring+Boot+%7C+Kafka+%7C+Distributed+Systems;ASX+CHESS+Replacement+%7C+20M+trade+events%2Fday;Contributor%3A+Apache+Fineract+%7C+Spring+AI+%7C+Apache+Kafka;AWS+%26+Azure+Certified+%7C+Best+Employee+2025+%40+TCS" alt="Typing SVG" />

<p>
  <img src="https://img.shields.io/badge/SDE--2%20%40%20Flipkart-F6C517?style=for-the-badge&logo=flipkart&logoColor=2874F0" />
</p>

<p>
  <a href="https://www.linkedin.com/in/deepak-kumar-s-s-523335207">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:deepakpersonal376@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-8B5E3C?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://dpk-portfolio-chi.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-2A1F18?style=for-the-badge&logo=vercel&logoColor=D4B896" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=Dpk376&style=for-the-badge&color=C9A87C" />
</p>

</div>

---

### 👨‍💻 About Me

- <img src="https://raw.githubusercontent.com/Dpk376/Dpk376/main/flipkart.png" width="18" style="vertical-align:middle"/> **SDE-2 at Flipkart** - Backend Engineer on one of India's largest e-commerce and supply chain platforms
- 🏢 **Previously - Senior Backend Engineer at TCS** - Core engineer on the ASX CHESS Replacement program, Australia's national financial market clearing infrastructure
- 🌍 Personally owned **4 production microservices** processing **20 million trade settlement events/day** with exactly-once delivery guarantees
- 🔐 Built the **Quartz Gateway** - SAML 2.0 SSO (ForgeRock) + SCIM 2.0 provisioning (SailPoint) + TLS/mTLS on AWS ALB across 58+ production releases in 23+ environments
- 🔭 Open-source contributor across **Apache Fineract** (5 merged PRs), **Spring AI**, **Apache Kafka**, and **OpenHands**
- ⛓️ Blockchain researcher - preprint published on Zenodo, **TCS TACTICS 2023 India 1st place** (287 participants)
- 🥇 **Best Employee Award 2025** at TCS for engineering contribution and client ownership on ASX CHESS
- 🏆 AWS Solutions Architect Associate · Azure Developer Associate (AZ-204) · GitHub Copilot certified
- 📍 Chennai, India

---

### 📈 TCS - ASX CHESS Replacement (Production Impact)

<div align="center">

| Scale | Reliability | Ownership |
|:---:|:---:|:---:|
| 20M settlement events/day | Exactly-once Kafka delivery | 4 microservices owned end-to-end |
| 75% consumer lag reduction | sub-200ms p99 latency | 58+ releases, 23+ environments |
| 40% API latency reduction | sub-50ms Redis pub/sub | 14-month forward-deployed client lead |

</div>

---

### 🌐 Open Source Contributions

| Project | PRs | What I did |
|---|:---:|---|
| 🌿 **[Apache Fineract](https://github.com/apache/fineract)** | **5 merged** | Migrated integration tests from RestAssured to type-safe Feign clients - FINERACT-2454 (PR [#5668](https://github.com/apache/fineract/pull/5668), [#5670](https://github.com/apache/fineract/pull/5670)), FINERACT-2549 (PR [#5658](https://github.com/apache/fineract/pull/5658), [#5659](https://github.com/apache/fineract/pull/5659), [#5675](https://github.com/apache/fineract/pull/5675)) |
| 🤖 **[Spring AI](https://github.com/spring-projects/spring-ai)** | **2 open** | `Locale.ROOT` consistency fixes for Pinecone filter operators ([#6479](https://github.com/spring-projects/spring-ai/pull/6479)) and OpenAI protocol enum values ([#6477](https://github.com/spring-projects/spring-ai/pull/6477)) |
| 📨 **[Apache Kafka](https://github.com/apache/kafka)** | **3 open** | Unit tests for `ToolsUtils` ([#22577](https://github.com/apache/kafka/pull/22577)), `KStream` API ([#22574](https://github.com/apache/kafka/pull/22574)), `DeleteRecordsCommand` ([#22573](https://github.com/apache/kafka/pull/22573)) |
| 🙌 **[OpenHands](https://github.com/OpenHands/OpenHands)** | **1 open** | Fixed git pagination boundary bug causing item drops in app-server ([#14785](https://github.com/OpenHands/OpenHands/pull/14785)) |

---

### 🚀 Backend Portfolio

#### Distributed Systems & Infrastructure

| Repository | Description | Stack |
|---|---|---|
| 🏦 **[PostTradeClearingPlatform](https://github.com/Dpk376/PostTradeClearingPlatform)** | Production-grade post-trade clearing and settlement platform simulating a stock exchange clearing backend. 8 microservices (TradeService, PositionService, ClearingService, ReferenceDataService, CorporateActionService, NotificationService, MarketIntegrationGateway, API Gateway) communicating via Kafka. Transactional Outbox, DLQ, oversell protection, Keycloak OAuth2/OIDC, Flyway migrations, Prometheus + ELK observability stack | Java 21, Spring Boot 3.3, Kafka, PostgreSQL, Redis, Keycloak, Flyway, Prometheus, Grafana, ELK |
| 📨 **[kafka-production-patterns-java](https://github.com/Dpk376/kafka-production-patterns-java)** | Staff-level Kafka patterns reference: idempotent consumers, exactly-once semantics via Transactional Outbox, DLQ design, and consumer-lag observability. Built to demonstrate production-grade event streaming at scale | Java 21, Spring Boot, Spring Kafka, Micrometer |
| ⚡ **[RateLimitControlPlane](https://github.com/Dpk376/RateLimitControlPlane)** | Per-tenant distributed rate limiting with Redis Token Bucket via atomic Lua scripts, runtime hot-loadable plugin architecture via `URLClassLoader` + `ServiceLoader`, admin REST API for quota management, and Micrometer/Prometheus observability | Java, Spring Boot, Spring Cloud Gateway, Redis, Prometheus |
| ☁️ **[Capacity-manager-workload-router-service](https://github.com/Dpk376/Capacity-manager-workload-router-service)** | Spring Boot control-plane that tracks capacity units across simulated worker nodes, routes workloads using a Least-Loaded algorithm, and automatically rebalances on node failure | Java, Spring Boot |
| 🎼 **[Orchestra-SF](https://github.com/Dpk376/Orchestra-SF)** | Workload-orchestration control plane on Azure Service Fabric - stateless/stateful Reliable Services, Int64 partitioning, replica failover, service remoting, and Reliable Collections through a capacity-aware workload lifecycle engine | C#, Azure Service Fabric, ASP.NET Core |

#### API Gateways & Security

| Repository | Description | Stack |
|---|---|---|
| 🔐 **[enterprise-rbac-gateway](https://github.com/Dpk376/enterprise-rbac-gateway)** | Reactive API Gateway with edge OIDC/JWT validation, Open Policy Agent (OPA) + Rego for declarative route-level authorization, non-blocking append-only PostgreSQL audit log, and deep Prometheus metrics for compliance | Java, Spring Cloud Gateway, OPA, PostgreSQL, Prometheus |

#### AI & LLM Infrastructure

| Repository | Description | Stack |
|---|---|---|
| 🔄 **[Event-Driven-AI-Agent-Orchestration-Platform](https://github.com/Dpk376/Event-Driven-AI-Agent-Orchestration-Platform)** | Event-driven platform where clinical events flow through Kafka (KRaft mode) into a 4-stage LLM agent pipeline (Classify → Summarize → Route → Act). Transactional Outbox for reliable event publishing, Resilience4j circuit breakers, Redis-backed token budgets, idempotent consumers, DLQ, and distributed tracing | Java 21, Spring Boot, Kafka, Redis, OpenAI/Anthropic, PostgreSQL |
| 🤖 **[AI-Assisted-Workflow-Automation-Agent](https://github.com/Dpk376/AI-Assisted-Workflow-Automation-Agent)** | PR review agent as a modular monolith - receives GitHub webhooks, durably queues review jobs using PostgreSQL `FOR UPDATE SKIP LOCKED`, runs a bounded tool-using LLM loop, posts structured review comments. Webhook sig verification, exponential retry, circuit breakers, token budget enforcement | Java 21, Spring Boot, PostgreSQL, Redis, OpenAI |
| 🧠 **[llm-inference-gateway](https://github.com/Dpk376/llm-inference-gateway)** | Load-aware LLM request routing using a composite score (70% p99 latency + 30% active request count) across multiple model-serving backends with health checks, circuit breaking, Prometheus metrics, and Grafana dashboards | Java 17, Spring Boot, Prometheus, Grafana |
| 🚀 **[dynamic-batching-inference-server](https://github.com/Dpk376/dynamic-batching-inference-server)** | LLM inference server that groups concurrent requests into dynamic batches (configurable max-batch + max-wait) to maximize throughput. Kubernetes HPA autoscaling on `inference_queue_depth` custom metric (2-20 replicas), load-generator stress harness | Java 17, Spring Boot, Kubernetes, Prometheus Adapter, HPA |

#### Interview Prep & LLD

| Repository | Description | Stack |
|---|---|---|
| 📚 **[low-level-design-java-dpk](https://github.com/Dpk376/low-level-design-java-dpk)** | Java LLD portfolio from OOP basics to Design Patterns and Multithreading. Maven multi-module, production-grade code with tests - built for backend system design interviews | Java 17, Maven |

---

### ⚡ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)

**Backend & Frameworks**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Spring Cloud Gateway](https://img.shields.io/badge/Spring_Cloud_Gateway-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium_CDC-FF6633?style=flat-square&logo=redhat&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-02569B?style=flat-square&logo=fastapi&logoColor=white)
![Hibernate](https://img.shields.io/badge/JPA_/_Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Resilience4j](https://img.shields.io/badge/Resilience4j-6DB33F?style=flat-square&logo=spring&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazon-dynamodb&logoColor=white)

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Azure Service Fabric](https://img.shields.io/badge/Azure_Service_Fabric-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazon-cloudwatch&logoColor=white)

**Identity & Security**

![SAML SSO](https://img.shields.io/badge/SAML_2.0_(ForgeRock)-2C3E50?style=flat-square&logo=keycloak&logoColor=white)
![SCIM](https://img.shields.io/badge/SCIM_2.0_(SailPoint)-1F6FEB?style=flat-square&logo=okta&logoColor=white)
![OPA](https://img.shields.io/badge/Open_Policy_Agent-7C5CBF?style=flat-square&logo=openpolicyagent&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2_/_OIDC-EB5424?style=flat-square&logo=auth0&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![mTLS](https://img.shields.io/badge/TLS_/_mTLS-2C3E50?style=flat-square&logo=letsencrypt&logoColor=white)

---

### 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Dpk376&show_icons=true&hide_border=true&count_private=true&title_color=C9A87C&icon_color=D2A679&text_color=E8D9C4&bg_color=00000000" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dpk376&layout=compact&hide_border=true&title_color=C9A87C&text_color=E8D9C4&bg_color=00000000" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=Dpk376&hide_border=true&background=00000000&ring=C9A87C&fire=D2A679&currStreakLabel=C9A87C&currStreakNum=E8D9C4&sideLabels=E8D9C4&sideNums=E8D9C4&dates=B08968&stroke=8B6F47" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Dpk376&hide_border=true&area=true&bg_color=0a0908&color=E8D9C4&line=C9A87C&point=D2A679&area_color=6b4f3a&title_color=C9A87C&custom_title=Contribution%20Graph" />

</div>

---

### 🏅 Achievements

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Dpk376&theme=gruvbox&no-frame=true&margin-w=4&column=7" />

</div>

- 🥇 **Best Employee Award 2025** at TCS, for engineering contribution and direct client ownership on the ASX CHESS Replacement program
- 🏆 **1st place (287 participants)** - TCS TACTICS 2023 India-level (Metaplay - Decentralized Content Marketplace)

---

### 📜 Research

**[Decentralized Content Creation Marketplace: A Modular Web3 Architecture](https://doi.org/10.5281/zenodo.19161365)**
*Preprint · Published on Zenodo · TCS TACTICS 2023 India-Level*

Proof-of-concept for a creator economy platform on Ethereum with IPFS storage, Polygon L2 scaling, DAO governance, and smart contract copyright enforcement.

---

### 📜 Certifications

![AWS](https://img.shields.io/badge/AWS_Solutions_Architect-Associate-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_Developer-Associate_AZ--204-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-Certified-2A1F18?style=flat-square&logo=github&logoColor=D4B896)

---

<div align="center">
  <i>"Building reliable, secure, and high-performance backend systems at scale."</i>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6b4f3a,100:0a0908&height=120&section=footer" width="100%" />
