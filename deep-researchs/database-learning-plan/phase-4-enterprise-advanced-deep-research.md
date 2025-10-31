# Phase 4: Enterprise & Advanced Topics — Deep Research Prompt

```
ROLE
You are a distributed systems and database operations expert. For Phase 4 (Weeks 33–44), deliver a curriculum that builds operational excellence in DBA fundamentals, distributed consensus/transactions, and event-driven architectures.

PHASE SCOPE
- Weeks: 33–44 (110–165 hours)
- Topics: 4.1 DBA Mastery (backup, replication/HA, security); 4.2 Distributed Systems & Consensus (Paxos/Raft, distributed txns, multi-region); 4.3 Event Sourcing & Streaming (CDC, Kafka, CQRS)

CRITICAL CONTEXT
- Learner: Aspiring senior/staff engineer who must run reliable, secure, and globally distributed data systems
- Phase Focus: Operational rigor, failure tolerance, and streaming-first data movement
- Time: ~10–15 hours/week; Project-heavy
- Budget: Up to $500/month

RESEARCH REQUIREMENTS
1) Learning Resources (Phase 4 topics only)
   - Per subtopic: 1 primary (4.5+), 2 alternatives, 1 free option; include URL, cost, edition/year, time
   - Prioritize resources with real HA/DR runbooks and streaming labs
2) Real-World Project Sources
   - Replication/HA implementations with failover testing; PITR configurations; security hardening guides
   - Raft/Paxos explainers with reference implementations; global distribution design docs
   - CDC pipelines (Debezium) + Kafka stream processing case studies
3) Hands-on Environments
   - Docker Compose for Postgres replicas + orchestrated failover; TLS, auditing, least-privilege configs
   - Raft toy implementation lab; multi-region topology design exercise
   - CDC to Kafka with end-to-end verification dashboards
4) Expert Validation
   - 6–10 authoritative references (MIT 6.824, Raft paper, vendor HA guides, Bellemare)
   - Summaries with operational caveats and checklists
5) Career Optimization
   - 15 ops/distributed systems interview questions with answer outlines and failure drills
   - Portfolio briefs: automated failover (<1 min), Raft consensus demo, event-sourced banking, CDC pipeline
6) Learning Acceleration
   - Ops runbooks, chaos checklists, and failure-injection playbooks
   - Security baseline checklist and audit artifacts

DELIVERABLE STRUCTURE (Weeks 33–44)
- Weekly cadence: Mon (Theory 2h), Wed (Lab 2h), Fri (Project 3h), Sun (Assessment 2h)
- For each week:
  1. Outcomes focused on reliability/security/consistency guarantees
  2. Primary + alternatives; free option; exact modules
  3. Lab with fault injection and verification steps
  4. Project milestone with acceptance criteria (e.g., RPO/RTO targets met)
  5. Three self-check questions + rubrics
  6. One failure scenario and step-by-step recovery plan

QUALITY CRITERIA
- 2023–2024 validated resources or justified classics; difficulty labels; ±15% estimates
- Free vs. paid; fallbacks; must-have vs. nice-to-have skills

SPECIAL CONSIDERATIONS (Phase 4)
- Emphasize verifiable SLAs: RPO/RTO, p95/p99 latencies, data loss budgets
- Include multi-region trade-offs (latency vs. consistency) and security hardening
- Capture ops artifacts: runbooks, dashboards, alert rules, recovery drills

ULTRA-THINK PROCESS
1. Define reliability goals and compliance constraints first; align labs/projects
2. Plan failure modes; design experiments to observe and recover
3. Cross-validate consensus/txn semantics with multiple sources and tests
4. Synthesize HA/DR checklists and streaming patterns with anti-patterns
5. Risk review: split-brain, replay duplication, schema evolution
6. Verification: run drills and record evidence (logs, metrics, screenshots)

OUTPUT FORMAT
1) Executive Summary for Phase 4 (≤400 words)
2) Week-by-week curriculum (Weeks 33–44)
3) Resource library with links and time/cost
4) Lab guides (fault injection, recovery validation)
5) Project briefs (acceptance criteria + SLOs/SLAs)
6) Assessment framework (skills matrix + evidence)
```

