# Secure-ELK-Stack-with-Instagram-Data-Collection-Sentiment-Analysis

## 📌 Project Overview

This project focuses on deploying and securing an ELK Stack (Elasticsearch, Logstash, Kibana) on a Linux virtual machine, combined with Instagram data collection, MongoDB storage, and sentiment analysis.

The main objective is to build a secure, end-to-end data pipeline that collects social media data, enriches it with sentiment analysis, indexes it into Elasticsearch, and visualizes insights through Kibana dashboards.

## 🏗️ Global Architecture
```
Instagram
   ↓
Python Script (Instaloader)
   ↓
MongoDB
   ↓
Logstash
   ↓
Elasticsearch
   ↓
Kibana (Dashboards & Analytics)

 ```
### 🛠️ ELK Stack Installation
**1️⃣ Elasticsearch**

Installation and service configuration

Cluster startup and health verification

Access via:
http://localhost:9200

**2️⃣ Kibana**

Configuration of Elasticsearch connection

Web interface access via:
http://localhost:5601
**3️⃣ Logstash**

Pipeline configuration (input, filter, output)

Verification of data ingestion from MongoDB into Elasticsearch

## 🔐 Security & Authentication

The ELK stack is fully secured using X-Pack Security:

X-Pack Security enabled

User and role creation

Role-based access control (RBAC)

Secured access to Elasticsearch and Kibana

Mandatory authentication (username & password)
