---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<div style="text-align: center; margin-bottom: 2rem;">
  <h2 style="margin-bottom: 0.4rem;">Yasmin (Zahra) Mohammadi</h2>
  Philadelphia, PA &nbsp;|&nbsp; <a href="mailto:zm1384414@gmail.com">zm1384414@gmail.com</a> &nbsp;|&nbsp; <a href="https://www.linkedin.com/in/yasmin-mohammadi-4a41b5151">LinkedIn</a> &nbsp;|&nbsp; <a href="/">Website</a>
</div>

Research Interests
======

Database Systems; Machine Learning for Data Systems; Adaptive and Learned Data Systems; Query Processing and Optimization; Natural-Language Interfaces to Databases; Graph Data Systems

Education
======

### Temple University

**Ph.D. in Computer and Information Sciences, Information Systems - GPA: 3.84/4.00**<br>
Philadelphia, PA &middot; 2025-Present

### Alzahra University

**B.S. in Computer Engineering**<br>
Tehran, Iran &middot; 2015-2021

- Undergraduate thesis: *Persian Text Normalization and Context-Aware Spelling Correction.*
- Developed a context-aware approach for detecting and correcting Persian spelling errors, with particular emphasis on homophones and context-dependent word substitutions that cannot be identified through dictionary lookup alone.
- Investigated lexical ambiguity introduced by languages that share the Perso-Arabic writing system, including Arabic and Urdu, identifying borrowed words and valid cross-lingual forms to distinguish them from true spelling errors.

### Sharif University of Technology

**Exchange Student, Computer Engineering**<br>
Tehran, Iran &middot; 2016-2021

- Completed nine semesters of undergraduate Computer Engineering coursework as an exchange student.

Publications
======

### CypherLens: An Interactive Demo for Evaluating and Diagnosing NL-to-Cypher Systems

**Yasmin Mohammadi**, et al.<br>
**VLDB 2026 Demonstration Track.** Accepted.

### CypherLens: Graph-Native Evaluation, Diagnosis, and Repair for NL-to-Cypher Systems

**Yasmin Mohammadi**, et al.<br>
Under review, **VLDB 2027**.

### CypherSem: Graph-Native Semantic Error Analysis for NL2Cypher

**Yasmin Mohammadi**, et al.<br>
Under review, **KDD 2027**.

Selected Research Projects
======

### Learned Indexes for Graph Databases

**Temple University**

- Implemented learned indexing techniques originally developed for relational data and adapted them for evaluation on knowledge graph workloads.
- Evaluated their performance across multiple knowledge graph data distributions to characterize how distributional properties affect learned-index accuracy, efficiency, and applicability to graph data.

### CypherSem - Semantic Error Analysis for NL-to-Cypher

**Temple University**

- Developed a three-level, graph-native semantic error taxonomy for NL-to-Cypher spanning four semantic dimensions, 17 categories, and 54 fine-grained error types, and constructed a 3,568-pair human-annotated benchmark.
- Evaluated seven LLMs for fine-grained semantic error detection and semantic correctness judging, uncovering persistent failures on graph-specific errors and systematic benchmark quality issues.

### CypherLens - Evaluation, Diagnosis, and Repair for NL-to-Cypher

**Temple University**

- Designed a graph-native evaluation framework that canonicalizes and aligns Cypher query outputs across aliases, lineage, graph-shaped values, and derived projections, reducing the average gap to human semantic judgments from 25.69% to 1.56% across three Neo4j databases.
- Developed a deterministic multi-agent repair architecture with specialized Diagnoser, Selector, Corrector, and Verifier agents backed by 28 schema-, structure-, execution-, plan-, and intent-aware tools, improving exact match from 24.3% to 68.4% on the evaluated repair set.

### CIRA - Continual Experience Learning for Adaptive Data Synthesis

**Temple University**

- Developing a training-free continual learning framework that converts human and automated feedback into structured, reusable experiences that improve future synthetic-data generation without updating LLM parameters.
- Building an experience lifecycle that compiles feedback into scoped semantic knowledge, then adds, updates, merges, rejects, and selectively retrieves experiences from an evolving memory to guide subsequent agents.
- Evaluating whether experience accumulation improves expert-validated data quality and difficult-query coverage while reducing human supervision, with NL-to-Cypher as the primary testbed and transfer across domains and to NL-to-SQL.

Industry Experience
======

### Jambit GmbH - Campaign Manager, DSSC1, DSSC2

**Software Engineer**<br>
Yerevan, Armenia &middot; 2022-2025

- Owned end-to-end development of large-scale production systems for Volkswagen Group vehicle-data platforms, working across frontend UI, backend services, database layers, deployment, production support, and debugging for applications used across Europe, the United States, and Canada.
- Developed and maintained a distributed microservice architecture comprising roughly ten cooperating services built with Java and Vert.x, with service coordination through Hazelcast, multithreaded processing, application-level caching, and high-volume database access.
- Improved performance, scalability, and reliability under high request volumes and time-sensitive vehicle data, including cache-refresh logic, concurrent processing, database optimization, production incident diagnosis, and deployment and operations using PostgreSQL, Docker, Kubernetes, and AWS.

### Polixis - Ardis

**Java Developer**<br>
Yerevan, Armenia &middot; 2021-2022

- Designed and developed a distributed data migration and streaming platform for moving datasets across heterogeneous storage systems, including MongoDB, Elasticsearch, and ScyllaDB.
- Built data-transfer and real-time migration services using Java, Spring Boot, Kafka, Kafka Streams, Kafka Connect, PostgreSQL, Docker, and Kubernetes.
- Managed database changes across the software release lifecycle by identifying and capturing approved changes in development and test environments and promoting them through test, pre-production, and production stages.

### Soha Software Group - Naira

**Java Developer**<br>
Tehran, Iran &middot; 2020-2021

- Developed an event-driven, self-hosted push-notification framework for large-scale message delivery without Firebase, focusing on server efficiency, delivery cost, and mobile battery consumption.

### DPI (formerly IBM-affiliated operations)

**Junior Java Developer**<br>
Tehran, Iran &middot; 2019-2020

- Developed and supported Java/Spring Boot microservices for a CRM platform serving approximately 500,000 active users, using IBM MQ, REST APIs, and DB2 with production deployment and incident support.

Technical Skills
======

- **Programming:** Python, Java, SQL, Cypher, Bash, C, JavaScript
- **Databases & Data Systems:** Neo4j, PostgreSQL, MongoDB, ScyllaDB, Elasticsearch, MySQL, MS SQL Server, DB2, Kafka, Kafka Streams, Kafka Connect
- **LLM & ML Systems:** Transformers, Tool-Using and Multi-Agent Systems, RAG, LLM Evaluation, Retrieval and Memory Systems, PyTorch, TensorFlow, LangChain
- **Distributed Systems & Cloud:** Spring Boot, Vert.x, Hazelcast, RabbitMQ, REST APIs, Microservices, Docker, Kubernetes, AWS, Jenkins
- **Research Methods & Tools:** Linux, Git, LaTeX, benchmark and dataset construction, human annotation, experimental evaluation
