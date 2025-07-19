# <p align="center">👷‍♂️ Data Engineer in Practice – Bruno Chiconato </p>

**Turning raw data into clean, automated, and observable pipelines using modern cloud & open-source stacks.**

Current role: BI Analyst Jr. (👀), but delivering like a full-stack data engineer.

> *I make data pipelines that don't cry at 2 AM.*

![Profile views](https://komarev.com/ghpvc/?username=BrunoChiconato&color=blue)

## 👋 About Me

I'm Bruno, a Data Engineer in practice (and in mindset).
Despite the “BI Analyst” title on paper, I spend my days solving real data engineering problems:
broken pipelines, poorly structured data lakes, unscalable ETLs, lack of observability — and turning them into robust, modular, and automated solutions.

I’ve built and deployed **serverless and open-source data pipelines** from scratch, using tools like **Apache Airflow**, **AWS Lambda**, **Docker**, **Spark**, **dbt**, **Step Functions**, and **MinIO**, with data visualized in **Metabase** or **Streamlit**, and monitored via **Slack/SNS**.

My focus:
**Architecture first, automation always, cloud when needed, and code that doesn’t cry in production.**

Currently pursuing a postgrad in Data Engineering while shipping personal projects that reflect real-world complexity.

## Tech Stack Snapshot

<p align="center">
  <!-- Python -->
  <a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/></a>
  <!-- Linux -->
  <a href="https://ubuntu.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/linux/linux-plain.svg" alt="Ubuntu" width="35" height="35"/></a>
  <!-- Docker -->
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/docker/docker-original.svg" alt="Docker" width="45" height="45"/></a>
  <!-- Terraform -->
  <a href="https://developer.hashicorp.com/terraform" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/terraform/terraform-original.svg" alt="Terraform" width="40" height="40"/></a>
  <!-- AWS -->
  <a href="https://aws.amazon.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" width="40" height="40"/></a>
  <!-- Git -->
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="40" height="40"/></a>
  <!-- Airflow -->
  <a href="https://airflow.apache.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/apacheairflow/apacheairflow-original.svg" alt="Airflow" width="35" height="35"/></a>
  <!-- dbt -->
  <a href="https://www.getdbt.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/simple-icons/simple-icons/refs/heads/develop/icons/dbt.svg" alt="dbt" width="35" height="35"/></a>
  <!-- MySQL -->
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="40" height="40"/></a>
  <!-- PostgreSQL -->
  <a href="https://www.postgresql.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="40" height="40"/></a>
  <!-- SQL Server -->
  <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" alt="SQL Server" width="40" height="40"/></a>

</p>

## Featured Projects

### Stock Market Data Pipeline with Apache Airflow, Spark & MinIO

![Stock Market](./pics/stock-market.png)

End-to-end orchestrated pipeline using an open-source stack for financial data processing and dashboarding.

* Built with **Apache Airflow (Astro CLI)**, containerized via **Docker Compose**.
* Ingests stock data from Yahoo Finance API, stores raw JSON in **MinIO (S3-compatible)**.
* Transforms data using **Apache Spark**, writes cleaned CSVs back to object storage.
* Loads final tables into **PostgreSQL**, visualized with **Metabase** dashboards.
* Integrates **Slack notifications** for monitoring pipeline success/failure.
* Focused on orchestration, transformation, and delivery with modular DAGs and TaskFlow API.

> *"This project simulates a production-grade ELT architecture using only open-source tools. It demonstrates my proficiency with Airflow orchestration, Spark processing, and cloud-native design principles."*

🔗 [Link to Repository](https://github.com/BrunoChiconato/airflow-project)

---

### Cryptocurrency Serverless Pipeline on AWS

![Crypto Pipeline](./pics/crypto-aws.png)

Real-time, cost-optimized pipeline for crypto data ingestion, transformation, alerting, and visualization — fully serverless.

* Automated ingestion every 5 minutes via **EventBridge** triggering **Step Functions**.
* Built with **6 AWS Lambda Functions** for fetch, validation, transformation, and notification.
* Raw and transformed data stored in **S3 (Parquet format)**.
* Dashboard built using **Streamlit**, deployed on **EC2**, visualizing historical and real-time metrics.
* Integrated alerting via **SNS Email Notifications** based on pipeline execution state.
* Designed for **free-tier compliance** and scalability with no servers to manage.

> *"This project shows how I design scalable and efficient data pipelines using the AWS serverless ecosystem, with strong emphasis on automation, resilience and low cost."*

🔗 [Link to Repository](https://github.com/BrunoChiconato/aws-bootcamp/tree/main/aula_14)

---

### Northwind Analytics Pipeline
![Northwind Analytics](./pics/northwind.png)

A fully automated analytics pipeline built with **dbt**, **AWS Fargate**, and **Terraform** to demonstrate modern DataOps practices.

* Manages all cloud infrastructure as code using **Terraform** to provision the AWS environment.
* Automates data transformation and testing via a **CI/CD pipeline** with **GitHub Actions**.
* Executes dbt jobs in a containerized, **serverless environment** on **AWS Fargate**, eliminating the need to manage servers.
* Features integrated data quality testing and automatically generates and hosts documentation (`dbt docs`) on **S3**.
* Ensures secure credential management with **AWS SSM Parameter Store**.

> *"This project is a blueprint for modern DataOps. It demonstrates my ability to architect and automate a complete analytics workflow, from infrastructure deployment with Terraform to CI/CD-driven transformations with dbt and GitHub Actions, ensuring a scalable, testable, and serverless solution."*

🔗 [Link to Repository](https://github.com/BrunoChiconato/dbt-analytics-pipeline)

## Education & Certifications

- ![PUC Minas Badge](https://img.shields.io/badge/PUC%20Minas-Data%20Engineering%20Postgrad-cd3724?style=flat&logoColor=white&labelColor=575757) – Focused on distributed systems, cloud pipelines, data modeling, big data frameworks, and streaming architecture.
- ![UTFPR Badge](https://img.shields.io/badge/UTFPR-Electrical%20Engineering-yellow?style=flat&logoColor=black&labelColor=575757) – Developed strong foundations in systems thinking, logic, and mathematical modeling.
- ![Jornada de Dados Badge](https://img.shields.io/badge/Jornada%20de%20Dados-Data%20Bootcamp-13d5ff?style=flat&logoColor=white&labelColor=575757) – Applied Airflow, dbt, and AWS tools to solve real-world data challenges in hands-on projects.
- ![Airflow Badge](https://img.shields.io/badge/Astronomer-Airflow%20Fundamentals%20Certified-8b52d6?style=flat&logoColor=white&labelColor=575757) – Certified in DAG architecture, scheduling lifecycle, task execution, and UI-based monitoring & debugging.
- ![Linux Tips Badge](https://img.shields.io/badge/Linux%20Tips-Advanced%20Python-2470ae?style=flat&logoColor=white&labelColor=575757) – Strong command of Python scripting, data manipulation, and functional programming patterns.
- ![Linux Tips Docker](https://img.shields.io/badge/Linux%20Tips-Advanced%20Docker-2191e5?style=flat&logoColor=white&labelColor=575757) – Built, deployed, and managed containerized environments, focused on pipeline automation and infrastructure reproducibility.

## GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=BrunoChiconato&theme=gruvbox&hide_border=true" alt="Bruno's GitHub Streak"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=BrunoChiconato&theme=gruvbox&no-frame=true&margin-w=15&column=3&rank=-C,-?" alt="Bruno's GitHub Trophies"/>
</p>

<picture align="center">
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/BrunoChiconato/BrunoChiconato/main/dist/github-snake-dark.svg" />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/BrunoChiconato/BrunoChiconato/main/dist/github-snake.svg" />
  <img
    alt="github-snake"
    src="https://raw.githubusercontent.com/BrunoChiconato/BrunoChiconato/main/dist/github-snake.gif" />
</picture>

## Connect with Me

<div align="center">
  <a href="https://www.linkedin.com/in/brunochiconato">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:brunochiconato01@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</div>
