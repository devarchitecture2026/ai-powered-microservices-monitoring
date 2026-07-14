# AI-Powered Microservices Monitoring Tool

An AI-powered monitoring solution that captures failed API requests, stores them in a SQL database, analyzes failures using AI, and suggests Java code fixes through an automated n8n workflow.

## 🚀 Project Objective

Build an intelligent monitoring pipeline that:

- Captures failed API requests from Java microservices
- Stores failure details in a SQL database
- Uses OpenAI to analyze errors and suggest fixes
- Notifies developers through Email/Slack
- Provides a foundation for future integrations with Jira and dashboards

## 🛠️ Tech Stack

- Java 21
- Spring Boot
- n8n
- PostgreSQL
- OpenAI GPT
- Email / Slack

## 📌 Planned Workflow

```text
Spring Boot API
       │
       ▼
Webhook (n8n)
       │
       ▼
Normalize Request
       │
       ▼
SQL Database
       │
       ▼
OpenAI Analysis
       │
       ▼
Update Database
       │
       ▼
Email / Slack Notifications
```

## 👥 Team

DEVStream Architecture  GenAI

## 📅 Status

🚧 Work in Progress
