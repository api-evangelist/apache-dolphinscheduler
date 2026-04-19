# Apache DolphinScheduler (apache-dolphinscheduler)
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
