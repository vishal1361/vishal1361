# Hi, I'm Vishal 👋

**Software Development Engineer II at [Rocketlane](https://www.rocketlane.com)** · Chennai, India · 🌐 [vishal1361.github.io](https://vishal1361.github.io)

I build scalable full-stack platforms: distributed systems, real-time sync, workflow automation and analytics data pipelines. Much of my work goes into making products faster, more reliable and easier to observe.

- 👥 Leading a team of **6 engineers** across **4 features**
- 🔄 Built a **CDC pipeline** from Postgres to Snowflake and BigQuery (Debezium, Kafka, Flink) and backfilled **700M+ rows** of historic data
- 🚀 Cut Resource Management API P95 latency from **30–50s to 2–4s**. The changes rolled out to **600+ paid accounts**.
- 💸 Built **Expense Management** (adopted by **250+** premium and enterprise accounts) and the **Revenue Recognition Ledger**
- 📈 Set up Datadog observability for SQS, Kinesis, reconciliation pipelines and APIs, and built an agent that posts a daily summary of production failures to Slack
- 🧩 Designed a hierarchical Custom Fields system and a trigger → condition → action automation framework

---

## 🏢 Work at Rocketlane

> This code is proprietary and lives in Rocketlane's private GitHub organization, so it isn't in my public repos. The links below go to public product demos and docs.

| Project | Stack | Highlights |
|---|---|---|
| **CDC Data Pipeline** | AWS, Debezium, Kafka, Flink, Snowflake, BigQuery | Change data capture from Postgres through Debezium and Kafka, transformed in Flink and written by sink connectors to Snowflake and BigQuery, with logging at each stage. Handles future DDL changes without pipeline updates. Backfilled 700M+ rows of historic data into Snowflake. |
| **Revenue Recognition Ledger** · [docs](https://help.rocketlane.com/support/solutions/articles/67000750715-managing-the-revenue-recognition-ledger-in-rocketlane) | React, AG-Grid, Redis, ClickHouse | Dual-view AG-Grid (server-side row model + multi-level tree grouping) with virtual scrolling and server-driven pagination; Redis-backed idempotency for concurrent bulk writes; ClickHouse aggregations for system-vs-recognized revenue; RBAC enforced across single, bulk and export paths. Used in several enterprise deals. |
| **Expense Management** · [demo](https://youtu.be/VTu8t8TQhp0) | React, AG-Grid, WebSockets, RBAC | Real-time grid with Project / Report / Expense grouping and WebSocket cell updates; multi-level approval chain (auto, owner, custom workflow, force-approve) modeled as a state machine with stage-scoped RBAC. Adopted by 250+ paid accounts. |
| **Resource Management Revamp** | Spring Boot, SQL | Redesigned the data-access layer and query execution paths: P95 went from 30–50s to 2–4s for 600+ paid accounts. |
| **Automation Platform & Custom Fields** · [demo](https://youtu.be/9s3H41xwoog) | Java, Spring Boot, React | Trigger-condition-action framework with reusable workflows; built 20+ workflow triggers; extensible hierarchical custom fields. |
| **Production Triage Agent** | Datadog, Slack | Reads observability metrics and posts a daily Slack summary of failures from the previous 24 hours. |

## 🛠️ Personal Projects

| Repo | What it is |
|---|---|
| [CoNote](https://github.com/vishal1361/CoNote) | Collaborative note-taking app with fine-grained permission management (Java) |
| [dShop](https://github.com/vishal1361/dShop-client) | Decentralized shopping platform: [client](https://github.com/vishal1361/dShop-client), [server](https://github.com/vishal1361/dShop-server), [Solidity contracts](https://github.com/vishal1361/dShop-contract), [ML model](https://github.com/vishal1361/dShop-ml-model) |
| [Project Memory](https://github.com/vishal1361/project-memory-frontend) | Full-stack JS app: [frontend](https://github.com/vishal1361/project-memory-frontend) + [backend](https://github.com/vishal1361/project-memory-backend) |
| [Blog Application](https://github.com/vishal1361/Blog-Application) | Spring Boot blog backend |
| [Flask REST API](https://github.com/vishal1361/Flask-REST-API) | REST API serving movie data |
| ML notebooks | [Face recognition](https://github.com/vishal1361/FACE_RECOGNITION_MODEL) · [OCR with KNN](https://github.com/vishal1361/OPTICAL_CHARACTER_RECOGNITION) · [Image compression with KNN](https://github.com/vishal1361/Image_compression_using_KNN) · [Sentiment analysis](https://github.com/vishal1361/Sentiment_analysis) |

## 🧰 Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=js,ts,java,py,cpp,react,nodejs,spring,postgres,redis,docker,aws,git" />
</p>
<p>
  <img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black" />
  <img src="https://img.shields.io/badge/AG--Grid-0E2A47?style=for-the-badge" />
  <img src="https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" />
  <img src="https://img.shields.io/badge/Ant_Design-0170FE?style=for-the-badge&logo=antdesign&logoColor=white" />
  <img src="https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Debezium-91D443?style=for-the-badge&logoColor=black" />
  <img src="https://img.shields.io/badge/Apache_Flink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white" />
</p>

## 🏆 Achievements

- Top **5.82%** on [LeetCode](https://leetcode.com/u/vishal1361/) with a contest rating of **1,870**
- **Pupil** on Codeforces, with a peak rating of 1,256
- Recognized by Rocketlane for the Resource Management revamp
- Recognized by Rocketlane for leading the Tax Codes, Invoicing, Expense & Governance workstream

## 🎓 Education

**B.E. Computer Science**, SSN College of Engineering, Chennai (2020–2024) · CGPA 8.45

## 📫 Reach me

[![Portfolio](https://img.shields.io/badge/Portfolio-vishal1361.github.io-6EF2C0?logo=githubpages&logoColor=black)](https://vishal1361.github.io)
[![Email](https://img.shields.io/badge/Email-sachanvishal.092%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:sachanvishal.092@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vishal2010073-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishal2010073)
[![LeetCode](https://img.shields.io/badge/LeetCode-vishal1361-FFA116?logo=leetcode&logoColor=black)](https://leetcode.com/u/vishal1361/)

