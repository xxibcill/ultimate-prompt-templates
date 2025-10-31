# Phase 1: Foundation Strengthening — Deep Research Prompt

```
ROLE
You are a world-class database systems researcher and educator. For Phase 1 (Weeks 1–8), design a rigorous, practical curriculum that builds elite fundamentals in relational theory, transactions/ACID, normalization, and CAP/distributed basics.

PHASE SCOPE
- Weeks: 1–8 (80–120 hours)
- Topics: 1.1 Relational Database Theory; 1.2 ACID & Transaction Management; 1.3 Normalization Mastery; 1.4 CAP Theorem & Distributed Basics

CRITICAL CONTEXT
- Learner: Mid-level engineer (3–5 years), knows basic SQL/CRUD
- Goal: Reach senior/staff-level database expertise over 12 months
- Phase Focus: Core fundamentals with production-grade practice
- Time: ~10–15 hours/week; Approach: Theory (30%) + Hands-on (50%) + Projects (20%)
- Budget: Up to $500/month for paid resources

RESEARCH REQUIREMENTS
1) Learning Resources Curation (Phase 1 topics only)
   - For each subtopic (1.1–1.4):
     - 1 primary resource (book/course) with 4.5+ rating (latest edition; if pre-2020, justify as “classic”)
     - 2 alternatives for different learning styles + a free high-quality option
     - Include URLs, prices, edition/year, and time commitments
2) Real-World Project Sources
   - Open-source references to study (specific modules/files) for: relational algebra processors, transaction managers (2PL/MVCC), normalization case studies, and CAP trade-off designs
   - Production incidents/postmortems illustrating isolation anomalies, deadlocks, and partition scenarios
   - Public schemas and design docs emphasizing BCNF/5NF trade-offs
3) Hands-on Environments
   - Docker Compose for Postgres + tooling (psql, pg_stat_statements); seed data at 1GB/10GB sizes
   - Scripts/labs to: implement/visualize isolation levels; reproduce write skew; practice lock diagnostics; simulate partitions
   - Benchmark harness (e.g., pgbench) and monitoring (Grafana/Prometheus) quickstart
4) Expert Validation
   - Curate 5–8 authoritative sources: researchers, talks, and papers (e.g., Gray & Reuter, ANSI isolation critique, Andy Pavlo)
   - Summarize 3 must-watch talks and 3 must-read papers with relevance to 1.1–1.4
5) Career Optimization
   - Map Phase 1 outcomes to common interview topics (isolation, normalization trade-offs, CAP) with 10 sample questions and ideal answer outlines
   - Identify skills gaps between mid-level vs. senior for fundamentals, with a practice checklist
6) Learning Acceleration
   - Spaced-repetition deck outline for: relational algebra ops, normal forms, isolation levels, consistency models
   - Fast-feedback exercises with auto-verifiable acceptance criteria

DELIVERABLE STRUCTURE (Weeks 1–8)
- Weekly cadence: Mon (Theory 2h), Wed (Lab 2h), Fri (Project 3h), Sun (Assessment 2h)
- For each week:
  1. Measurable outcomes (e.g., “Solve 20 relational algebra problems at ≥90% accuracy”)
  2. Primary resource with exact chapters/modules; 2 alternatives; free option noted
  3. Lab with provided environment (Docker, dataset, commands)
  4. Project milestone with acceptance criteria (e.g., implement 2PL deadlock detection test)
  5. Three self-assessment questions + rubrics
  6. One realistic scenario (e.g., diagnose phantom reads) with a step-by-step resolution plan

QUALITY CRITERIA
- Resources updated/validated in 2023–2024 or justified as classics
- Difficulty labels; time estimates ±15% accuracy
- Free vs. paid clearly marked; fallback options included
- Must-have vs. nice-to-have skills flagged per week

SPECIAL CONSIDERATIONS (Phase 1)
- Balance theory rigor (algebra/calculus/normal forms) with practical transaction debugging
- Demonstrate denormalization trade-offs with measured performance impacts
- Show concrete CAP implications via failure-mode simulations

ULTRA-THINK PROCESS
1. Map topics → skills → proofs of mastery; write acceptance tests first
2. Triage sources by authority, recency, and community adoption; justify picks
3. Cross-validate concepts across at least 3 independent sources
4. Design labs that make failure modes observable and repeatable
5. Synthesize into weekly plan; ensure coverage without overload
6. Risk review: list likely blockers (time, environment) + mitigations
7. Verification: dry-run the labs; confirm environment reproducibility

OUTPUT FORMAT
1) Executive Summary for Phase 1 (≤400 words)
2) Week-by-week curriculum (Weeks 1–8) with cadence
3) Resource table (primary/alternatives/free) per subtopic
4) Lab playbooks (commands, datasets, expected outputs)
5) Project briefs with acceptance criteria and rubrics
6) Assessment framework (skills matrix + evidence)
```

