# Apache DolphinScheduler (apache-dolphinscheduler)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache DolphinScheduler is a modern distributed and extensible data orchestration platform governed by the Apache Software Foundation. It provides a DAG-based visual workflow designer, multi-master/multi-worker architecture for horizontal scaling, and a comprehensive REST API for programmatic control. It supports dozens of task types (Shell, Spark, Flink, SQL, Python, HTTP, etc.), multi-cloud deployments, multi-tenancy, backfill, and a Python SDK (PyDolphinScheduler).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, DAG, Data Pipeline, Open Source, Orchestration, Python, Scheduling, Workflow

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache DolphinScheduler REST API
The DolphinScheduler REST API enables programmatic management of projects, workflow definitions (DAGs), workflow instances, task types, schedules, resources, data sources, alerts, tenants, and users. Authentication is via API token. A Swagger UI is available at /dolphinscheduler/swagger-ui/index.html.

**Human URL:** [https://dolphinscheduler.apache.org/en-us/docs/latest/user_doc/guide/open-api.html](https://dolphinscheduler.apache.org/en-us/docs/latest/user_doc/guide/open-api.html)

#### Tags:

 - Alerts, DAG, Data Sources, Projects, REST, Resources, Scheduling, Tasks, Tenants, Workflow

#### Properties

- [Documentation](https://dolphinscheduler.apache.org/en-us/docs/latest/user_doc/guide/open-api.html)
- [GettingStarted](https://dolphinscheduler.apache.org/en-us/docs/latest/user_doc/start/quick-start.html)
- [GitHubRepository](https://github.com/apache/dolphinscheduler)
- [Python SDK (PyDolphinScheduler)](https://pypi.org/project/apache-airflow-providers-apache-dolphinscheduler/)
- [Docker Image](https://hub.docker.com/r/apache/dolphinscheduler-standalone-server)
- [Kubernetes Operator](https://github.com/apache/dolphinscheduler-operator)
- [Schedule](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-schema/apache-dolphinscheduler-schedule-schema.json)
- [Task Definition](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-schema/apache-dolphinscheduler-task-definition-schema.json)
- [Workflow Definition](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-schema/apache-dolphinscheduler-workflow-definition-schema.json)
- [Workflow Instance](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-schema/apache-dolphinscheduler-workflow-instance-schema.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-structure/apache-dolphinscheduler-schedule-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-structure/apache-dolphinscheduler-task-definition-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-structure/apache-dolphinscheduler-workflow-definition-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-structure/apache-dolphinscheduler-workflow-instance-structure.json)
- [JSONLD](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-ld/apache-dolphinscheduler-context.jsonld)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/examples/apache-dolphinscheduler-schedule-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/examples/apache-dolphinscheduler-task-definition-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/examples/apache-dolphinscheduler-workflow-definition-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/examples/apache-dolphinscheduler-workflow-instance-example.json)

## Common Properties

- [Portal](https://dolphinscheduler.apache.org/)
- [Documentation](https://dolphinscheduler.apache.org/en-us/docs/latest/)
- [GettingStarted](https://dolphinscheduler.apache.org/en-us/docs/latest/user_doc/start/quick-start.html)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/dolphinscheduler)
- [PyDolphinScheduler Python SDK](https://github.com/apache/dolphinscheduler-sdk-python)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/vocabulary/apache-dolphinscheduler-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| DAG Visual Workflow Designer | Web-based drag-and-drop interface for building directed acyclic graph (DAG) workflows with real-time execution visualization. |
| REST Open API | Comprehensive REST API for all platform operations including workflow management, scheduling, resource management, and administration. |
| Multi-Master/Worker Architecture | Decentralized architecture with horizontal scaling support, capable of processing tens of millions of tasks per day. |
| Rich Task Types | Built-in task types including Shell, Spark, Flink, SQL, Python, HTTP, DataX, Seatunnel, Jupyter, and custom task plugins. |
| Multi-Tenancy | Supports multiple tenants with isolated resource quotas, permissions, and workflow namespaces. |
| Workflow Versioning | Version control for workflow definitions and instances, enabling rollback and auditing of workflow changes. |
| Data Source Management | Unified data source management supporting MySQL, PostgreSQL, Hive, Trino, Spark, ClickHouse, and many other databases. |
| Python SDK | PyDolphinScheduler allows defining and managing workflows programmatically in Python with code-first workflow authoring. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Pipeline Orchestration | Orchestrate complex ETL/ELT data pipelines with dependencies, retries, and monitoring across distributed systems. |
| Machine Learning Workflows | Schedule and manage ML model training, evaluation, and deployment pipelines with task dependencies. |
| Multi-Cloud Data Workflows | Orchestrate workflows spanning multiple cloud providers and data centers with unified scheduling. |
| SQL and Analytics Scheduling | Schedule recurring SQL queries, reports, and analytics jobs against multiple data sources. |
| DevOps and CI/CD Pipelines | Automate deployment workflows, data quality checks, and operational tasks with DolphinScheduler DAGs. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Spark | Native Spark task type for submitting Spark batch and streaming jobs from DolphinScheduler workflows. |
| Apache Flink | Native Flink task type for submitting Flink stream processing jobs. |
| Apache Hive | Hive data source and task type for SQL-on-Hadoop workloads. |
| Kubernetes | Kubernetes deployment mode and K8s task type for container-native workflow execution. |
| Docker | Official Docker images and Docker Compose configuration for rapid deployment. |
| DataX / SeaTunnel | Native task types for DataX and SeaTunnel data integration frameworks. |
| Apache Airflow | An Airflow provider package allows triggering DolphinScheduler workflows from Airflow DAGs. |

## Artifacts

Machine-readable schemas for Apache DolphinScheduler workflow, task, and scheduling models.

### JSON Schema

- [Schedule](json-schema/apache-dolphinscheduler-schedule-schema.json)
- [Task Definition](json-schema/apache-dolphinscheduler-task-definition-schema.json)
- [Workflow Definition](json-schema/apache-dolphinscheduler-workflow-definition-schema.json)
- [Workflow Instance](json-schema/apache-dolphinscheduler-workflow-instance-schema.json)

### JSON Structure

- [Schedule](json-structure/apache-dolphinscheduler-schedule-structure.json)
- [Task Definition](json-structure/apache-dolphinscheduler-task-definition-structure.json)
- [Workflow Definition](json-structure/apache-dolphinscheduler-workflow-definition-structure.json)
- [Workflow Instance](json-structure/apache-dolphinscheduler-workflow-instance-structure.json)

### JSON-LD

- [Apache Dolphinscheduler](json-ld/apache-dolphinscheduler-context.jsonld)

### Examples

- [Schedule](examples/apache-dolphinscheduler-schedule-example.json)
- [Task Definition](examples/apache-dolphinscheduler-task-definition-example.json)
- [Workflow Definition](examples/apache-dolphinscheduler-workflow-definition-example.json)
- [Workflow Instance](examples/apache-dolphinscheduler-workflow-instance-example.json)

## Vocabulary

- [Apache DolphinScheduler Vocabulary](vocabulary/apache-dolphinscheduler-vocabulary.yaml) — Taxonomy mapping 9 resources, 8 actions, and 3 personas across DolphinScheduler workflow orchestration

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
