# Secure-ELK-Stack-with-Instagram-Data-Collection-Sentiment-Analysis

## 📌 Project Overview

This project focuses on deploying and securing an ELK Stack (Elasticsearch, Logstash, Kibana) on a Linux virtual machine, combined with Instagram data collection, MongoDB storage, and sentiment analysis.

The main objective is to build a secure, end-to-end data pipeline that collects social media data, enriches it with sentiment analysis, indexes it into Elasticsearch, and visualizes insights through Kibana dashboards.

## 🏗️ Global Architecture
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
### 🛠️ ELK Stack Installation
**1️⃣ Elasticsearch**

Installation and service configuration

Cluster startup and health verification

Access via:
http://localhost:9200
