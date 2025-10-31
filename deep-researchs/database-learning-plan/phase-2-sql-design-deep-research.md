# Phase 2: SQL Expertise & Design Patterns — Deep Research Prompt

```
ROLE
You are a world-class database educator and performance engineer. For Phase 2 (Weeks 9–20), architect a curriculum that drives mastery of advanced SQL, database design patterns, and performance engineering for production systems.

PHASE SCOPE
- Weeks: 9–20 (120–180 hours)
- Topics: 2.1 Advanced SQL (CTEs, recursion, windows, plans); 2.2 Database Design Excellence (dimensional modeling, EAV, temporal, multi-tenancy); 2.3 Performance Engineering (indexing, partitioning, sharding, read/write trade-offs)

CRITICAL CONTEXT
- Learner: Mid-level engineer advancing toward senior/staff in 12 months
- Phase Focus: Production-grade query craftsmanship, scalable designs, measurable performance wins
- Time: ~10–15 hours/week; Approach: Theory (30%) + Hands-on (50%) + Projects (20%)
- Budget: Up to $500/month

RESEARCH REQUIREMENTS
1) Learning Resources (Phase 2 topics only)
   - Per subtopic: 1 primary resource (4.5+), 2 alternatives, 1 free option; include URL, price, edition, time
   - Prefer resources with real execution plan analysis and lab datasets
2) Real-World Project Sources
   - Codebases illustrating advanced SQL patterns (analytic reporting, recursive hierarchies)
   - Case studies of dimensional models at scale; multi-tenant architectures with partitioning/sharding
   - Incident reports tied to missing indexes, hot partitions, or plan regressions
3) Hands-on Environments
   - Docker Compose: Postgres/MySQL with sample OLTP + OLAP datasets (1GB/10GB/100GB)
   - Tooling: EXPLAIN ANALYZE, pg_stat_statements, auto_explain; query profiling scripts
   - Benchmarks comparing index types, partitioning strategies, and shard keys
4) Expert Validation
   - Curate 6–10 authoritative references (Markus Winand, Kimball, vendor perf guides)
   - Summaries with guidance on when to use/not use specific patterns (e.g., EAV, temporal)
5) Career Optimization
   - 15 senior-level SQL/perf design questions with graded answer outlines
   - Portfolio scaffolds: 100-query pattern library, index recommender prototype, warehouse reporting pack
6) Learning Acceleration
   - Spaced repetition coverage for window functions, execution plan cues, dimensional modeling heuristics
   - Fast feedback: CI for query perf regressions, acceptance thresholds

DELIVERABLE STRUCTURE (Weeks 9–20)
- Weekly cadence: Mon (Theory 2h), Wed (Lab 2h), Fri (Project 3h), Sun (Assessment 2h)
- For each week:
  1. Measurable outcomes (e.g., “Rewrite 10 queries using windows with 2× speedup”)
  2. Primary + alternatives; free option; direct chapter/module references
  3. Lab with reproducible environment and datasets; include plan diffs before/after
  4. Project milestone with acceptance criteria (e.g., design multi-tenant schema with load tests)
  5. Three self-check questions + rubrics
  6. One realistic scenario (e.g., hot partition fix) with mitigation plan

QUALITY CRITERIA
- 2023–2024 validated resources or justified classics; difficulty labels; ±15% time estimates
- Free vs. paid flagged; fallback options ready; must-have vs. nice-to-have skills noted

SPECIAL CONSIDERATIONS (Phase 2)
- Emphasize reasoning from execution plans to design changes
- Contrast OLTP vs. OLAP query patterns and indexing choices
- Include trade-off narratives for EAV, snowflake vs. star, temporal tables

ULTRA-THINK PROCESS
1. Derive performance hypotheses from schema/workload; design experiments
2. Triangulate patterns across sources; document when patterns fail
3. Build repeatable plan-diffing and benchmarking harnesses
4. Synthesize a pattern library with anti-pattern callouts
5. Validate improvements with measurable SLOs (e.g., p95 latency)
6. Risk review: data skew, plan instability, maintenance cost
7. Verification: automate regression checks in the lab

OUTPUT FORMAT
1) Executive Summary for Phase 2 (≤400 words)
2) Week-by-week plan (Weeks 9–20) with outputs and metrics
3) Resource library per subtopic with links and time/cost
4) Lab guides (commands, expected plan changes, KPIs)
5) Project briefs (acceptance criteria + perf SLOs)
6) Assessment framework (skills matrix + evidence)
```

