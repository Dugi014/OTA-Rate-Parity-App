# 🏨 OTA Rate Parity Tracker (Learning Prototype)
### AppSheet + Google Workspace Automation · Synthetic Demo Version

This repository contains a **public-safe learning prototype** of an OTA Rate Parity Tracker built using the Google Workspace ecosystem.  
It demonstrates how **AppSheet**, **Google Sheets**, **Apps Script**, and **Google Drive** can work together to automate parity auditing workflows, reduce manual reporting, and centralize visual evidence.

All data, screenshots, and examples in this repository are **synthetic** and do **not** represent any real company systems, rates, or properties.

---

## 🏛️ System Overview

This project showcases a modular, event-driven workflow designed to automate OTA parity checks:

- **Gmail → Apps Script**  
  Automated ingestion of parity-related emails using simple triggers.

- **Apps Script → Google Sheets**  
  Parsed data is normalized into a structured sheet for downstream use.

- **Google Sheets → AppSheet**  
  AppSheet provides a mobile-friendly UI for reviewing parity issues.

- **AppSheet → Google Drive**  
  Users upload screenshots or evidence files directly from the app.

- **(Future) BigQuery Integration**  
  Planned migration to a scalable warehouse for historical analysis.

- **(Future) Looker Studio Dashboards**  
  Planned visualizations for parity trends, channel performance, and alerting.

---

## 🔄 Data Flow Diagram

```text
1. OTA parity email arrives in Gmail
2. Apps Script parses email → extracts key fields
3. Parsed data written into Google Sheets (normalized)
4. AppSheet syncs → displays new entries
5. User uploads screenshots → stored in Google Drive
6. AppSheet links Drive files back to the record
7. (Future) Data flows into BigQuery for long-term storage
8. (Future) Looker Studio visualizes trends & anomalies
