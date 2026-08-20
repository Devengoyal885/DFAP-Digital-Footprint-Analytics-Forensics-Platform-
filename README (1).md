<p align="center">
  <img src="assets/banner.png" alt="DFAP — Digital Footprint Analytics & Forensics Platform" width="100%">
</p>

<h1 align="center">DFAP</h1>
<p align="center"><b>Digital Footprint Analytics & Forensics Platform</b></p>
<p align="center">AI-powered unified digital intelligence for telecom, banking & social-media investigations</p>

<p align="center">
  <img alt="Team" src="https://img.shields.io/badge/Team-ArcLight-0E2841?style=for-the-badge&labelColor=0E2841&color=FFC000">
  <img alt="Status" src="https://img.shields.io/badge/Status-Prototype-FFC000?style=for-the-badge&labelColor=0E2841">
  <img alt="License" src="https://img.shields.io/badge/License-MIT-0E2841?style=for-the-badge&labelColor=0E2841&color=FFC000">
</p>

<p align="center">
  <a href="#-problem-statement">Problem</a> •
  <a href="#-target-audience">Audience</a> •
  <a href="#-proposed-solution">Solution</a> •
  <a href="#-key-features">Features</a> •
  <a href="#-system-architecture">Architecture</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-team--developers">Team</a>
</p>

---

## 📌 Overview

Digital evidence today is fragmented across **telecom (CDR/IPDR)**, **banking**, and **social media** platforms. Investigators are forced to analyze each source in isolation and manually stitch together phone numbers, bank accounts, IP addresses, and social identities — a slow, error-prone process that buries actionable intelligence in disconnected data.

**DFAP** is an AI-powered unified digital intelligence platform that ingests telecom, banking, and social-media signals, resolves fragmented identities into a single **Digital Footprint Graph**, and surfaces **explainable, evidence-backed insights** — turning isolated data points into one connected investigation.

---

## 🚨 Problem Statement

| Pain Point | Why It Matters |
|---|---|
| **Siloed Data** | CDR/IPDR, bank statements & social activity are analyzed independently, hiding cross-domain criminal patterns |
| **Manual Correlation** | Investigators spend days manually linking phone numbers, accounts & IPs across disconnected systems |
| **No Explainability** | Existing tools output black-box anomaly scores with no reasoning an investigator can act on or present as evidence |
| **Fragmented Identities** | The same individual appears as different digital identities across platforms, breaking the investigative trail |

> **Result:** slower investigations, missed connections, and intelligence buried in disconnected data.

---

## 🎯 Target Audience

DFAP is built for investigators who need **one platform — not five browser tabs** — to see the full picture.

- 🚓 **Law Enforcement & Cyber Cells** — investigate financial fraud, cybercrime & organized criminal networks
- 🏦 **Banks & Financial Intelligence Units** — detect money-laundering rings, mule accounts & suspicious transaction chains
- 📡 **Telecom Fraud & Security Teams** — correlate CDR/IPDR anomalies with financial and social behavior to flag SIM fraud & scam networks
- 🕵️ **Intelligence & Investigation Agencies** — reconstruct timelines and relationship networks for large-scale forensic investigations

---

## 💡 Proposed Solution

DFAP unifies telecom, banking & social data into one explainable Digital Footprint Graph — turning fragmented signals into investigation-ready intelligence.

<p align="center">
  <img src="assets/pipeline_diagram.png" alt="DFAP Pipeline: Ingest, Resolve, Analyze, Explain & Act" width="100%">
</p>

1. **Ingest** — Privacy-safe synthetic CDR/IPDR, bank statement & social-media datasets
2. **Resolve** — AI Entity Resolution Engine links phone numbers, accounts, IPs & social identities into one profile
3. **Analyze** — ML anomaly detection, behavioral profiling, graph analytics & temporal correlation
4. **Explain & Act** — Explainable risk scores, interactive graph, AI Copilot & auto-generated investigation summaries

Instead of analyzing each data source independently, DFAP correlates all three — turning isolated signals into one connected investigation.

---

## ✨ Key Features

| # | Feature | Description |
|---|---|---|
| 1 | **AI Entity Resolution Engine** | Connects phone numbers, bank accounts, IPs & social accounts into one Digital Footprint Graph |
| 2 | **Explainable Risk Scoring** | Every risk score shows exactly which factors contributed — fully transparent to investigators |
| 3 | **Interactive Graph & Timeline** | Visualize relationships and reconstruct chronological events across all data sources |
| 4 | **AI Investigation Copilot** | Ask natural-language questions like *"Why was this entity flagged?"* and get evidence-backed answers |
| 5 | **Digital Twin Profiling** | Continuously updated behavioral profile detects drift in communication, financial & social activity |
| 6 | **Auto-Generated Reports** | One-click investigation summaries with key entities, timelines, risk factors & recommended leads |

---

## 🖥️ Prototype Preview

<p align="center">
  <img src="assets/dashboard_preview.png" alt="DFAP Investigator Console Preview" width="100%">
</p>

*Illustrative mockup of the investigator console — entity graph, KPI overview, and explainable risk-score panel.*

---

## 🏗 System Architecture

<p align="center">
  <img src="assets/architecture_diagram.png" alt="DFAP System Architecture Diagram" width="100%">
</p>

DFAP is organized into five layers:

1. **Data Sources** — Telecom CDR/IPDR, bank statements, social-media activity (synthetic, privacy-safe for the demo)
2. **Ingestion & Privacy Layer** — Synthetic data generation, anonymization/consent filters, schema normalization
3. **AI Intelligence Layer** — Entity resolution, ML-based anomaly detection, graph analytics, digital twin engine, temporal correlation
4. **Intelligence Output** — Digital Footprint Graph, explainable risk scores, RAG-based Investigation Copilot, auto-generated reports
5. **Investigator Interface** — Interactive dashboard, graph explorer, timeline view, natural-language query

---

## 🛠 Tech Stack

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-0E2841?style=for-the-badge&logo=python&logoColor=FFC000">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-0E2841?style=for-the-badge&logo=fastapi&logoColor=FFC000">
  <img alt="React" src="https://img.shields.io/badge/React-0E2841?style=for-the-badge&logo=react&logoColor=FFC000">
  <img alt="Neo4j" src="https://img.shields.io/badge/Neo4j%20Graph%20DB-0E2841?style=for-the-badge&logo=neo4j&logoColor=FFC000">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch%20%2F%20Scikit--learn-0E2841?style=for-the-badge&logo=pytorch&logoColor=FFC000">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-0E2841?style=for-the-badge&logo=postgresql&logoColor=FFC000">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-0E2841?style=for-the-badge&logo=docker&logoColor=FFC000">
</p>

| Layer | Technology |
|---|---|
| Backend API | Python, FastAPI |
| ML / Anomaly Detection | PyTorch, Scikit-learn |
| Graph Storage & Analytics | Neo4j (Graph DB) |
| Relational Storage | PostgreSQL |
| AI Copilot | LLM-based, Retrieval-Augmented Generation (RAG) |
| Frontend | React |
| Containerization | Docker |

> Adjust the table above to match the exact versions/libraries used in your final implementation.

---

## 📊 Competitive Analysis

| Capability | Manual / Siloed Review | Single-Domain Fraud Tools | **DFAP (Ours)** |
|---|:---:|:---:|:---:|
| Cross-Domain Correlation (Telecom + Bank + Social) | ✗ | Partial | ✅ |
| AI Entity Resolution Across Identities | ✗ | ✗ | ✅ |
| Explainable, Factor-Level Risk Scoring | ✗ | ✗ | ✅ |
| Natural-Language Investigation Copilot | ✗ | ✗ | ✅ |
| Behavioral Drift / Digital Twin Detection | ✗ | ✗ | ✅ |
| Auto-Generated Investigation Reports | ✗ | Partial | ✅ |

---

## 📦 Deliverables & Expected Impact

**What We'll Deliver**
- Working prototype with synthetic CDR/IPDR, banking & social datasets
- Interactive entity graph + digital footprint timeline
- Explainable risk-scoring dashboard
- AI Investigation Copilot (natural-language Q&A)
- Auto-generated investigation summary reports

**Expected Impact**
- Faster investigations — cross-domain correlation in minutes, not days
- Higher case-closure accuracy with explainable, evidence-backed leads
- Scalable architecture ready for real-world fraud & cyber investigations
- Reusable framework across telecom, banking & law-enforcement agencies

---

## 🚀 Getting Started

> The steps below reflect the intended tech stack for the prototype. Update them once the implementation is finalized so they match the actual repo structure.

### Prerequisites
- Python 3.10+
- Node.js 18+
- Docker & Docker Compose
- Neo4j (local or containerized)
- PostgreSQL 14+

### Clone the repository
```bash
git clone https://github.com/Devengoyal885/DFAP-Digital-Footprint-Analytics-Forensics-Platform-.git
cd DFAP-Digital-Footprint-Analytics-Forensics-Platform-
```

### Backend setup
```bash
cd backend
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend setup
```bash
cd frontend
npm install
npm run dev
```

### Run with Docker Compose (recommended)
```bash
docker compose up --build
```

### Environment variables
Create a `.env` file in the backend directory:
```env
NEO4J_URI=bolt://localhost:7687
NEO4J_USER=neo4j
NEO4J_PASSWORD=your_password
POSTGRES_URL=postgresql://user:password@localhost:5432/dfap
LLM_API_KEY=your_llm_api_key
```

---

## 🔒 Data & Privacy

DFAP is demonstrated using **privacy-safe, synthetic** CDR/IPDR, banking, and social-media datasets. No real personal data is used in the prototype. The architecture is designed to be compliant-by-default and scalable to real-world, authorized investigative use cases.

---

## 🗺 Roadmap

- [ ] Expand entity resolution to additional identity types (device fingerprints, crypto wallets)
- [ ] Real-time streaming ingestion for live investigations
- [ ] Multi-language support for the AI Investigation Copilot
- [ ] Role-based access control & audit trails for evidentiary chain-of-custody
- [ ] Integration APIs for existing case-management systems

---

## 👥 Team & Developers

**Team ArcLight**

| Member | Role | GitHub | Portfolio |
|---|---|---|---|
| **Deven Goyal** | Team Leader | [@Devengoyal885](https://github.com/Devengoyal885) | [devengoyal.netlify.app](https://devengoyal.netlify.app/) |
| **Aryan Yadav** | Team Member | [@aryanrao](https://github.com/aryanrao) | — |
| **Rishabh Verma** | Team Member | [@Rishabhv16](https://github.com/Rishabhv16) | — |
| **Aditya Singh** | Team Member | [@aditya511-GH](https://github.com/aditya511-GH) | — |
| **V Naveen Shankar** | Team Member | [@naveen-devcodes](https://github.com/naveen-devcodes) | — |

📁 **Project Repository:** [DFAP-Digital-Footprint-Analytics-Forensics-Platform-](https://github.com/Devengoyal885/DFAP-Digital-Footprint-Analytics-Forensics-Platform-)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details. *(Add a `LICENSE` file to the repo, or swap this section for whichever license you choose.)*

---

## 🙏 Acknowledgments

Built by **Team ArcLight** for a hackathon submission focused on digital forensics and investigative intelligence.

<p align="center">Made with ❤️ by Team ArcLight</p>
