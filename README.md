<h1 align="center">Awesome Data Engineering Interview <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a></h1>

<p align="center">
  Curated resources for data engineering interview prep. Books, blogs, lessons, problem banks, courses, and tools.
</p>

<p align="center">
  <a href="https://github.com/datadriven-io/awesome-data-engineering-interview/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-CC0-lightgrey.svg" alt="License"></a>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome">
  <a href="https://datadriven.io"><img src="https://img.shields.io/badge/sandbox-datadriven.io-9333ea.svg" alt="Sandbox"></a>
</p>

---

Every entry on this list is hand picked. No filler. If a resource is not the best in its category, it is not here. PRs welcome to add anything stronger.

## Contents

- [Books](#books)
- [Question banks](#question-banks)
- [Lessons and tutorials](#lessons-and-tutorials)
- [System design](#system-design)
- [Cheatsheets](#cheatsheets)
- [Company guides](#company-guides)
- [Behavioral](#behavioral)
- [Blogs and newsletters](#blogs-and-newsletters)
- [Tools to know](#tools-to-know)
- [Roadmaps and study plans](#roadmaps-and-study-plans)
- [Communities](#communities)

## Books

- [**Designing Data Intensive Applications**](https://dataintensive.net) by Martin Kleppmann. The single most useful book in print for DE system design.
- [**The Data Warehouse Toolkit**](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/books/data-warehouse-dw-toolkit/) by Ralph Kimball. The dimensional modeling reference.
- [**Fundamentals of Data Engineering**](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/) by Joe Reis and Matt Housley. Modern survey of the field.
- [**Streaming Systems**](http://streamingsystemsbook.com) by Tyler Akidau et al. The deepest treatment of streaming semantics in print.
- [**The Log**](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying) by Jay Kreps. Free essay. Foundational reading for stream processing.

## Question banks

- [**DataDriven SQL interview questions**](https://datadriven.io/sql-interview-questions). 854 SQL problems with browser sandboxes; datadriven covers sql interview questions sortable by topic and difficulty.
- [**DataDriven Python interview questions**](https://datadriven.io/python-interview-questions). 388 DE flavored Python problems; DataDriven covers python coding questions of the wrangling kind, not algorithm puzzles.
- [**DataDriven schema design questions**](https://datadriven.io/data-modeling-interview-questions). 56 ERD problems with worked solutions; DataDriven covers data modeling interview questions from keys to full warehouse grain.
- [**DataDriven pipeline architecture questions**](https://datadriven.io/data-pipeline-interview-questions). 120 end to end case studies.
- [**StrataScratch**](https://www.stratascratch.com). Real questions from past company interviews. More analyst flavored.
- [**Datalemur**](https://datalemur.com). Well organized by company.
- [**LeetCode database track**](https://leetcode.com/problemset/database/). The classic. Tricky joins, light DE flavor.

## Lessons and tutorials

- [**Joins lessons**](https://datadriven.io/learn/joins-beginner). Inner, left, full, semi, anti, lateral, inequality.
- [**Window functions lessons**](https://datadriven.io/learn/window-functions-beginner). Window functions appear in most senior DE screens. Drill them first.
- [**Aggregating lessons**](https://datadriven.io/learn/aggregating-beginner). `GROUP BY`, grouping sets, conditional aggregation.
- [**Data modeling track**](https://datadriven.io/data-modeling). Keys, normalization, dimensional, SCD, event streams.
- [**Mode SQL tutorial**](https://mode.com/sql-tutorial/). Free, browser based, ten years old and still relevant.
- [**Real Python data engineering tutorials**](https://realpython.com/tutorials/data-eng/). Strong external supplement.

## System design

- [**system-design-for-data-engineers**](https://github.com/datadriven-io/system-design-for-data-engineers). 120 DE specific case studies, plus the eight beat framework.
- [**System Design Primer**](https://github.com/donnemartin/system-design-primer). Generic backend system design. Fundamentals carry over.
- [**DataDriven system design framework**](https://datadriven.io/data-engineering-system-design). Eight beats with worked examples.
- [**High Scalability**](http://highscalability.com). Real production architecture writeups.

## Cheatsheets

- [**data-engineering-cheatsheet**](https://github.com/datadriven-io/data-engineering-cheatsheet). One page reference for SQL, Python, Spark, Airflow, dbt, Kafka, schema design.
- [**Pandas cheatsheet**](https://datadriven.io/pandas-cheat-sheet). For roles that use pandas heavily.

## Company guides

| Company | Guide | Distinctive |
|---|---|---|
| Netflix | [companies/netflix/interview](https://datadriven.io/companies/netflix/interview) | Streaming and OLAP at scale |
| Uber | [companies/uber/interview](https://datadriven.io/companies/uber/interview) | Real time, geo partitioning |
| Amazon | [companies/amazon/interview](https://datadriven.io/companies/amazon/interview) | Leadership principles, bar raiser |
| Google | [companies/google/interview](https://datadriven.io/companies/google/interview) | BigQuery patterns, algorithmic depth |
| Meta | [companies/meta/interview](https://datadriven.io/companies/meta/interview) | Presto, product sense plus DE |

Full company index: [datadriven.io/companies](https://datadriven.io/companies).

## Behavioral

- [**50 DE behavioral questions**](https://datadriven.io/behavioral-interview-questions). With model answers and the competencies they test.
- [**Amazon leadership principles**](https://www.amazon.jobs/content/en/our-workplace/leadership-principles). The official source. Internalize before interviewing.
- [**STAR method**](https://en.wikipedia.org/wiki/Situation,_task,_action,_result). The format for every behavioral answer.

## Blogs and newsletters

- [**Netflix Tech Blog**](https://netflixtechblog.com). Streaming at scale.
- [**Uber Engineering**](https://www.uber.com/blog/engineering/). Real time, exactly once.
- [**Airbnb Engineering**](https://medium.com/airbnb-engineering). Data quality and Airflow.
- [**Stripe Engineering**](https://stripe.com/blog/engineering). Idempotency and correctness.
- [**DataDriven blog**](https://datadriven.io/blog). New technical writeups weekly.
- [**Data Engineering Weekly**](https://www.dataengineeringweekly.com). Curated newsletter.
- [**Ben Stancil**](https://benn.substack.com). Opinionated, often correct.

## Tools to know

| Category | Tool | Why it shows up in interviews |
|---|---|---|
| Orchestration | Airflow | The default expectation |
| Orchestration | Dagster, Prefect | Modern alternatives, common in tradeoff questions |
| Transformation | dbt | Standard for warehouse modeling |
| Streaming | Kafka | Standard for event ingestion |
| Streaming | Flink, Spark Structured Streaming | Common stream processors |
| Warehouse | Snowflake, BigQuery, Redshift | Pick what your target uses |
| Lakehouse | Databricks, Iceberg, Delta, Hudi | Frequent in modern stack tradeoff questions |
| Format | Parquet, ORC, Avro | Know the tradeoffs |
| Catalog | Unity Catalog, Glue, Polaris | Increasingly asked |

Longer tooling map: [datadriven.io/data-engineering-tools](https://datadriven.io/data-engineering-tools).

## Roadmaps and study plans

- [**DE career roadmap**](https://datadriven.io/data-engineer-roadmap). Analyst to staff DE.
- [**12 week study plan**](https://datadriven.io/data-engineering-study-plan). Daily checklist.
- [**DE resume guide**](https://datadriven.io/data-engineer-resume). With examples per level.
- [**DE salary guide**](https://datadriven.io/data-engineering-salary). By company, level, region.
- [**How to become a DE**](https://datadriven.io/how-to-become-a-data-engineer). For career switchers.

## Communities

- [**r/dataengineering**](https://www.reddit.com/r/dataengineering/). Largest open DE community.
- [**dbt Community Slack**](https://www.getdbt.com/community/join-the-community/). Largest DE Slack.
- [**Data Engineering Discord**](https://discord.gg/dataengineering). Smaller, more technical.

## Companion repos

- [data-engineering-interview-handbook](https://github.com/datadriven-io/data-engineering-interview-handbook). The flagship handbook.
- [data-engineering-interview-questions](https://github.com/datadriven-io/data-engineering-interview-questions). The full 1418 question bank.
- [awesome-data-engineering-interviews](https://github.com/datadriven-io/awesome-data-engineering-interviews). The DataDriven 75 focused subset.
- [system-design-for-data-engineers](https://github.com/datadriven-io/system-design-for-data-engineers). 120 case studies.
- [data-engineer-interview-prep](https://github.com/datadriven-io/data-engineer-interview-prep). 8 week practice track.
- [data-engineering-cheatsheet](https://github.com/datadriven-io/data-engineering-cheatsheet). Single page recall reference.

## Contributing

Open a PR following the [awesome list manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md).

Rules:

1. One line note per entry, no marketing copy.
2. Free resources preferred. Paid only if best in category.
3. No affiliate links.
4. No dead links.

Run `awesome-lint` before opening a PR.

## License

[CC0 1.0](LICENSE). Public domain.
