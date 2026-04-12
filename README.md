# Awesome Data Engineering Interview [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of the best resources for preparing for data engineering interviews. Updated for 2026.

If you have ever searched "data engineering interview prep", you know the problem: ten browser tabs open, every link either too shallow or too generic. This list is the antidote. Every entry is hand picked, current, and includes a one line note on what it is actually good for.

## Contents

- [Question banks and practice problems](#question-banks-and-practice-problems)
  - [SQL](#sql)
  - [Python](#python)
  - [Schema design](#schema-design)
  - [Pipeline architecture](#pipeline-architecture)
- [Lessons and tutorials](#lessons-and-tutorials)
  - [SQL fundamentals](#sql-fundamentals)
  - [Python for data engineers](#python-for-data-engineers)
  - [Data modeling](#data-modeling)
  - [Distributed systems](#distributed-systems)
- [System design for data engineers](#system-design-for-data-engineers)
- [Company specific guides](#company-specific-guides)
- [Behavioral interviews](#behavioral-interviews)
- [Books](#books)
- [Blogs and newsletters](#blogs-and-newsletters)
- [Tools you should know cold](#tools-you-should-know-cold)
- [Roadmaps and study plans](#roadmaps-and-study-plans)
- [Communities](#communities)
- [Contributing](#contributing)

## Question banks and practice problems

### SQL

- **[DataDriven SQL interview questions](https://datadriven.io/sql-interview-questions)**. 850+ DE flavored SQL problems with browser sandboxes, sortable by difficulty and topic. The largest curated DE SQL set on the open web.
- **[StrataScratch](https://www.stratascratch.com)**. Real questions from past company interviews, mostly analyst flavored.
- **[LeetCode database track](https://leetcode.com/problemset/database/)**. The classic. Heavy on tricky joins, light on real DE flavor.
- **[HackerRank SQL](https://www.hackerrank.com/domains/sql)**. Good for warmup. Not enough depth for senior loops.
- **[Datalemur](https://datalemur.com)**. Similar to StrataScratch, well organized by company.
- **[Mode SQL tutorial](https://mode.com/sql-tutorial/)**. Free, well written, ten years old and still relevant.

### Python

- **[DataDriven Python interview questions](https://datadriven.io/python-interview-questions)**. 388 DE flavored Python problems, browser sandbox, focused on data manipulation patterns rather than LeetCode tricks.
- **[Neetcode 150](https://neetcode.io)**. Core algorithm patterns. Some overlap with DE phone screens.
- **[Real Python](https://realpython.com)**. Tutorial site. Great for filling specific gaps.
- **[Pandas exercises](https://github.com/guipsamora/pandas_exercises)**. If your role uses pandas heavily.

### Schema design

- **[DataDriven schema design questions](https://datadriven.io/data-modeling-interview-questions)**. 56 schema design problems, each with a worked solution and ERD.
- **[Vertabelo data modeling examples](https://vertabelo.com/blog/data-modeling-examples/)**. Good for browsing reference schemas across domains.
- **[The Data Warehouse Toolkit](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/books/data-warehouse-dw-toolkit/)**. The book. Still the canonical reference for dimensional modeling.

### Pipeline architecture

- **[DataDriven pipeline architecture questions](https://datadriven.io/data-pipeline-interview-questions)**. 120 end to end pipeline case studies covering batch, streaming, lakehouse, and regulatory scenarios.
- **[System Design Primer](https://github.com/donnemartin/system-design-primer)**. Generic backend system design, not DE focused, but the fundamentals carry over.

## Lessons and tutorials

### SQL fundamentals

- **[Joins, beginner to advanced](https://datadriven.io/learn/joins-beginner)**. Three lesson progression covering inner, left, full, semi, anti, lateral, and inequality joins.
- **[Aggregating, beginner to advanced](https://datadriven.io/learn/aggregating-beginner)**. From `GROUP BY` to grouping sets and rollups.
- **[Window functions, beginner to advanced](https://datadriven.io/learn/window-functions-beginner)**. The single highest leverage SQL topic for DE interviews.
- **[Filtering, beginner to advanced](https://datadriven.io/learn/filtering-beginner)**. Including the surprisingly tricky world of `NULL` and three valued logic.
- **[Mode SQL tutorial](https://mode.com/sql-tutorial/)**. Free external reference, browser based.

### Python for data engineers

- **[Foundations](https://datadriven.io/learn/foundations-beginner)**. Variables, types, control flow, refresher track for rust removal.
- **[Collections](https://datadriven.io/learn/collections-beginner)**. Dicts, lists, sets, tuples, comprehensions.
- **[Complexity](https://datadriven.io/learn/complexity-beginner)**. Big O for people who hate big O.
- **[Real Python tutorials](https://realpython.com/tutorials/data-eng/)**. Solid external supplement.

### Data modeling

- **[Keys and identity](https://datadriven.io/learn/data-modeling-keys)**. Surrogate vs natural keys, composite keys, identity columns.
- **[Relationships](https://datadriven.io/learn/data-modeling-relationships)**. One to one, one to many, many to many, recursive.
- **[Normalization](https://datadriven.io/learn/data-modeling-normalization)**. 1NF through BCNF, with examples that are not contrived.
- **[Dimensional modeling](https://datadriven.io/learn/data-modeling-dimensional)**. Star schemas, snowflake schemas, conformed dimensions.
- **[Slowly changing dimensions](https://datadriven.io/learn/data-modeling-scd)**. Type 0 through Type 6, when to use each.
- **[Event streams](https://datadriven.io/learn/data-modeling-event-streams)**. Modeling immutable event logs and how to derive state.
- **[Nested data](https://datadriven.io/learn/data-modeling-nested-data)**. Structs, arrays, maps, JSON, when to flatten.

### Distributed systems

- **[Designing Data Intensive Applications](https://dataintensive.net)**. The book. Required reading.
- **[The Log: What every software engineer should know about real time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)**. Jay Kreps' essay. Foundational.
- **[Streaming Systems book](http://streamingsystemsbook.com)**. The deepest treatment of streaming semantics in print.

## System design for data engineers

- **[System Design for Data Engineers](https://github.com/system-design-for-data-engineers/system-design-for-data-engineers)**. Companion repo to this list, focused on long form DE specific case studies.
- **[Data engineering system design framework](https://datadriven.io/data-engineering-system-design)**. The eight beat framework that turns vague design questions into structured answers.
- **[High Scalability](http://highscalability.com)**. Old school real architecture writeups from production systems.

## Company specific guides

DE loops differ by company. Each guide below covers loop structure, leveling rubric, question style, and a curated practice set.

| Company | Guide | What is distinctive |
|---|---|---|
| Netflix | <https://datadriven.io/companies/netflix/interview> | Heavy on streaming and OLAP at scale |
| Uber | <https://datadriven.io/companies/uber/interview> | Real time, geo partitioning, exactly once |
| Amazon | <https://datadriven.io/companies/amazon/interview> | Leadership principles, bar raiser |
| Google | <https://datadriven.io/companies/google/interview> | Algorithmic depth, BigQuery patterns |
| Meta | <https://datadriven.io/companies/meta/interview> | Product sense plus DE, Presto heavy |

The full company index is at <https://datadriven.io/companies>.

## Behavioral interviews

- **[The 50 most common DE behavioral questions](https://datadriven.io/behavioral-interview-questions)**. With model answers and the underlying competencies they are testing.
- **[Amazon leadership principles guide](https://www.amazon.jobs/content/en/our-workplace/leadership-principles)**. The official source. Internalize these if you are interviewing at Amazon.
- **[The STAR method](https://en.wikipedia.org/wiki/Situation,_task,_action,_result)**. The format for every behavioral answer.

## Books

- **Designing Data Intensive Applications**, Martin Kleppmann. Required.
- **The Data Warehouse Toolkit**, Ralph Kimball. The dimensional modeling bible.
- **Fundamentals of Data Engineering**, Joe Reis and Matt Housley. Best modern survey.
- **Streaming Systems**, Tyler Akidau et al. Deepest treatment of streaming semantics.
- **The Log Structured Merge Tree paper**, Patrick O'Neil. Worth reading once.

## Blogs and newsletters

- **Netflix Tech Blog**. Best in class writing on streaming at scale.
- **Uber Engineering**. Pipeline scale and exactly once semantics.
- **Airbnb Engineering**. Strong on data quality and Airflow.
- **Stripe Engineering**. Strong on data correctness and idempotency.
- **DataDriven blog**: <https://datadriven.io/blog>. New technical writeups weekly.
- **Data Engineering Weekly**. Curated newsletter, free.
- **Ben Stancil's Substack**. Opinionated, often correct.

## Tools you should know cold

If you cannot answer "why and when would I use X" for each of these, fill the gap before your loop.

| Category | Tool | Why it matters in interviews |
|---|---|---|
| Orchestration | Airflow | The default expectation |
| Orchestration | Dagster, Prefect | Modern alternatives, often discussed in tradeoff questions |
| Transformation | dbt | Standard for warehouse modeling |
| Streaming | Kafka | Standard for event ingestion |
| Streaming | Flink, Spark Structured Streaming | Common stream processors |
| Warehouse | Snowflake, BigQuery, Redshift | Pick the one your target company uses |
| Lakehouse | Databricks, Iceberg, Delta, Hudi | Hot topic in 2026 loops |
| Format | Parquet, ORC, Avro | Know the tradeoffs |
| Catalog | Unity Catalog, Glue, Polaris | Increasingly asked |

A longer tooling map is at <https://datadriven.io/data-engineering-tools>.

## Roadmaps and study plans

- **[DE career roadmap](https://datadriven.io/data-engineer-roadmap)**. From analyst to staff DE.
- **[12 week study plan](https://datadriven.io/data-engineering-study-plan)**. Daily checklist.
- **[Resume guide](https://datadriven.io/data-engineer-resume)**. With examples for each level.
- **[Salary guide](https://datadriven.io/data-engineering-salary)**. By company, level, and region.
- **[How to become a data engineer](https://datadriven.io/how-to-become-a-data-engineer)**. For career switchers.

## Communities

- **r/dataengineering**. The largest DE community on the open web.
- **DBT Community Slack**. Largest DE Slack.
- **Data Engineering Discord**. Smaller, more technical.
- **LinkedIn**. Where most jobs are actually posted.

## Contributing

Contributions welcome. Please open an issue or PR following the [awesome list manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md).

Rules:

1. Each entry must include a one line note on what it is actually good for. No "great resource" filler.
2. Free resources preferred. Paid resources allowed only if they are the best in category.
3. No affiliate links.
4. No dead links.

Run `awesome-lint` on your changes before opening a PR.

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Public domain. Copy, fork, and republish freely.
