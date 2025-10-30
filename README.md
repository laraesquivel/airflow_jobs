# Airflow + Spark + MinIO - Data Pipeline Environment

Stack completa para desenvolvimento de pipelines de dados com Apache Airflow, Apache Spark e MinIO (S3-compatible storage).
## 🏗️ Arquitetura

Apache Airflow 2.8.1: Orquestração de workflows
Apache Spark 3.5.0: Processamento distribuído de dados
MinIO: Storage S3-compatible (Data Lake)
PostgreSQL: Metadata database do Airflow
Redis: Message broker para Celery
Celery: Executor distribuído do Airflow

## 📋 Pré-requisitos

Docker Desktop ou Docker Engine + Docker Compose
VS Code com extensão Dev Containers (para desenvolvimento)
Mínimo 8GB RAM e 10GB de espaço em disco
Git

## Links de Documentações
https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html

