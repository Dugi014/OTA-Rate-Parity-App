\# 🏨 OTA Rate Parity Tracker

This repository contains a public demo version of an internal learning prototype.
All data, screenshots, and examples are synthetic and do not represent real Vacatia systems.

\### AppSheet + Google Workspace Automation (Learning Prototype)



A no‑code/low‑code prototype designed to automate OTA rate parity checks using the Google Ecosystem.

This project demonstrates how AppSheet, Google Sheets, Apps Script, and Google Drive can work together to streamline parity auditing workflows, reduce manual reporting, and centralize visual evidence.



This public version uses \*\*synthetic demo data\*\* and does \*\*not\*\* contain any internal company information.



\---



\## 🏛️ System Architecture



The system is built using Google Workspace tools and follows a modular, event‑driven workflow:



\- \*\*Gmail → Apps Script\*\*

&#x20; Automated ingestion of OTA parity emails using simple triggers.



\- \*\*Apps Script → Google Sheets\*\*

&#x20; Parsed data is normalized into a structured sheet for downstream use.



\- \*\*Google Sheets → AppSheet\*\*

&#x20; AppSheet provides a mobile‑friendly UI for reviewing parity issues.



\- \*\*AppSheet → Google Drive\*\*

&#x20; Users can upload screenshots or evidence files directly from the app.



\- \*\*(Future) Google BigQuery\*\*

&#x20; Planned migration to a scalable warehouse for historical analysis.



\- \*\*(Future) Looker Studio\*\*

&#x20; Planned dashboards for parity trends, channel performance, and alerts.



\---



\## 🔄 Data Flow Overview



1\. OTA parity email arrives in Gmail.

2\. Apps Script parses the email body and extracts key fields.

3\. Parsed data is written into a structured Google Sheet.

4\. AppSheet syncs automatically and displays new entries.

5\. User uploads screenshots/evidence via AppSheet → stored in Drive.

6\. AppSheet links Drive files back to the record.

7\. (Future) Data flows into BigQuery for long‑term storage.

8\. (Future) Looker Studio dashboards visualize trends and anomalies.



\---



\## 🧩 Current Features



\### ✔ Email Automation

\- Basic Gmail trigger

\- Apps Script parsing

\- Automatic row creation in Google Sheets



\### ✔ AppSheet UI

\- Mobile‑friendly interface

\- Parity review workflow

\- Status fields (Open, Resolved, Needs Review)



\### ✔ Evidence Management

\- Screenshot upload via AppSheet

\- Files stored in Google Drive

\- Automatic file linking



\### ✔ Synthetic Demo Dataset

\- Fake property names

\- Fake OTA channels

\- Fake rate values

\- Fake email examples



\---



\## 🚧 Planned Enhancements (Roadmap)



\### 🔜 Data \& Analytics

\- BigQuery warehouse integration

\- SQL normalization

\- Partitioned tables for historical parity trends



\### 🔜 Dashboards

\- Looker Studio visualizations

\- Channel mix analysis

\- Threshold‑based alerting



\### 🔜 Automation

\- Cloud Run Functions for scheduled parity checks

\- AI agent for parity anomaly detection

\- Automated Slack/Gmail notifications



\### 🔜 AppSheet Improvements

\- Multi‑property filtering

\- Role‑based access

\- Enhanced evidence viewer



\---



\## 🧪 Demo Dataset (Synthetic)



The demo version uses a safe, synthetic dataset:



| Property       | OTA Channel | Rate | Parity Status | Screenshot |

|----------------|-------------|------|----------------|------------|

| Demo Resort A  | Booking.com | 149  | Underpriced    | link       |

| Demo Resort B  | Expedia     | 179  | Overpriced     | link       |

| Demo Resort C  | Hotels.com  | 129  | Matched        | link       |



This dataset is included only for demonstration and testing.



\---



\## 📸 Screenshots



Screenshots included in this repository are:



\- AppSheet demo UI

\- Google Drive upload demo

\- Apps Script logs (synthetic)

\- Google Labs screenshots



No internal or confidential data is used.



\---



\## 📂 Repository Structure





\---



\## ⚠️ Disclaimer



This project is a \*\*learning prototype\*\* built using synthetic demo data.

It does \*\*not\*\* contain any internal company information, real OTA rates, or real property data.



\---



\## 📚 Learning Stack



This project was built while learning:



\- AppSheet (No‑Code App Development)

\- Google Sheets (Data Modeling)

\- Google Apps Script (Automation)

\- Google Drive (File Management)

\- Gmail Triggers

\- BigQuery (Beginner)

\- SQL (Beginner)

\- Looker Studio (Basic Dashboards)



\---



\## 🎯 Purpose



This project is part of a broader learning journey toward:



\- Commercial Systems

\- RevOps

\- Revenue Operations

\- BI \& Automation

\- Google Cloud ecosystem development



It will evolve over time as new skills are acquired.

