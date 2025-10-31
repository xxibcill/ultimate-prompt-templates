# Phase 3: NoSQL & Specialized Databases — Deep Research Prompt

```
ROLE
You are a database generalist with deep expertise in NoSQL and specialized data systems. For Phase 3 (Weeks 21–32), craft a curriculum that builds practical mastery across document, key-value/column-family, graph, and specialized (time-series, vector) databases.

PHASE SCOPE
- Weeks: 21–32 (110–165 hours)
- Topics: 3.1 Document Stores (MongoDB); 3.2 Key-Value & Column-Family (Redis, Cassandra/DynamoDB); 3.3 Graph (Neo4j); 3.4 Specialized (InfluxDB, vector DBs like Pinecone/Weaviate)

CRITICAL CONTEXT
- Learner: Mid-level engineer aiming for staff-level versatility
- Phase Focus: Choosing the right store, modeling trade-offs, and delivering working systems with clear SLAs
- Time: ~10–15 hours/week; Practice-heavy orientation
- Budget: Up to $500/month

RESEARCH REQUIREMENTS
1) Learning Resources (Phase 3 topics only)
   - For each DB family: 1 primary (4.5+), 2 alternatives, 1 free option; include URL, price, edition, time
   - Prefer official courses/certs (MongoDB U, Redis U, DataStax Academy) with hands-on labs
2) Real-World Project Sources
   - Reference code and schemas from production-style apps (e-commerce, IoT time-series, recommendations)
   - Case studies: consistency models in practice, hot key mitigation, denormalized document design, graph traversal costs
   - Incident reports: cache stampedes, tombstone issues, write amplification
3) Hands-on Environments
   - Docker Compose stacks: MongoDB, Redis, Cassandra, Neo4j, InfluxDB; optional vector DB (Pinecone/Weaviate) with Python client
   - Seed datasets (1GB/10GB) and workload generators per store; perf dashboards
   - Labs: aggregation pipelines, Redis eviction strategies, Cassandra partitioning, graph algorithms, vector similarity search
4) Expert Validation
   - Curate 6–10 authoritative resources (vendor docs, books, conference talks)
   - Summarize when to prefer each store; decision matrix linking workloads to stores
5) Career Optimization
   - 15 scenario questions mapping use-cases → store choice → model → ops plan → SLA
   - Portfolio briefs: real-time analytics dashboard (MongoDB), distributed session store (Redis), IoT platform (Cassandra), recommendation engine (Neo4j), AI semantic search (vector)
6) Learning Acceleration
   - Spaced repetition for consistency models, data modeling heuristics, index/partition rules
   - Fast-feedback labs with measurable KPIs and pass/fail thresholds

DELIVERABLE STRUCTURE (Weeks 21–32)
- Weekly cadence: Mon (Theory 2h), Wed (Lab 2h), Fri (Project 3h), Sun (Assessment 2h)
- For each week:
  1. Outcomes tied to model/query/ops skills per store
  2. Primary + alternatives; free option; exact modules
  3. Lab with workload and KPIs (throughput, p95, storage)
  4. Project milestone with acceptance criteria (deploy, test, observe)
  5. Three self-check questions + rubrics
  6. One realistic scenario (e.g., cache stampede) with mitigation plan

QUALITY CRITERIA
- 2023–2024 resources or justified classics; difficulty labels; ±15% estimates
- Free vs. paid flagged; fallbacks included; must-have vs. nice-to-have skills

SPECIAL CONSIDERATIONS (Phase 3)
- Make trade-offs explicit: consistency vs. latency; read vs. write patterns; storage/TTL policies
- Ensure modeling examples include migrations and evolution strategies
- Include operational care: backups, monitoring, scaling/partition tuning

ULTRA-THINK PROCESS
1. Start from workload and access patterns; select store & model intentionally
2. Validate with small spikes; measure KPIs before/after model/index changes
3. Cross-check guidance across vendor docs and independent sources
4. Synthesize decision matrix + anti-patterns list
5. Risk review: hot keys, cross-partition queries, eviction storms, tombstones
6. Verification: repeatable perf tests with reproducible environments

OUTPUT FORMAT
1) Executive Summary for Phase 3 (≤400 words)
2) Week-by-week curriculum (Weeks 21–32)
3) Resource library per store with links and time/cost
4) Lab guides (commands, KPIs, expected behaviors)
5) Project briefs with acceptance criteria + SLAs
6) Assessment framework (skills matrix + evidence)
```

