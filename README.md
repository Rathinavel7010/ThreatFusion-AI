# 🛡️ ThreatFusion AI

> **Unified Threat Intelligence Aggregator with AI-Powered Investigation**

ThreatFusion AI is a modern cybersecurity platform that aggregates threat intelligence from multiple open-source intelligence (OSINT) providers into a single dashboard. It automatically analyzes Indicators of Compromise (IOCs), enriches them with threat intelligence, and generates AI-powered investigation summaries to help Security Operations Center (SOC) analysts make faster and more informed decisions.

---

## 📌 Project Overview

Security analysts often spend valuable time checking multiple threat intelligence platforms individually to investigate a single IOC.

ThreatFusion AI simplifies this workflow by collecting data from multiple intelligence sources, normalizing the results, calculating a unified risk score, and generating an AI-assisted investigation report.

This project is designed to simulate a real-world SOC analyst workflow while demonstrating practical cybersecurity engineering, API integration, automation, and AI-assisted incident investigation.

---

## 🎯 Objectives

* Aggregate threat intelligence from multiple providers
* Reduce manual IOC investigation time
* Normalize data into a unified format
* Generate AI-powered investigation summaries
* Provide actionable recommendations
* Export professional investigation reports

---

# ✨ Features

### IOC Detection

* IPv4 Address
* IPv6 Address
* Domain
* URL
* MD5 Hash
* SHA1 Hash
* SHA256 Hash

---

### Threat Intelligence Sources

* VirusTotal
* AbuseIPDB
* AlienVault OTX
* URLHaus
* WHOIS

---

### Threat Enrichment

* Reputation Analysis
* Malware Association
* Abuse Confidence
* Threat Categories
* Country Information
* ASN Details
* Registrar Information
* IOC Metadata

---

### AI Investigation

* AI-generated IOC Summary
* Threat Explanation
* Risk Assessment
* Security Recommendations
* Executive Summary

---

### Dashboard

* IOC Overview
* Threat Intelligence Summary
* Risk Score
* Threat Timeline
* Intelligence Sources
* Detection Statistics
* Investigation History

---

### Reports

* PDF Report
* JSON Export
* CSV Export

---

# 🏗️ System Architecture

```text
                   User
                    │
                    ▼
            IOC Input Engine
                    │
                    ▼
          IOC Type Detection
                    │
                    ▼
      Threat Intelligence Engine
                    │
      ┌──────────┬──────────┬──────────┐
      │          │          │          │
 VirusTotal  AbuseIPDB   OTX      URLHaus
      │          │          │          │
      └──────────┴──────────┴──────────┘
                    │
                    ▼
          Data Normalization
                    │
                    ▼
             AI Investigation
                    │
                    ▼
           Risk Score Engine
                    │
                    ▼
        Dashboard & Report Export
```

---

# 🛠️ Technology Stack

## Backend

* Python
* FastAPI
* Pydantic
* SQLAlchemy
* Requests / HTTPX

## Frontend

* React
* Tailwind CSS
* Chart.js

## Database

* PostgreSQL
* SQLite (Development)

## AI

* OpenAI API (Planned)
* Local LLM Support (Future)

## Reporting

* ReportLab

## Deployment

* Docker
* GitHub

---

# 📂 Project Structure

```text
ThreatFusion-AI/
│
├── backend/
│   ├── app/
│   │   ├── api/
│   │   ├── services/
│   │   ├── models/
│   │   ├── database/
│   │   ├── schemas/
│   │   ├── utils/
│   │   ├── config/
│   │   └── main.py
│   │
│   ├── tests/
│   ├── requirements.txt
│   └── .env.example
│
├── frontend/
│
├── docs/
│
├── reports/
│
├── sample_data/
│
├── docker/
│
├── scripts/
│
├── README.md
├── LICENSE
└── CHANGELOG.md
```

---

# 🚀 Development Roadmap

## Phase 1

* Project Setup
* Folder Structure
* GitHub Repository

## Phase 2

* IOC Type Detection

## Phase 3

* VirusTotal Integration

## Phase 4

* AbuseIPDB Integration

## Phase 5

* AlienVault OTX Integration

## Phase 6

* URLHaus Integration

## Phase 7

* Data Normalization

## Phase 8

* Risk Scoring Engine

## Phase 9

* AI Investigation Summary

## Phase 10

* Dashboard Development

## Phase 11

* PDF Report Generator

## Phase 12

* Docker Deployment

---

# 🔒 Supported IOC Types

* IP Address
* Domain
* URL
* MD5
* SHA1
* SHA256

---

# 🎯 Future Enhancements

* MITRE ATT&CK Mapping
* Threat Actor Attribution
* IOC Relationship Graph
* Bulk IOC Analysis
* Sigma Rule Suggestions
* YARA Rule Suggestions
* Case Management
* User Authentication
* Investigation History
* Real-time Threat Intelligence Updates
* Slack & Email Notifications

---

# 📖 Learning Goals

This project demonstrates practical knowledge in:

* Threat Intelligence
* SOC Operations
* API Integration
* Python Development
* FastAPI
* React
* AI Integration
* Risk Assessment
* Incident Investigation
* Report Generation
* Secure Software Development

---

# 🤝 Contributing

Contributions, feature suggestions, and improvements are welcome.

Please create an issue before submitting major changes.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Rathinavel R**

Cybersecurity Student | SOC Enthusiast | Threat Intelligence Learner

---

> **"Transforming raw threat intelligence into actionable security insights through automation and AI."**
