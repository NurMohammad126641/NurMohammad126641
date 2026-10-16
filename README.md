# Hi, I'm Nur Mohammad Siddiq 👋

**Data, BI & Automation Engineer** · Dhaka, Bangladesh

I build Python automation, data pipelines and AI-powered tools for fintech and microfinance. At **Padakhep Manabik Unnayan Kendra**, my systems serve **406 branches** and **4,000+ users**.

### 🚀 Highlights

- **Overdue Tracking Platform**: Django REST Framework, PostgreSQL, Celery and Redis. Replaced manual Excel workflows across 406 branches for 4,000+ users.
- **AI Analytics Chatbot**: Gemini with agentic workflows inside the reporting dashboard. Anyone can ask for a chart in plain English.
- **Branch Report Automation**: pulls all 406 branches in parallel with self-healing recovery into a ~730K-row, 100%-accurate master report. A 2–3 day job now takes under 2 hours.
- **Metabase Microfinance Dashboard**: live portfolio, collection and disbursement tracking on a partitioned PostgreSQL backend. One screen replaces 10+ Excel files.
- **n8n Workflows**: daily end-of-day reports to management, plus real-time alerts when a system goes down.
- **Central PostgreSQL Data Warehouse** *(in progress)*: Python ETL/ELT pipelines bringing multi-source financial data together.

> These systems run in production at work, so their code is private.

### 🧰 Open-source projects

| Project | What it shows |
|---|---|
| [**payments-ops-monitoring**](https://github.com/NurMohammad126641/payments-ops-monitoring) | Config-driven monitoring for a payments platform: parallel read-only PostgreSQL metrics feed Google Sheets and Looker Studio, with alerts when failures spike above the 4-week baseline. CI runs it against a real PostgreSQL. |
| [**redmine-issue-reporter**](https://github.com/NurMohammad126641/redmine-issue-reporter) | Weekly support-issue reporting from the Redmine API: pandas summaries per owner and week, team matrix, resolved-by stats, a Jinja2 HTML email and CSV exports. |
| [**sms-balance-monitor**](https://github.com/NurMohammad126641/sms-balance-monitor) | A Selenium bot that reads SMS-gateway balances (handles OTP, pop-ups and hover-only values) and sends email or Teams alerts. Its browser tests run against a fixture portal in CI. |
| [**nextjs-social-feed**](https://github.com/NurMohammad126641/nextjs-social-feed) | A full-stack Next.js 16 + Prisma social feed with secure cookie sessions, public and private posts, image uploads, nested comments and likes. |

The first three are public rewrites of tools I built at TallyKhata. They use synthetic data only, and every credential comes from environment variables.

Before Padakhep, at **TallyKhata (Progoti Systems)**, I supported Bangla QR payments for 100K+ merchants across NPSB, bKash, Rocket and 30+ banks, and built KPI and fraud-detection dashboards that improved visibility by 80%.

### 🛠️ Tech stack

| Area | Tools |
|---|---|
| Backend | Python, SQL, Django, Django REST Framework, REST APIs, Celery, Redis |
| Data | PostgreSQL, MySQL, BigQuery, ETL/ELT, Data Warehousing, Pandas |
| AI & Agents | Gemini API, LLM integration, Agentic workflows, n8n |
| Automation | Selenium, Playwright, BeautifulSoup, Headless browsers |
| BI | Power BI, Metabase, Looker Studio |
| DevOps & Testing | Docker, Gunicorn, Git, Postman, JMeter |

### 📜 Certifications

- Data Science & Machine Learning Using Python — BASIS (BITM), 2024
- The Data Engineer Bootcamp — Udemy, 2025
- Multi-Agent AI Systems — Udemy, 2026

### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/nur-mohammad-siddiq-9a73931b6) · rabbins.eng@gmail.com
