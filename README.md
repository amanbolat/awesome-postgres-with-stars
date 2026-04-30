# Awesome Postgres

This repository is a clone of [Awesome Postgres](https://github.com/dhamaniasad/awesome-postgres) but with stars.
All repositories are sorted by star count. Stars are updated every day automatically.

## Table of contents

- [High-Availability](#high-availability)
- [Backups](#backups)
- [GUI](#gui)
- [Distributions](#distributions)
- [CLI](#cli)
- [Server](#server)
- [Security](#security)
- [Monitoring](#monitoring)
- [Extensions](#extensions)
- [Platforms](#platforms)
- [Work Queues](#work-queues)
- [Optimization](#optimization)
- [Utilities](#utilities)
- [Language bindings](#language-bindings)
- [PaaS (PostgreSQL as a Service)](#paas-postgresql-as-a-service)
- [Docker images](#docker-images)
- [Kubernetes](#kubernetes)
- [Tutorials](#tutorials)
- [Blogs](#blogs)
- [Books](#books)
- [Documentation](#documentation)
- [Newsletters](#newsletters)
- [Podcasts](#podcasts)
- [Videos](#videos)
- [Community](#community)
- [Roadmaps](#roadmaps)
- [External lists](#external-lists)

## High-Availability

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 8395 | [Patroni](https://github.com/zalando/patroni) | Template for PostgreSQL HA with ZooKeeper or etcd. | 2026-04-24 |
| 4816 | [Stolon](https://github.com/sorintlab/stolon) | PostgreSQL HA based on Consul or etcd, with Kubernetes integration. | 2023-09-06 |
| 4151 | [autobase](https://github.com/vitabaks/autobase) | Autobase for PostgreSQL® is an open-source DBaaS that automates the deployment and management of highly available PostgreSQL clusters. | 2026-04-29 |
| 1691 | [repmgr](https://github.com/2ndQuadrant/repmgr) | Open-source tool suite to manage replication and failover in a cluster of PostgreSQL servers. | 2025-04-17 |
| 1341 | [pg_auto_failover](https://github.com/citusdata/pg_auto_failover) | Postgres extension and service for automated failover and high-availability. | 2025-11-17 |
| 705 | [Spock](https://github.com/pgEdge/spock) | 100% open-source logical multi-master PostgreSQL replication. | 2026-04-29 |
| 360 | [BDR](https://github.com/2ndQuadrant/bdr) | BiDirectional Replication - a multimaster replication system for PostgreSQL | 2020-02-20 |
| 347 | [PAF](https://github.com/ClusterLabs/PAF) | PostgreSQL Automatic Failover: High-Availibility for Postgres, based on Pacemaker and Corosync. | 2024-06-13 |
| 250 | [SkyTools](https://github.com/pgq/skytools-legacy) | Replication tools, including PgQ, a queuing system, and Londiste, a replication system a bit simpler to manage than Slony. | 2017-06-28 |
| 189 | [pglookout](https://github.com/aiven/pglookout) | Replication monitoring and failover daemon. | 2025-01-13 |
| 105 | [pgrwl](https://github.com/hashmap-kz/pgrwl) | Stream write-ahead logs (WAL) from a PostgreSQL server in real time. A drop-in, container-friendly alternative to pg_receivewal. | 2026-04-30 |
| 67 | [pg-status](https://github.com/krylosov-aa/pg-status) | A microservice that provides HTTP endpoints for instantly retrieving the current master host or a replica that meets various criteria. | 2026-02-15 |
| - | [Slony-I](https://slony.info/) | "Master to multiple slaves" replication system with cascading and failover. | - |

## Backups

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 4051 | [wal-g](https://github.com/wal-g/wal-g) | The successor of WAL-E rewritten in Go. Currently supports cloud object storage services by AWS (S3), Google Cloud (GCS), Azure, as well as OpenStack Swift, MinIO, and file system storages. Supports block-level incremental backups, offloading backup tasks to a standby server, provides parallelization and throttling options. In addition to Postgres, WAL-G can be used for MySQL and MongoDB databases. | 2026-04-30 |
| 3470 | [wal-e](https://github.com/wal-e/wal-e) | (obsolete) - Simple Continuous Archiving for PostgreSQL to S3, Azure, or Swift by Heroku. | 2023-12-20 |
| 2572 | [pgbackweb](https://github.com/eduardolat/pgbackweb) | A Complete Docker-based Postgres backup and maintenance tool with Web UI. | 2025-11-21 |
| 1410 | [pghoard](https://github.com/aiven/pghoard) | Backup and restore tool for cloud object stores (AWS S3, Azure, Google Cloud, OpenStack Swift). | 2026-03-11 |
| 787 | [pg_probackup](https://github.com/postgrespro/pg_probackup) | – A fork of pg_arman, improved by @PostgresPro, supports incremental backups, backups from replica, multithreaded backup and restore, and anonymous backup without archive command. | 2026-03-16 |
| 563 | [pg_back](https://github.com/orgrim/pg_back/) | pg_back is a simple backup script | 2026-04-21 |
| 179 | [OmniPITR](https://github.com/omniti-labs/omnipitr) | Advanced WAL File Management Tools for PostgreSQL. | 2019-06-25 |
| 19 | [pg-backups-to-s3](https://github.com/Saicheg/pg-backups-to-s3) | Docker-first solution on top of pg_dump with support for environment-based configuration for scheduled PostgreSQL backups with optional compression, GPG encryption, webhooks, automatic upload to Amazon S3. | 2025-05-30 |
| 5 | [pgbackup-sidecar](https://github.com/Musab520/pgbackup-sidecar) | pgbackup-sidecar is a lightweight Docker sidecar container designed to automate regular backups of a PostgreSQL database using pg_dump, cron, and bash scripts while also sending output to a webhook. | 2024-11-08 |
| 1 | [postgres-backup-oss](https://github.com/isaced/postgres-backup-oss) | A handy Docker container to periodically backup PostgreSQL to Alibaba Cloud Object Storage Service (OSS) | 2025-05-12 |
| - | [Barman](https://www.pgbarman.org/index.html) | Backup and Recovery Manager for PostgreSQL by 2ndQuadrant. | - |
| - | [Databasus](https://databasus.com) | tool for scheduled PostgreSQL backups via web UI with external storages (local, S3, FTP, Google Drive, etc.), notifications (webhook, Discord, Slack, etc.) and team management. | - |
| - | [pgBackRest](https://pgbackrest.org/) | Reliable PostgreSQL Backup & Restore. | - |
| - | [pitrery](https://dalibo.github.io/pitrery/) | pitrery is a set of Bash scripts to manage Point In Time Recovery (PITR) backups for PostgreSQL. | - |

## GUI

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 28546 | [Redash](https://github.com/getredash/redash) | Connect to any data source, easily visualize and share your data. | 2026-04-01 |
| 21186 | [Teable](https://github.com/teableio/teable) | A Super fast, Real-time, Professional, Developer friendly, No code database. | 2026-04-21 |
| 9340 | [pgweb](https://github.com/sosedoff/pgweb) | Web-based PostgreSQL database browser written in Go. | 2026-04-26 |
| 1622 | [Postbird](https://github.com/Paxa/postbird) | PostgreSQL Client for macOS. | 2025-06-30 |
| 1006 | [PgManage](https://github.com/commandprompt/pgmanage) | A modern multi-platform Postgres-centric database client/administration tool. | 2026-01-14 |
| 845 | [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) | The Premier Web Based Administration Tool for PostgreSQL. | 2023-12-17 |
| 760 | [temBoard](https://github.com/dalibo/temboard) | Web-based PostgreSQL GUI and monitoring. | 2026-03-03 |
| - | [Adminer](https://www.adminer.org/) | Full-featured database management tool written in PHP. | - |
| - | [Beekeeper Studio](https://www.beekeeperstudio.io) | Free and open source SQL client with a modern UI and great Postgres support. Cross platform. | - |
| - | [Bytebase](https://www.bytebase.com) | Database DevSecOps solution for Developer, Security, DBA, and Platform Engineering teams. | - |
| - | [Chartbrew](https://chartbrew.com) | Create live dashboards, charts, and client reports from PostgreSQL data. Features a query tool that works with SQL. | - |
| - | [Count](https://count.co/) | Web-based analytics platform with a notebook interface which connects to PostgreSQL (Commercial Software). | - |
| - | [DataGrip](https://www.jetbrains.com/datagrip/) | IDE with advanced tool sets and good cross-platform experience (Commercial Software). | - |
| - | [DataRow](https://www.datarow.com/) | Cross-platform SQL Client for Amazon Redshift: Simple, Effortless, Extensible. | - |
| - | [Datazenit](https://datazenit.com/) | Web-based PostgreSQL GUI (Commercial Software). | - |
| - | [DBConvert Streams](https://streams.dbconvert.com/) | A cloud-native platform for real-time data migration and CDC replication between PostgreSQL and MySQL databases across various cloud environments. (Commercial Software). | - |
| - | [DBeaver](https://dbeaver.io/) | Universal Database Manager with excellent support for PostgreSQL. | - |
| - | [dbForge Edge](https://www.devart.com/dbforge/edge/) | All-in-one multidatabase solution supporting PostgreSQL, MySQL, MariaDB, SQL Server, Oracle, and a wide range of related cloud services (Commercial Software). | - |
| - | [DbGate](https://dbgate.org) | The Smartest (no)SQL Database Client | - |
| - | [DbVisualizer](http://www.dbvis.com) | Cross-platform database client for developers, DBAs, and analysts (Commercial Software). | - |
| - | [Holistics](https://www.holistics.io/) | Online cross platform database management tool and SQL query reporting GUI with strong PostgreSQL support (Commercial Software). | - |
| - | [JackDB](https://www.jackdb.com/) | Web-based SQL query interface (Commercial Software). | - |
| - | [Luna Modeler](http://www.datensen.com) | Cross-platform desktop data modeling tool (Commercial Software). | - |
| - | [Mathesar](https://mathesar.org/) | Web application providing an intuitive user experience to databases. | - |
| - | [Metabase](https://www.metabase.com/) | Simple dashboards, charts and query tool for PostgreSQL. | - |
| - | [Numeracy](https://numeracy.co/) | Fast SQL editor with charts and dashboards for PostgreSQL (Commercial Software). | - |
| - | [pgAdmin](https://www.pgadmin.org/) | PostgreSQL Administration and Management GUI. | - |
| - | [pgMagic🪄](https://pgmagic.app/?ref=awesomepostgres) | Chat to Postgres in Natural Language (Commercial Software). | - |
| - | [pgModeler](https://pgmodeler.io/) | pgModeler is an open-source PostgreSQL Database Modeler. | - |
| - | [PostgresCompare](https://www.postgrescompare.com) | Cross-platform database comparison and deployment tool (Commercial Software). | - |
| - | [Postico](https://eggerapps.at/postico/) | Modern PostgreSQL Client for macOS (Commercial Software). | - |
| - | [PSequel](http://www.psequel.com/) | Clean and simple interface to perform common PostgreSQL tasks quickly (Commercial Software). | - |
| - | [SQL Tabs](http://www.sqltabs.com/) | Cross Platform Desktop Client for PostgreSQL written in JS. | - |
| - | [SQLPro for Postgres](http://macpostgresclient.com/) | Simple, powerful PostgreSQL manager for macOS (Commercial Software). | - |
| - | [TablePlus](https://tableplus.com/) | Native App which let you edit database and structure. High-end security ensured (Commercial Software). | - |
| - | [Valentina Studio](https://www.valentina-db.com/en/valentina-studio-overview) | Cross-platform database administration tool (Free/Commercial) | - |
| - | [WebDB](https://webdb.app) | – Efficient Database IDE. | - |

## Distributions

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 5061 | [Pigsty](https://github.com/Vonng/pigsty) | Battery-Included Open-Source Distribution for PostgreSQL with ultimate observability & Database-as-Code toolbox for developers. | 2026-03-23 |
| - | [Postgres.app](https://postgresapp.com/) | The Easiest Way to Get Started with PostgreSQL on macOS. | - |

## CLI

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 13136 | [pgcli](https://github.com/dbcli/pgcli) | Postgres CLI with autocompletion and syntax highlighting | 2026-04-27 |
| 8340 | [atlas](https://github.com/ariga/atlas) | Atlas is a tool for managing and migrating database schemas using modern DevOps principles. | 2026-04-14 |
| 3575 | [schemaspy](https://github.com/schemaspy/schemaspy) | SchemaSpy is a JAVA JDBC-compliant tool for generating your database to HTML documentation, including Entity Relationship diagrams | 2026-03-05 |
| 842 | [pg-schema-diff](https://github.com/stripe/pg-schema-diff) | CLI (and Golang library) for diffing Postgres schemas and generating SQL migrations with minimal locking. | 2026-01-07 |
| 600 | [pgsh](https://github.com/sastraxi/pgsh) | Branch your PostgreSQL Database like Git | 2022-03-13 |
| 186 | [psql2csv](https://github.com/fphilipe/psql2csv) | Run a query in psql and output the result as CSV | 2022-02-23 |
| 173 | [sabiql](https://github.com/riii111/sabiql) | A fast, driver-less TUI to browse, query, and edit PostgreSQL databases. | 2026-04-30 |
| 12 | [pgplan](https://github.com/JacobArthurs/pgplan) | compare and analyze PostgreSQL EXPLAIN plans from the CLI | 2026-04-23 |
| 3 | [MigrationPilot](https://github.com/mickelsamuel/migrationpilot) | PostgreSQL migration safety CLI that catches dangerous DDL before production — 80 rules, lock classification, auto-fix, GitHub Action. | 2026-03-07 |
| - | [pdot](https://gitlab.com/dmfay/pdot) | Visualize and explore database structures in your shell, from high-context views of the foreign key graph to trigger cascades, role inheritance and permissions, and many more | - |
| - | [pgschema](https://www.pgschema.com) | Terraform-style declarative schema migration for Postgres | - |
| - | [psql](https://www.postgresql.org/docs/current/static/app-psql.html) | The built-in PostgreSQL CLI client | - |

## Server

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 1213 | [Apache Cloudberry](https://github.com/apache/cloudberry) | And MPP PostgreSQL fork. Open source alternative to Greenplum Database. | 2026-04-29 |
| - | [AgensGraph](https://bitnine.net/) | Powerful graph database based on the PostgreSQL. | - |
| - | [FerretDB](https://www.ferretdb.io) | A truly Open Source MongoDB alternative on top of PostgreSQL. | - |
| - | [Postgres-XL](https://www.postgres-xl.org/) | Scalable Open Source PostgreSQL-based Database Cluster. | - |
| - | [YugabyteDB](https://yugabyte.com/) | Open Source Distributed SQL using  a fork of PostgreSQL on top of distributed storage and transaction | - |

## Security

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 1473 | [Acra](https://github.com/cossacklabs/acra) | SQL database security suite: proxy for data protection with transparent "on the fly" data encryption, SQL firewall (SQL injections prevention), intrusion detection system. | 2025-12-05 |

## Monitoring

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 7588 | [coroot](https://github.com/coroot/coroot) | Coroot is an open-source APM & Observability tool, a DataDog and NewRelic alternative. Powered by eBPF for rapid insights into system performance. | 2026-04-30 |
| 3503 | [postgres_exporter](https://github.com/wrouesnel/postgres_exporter) | Prometheus exporter for PostgreSQL server metrics. | 2026-04-23 |
| 2075 | [dexter](https://github.com/ankane/dexter) | The automatic indexer for Postgres. Detects slow queries and creates indexes if configured to do so. | 2025-12-26 |
| 1844 | [pgwatch2](https://github.com/cybertec-postgresql/pgwatch2) | Flexible and easy to get started PostgreSQL metrics monitor focusing on Grafana dashboards. | 2024-12-17 |
| 1076 | [Pome](https://github.com/rach/pome) | Pome stands for PostgreSQL Metrics. Pome is a PostgreSQL Metrics Dashboard to keep track of the health of your database. | 2016-05-25 |
| 1013 | [PMM](https://github.com/percona/pmm) | Percona Monitoring and Management (PMM) is a Free and Open Source platform for monitoring and managing PostgreSQL, MySQL, and MongoDB. | 2026-04-30 |
| 598 | [Check_postgres](https://github.com/bucardo/check_postgres) | Nagios check_postgres plugin for checking status of PostgreSQL databases. | 2025-01-02 |
| 505 | [pg_view](https://github.com/zalando/pg_view) | Open-source command-line tool that shows global system stats, per-partition information, memory stats and other information. | 2020-10-02 |
| 345 | [pg_exporter](https://github.com/Vonng/pg_exporter) | Fully customizable Prometheus exporter for PostgreSQL & Pgbouncer with fine-grained execution control. | 2026-04-14 |
| 220 | [pg_ash](https://github.com/NikolayS/pg_ash) | Active Session History for PostgreSQL. Samples pg_stat_activity once per second via pg_cron, stores encoded snapshots, and provides 32 SQL functions for wait event analysis. Pure SQL, no extensions, works on managed providers (RDS, Cloud SQL, Supabase, etc.). | 2026-04-25 |
| 181 | [check_pgactivity](https://github.com/OPMDG/check_pgactivity) | check_pgactivity is designed to monitor PostgreSQL clusters from Nagios. It offers many options to measure and monitor useful performance metrics. | 2026-04-27 |
| 155 | [libzbxpgsql](https://github.com/cavaliercoder/libzbxpgsql) | Comprehensive PostgreSQL monitoring module for Zabbix. | 2023-11-14 |
| 15 | [Instrumental](https://github.com/Instrumental/instrumentald) | Real-time performance monitoring, including pre-made graphs for ease of setup (Commercial Software) | 2018-09-17 |
| - | [Datadog](https://www.datadoghq.com/product/database-monitoring/) | SaaS monitoring that collects and visualizes metrics, queries, and explain plans, and sends alerts when problems are encountered (Commercial Software). | - |
| - | [myDBA](https://mydba.dev) | PostgreSQL performance monitoring with 75+ automated health checks, cluster-aware index advisor, query analysis, and extension monitoring for TimescaleDB, pgvector, and PostGIS (Commercial Software). | - |
| - | [okmeter.io](https://okmeter.io/pg) | Commercial SaaS agent-based monitoring with a very detailed PostgreSQL plugin. It automatically gathers 100s of stats, displays dashboards on every aspect and sends alerts when something goes wrong (Commercial Software). | - |
| - | [opm.io](http://opm.io) | Open PostgreSQL Monitoring is a free software suite designed to help you manage your PostgreSQL servers. It can gather stats, display dashboards and send warnings when something goes wrong. | - |
| - | [pgbench](https://www.postgresql.org/docs/devel/static/pgbench.html) | Run a benchmark test on PostgreSQL. | - |
| - | [pgmetrics](https://pgmetrics.io/) | pgmetrics is an open-source, zero-dependency, single-binary tool that can collect a lot of information and statistics from a running PostgreSQL server and display it in easy-to-read text format or export it as JSON and CSV for scripting. | - |
| - | [StatsMgr](https://codeberg.org/data-bene/statsmgr) | An open-source PostgreSQL extension designed for efficient and organized advanced statistics management. | - |

## Extensions

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 12455 | [Citus](https://github.com/citusdata/citus) | Scalable PostgreSQL cluster for real-time workloads. | 2026-04-30 |
| 8715 | [ParadeDB](https://github.com/paradedb/paradedb) | Postgres for Search and Analytics | 2026-04-30 |
| 8715 | [pg_search](https://github.com/paradedb/paradedb) | pg_search is a PostgreSQL extension that enables full-text search over SQL tables using the BM25 algorithm, the state-of-the-art ranking function for full-text search. | 2026-04-30 |
| 4735 | [zomboDB](https://github.com/zombodb/zombodb) | Extension that enables efficient full-text searching via the use of indexes backed by Elasticsearch. | 2025-03-01 |
| 4467 | [AGE](https://github.com/apache/age) | Adds fully-functional graph database support including Cypher queries. | 2026-04-30 |
| 3768 | [pg_cron](https://github.com/citusdata/pg_cron) | Run periodic jobs in PostgreSQL. | 2026-04-21 |
| 2685 | [pg_partman](https://github.com/pgpartman/pg_partman) | Partition management extension for PostgreSQL. | 2026-03-05 |
| 1786 | [cstore_fdw](https://github.com/citusdata/cstore_fdw) | Columnar store for analytics with PostgreSQL. | 2021-03-08 |
| 1642 | [HypoPG](https://github.com/HypoPG/hypopg) | HypoPG provides hypothetical/virtual indexes feature. | 2026-04-18 |
| 1392 | [pgRouting](https://github.com/pgRouting/pgrouting) | pgRouting extends the PostGIS/PostgreSQL geospatial database to provide geospatial routing and other network analysis functionality. | 2026-03-06 |
| 1216 | [pglogical](https://github.com/2ndQuadrant/pglogical) | Extension that provides logical streaming replication. | 2026-02-28 |
| 1063 | [pg_shard](https://github.com/citusdata/pg_shard) | Extension to scale out real-time reads and writes. | 2016-08-03 |
| 752 | [plpgsql_check](https://github.com/okbob/plpgsql_check) | Extension that allows to check plpgsql source code. | 2026-04-26 |
| 667 | [pg_squeeze](https://github.com/cybertec-postgresql/pg_squeeze) | An extension for automatic bloat cleanup with minimal locking. | 2025-09-15 |
| 574 | [pg_stat_monitor](https://github.com/percona/pg_stat_monitor) | Query Performance Monitoring tool for PostgreSQL. | 2026-04-29 |
| 406 | [pgMemento](https://github.com/pgMemento/pgMemento) | Provides an audit trail for your data inside a PostgreSQL database using triggers and server-side functions written in PL/pgSQL. | 2026-04-27 |
| 386 | [pgcat](https://github.com/kingluo/pgcat) | Enhanced PostgreSQL logical replication | 2024-09-26 |
| 309 | [pg_paxos](https://github.com/citusdata/pg_paxos/) | Basic implementation of Paxos and Paxos-based table replication for a cluster of PostgreSQL nodes. | 2016-11-14 |
| 33 | [PG_Themis](https://github.com/cossacklabs/pg_themis) | Postgres binding as extension for crypto library Themis, providing various security services on PgSQL's side. | 2016-12-12 |
| 1 | [pg_barcode](https://github.com/btouchard/pg_barcode/) | PostgreSQL SVG QRcode & Datamatrix generator. | 2025-01-09 |
| - | [cyanaudit](https://pgxn.org/dist/cyanaudit/) | Cyan Audit provides in-database logging of all DML activity on a column-by-column basis. | - |
| - | [Extensions listing by joelonsql](https://gist.github.com/joelonsql/e5aa27f8cc9bd22b8999b7de8aee9d47) | 1000+ PostgreSQL extensions. | - |
| - | [OrioleDB](https://www.orioledb.com/) | The cloud-native storage engine for PostgreSQL. OrioleDB is a PostgreSQL extension that combines the advantages of both on-disk and in-memory engines. | - |
| - | [PGAudit](https://www.pgaudit.org/) | The PostgreSQL Audit Extension (or pgaudit) provides detailed session and/or object audit logging via the standard logging facility provided by PostgreSQL. | - |
| - | [PGroonga](https://pgroonga.github.io/) | PGroonga provides a new index access method that uses Groonga allowing super fast full text search feature against all languages. | - |
| - | [PGStrom](https://wiki.postgresql.org/wiki/PGStrom) | Extension to offload CPU intensive workloads to GPU. | - |
| - | [pgTAP](https://pgtap.org/) | Database testing framework for Postgres | - |
| - | [pgxn](https://pgxn.org/) | PostgreSQL Extension Network - central distribution point for many open-source PostgreSQL extensions. | - |
| - | [Pigsty extensions catalogue](https://ext.pigsty.io/list/) | 400+ PostgreSQL extensions. | - |
| - | [PipelineDB](https://www.confluent.io/blog/pipelinedb-team-joins-confluent/) | A PostgreSQL extension that runs SQL queries continuously on streams, incrementally storing results in tables. | - |
| - | [PostGIS](http://postgis.net/) | Spatial and Geographic objects for PostgreSQL. | - |
| - | [PostgresML](https://postgresml.org/) | Machine learning and AI inside your database, including vectors, LLMs, and classic ML. Train, predict and manage the entire lifecycle of machine learning models using only SQL. | - |
| - | [PostgreSQL Anonymizer](https://postgresql-anonymizer.readthedocs.io/en/stable/) | An extension to mask or replace personally identifiable information (PII) or commercially sensitive data from a Postgres database, through PG Security Labels. | - |
| - | [TimescaleDB](https://www.timescale.com/) | Open-source time-series database fully compatible with Postgres, distributed as extension | - |

## Platforms

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 13 | [Atlas4D](https://github.com/crisbez/atlas4d-base) | Open-source 4D spatiotemporal platform combining PostGIS, TimescaleDB, pgvector, and H3 for unified geospatial and time-series intelligence. | 2025-12-25 |

## Work Queues

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 5066 | [river](https://github.com/riverqueue/river) | A high-performance job processing system for Go and Postgres. | 2026-04-27 |
| 4821 | [pgmq](https://github.com/pgmq/pgmq) | A lightweight message queue. Like AWS SQS and RSMQ but on Postgres. | 2026-04-29 |
| 3461 | [pgBoss](https://github.com/timgit/pg-boss) | Queueing jobs in Postgres from Node.js like a boss. | 2026-04-26 |
| 27 | [BeanQueue](https://github.com/LaunchPlatform/bq) | A Python work queue framework based on SKIP LOCKED, LISTEN and NOTIFY | 2026-03-26 |
| - | [@andyrmitchell/pg-queue](https://www.npmjs.com/package/@andyrmitchell/pg-queue) | The 'No Maintenance' Postgres Queue for Node.js | - |
| - | [dbos](https://www.dbos.dev/) | Durable workflows in Typescript and Python | - |
| - | [Graphile Worker](https://worker.graphile.org) | A high performance job queue for PostgreSQL, written in Node.js | - |

## Optimization

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 8852 | [PgHero](https://github.com/ankane/pghero) | PostgreSQL insights made easy. | 2026-04-15 |
| 3462 | [PEV2](https://github.com/dalibo/pev2) | Online Postgres Explain Visualizer. | 2026-04-07 |
| 2702 | [pgtune](https://github.com/le0pard/pgtune) | Online version of PostgreSQL configuration wizard. | 2026-04-23 |
| 1618 | [pg_flame](https://github.com/mgartner/pg_flame) | A flamegraph generator for query plans. | 2020-01-13 |
| 1085 | [pgtune](https://github.com/gregs1104/pgtune/) | PostgreSQL configuration wizard. | 2020-06-28 |
| 500 | [TimescaleDB Tune](https://github.com/timescale/timescaledb-tune) | a program for tuning a TimescaleDB database to perform its best based on the host's resources such as memory and number of CPUs. | 2026-04-30 |
| 491 | [aqo](https://github.com/postgrespro/aqo) | Adaptive query optimization for PostgreSQL. | 2025-03-17 |
| 97 | [pg_web_stats](https://github.com/kirs/pg_web_stats) | Web UI to view pg_stat_statements. | 2018-10-14 |
| 88 | [pgconfig.org](https://github.com/sebastianwebber/pgconfig) | PostgreSQL Online Configuration Tool (also based on pgtune). | 2020-08-20 |
| 29 | [pgassistant](https://github.com/beh74/pgassistant-community) | A PostgreSQL tool for developers to help understand, optimize database with LLM and pgTune integration. | 2026-04-29 |
| - | [EverSQL](https://www.eversql.com/) | Automated query optimization tool, monitoring and analysis tool, indexing recommendation tool. (Commercial Software) | - |
| - | [Metis](https://www.metisdata.io/product/troubleshooting) | Metis provides observability and performance tuning for SQL databases including PostgreSQL. (Commercial Software) | - |
| - | [pgMustard](https://www.pgmustard.com/) | A modern user interface<br>for EXPLAIN, that also provides performance tips (Commercial Software). | - |
| - | [PoWA](https://powa.readthedocs.io/en/latest/) | PostgreSQL Workload Analyzer gathers performance stats and provides real-time charts and graphs to help monitor and tune your PostgreSQL servers. | - |

## Utilities

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 31967 | [Hasura GraphQL Engine](https://github.com/hasura/graphql-engine) | Blazing fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events. | 2026-04-30 |
| 27052 | [PostgREST](https://github.com/PostgREST/postgrest) | Serves a fully RESTful API from any existing PostgreSQL database. | 2026-04-29 |
| 12921 | [PostGraphile](https://github.com/graphile/postgraphile) | Instant GraphQL API or GraphQL schema for your PostgreSQL database | 2026-04-28 |
| 6454 | [pgroll](https://github.com/xataio/pgroll) | Zero-downtime, reversible, schema migrations for Postgres | 2026-02-16 |
| 6405 | [pgloader](https://github.com/dimitri/pgloader) | Loads data into PostgreSQL using the COPY streaming protocol, and does so with separate threads for reading and writing data. | 2025-06-04 |
| 4548 | [pREST](https://github.com/prest/prest) | Serve a RESTful API from any PostgreSQL database (Golang) | 2026-04-30 |
| 4003 | [pgbadger](https://github.com/darold/pgbadger) | Fast PostgreSQL Log Analyzer. | 2026-04-10 |
| 3449 | [pgsync](https://github.com/ankane/pgsync) | Tool to sync PostgreSQL data to your local machine. | 2025-12-26 |
| 3126 | [sqitch](https://github.com/sqitchers/sqitch) | Tool for managing versioned schema deployment | 2026-01-25 |
| 3050 | [migra](https://github.com/djrobstep/migra) | Like diff but for Postgres schemas. | 2025-08-25 |
| 3013 | [pg_activity](https://github.com/dalibo/pg_activity) | top like application for PostgreSQL server activity monitoring. | 2026-01-13 |
| 2520 | [sqlcheck](https://github.com/jarulraj/sqlcheck) | Automatically detects common SQL anti-patterns. Such anti-patterns often slow down queries. Addressing them will, therefore, help accelerate queries. | 2024-02-21 |
| 1601 | [pgCenter](https://github.com/lesovsky/pgcenter) | Provides convenient interface to various statistics, management task, reloading services, viewing log files and canceling or terminating database backends. | 2026-01-06 |
| 1407 | [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) | ERAlchemy generates Entity Relation (ER) diagram from databases. | 2026-04-27 |
| 1350 | [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) | Advanced job scheduler for PostgreSQL. | 2026-04-21 |
| 1345 | [pgfutter](https://github.com/lukasmartinelli/pgfutter) | Import CSV and JSON into PostgreSQL the easy way. | 2019-05-13 |
| 1341 | [yoke](https://github.com/nanopack/yoke) | PostgreSQL high-availability cluster with auto-failover and automated cluster recovery. | 2016-01-07 |
| 1309 | [mysql-postgresql-converter](https://github.com/lanyrd/mysql-postgresql-converter) | Lanyrd's MySQL to PostgreSQL conversion script. | 2016-03-07 |
| 703 | [pgMonitor](https://github.com/CrunchyData/pgmonitor) | Postgres metrics collection and visualization that can be deployed to bare metal, virtual machines, or Kubernetes. | 2026-02-13 |
| 666 | [pgmigrate](https://github.com/yandex/pgmigrate) | CLI tool to evolve schema migrations, developed by Yandex. | 2026-03-10 |
| 599 | [postgresql-metrics](https://github.com/spotify/postgresql-metrics) | Tool that extracts and provides metrics for your PostgreSQL database. | 2021-07-12 |
| 569 | [ZSON](https://github.com/postgrespro/zson) | PostgreSQL extension for transparent JSONB compression | 2023-04-14 |
| 558 | [planter](https://github.com/achiku/planter) | Generate PlantUML ER diagram textual description from PostgreSQL tables | 2024-01-23 |
| 435 | [pg_chameleon](https://github.com/the4thdoctor/pg_chameleon) | Real time replica from MySQL to PostgreSQL with optional type override migration and migration capabilities. | 2025-01-21 |
| 407 | [Pyrseas](https://github.com/perseas/Pyrseas) | Postgres database schema versioning. | 2024-07-10 |
| 392 | [pgclimb](https://github.com/lukasmartinelli/pgclimb) | Export data from PostgreSQL into different data formats. | 2018-11-28 |
| 391 | [bemi](https://github.com/BemiHQ/bemi) | Automatic data change tracking for PostgreSQL | 2025-12-23 |
| 354 | [RegreSQL](https://github.com/dimitri/regresql) | Tool to build, maintain and execute a regression testing suite for SQL queries. | 2024-09-04 |
| 309 | [pg_insights](https://github.com/lob/pg_insights) | Convenient SQL for monitoring Postgres database health. | 2019-12-11 |
| 282 | [GatewayD](https://github.com/gatewayd-io/gatewayd) | Cloud-native database gateway and framework for building data-driven applications. Like API gateways, for databases. | 2026-02-22 |
| 232 | [ldap2pg](https://github.com/dalibo/ldap2pg) | Synchronize roles and privileges from YML and LDAP. | 2026-04-13 |
| 159 | [PGXN client](https://github.com/pgxn/pgxnclient) | Command line tool to interact with the PostgreSQL Extension Network | 2021-08-30 |
| 133 | [pgspot](https://github.com/timescale/pgspot) | Spot vulnerabilities in PostgreSQL extension scripts. | 2026-03-21 |
| 112 | [diesel-guard](https://github.com/ayarotsky/diesel-guard) | Linter for dangerous Postgres migration patterns in Diesel and SQLx. | 2026-04-26 |
| 84 | [pg-formatter](https://github.com/gajus/pg-formatter) | A PostgreSQL SQL syntax beautifier (Node.js). | 2024-12-18 |
| 59 | [pg-spot-operator](https://github.com/pg-spot-ops/pg-spot-operator) | A daemon to run stateful Postgres on cheap AWS Spot VMs | 2026-01-17 |
| 47 | [NServiceBus.Transport.PostgreSql](https://github.com/Particular/NServiceBus.SqlServer) | The NServiceBus.Transport.PostgreSql library allows .NET developers to use a PostgreSQL database as a message broker. (Commerical Software) | 2026-04-28 |
| 46 | [pgcmp](https://github.com/cbbrowne/pgcmp) | Tool to compare database schemas, with capability to accept some persistent differences | 2020-05-20 |
| 40 | [pg-differ](https://github.com/multum/pg-differ) | Tool for easy initialization / updating of the structure of PostgreSQL tables, migration alternative (Node.js). | 2020-10-28 |
| 32 | [pg_migrate](https://github.com/jwdeitch/pg_migrate) | Manage PostgreSQL codebases and make VCS simple. | 2017-10-11 |
| 30 | [pglistend](https://github.com/kabirbaidhya/pglistend) | A lightweight PostgresSQL LISTEN/NOTIFY daemon built on top of node-postgres. | 2017-03-29 |
| 18 | [pg_docs_bot](https://github.com/mchristofides/pg_docs_bot/) | Browser extension to redirect PostgreSQL docs links to the current version. | 2025-04-04 |
| 1 | [pg-safe-migrate](https://github.com/defnotwig/pg-safe-migrate) | Safety-first Node.js migration engine with advisory locks, SHA-256 drift detection, and 10 built-in lint rules for PostgreSQL. | 2026-03-03 |
| - | [apgdiff](https://www.apgdiff.com/) | Compares two database dump files and creates output with DDL statements that can be used to update old database schema to new one. | - |
| - | [flyway](https://flywaydb.org/) | Schema migration tool for Postgres and others. | - |
| - | [ora2pg](http://ora2pg.darold.net) | Perl module to export an Oracle database schema to a PostgreSQL compatible schema. | - |
| - | [pg_bulkload](http://ossc-db.github.io/pg_bulkload/index.html) | It's a high speed data loading utility for PostgreSQL. | - |
| - | [pganalyze](https://pganalyze.com) | PostgreSQL Performance Monitoring (Commercial Software). | - |
| - | [PgBouncer](http://www.pgbouncer.org/) | Lightweight connection pooler for PostgreSQL. | - |
| - | [PGInsight](http://pginsight.io/) | CLI tool to easily dig deep inside your PostgreSQL database. | - |
| - | [pgpool-II](https://www.pgpool.net/mediawiki/index.php/Main_Page) | Middleware that provides connection pooling, replication, load balancing and limiting exceeding connections. | - |
| - | [postgres-checkup](https://gitlab.com/postgres-ai/postgres-checkup) | a new-generation diagnostics tool that allows users to collect deep analysis of the health of a Postgres database. | - |
| - | [ScaffoldHub.io](https://scaffoldhub.io) | Generate fullstack PostgreSQL apps with Angular, Vue or React (Commercial Software). | - |

## Language bindings

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 13123 | [node-postgres](https://github.com/brianc/node-postgres) |  | 2026-04-30 |
| 9871 | [pq](https://github.com/lib/pq) |  | 2026-04-08 |
| 3933 | [rust-postgresql](https://github.com/sfackler/rust-postgres) |  | 2026-04-04 |
| 3679 | [Npgsql](https://github.com/npgsql/npgsql) |  | 2026-04-24 |
| 1401 | [zapatos](https://github.com/jawj/zapatos) |  | 2025-09-19 |
| 1210 | [postgrex](https://github.com/elixir-ecto/postgrex) |  | 2026-04-11 |
| 856 | [pg](https://github.com/ged/ruby-pg) |  | 2026-03-13 |
| 543 | [pg.zig](https://github.com/karlseguin/pg.zig) |  | 2026-04-25 |
| 429 | [Postmodern](https://github.com/marijnh/Postmodern) |  | 2025-07-24 |
| 337 | [RPostgres](https://github.com/r-dbi/RPostgres) |  | 2026-03-22 |
| 162 | [clj-postgresql](https://github.com/remodoy/clj-postgresql) |  | 2020-10-23 |
| 120 | [luapgsql](https://github.com/arcapos/luapgsql) |  | 2026-02-07 |
| - | [DBD-Pg](https://metacpan.org/pod/distribution/DBD-Pg/Pg.pm) |  | - |
| - | [Pomm](http://www.pomm-project.org) |  | - |
| - | [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/) |  | - |
| - | [postgresql-simple](http://hackage.haskell.org/package/postgresql-simple) |  | - |
| - | [psycopg2](https://pypi.org/project/psycopg2/) |  | - |

## PaaS (PostgreSQL as a Service)

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| - | [Aiven PostgreSQL](https://aiven.io/postgresql) | PostgreSQL as a service in AWS, Azure, DigitalOcean, Google Cloud and UpCloud; plans range from $19/month single node instances to large highly-available setups, free trial for two weeks. | - |
| - | [Amazon RDS for PostgreSQL](https://aws.amazon.com/rds/postgresql/) | Amazon Relational Database Service (RDS) for PostgreSQL | - |
| - | [Azure Database for PostgreSQL](https://azure.microsoft.com/en-us/services/postgresql/) | Azure Database for PostgreSQL provides fully managed, enterprise-ready community PostgreSQL database as a service. It provides builtin HA, elastic scaling and native integration with Azure ecosystem. | - |
| - | [Crunchy Bridge](https://www.crunchydata.com/products/crunchy-bridge/) | Fully managed Postgres from the Postgres experts. Available across all major cloud providers: Amazon AWS, Google GCP, Microsoft Azure. No lock-in with full super-user support. | - |
| - | [Database Labs](https://www.databaselabs.io) | Get a production-ready cloud PostgreSQL server in minutes, from $20 a month Backups, monitoring, patches, and 24/7 tech support all included. | - |
| - | [DigitalOcean Managed Databases](https://www.digitalocean.com/products/managed-databases/) | Fully managed PostgreSQL databases. No free plan. Starting at $15/mo. Daily backups with point-in-time recovery. Standby nodes with auto-failover. | - |
| - | [Google Cloud SQL for PostgreSQL](https://cloud.google.com/sql/docs/postgres/) | Fully-managed database service that makes it easy to set up, maintain, manage, and administer your PostgreSQL relational databases on Google Cloud Platform. | - |
| - | [Heroku Postgres](https://elements.heroku.com/addons/heroku-postgresql) | Plans from free to huge, operated by PostgreSQL experts. Does not require running your app on Heroku. Free plan includes 10,000 rows, 20 connections, up to two backups, and has PostGIS support. | - |
| - | [Neon](https://neon.tech) | Fully managed serverless PostgreSQL. Neon separates storage and compute to offer modern developer features such as serverless, branching, bottomless storage, and more. | - |
| - | [Nile](https://www.thenile.dev/) | Fully managed PostgreSQL . Nile decouples storage from compute and virtualizes tenants to ship multi-tenant AI applications fast, safe, and with limitless scale. Free tier provides unlimited databases. | - |
| - | [OVHcloud Cloud Databases](https://www.ovhcloud.com/en/public-cloud/databases/) | Highly available, scalable, and secured PostgreSQL. Daily backups with point-in-time recovery, no lock-in, free incoming and outgoing traffic. | - |
| - | [PlanetScale](https://planetscale.com/postgres) | PlanetScale for Postgres provides fully-managed, high availability PostgreSQL database clusters built on modern cloud infrastructure. | - |
| - | [Render Managed PostgreSQL](https://render.com/docs/databases) | Secure, reliable, and completely hands-off managed PostgreSQL. Encryption at rest, automated backups, and expandable SSD storage included in all plans. Plans start at $7 per month for 256MB RAM and 1GB storage (free for first 90 days). | - |
| - | [ScaleGrid PostgreSQL DBaaS](https://scalegrid.io/postgresql.html) | Fully managed PostgreSQL hosting with high availability, dedicated servers, and superuser control on the #1 multi-cloud Amazon RDS alternative. | - |
| - | [Scaleway Managed Database](https://www.scaleway.com/en/database/) | Fully managed PostgreSQL databases with HA, scaling, and automated backups, hosted in the EU. Starting at €10 per month. | - |
| - | [Supabase](https://www.supabase.com) | Fully managed Postgres with read replicas, point-in-time-recovery, support packages, browser based GUI, and a generous free tier. | - |
| - | [Thalassa Cloud DBaaS](https://thalassa.cloud/products/databases/postgresql/) | Fully managed PostgreSQL database, multi-AZ, automated backups, hosted in the Netherlands. | - |
| - | [Vela](https://vela.run) | Postgres-based backend-as-a-service built for modern AI apps. Offers instant database branches and clones, production-like test environments, and serverless scaling. | - |

## Docker images

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| - | [citusdata/citus](https://hub.docker.com/r/citusdata/citus/) | Citus official images with citus extensions. Based on the official Postgres container. | - |
| - | [mdillon/postgis](https://hub.docker.com/r/mdillon/postgis/) | PostGIS 2.3 on Postgres 9. Based on the official Postgres container. | - |
| - | [paradedb/paradedb](https://hub.docker.com/r/paradedb/paradedb/) | ParadeDB is Postgres for Search and Analytics. Based on the official Postgres container with pg_search extension. | - |
| - | [postgres](https://hub.docker.com/_/postgres/) | Official postgres container (from Docker) | - |

## Kubernetes

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 8538 | [CloudNativePG operator](https://github.com/cloudnative-pg/cloudnative-pg) | A comprehensive platform designed to seamlessly manage PostgreSQL databases within Kubernetes environments. | 2026-04-30 |
| 5148 | [Zalando Operator](https://github.com/zalando/postgres-operator) | Creates and manages PostgreSQL clusters running in Kubernetes. | 2026-04-28 |
| 4399 | [Crunchy Operator](https://github.com/CrunchyData/postgres-operator) | Production PostgreSQL for Kubernetes, from high availability Postgres clusters to full-scale database-as-a-service. | 2026-03-12 |
| 1392 | [StackGres Operator](https://github.com/ongres/stackgres/) | Full Stack PostgreSQL on Kubernetes. | 2026-03-09 |
| 1353 | [Kubegres Operator](https://github.com/reactive-tech/kubegres) | Kubegres is a Kubernetes operator allowing to deploy one or many clusters of PostgreSql instances and manage databases replication, failover and backup. | 2025-01-04 |
| 362 | [Percona PostgreSQL Operator](https://github.com/percona/percona-postgresql-operator) | Percona Operator for PostgreSQL based on Crunchy Data operator. | 2026-04-30 |
| 41 | [Percona Everest Operator](https://github.com/percona/everest-operator) | Everest Operator is a Kubernetes Operator responsible for managing the lifecycle of MySQL, MongoDB, and PostgreSQL databases. It leverages Percona's Kubernetes Operators for MySQL, MongoDB, and PostgreSQL under the hood but provides a unified API and a single pane of glass for managing all three database types. | 2026-04-29 |
| - | [Fujitsu Enterprise Postgres for Kubernetes](https://www.postgresql.fastware.com/) | Enterprise-grade PostgreSQL on OpenShift Container Platform (Commercial Software). | - |
| - | [KubeDB operator](https://kubedb.com/) | Run Production-Grade Databases on Kubernetes (Commercial Software). | - |

## Tutorials

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 1206 | [pg-utils](https://github.com/dataegret/pg-utils) | Useful DBA tools by Data Egret | 2025-12-05 |
| 549 | [postgresDBSamples](https://github.com/morenoh149/postgresDBSamples) | A collection of sample postgres schemas | 2023-09-20 |
| 73 | [pagila](https://github.com/xzilla/pagila) | Pagila, Postgres Sample Database | 2026-03-26 |
| 39 | [SQL Syntax Cheat Sheet](https://github.com/mergisi/sql-syntax-cheat-sheet) | Comprehensive SQL syntax reference covering window functions, CTEs, and PostgreSQL-specific syntax (UPSERT, JSON queries, array operations). | 2026-03-09 |
| - | [Backup and recover a PostgreSQL DB using wal-e](https://coderwall.com/p/cwe2_a/backup-and-recover-a-postgres-db-using-wal-e) | Tutorial about setting up continuous archiving in PostgreSQL using wal-e. | - |
| - | [Operations cheat sheet](https://wiki.postgresql.org/wiki/Operations_cheat_sheet) | Operations cheat sheet from PostgreSQL Wiki. | - |
| - | [PG Casts](https://www.pgcasts.com) | Free weekly PostgreSQL screencasts by Hashrocket. | - |
| - | [Postgres Guide](http://postgresguide.com/) | Guide designed as an aid for beginners and experienced users to find specific tips and explore tools available within PostgreSQL. | - |
| - | [PostgreSQL Exercises](https://pgexercises.com/) | Site  to make it easy to learn PostgreSQL by doing exercises. | - |
| - | [PostgreSQL Primer for Busy People](https://zaiste.net/posts/postgresql-primer-for-busy-people/) | A collection of the most common commands used in PostgreSQL | - |
| - | [tutorialspoint PostgreSQL tutorial](http://www.tutorialspoint.com/postgresql/) | Very extensive collection of tutorials on PostgreSQL | - |

## Blogs

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| 8473 | [Digoal's PostgreSQL and Technical blog(Chinese Language)](https://github.com/digoal/blog/blob/master/README.md) |  | 2026-04-30 |
| - | [Andrew Dunstan's PostgreSQL and Technical blog](http://adpgtech.blogspot.com/search/label/PostgreSQL/) |  | - |
| - | [BigData Boutique Blog / PostgreSQL](https://bigdataboutique.com/blog/tagged/postgresql) | Blog by the BigData Boutique team, mostly with analytics focus). | - |
| - | [Bruce Momjian's PostgreSQL blog](https://momjian.us/main/blogs/pgblog.html) |  | - |
| - | [Craig Kerstiens PostgreSQL posts](http://www.craigkerstiens.com/categories/postgres/) | Set of posts on PostgreSQL cool features, tips and tricks. | - |
| - | [Database Soup](http://www.databasesoup.com/search/label/postgresql/) | Josh Berkus' blog. | - |
| - | [Metis Blog](https://www.metisdata.io/blog) | Set of posts on PostgreSQL, SQL databases, performance, and tuning. | - |
| - | [Michael Paquier's blog](https://paquier.xyz/) |  | - |
| - | [Percona's PostgreSQL blog posts](https://www.percona.com/blog/category/postgresql/) |  | - |
| - | [Pigsty blog / PostgreSQL](https://pigsty.io/blog/pg/) | Blog by the author of PIGSTY with insightful articles on PostgreSQL (as well as databases and cloud infrastructure). | - |
| - | [Planet PostgreSQL](https://planet.postgresql.org/) | Blog aggregation service for PostgreSQL. | - |
| - | [Robert Haas' blog](http://rhaas.blogspot.com/search/label/postgresql/) |  | - |
| - | [select * from depesz;](https://www.depesz.com/tag/postgresql/) | Hubert Lubaczewski's blog. | - |

## Books

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| - | [Lift the Elephant](https://leanpub.com/lift-the-elephant) | A practical guide to scaling Postgres in production, covering tuning, connection pooling, partitioning, and high availability. | - |
| - | [PostgreSQL 14 Internals](https://postgrespro.com/community/books/internals) | A free e-book by Egor Rogov | - |
| - | [PostgreSQL Mistakes and How to Avoid Them](https://www.manning.com/books/postgresql-mistakes-and-how-to-avoid-them) |  | - |
| - | [The Internals of PostgreSQL](https://www.interdb.jp/pg/index.html) | A free e-book by Hironobu Suzuki | - |

## Documentation

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| - | [create_pg_super_document](https://ryogrid.github.io/create_pg_super_document/index.html) | A project that aim to generate documentation for all symbols in the PostgreSQL codebase using AI agents | - |
| - | [pgPedia](https://pgpedia.info/) | An encyclopedia of things related to postgreSQL. | - |
| - | [Wiki](https://wiki.postgresql.org/wiki/Main_Page) | user documentation, how-tos, and tips 'n' tricks | - |

## Newsletters

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| - | [pgMustard newsletter](https://www.pgmustard.com/newsletter) | Monthly newsletter that contains Postgres performance articles and videos. | - |
| - | [Postgres Weekly](https://postgresweekly.com/) | Weekly newsletter that contains articles, news, and repos relevant to PostgreSQL. | - |

## Podcasts

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| - | [Path to Citus Con](https://www.citusdata.com/podcast/path-to-citus-con/) | Monthly interviews with people in the Postgres world. | - |
| - | [PostgresFM](https://postgres.fm/) | Weekly discussions about Postgres topics. | - |
| - | [Scaling Postgres](https://www.scalingpostgres.com/) | Weekly roundups of PostgreSQL related content. | - |

## Videos

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| - | [Citus Data Youtube channel](https://www.youtube.com/channel/UC8jpoK1BqQhDh6HDGFnM_DA/videos) | Citus related videos | - |
| - | [EnterpriseDB Youtube channel](https://www.youtube.com/channel/UCkIPoYyNr1OHgTo0KwE9HJw) | EnterpriseDB related videos | - |
| - | [Postgres Conference Youtube channel](https://www.youtube.com/channel/UCsJkVvxwoM7R9oRbzvUhbPQ/videos) | Conference videos | - |
| - | [PostgresTV Youtube channel](https://www.youtube.com/@PostgresTV) | Postgres talks, hacking sessions, interviews, and podcast episodes | - |
| - | [Scaling Postgres](https://www.scalingpostgres.com/) | Postgres video blog series by Creston Jamison | - |

## Community

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| - | [#postgresql on Freenode](https://webchat.freenode.net/#postgresql) | The most popular IRC channel about Postgres on Freenode with over 1000 users | - |
| - | [Discord](https://discord.gg/bW2hsax8We) | A Discord server for Postgres with over 6k members | - |
| - | [Mailing lists](https://www.postgresql.org/list/) | Official mailing lists for Postgres for support, outreach, and more. One of the primary channels of communication in the Postgres community. | - |
| - | [Reddit](https://www.reddit.com/r/PostgreSQL/) | A reddit community for PostgreSQL users with over 12000 users | - |
| - | [Russian](https://t.me/pgsql) | Several groups for PostgreSQL in different languages: Russian >4200 people, Brazilian Portuguese >2300 people, Indonesian ~1000 people, English >750 people | - |
| - | [Slack](https://pgtreats.info/slack-invite) | Slack workspace for Postgres with over 20k members | - |

## Roadmaps

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| - | [PostgreSQL Roadmap](https://roadmap.sh/postgresql-dba) | A roadmap providing step wise guide to PostgreSQL. | - |

## External lists

| Stars | Name | Description | Last Commit |
| ---: | --- | --- | --- |
| - | [PostgreSQL Wiki Foreign Data Wrappers list](https://wiki.postgresql.org/wiki/Foreign_data_wrappers) | Foreign data wrappers | - |
| - | [PostgreSQL Wiki GUI tools list](https://wiki.postgresql.org/wiki/Community_Guide_to_PostgreSQL_GUI_Tools) | Community Guide to PostgreSQL GUI Tools | - |
| - | [Wikipedia admin tools list](https://en.wikipedia.org/wiki/Comparison_of_database_tools) | Comparison of database administration tools on Wikipedia | - |
