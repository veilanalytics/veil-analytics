# 🛡️ VeilAnalytics — Zero-Raw-Data Privacy Analytics Engine

> High-speed, local-first SQL analytics powered by in-process **DuckDB**, AST security validation, and interactive chart visualizations.

[![Live Demo](https://img.shields.io/badge/Live_Demo-veil--analytics.onrender.com-06b6d4?style=for-the-badge&logo=render)](https://veil-analytics.onrender.com)
[![Official Website](https://img.shields.io/badge/Website-veilanalytics.netlify.app-10b981?style=for-the-badge&logo=netlify)](https://veilanalytics.netlify.app)
[![Powered by DuckDB](https://img.shields.io/badge/Engine-DuckDB-fff000?style=for-the-badge&logo=duckdb)](https://duckdb.org)

---

## 🚀 Why VeilAnalytics?

Traditional SaaS BI tools (Tableau, PostHog Cloud, Mixpanel) force you to upload raw customer data to third-party cloud servers. For healthcare, fintech, legal, and compliance-sensitive teams, this creates massive security and GDPR/HIPAA risks.

**VeilAnalytics** flips the model: **100% of data processing happens locally in-memory** on your machine or local server using DuckDB. Zero raw data ever leaves your environment.

---

## ✨ Key Features

- **⚡️ In-Process DuckDB Engine:** Execute analytical SQL queries across 1,000,000+ rows of CSV, Parquet, JSON, or Excel files in milliseconds.
- **🔒 Zero Raw-Data Retention:** Computation is isolated locally. No raw customer rows are transmitted over the web.
- **🛡️ AST Query Guardrails:** Powered by `node-sql-parser` to sanitize and restrict query execution strictly to safe `SELECT` operations.
- **📊 Interactive Offline Dashboard Exporter:** Export standalone, fully interactive Chart.js HTML dashboards in 1 click that open in any browser offline.
- **🤖 Built-in AI Insights (Optional):** Connect local Ollama or cloud AI endpoints (Gemini, OpenAI, Groq) via UI settings for automated SQL generation.

---

## 🛠️ Quick Start (Turnkey Docker)

Run VeilAnalytics locally in 60 seconds with Docker Compose:

```bash
git clone https://github.com/shyamprasath-arc/presentation-antigravity.git veilanalytics
cd veilanalytics
docker compose up -d --build
```

Access the app in your browser:  
👉 **`http://localhost:8080`**

---

## 🔧 Local Development Setup (Node.js)

```bash
# 1. Install dependencies
npm run install:all

# 2. Configure environment variables (Optional)
cp .env.example .env

# 3. Run development mode (Client + Server concurrently)
npm run dev
```

- **Frontend:** `http://localhost:5173`
- **Backend API:** `http://localhost:3001`

---

## 📚 Technical Documentation & Articles

- 📖 [Architecture & Security Audit Guide](https://veilanalytics.netlify.app/docs/documentation.md)
- 📝 [Why We Replaced SaaS Analytics with In-Process DuckDB (Hashnode Article)](https://veilanalytics.hashnode.dev/why-we-replaced-saas-analytics-with-in-process-duckdb-zero-raw-data-architecture)

---

## 💳 Commercial Licenses & Source Code Access

Need desktop binaries or full commercial white-label source code rights for agency client work?

- **Desktop License ($149):** [Buy Instant Download](https://buy.polar.sh/polar_cl_yHRXs7OkyDwTtWeYVK6RggEUshUxueycMYs7e2rzzNm)
- **Full Source Code & Agency Pass ($950):** [Buy Instant Access](https://polar.sh/checkout/polar_c_g6UbasyYXi7DttF074yWBsTBzmTkm3bSZlNKw0VF5Uv)

---

## 📄 License

Distributed under commercial and developer license options. See [LICENSE](LICENSE.md) for details.
