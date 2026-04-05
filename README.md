# Awesome Data Engineering 2026 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of 150+ data engineering tools, frameworks, platforms, and resources for 2026. From ETL pipelines to real-time streaming, data quality to orchestration.

**⭐ Star this repo** to keep up with the fast-moving data engineering ecosystem!

---

## Contents

- [ETL & Data Integration](#etl--data-integration)
- [Workflow Orchestration](#workflow-orchestration)
- [Stream Processing](#stream-processing)
- [Batch Processing](#batch-processing)
- [Data Warehouses & Lakes](#data-warehouses--lakes)
- [Data Quality & Testing](#data-quality--testing)
- [Data Transformation](#data-transformation)
- [Data Catalogs & Discovery](#data-catalogs--discovery)
- [Data Observability](#data-observability)
- [File Formats](#file-formats)
- [Messaging & Event Streaming](#messaging--event-streaming)
- [Databases](#databases)
- [Web Scraping & Data Collection](#web-scraping--data-collection)
- [Data Governance & Privacy](#data-governance--privacy)
- [MLOps & Feature Stores](#mlops--feature-stores)
- [BI & Visualization](#bi--visualization)
- [Infrastructure & DevOps](#infrastructure--devops)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

---

## ETL & Data Integration

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Airbyte](https://github.com/airbytehq/airbyte) | Open-source data integration platform with 300+ connectors | Java/Python | 16k+ |
| [Singer](https://github.com/singer-io/getting-started) | Open-source standard for writing scripts that move data | Python | 1k+ |
| [Meltano](https://github.com/meltano/meltano) | DataOps OS — ELT+ built on Singer | Python | 2k+ |
| [Fivetran](https://fivetran.com) | Automated data integration (commercial) | SaaS | — |
| [Stitch](https://www.stitchdata.com) | Simple ETL service built on Singer | SaaS | — |
| [dlt](https://github.com/dlt-hub/dlt) | Data load tool — Python library for data pipelines | Python | 3k+ |
| [Sling](https://github.com/slingdata-io/sling-cli) | CLI tool for data transfers between databases and storage | Go | 500+ |
| [CloudQuery](https://github.com/cloudquery/cloudquery) | High-performance ELT framework | Go | 6k+ |
| [Ingestr](https://github.com/bruin-data/ingestr) | CLI tool to copy data between any source and destination | Python | 2k+ |
| [PipelineWise](https://github.com/transferwise/pipelinewise) | Data pipeline framework by Wise | Python | 1k+ |

## Workflow Orchestration

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Apache Airflow](https://github.com/apache/airflow) | The standard for programmatic workflow authoring | Python | 37k+ |
| [Dagster](https://github.com/dagster-io/dagster) | Cloud-native orchestrator for data assets | Python | 12k+ |
| [Prefect](https://github.com/PrefectHQ/prefect) | Modern workflow orchestration | Python | 17k+ |
| [Mage](https://github.com/mage-ai/mage-ai) | Open-source data pipeline tool for transforming data | Python | 8k+ |
| [Temporal](https://github.com/temporalio/temporal) | Durable execution for microservices | Go | 12k+ |
| [Kestra](https://github.com/kestra-io/kestra) | Declarative, language-agnostic orchestration | Java | 10k+ |
| [Argo Workflows](https://github.com/argoproj/argo-workflows) | Kubernetes-native workflow engine | Go | 15k+ |
| [Luigi](https://github.com/spotify/luigi) | Python module for pipeline building (Spotify) | Python | 18k+ |
| [n8n](https://github.com/n8n-io/n8n) | Workflow automation with 400+ integrations | TypeScript | 50k+ |
| [Windmill](https://github.com/windmill-labs/windmill) | Developer platform for scripts, flows, and apps | Rust/TS | 10k+ |

## Stream Processing

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Apache Kafka](https://github.com/apache/kafka) | Distributed event streaming platform | Java | 29k+ |
| [Apache Flink](https://github.com/apache/flink) | Stream and batch processing framework | Java | 24k+ |
| [Apache Spark Streaming](https://spark.apache.org/streaming/) | Micro-batch stream processing | Scala | — |
| [Redpanda](https://github.com/redpanda-data/redpanda) | Kafka-compatible streaming without ZooKeeper | C++ | 10k+ |
| [RisingWave](https://github.com/risingwavelabs/risingwave) | SQL-based stream processing database | Rust | 7k+ |
| [Materialize](https://github.com/MaterializeInc/materialize) | Streaming SQL database | Rust | 6k+ |
| [Bytewax](https://github.com/bytewax/bytewax) | Python stream processing framework | Python/Rust | 2k+ |
| [Quix Streams](https://github.com/quixio/quix-streams) | Python library for Kafka stream processing | Python | 1k+ |
| [Benthos/Redpanda Connect](https://github.com/redpanda-data/connect) | Stream processor with 200+ connectors | Go | 8k+ |
| [Memphis](https://github.com/memphisdev/memphis) | Real-time data processing platform | Go | 3k+ |

## Batch Processing

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Apache Spark](https://github.com/apache/spark) | Unified analytics engine for big data | Scala | 40k+ |
| [DuckDB](https://github.com/duckdb/duckdb) | In-process analytical database (blazing fast) | C++ | 25k+ |
| [Polars](https://github.com/pola-rs/polars) | Lightning-fast DataFrame library | Rust | 31k+ |
| [dask](https://github.com/dask/dask) | Parallel computing with Python | Python | 13k+ |
| [Vaex](https://github.com/vaexio/vaex) | Out-of-core DataFrames for large datasets | Python | 8k+ |
| [Ray](https://github.com/ray-project/ray) | Unified framework for scaling AI and Python | Python | 35k+ |
| [Modin](https://github.com/modin-project/modin) | Speed up Pandas by changing one line of code | Python | 10k+ |
| [Ibis](https://github.com/ibis-project/ibis) | Portable Python dataframe library | Python | 5k+ |
| [Apache Beam](https://github.com/apache/beam) | Unified batch and streaming model | Java/Python | 8k+ |
| [Fugue](https://github.com/fugue-project/fugue) | Unified interface for Spark, Dask, Ray, DuckDB | Python | 2k+ |

## Data Warehouses & Lakes

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Apache Iceberg](https://github.com/apache/iceberg) | Open table format for huge analytic datasets | Java | 7k+ |
| [Delta Lake](https://github.com/delta-io/delta) | Open-source storage framework by Databricks | Scala | 7k+ |
| [Apache Hudi](https://github.com/apache/hudi) | Ingests and manages storage of large datasets | Java | 5k+ |
| [ClickHouse](https://github.com/ClickHouse/ClickHouse) | Real-time OLAP database | C++ | 38k+ |
| [Apache Doris](https://github.com/apache/doris) | High-performance real-time analytical database | C++ | 13k+ |
| [StarRocks](https://github.com/StarRocks/starrocks) | Sub-second OLAP database | C++ | 9k+ |
| [Snowflake](https://snowflake.com) | Cloud data platform (commercial) | SaaS | — |
| [BigQuery](https://cloud.google.com/bigquery) | Serverless data warehouse (Google Cloud) | SaaS | — |
| [Redshift](https://aws.amazon.com/redshift/) | Cloud data warehouse (AWS) | SaaS | — |
| [LakeFS](https://github.com/treeverse/lakeFS) | Git-like version control for data lakes | Go | 4k+ |

## Data Quality & Testing

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Great Expectations](https://github.com/great-expectations/great_expectations) | Data validation and documentation | Python | 10k+ |
| [Soda](https://github.com/sodadata/soda-core) | Data quality checks with SodaCL | Python | 2k+ |
| [dbt tests](https://docs.getdbt.com/docs/build/data-tests) | Built-in data testing in dbt | SQL | — |
| [Pandera](https://github.com/unionai-oss/pandera) | Data validation for DataFrames | Python | 3k+ |
| [Deequ](https://github.com/awslabs/deequ) | Data quality validation on Spark (AWS) | Scala | 3k+ |
| [Datafold](https://datafold.com) | Automated data quality platform | SaaS | — |
| [Elementary](https://github.com/elementary-data/elementary) | Data observability for dbt | Python | 2k+ |
| [MobyDQ](https://github.com/ubisoft/mobydq) | Data quality monitoring tool | Python | 200+ |
| [Cerberus](https://github.com/pyeve/cerberus) | Lightweight data validation library | Python | 3k+ |
| [Pydantic](https://github.com/pydantic/pydantic) | Data validation using Python type hints | Python | 22k+ |

## Data Transformation

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [dbt](https://github.com/dbt-labs/dbt-core) | Transform data in your warehouse with SQL | Python | 10k+ |
| [SQLMesh](https://github.com/TobikoData/sqlmesh) | Next-gen data transformation framework | Python | 2k+ |
| [SQLFluff](https://github.com/sqlfluff/sqlfluff) | SQL linter and auto-formatter | Python | 8k+ |
| [Apache Hive](https://github.com/apache/hive) | Data warehouse software for reading/writing big data | Java | 5k+ |
| [Malloy](https://github.com/malloydata/malloy) | Experimental language for data (Google) | TypeScript | 2k+ |
| [Jinja SQL](https://github.com/hashedin/jinjasql) | Template SQL queries with Jinja | Python | 800+ |
| [SDF](https://github.com/sdf-labs/sdf-cli) | SQL development framework with type checking | Rust | 500+ |
| [Bruin](https://github.com/bruin-data/bruin) | Multi-language data pipelines (SQL + Python) | Go | 1k+ |
| [Presto](https://github.com/prestodb/presto) | Distributed SQL query engine | Java | 16k+ |
| [Trino](https://github.com/trinodb/trino) | Fast distributed SQL (formerly PrestoSQL) | Java | 10k+ |

## Data Catalogs & Discovery

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [DataHub](https://github.com/datahub-project/datahub) | Metadata platform for the modern data stack | Java/Python | 10k+ |
| [Amundsen](https://github.com/amundsen-io/amundsen) | Data discovery and metadata engine (Lyft) | Python | 4k+ |
| [Apache Atlas](https://github.com/apache/atlas) | Data governance and metadata framework | Java | 2k+ |
| [OpenMetadata](https://github.com/open-metadata/OpenMetadata) | Unified metadata platform | Java | 5k+ |
| [Marquez](https://github.com/MarquezProject/marquez) | Open-source data lineage tracking | Java | 2k+ |
| [Stemma](https://stemma.ai) | Data catalog built on Amundsen | SaaS | — |
| [Select Star](https://selectstar.com) | Automated data discovery and lineage | SaaS | — |
| [Castor](https://castordoc.com) | AI-powered data catalog | SaaS | — |

## Data Observability

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Monte Carlo](https://montecarlodata.com) | Data reliability platform | SaaS | — |
| [Elementary](https://github.com/elementary-data/elementary) | Open-source data observability for dbt | Python | 2k+ |
| [Soda](https://github.com/sodadata/soda-core) | Data quality monitoring | Python | 2k+ |
| [Re:Data](https://github.com/re-data/re-data) | Data quality framework for dbt | Python | 900+ |
| [Bigeye](https://bigeye.com) | Data observability platform | SaaS | — |
| [Databand](https://databand.ai) | Pipeline observability (IBM) | SaaS | — |
| [Metaplane](https://metaplane.dev) | Data observability for modern data stack | SaaS | — |
| [Kensu](https://kensu.io) | Data observability in real-time | SaaS | — |

## File Formats

| Format | Description | Best For |
|--------|-------------|----------|
| [Apache Parquet](https://github.com/apache/parquet-format) | Columnar storage for Hadoop | Analytics, data warehousing |
| [Apache Avro](https://github.com/apache/avro) | Row-based serialization format | Data serialization, Kafka |
| [Apache ORC](https://github.com/apache/orc) | Optimized Row Columnar format | Hive, Spark workloads |
| [Apache Arrow](https://github.com/apache/arrow) | In-memory columnar format | Cross-language data sharing |
| [Protocol Buffers](https://github.com/protocolbuffers/protobuf) | Language-neutral serialization | gRPC, microservices |
| [JSON Lines](https://jsonlines.org) | Newline-delimited JSON | Log files, streaming data |
| [CSV/TSV](https://tools.ietf.org/html/rfc4180) | Comma/tab-separated values | Simple data exchange |
| [Lance](https://github.com/lancedb/lance) | Modern columnar format for ML | ML datasets, vector data |

## Messaging & Event Streaming

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Apache Kafka](https://github.com/apache/kafka) | Distributed event streaming | Java | 29k+ |
| [RabbitMQ](https://github.com/rabbitmq/rabbitmq-server) | Open-source message broker | Erlang | 13k+ |
| [NATS](https://github.com/nats-io/nats-server) | Cloud-native messaging system | Go | 16k+ |
| [Apache Pulsar](https://github.com/apache/pulsar) | Cloud-native pub-sub messaging | Java | 14k+ |
| [Redis Streams](https://redis.io/docs/data-types/streams/) | Append-only log data structure in Redis | C | — |
| [ZeroMQ](https://github.com/zeromq/libzmq) | High-performance messaging library | C++ | 10k+ |
| [Amazon SQS](https://aws.amazon.com/sqs/) | Managed message queue | SaaS | — |
| [Google Pub/Sub](https://cloud.google.com/pubsub) | Real-time messaging | SaaS | — |

## Databases

### Analytical (OLAP)
| Tool | Description | Stars |
|------|-------------|-------|
| [ClickHouse](https://github.com/ClickHouse/ClickHouse) | Real-time analytics | 38k+ |
| [DuckDB](https://github.com/duckdb/duckdb) | In-process analytics | 25k+ |
| [Apache Druid](https://github.com/apache/druid) | Real-time analytics database | 13k+ |
| [Apache Pinot](https://github.com/apache/pinot) | Real-time OLAP (LinkedIn) | 5k+ |
| [QuestDB](https://github.com/questdb/questdb) | Time-series SQL database | 15k+ |
| [TimescaleDB](https://github.com/timescale/timescaledb) | Time-series on PostgreSQL | 18k+ |

### Vector Databases
| Tool | Description | Stars |
|------|-------------|-------|
| [Milvus](https://github.com/milvus-io/milvus) | Cloud-native vector database | 32k+ |
| [Qdrant](https://github.com/qdrant/qdrant) | Vector similarity search engine | 22k+ |
| [Weaviate](https://github.com/weaviate/weaviate) | AI-native vector database | 12k+ |
| [Chroma](https://github.com/chroma-core/chroma) | AI-native embedding database | 16k+ |
| [LanceDB](https://github.com/lancedb/lancedb) | Serverless vector database | 5k+ |
| [Pinecone](https://pinecone.io) | Managed vector database | SaaS |

## Web Scraping & Data Collection

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Scrapy](https://github.com/scrapy/scrapy) | Web crawling framework | Python | 53k+ |
| [Playwright](https://github.com/microsoft/playwright) | Browser automation | TypeScript | 68k+ |
| [Puppeteer](https://github.com/puppeteer/puppeteer) | Chrome automation | TypeScript | 89k+ |
| [Apify SDK](https://github.com/apify/crawlee) | Web scraping and browser automation | TypeScript | 16k+ |
| [Beautiful Soup](https://pypi.org/project/beautifulsoup4/) | HTML/XML parser | Python | — |
| [Selenium](https://github.com/SeleniumHQ/selenium) | Browser automation suite | Java | 31k+ |
| [Crawl4AI](https://github.com/unclecode/crawl4ai) | AI-ready web crawler | Python | 30k+ |
| [Firecrawl](https://github.com/mendableai/firecrawl) | Turn websites into LLM-ready data | TypeScript | 25k+ |

> 🔗 See also: [Awesome Web Scraping 2026](https://github.com/spinov001-art/awesome-web-scraping-2026) — our comprehensive scraping tools list

## Data Governance & Privacy

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Apache Ranger](https://github.com/apache/ranger) | Security framework for Hadoop | Java | 1k+ |
| [Open Policy Agent](https://github.com/open-policy-agent/opa) | Policy engine for cloud-native | Go | 10k+ |
| [Presidio](https://github.com/microsoft/presidio) | Data protection and PII anonymization | Python | 3k+ |
| [Piiano Vault](https://piiano.com) | Data privacy vault | SaaS | — |
| [Privacera](https://privacera.com) | Unified data governance | SaaS | — |
| [Collibra](https://collibra.com) | Data intelligence platform | SaaS | — |
| [Immuta](https://immuta.com) | Data security platform | SaaS | — |
| [DataGrail](https://datagrail.io) | Privacy management platform | SaaS | — |

## MLOps & Feature Stores

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [MLflow](https://github.com/mlflow/mlflow) | ML lifecycle management | Python | 19k+ |
| [Feast](https://github.com/feast-dev/feast) | Open-source feature store | Python | 6k+ |
| [Kubeflow](https://github.com/kubeflow/kubeflow) | ML toolkit for Kubernetes | Go | 14k+ |
| [Metaflow](https://github.com/Netflix/metaflow) | ML infrastructure (Netflix) | Python | 8k+ |
| [Weights & Biases](https://wandb.ai) | ML experiment tracking | SaaS | — |
| [DVC](https://github.com/iterative/dvc) | Data version control for ML | Python | 14k+ |
| [Hopsworks](https://github.com/logicalclocks/hopsworks) | Feature store and ML platform | Java | 1k+ |
| [Tecton](https://tecton.ai) | Enterprise feature platform | SaaS | — |

## BI & Visualization

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Apache Superset](https://github.com/apache/superset) | Modern BI platform | Python | 64k+ |
| [Metabase](https://github.com/metabase/metabase) | Simple analytics for everyone | Clojure | 40k+ |
| [Grafana](https://github.com/grafana/grafana) | Observability and data visualization | Go | 66k+ |
| [Redash](https://github.com/getredash/redash) | Connect and visualize data | Python | 26k+ |
| [Lightdash](https://github.com/lightdash/lightdash) | BI for dbt users | TypeScript | 4k+ |
| [Evidence](https://github.com/evidence-dev/evidence) | BI as code with SQL + Markdown | Svelte | 4k+ |
| [Streamlit](https://github.com/streamlit/streamlit) | Build data apps fast | Python | 36k+ |

## Infrastructure & DevOps

| Tool | Description | Language | Stars |
|------|-------------|----------|-------|
| [Terraform](https://github.com/hashicorp/terraform) | Infrastructure as code | Go | 43k+ |
| [Pulumi](https://github.com/pulumi/pulumi) | IaC with real programming languages | Go | 22k+ |
| [Docker](https://github.com/moby/moby) | Containerization platform | Go | 69k+ |
| [Kubernetes](https://github.com/kubernetes/kubernetes) | Container orchestration | Go | 112k+ |
| [Helm](https://github.com/helm/helm) | Kubernetes package manager | Go | 27k+ |
| [ArgoCD](https://github.com/argoproj/argo-cd) | GitOps for Kubernetes | Go | 18k+ |

## Learning Resources

### Books
- *Designing Data-Intensive Applications* by Martin Kleppmann
- *Fundamentals of Data Engineering* by Joe Reis & Matt Housley
- *The Data Warehouse Toolkit* by Ralph Kimball
- *Data Pipelines Pocket Reference* by James Densmore
- *Data Engineering with Python* by Paul Crickard

### Courses
- [DataTalksClub Data Engineering Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) (FREE, 14k+ stars)
- [Coursera — Data Engineering on GCP](https://www.coursera.org/professional-certificates/gcp-data-engineering)
- [Udemy — Apache Airflow: The Hands-On Guide](https://www.udemy.com/course/the-complete-hands-on-course-to-master-apache-airflow/)

### Communities
- [r/dataengineering](https://reddit.com/r/dataengineering) — 250k+ members
- [Data Engineering Discord](https://discord.gg/dataengineering)
- [dbt Community Slack](https://getdbt.slack.com)
- [Apache Airflow Slack](https://apache-airflow-slack.herokuapp.com)

## Related Awesome Lists

- 🕷️ [Awesome Web Scraping 2026](https://github.com/spinov001-art/awesome-web-scraping-2026) — 250+ web scraping tools
- 🌐 [Awesome Free APIs 2026](https://github.com/spinov001-art/awesome-free-apis-2026) — 150+ free APIs without keys
- 🔒 [Awesome Security Tools 2026](https://github.com/spinov001-art/awesome-security-tools-2026) — 150+ cybersecurity tools
- 🤖 [Awesome MCP Tools 2026](https://github.com/spinov001-art/awesome-mcp-tools-2026) — MCP servers and tools
- 📊 [Awesome AI Tools 2026](https://github.com/spinov001-art/awesome-ai-tools-2026) — AI/ML tools collection
- 💻 [Awesome Dev Tools 2026](https://github.com/spinov001-art/awesome-dev-tools-2026) — Developer tools
- 🐍 [Awesome Python Tools 2026](https://github.com/spinov001-art/awesome-python-tools-2026) — Python ecosystem
- ☁️ [Awesome Cloud Tools 2026](https://github.com/spinov001-art/awesome-cloud-tools-2026) — Cloud-native tools
- 🏠 [Awesome Self-Hosted 2026](https://github.com/spinov001-art/awesome-self-hosted-2026) — Self-hosted alternatives

---

## Contributing

Found a missing tool? Open an issue or submit a PR!

## Author

**Aleksej Spinov** — Data Engineer & Technical Writer
- 🔗 [GitHub](https://github.com/spinov001-art) (285+ repos)
- 📝 [Dev.to](https://dev.to/spinov001) (480+ articles)
- 💼 Available for technical writing & consulting: Spinov001@gmail.com

---

*Last updated: March 2026*


---

## Need Custom Developer Tools or Data Solutions?

I build **production-ready scrapers, APIs, and automation tools** for businesses. 78+ tools deployed on Apify, 270+ open-source repos.

📧 **[spinov001@gmail.com](mailto:spinov001@gmail.com)** — describe your data challenge, get a free estimate within 2 hours.

🔧 **[Browse 78+ ready-made scrapers on Apify →](https://apify.com/knotless_cadence)** — Reddit, Google, Amazon, HN and more. Deploy in 1 click.
