# Urban Scooter – Final Project (Sprint 9)

# 🗓️Project Details

- **Type:** QA Bootcamp Final Capstone (TripleTen LatAm)
- **Execution Date:** June 2025
- **Status:** Completed and Approved
- **Testing Type:** Comprehensive Multi-Platform QA – Web + Mobile + API

---

# 📌Project Overview
This is the culminating project of the TripleTen QA Engineering Bootcamp, fully testing the Urban Scooter application (electric scooter rental service).
The project integrates all learned skills: requirements analysis, test design (mind maps, checklists, ECP/BVA/decision tables), execution across web, mobile, and API layers, defect reporting, and optimization for efficient coverage.

# Scope (per instructions):
- **Task 1 – Web App:** Mind map for order form, checklist for "Order Status" screen, validation tables for order form fields, full functional testing (excluding landing page) using Figma designs.
- **Task 2 – Mobile App:** Test cases for bold-highlighted features on Android (UI/functional flows, error handling).
- **Task 3 – API:** Checklist for key backend endpoints (validated via Postman/DevTools).

No complete app testing — focused on scoped requirements.

---

# 🛠️Tools & QA Techniques
# Tools Used:

- **Postman / Browser DevTools** – API requests, network inspection, URL validation
- **Android Emulator** – Mobile app execution and testing
- **Figma** – UI design reference for visual validation
- **Draw.io** – Mind mapping for requirements visualization
- **Google Sheets** – Checklists, validation tables, test cases, execution results, bug tracking
- **Jira** – Standard defect reporting (used for 35 bug documentation)

# QA Techniques Applied:

- Mind mapping for requirement visualization (order form logic)
- Checklist & test case design (atomic blocks, objects of test)
- Equivalence Class Partitioning (ECP), Boundary Value Analysis (BVA), Decision Tables
- Positive/Negative/Edge case & exploratory testing
- Test suite optimization (minimal effective coverage)
- Full defect lifecycle: identification, reproduction, severity rating

---

# 🌍Test Environment

- **Web:** Browser-based Urban Scooter client (noted server/DB/API info)
- **Mobile:** Android Emulator (Android 9.0)
- **API:** Backend endpoints (requirements from backend specs)

---

# 📋Test Artifacts
All deliverables (mind map, checklists, validation tables, test cases, execution results, bug reports) are compiled in the main Google Sheet:

- **Full Capstone Artifacts:** Web checklists/validation, Mobile test cases, API checklist
- **Google Sheets:** https://docs.google.com/spreadsheets/d/1LTpzLHCnDSOU7zk92mR5PJeIHhO68ZUM/edit?usp=sharing&ouid=110773353333564353107&rtpof=true&sd=true

# Key elements:

- **Task 1:** Mind Map (Urban Scooter.drawio) + Checklist (Order Status) + Data Validation Tables (Order Form fields)
- **Task 2:** Test Cases (bold-highlighted mobile features)
- **Task 3:** API Checklist (backend endpoints like POST /api/v1/courier, DELETE /api/v1/courier/:id, PUT /api/v1/orders/cancel, GET /api/v1/orders/track)

---

# 🐞Bug Reporting
35 defects were documented in Jira-style format within the sheet, including:

- Steps to reproduce
- Expected vs. Actual results
- Severity/priority
- Screenshots/evidence

- **Common defect categories:** Input validation failures (e.g., length limits, special chars), UI mismatches vs Figma, API response errors (e.g., incorrect status codes, missing fields), mobile notification issues.
- **Bug links:** FPUS-1 to FPUS-35 (Atlassian Jira).

---

# 📊Test Metrics

- **Total Test Cases/Checklist/Validation Items (across Task 1–3):** 199 (61 checklist + 94 validation + 8 test cases + 36 API checklist)
- **Passed:** ~149 (approx 75% pass rate)
- **Failed / Bugs Reported:** 35 real defects identified
- **Coverage:** Complete for scoped requirements (web order flows/status, mobile interactions, API creation/deletion/cancelation/track)
- **Omitted Items:** 8 (non-critical or dependent on untriggered scenarios)

---

# 📸Visual Evidence

- **Mindmap**
https://drive.google.com/file/d/1P_bEQsEMQQ-2uEiii_NTWA1oCa9qF2H4/view

- **Jira Kanban Board**
<img width="1362" height="707" alt="image" src="https://github.com/user-attachments/assets/6d0897c2-567d-4729-8377-fe3fc8df3303" />

- **Bug Example**
<img width="1112" height="866" alt="image" src="https://github.com/user-attachments/assets/ab2f06e2-da6a-4681-89f2-04e87e27fa20" />
- **Bug Evidence**
<img width="738" height="608" alt="image" src="https://github.com/user-attachments/assets/b6ae1662-3cc0-4075-8d6d-8cbd9f6bdc0f" />

---

# 🎯Key Takeaways

- Synthesized bootcamp knowledge into a multi-platform capstone (web + mobile + API on same app)
- Demonstrated advanced test design (mind maps, ECP/BVA, decision tables), optimization, traceability, and high defect detection
- Proven readiness for junior QA roles with cross-platform experience and full lifecycle handling

---

## 🌐 Language Note (Important)

> ⚠️ **Documentation Language Notice**  
All test cases and bug reports for this project were originally created and delivered in **Spanish**, as required by the project guidelines at the time of execution.

To preserve authenticity and avoid misinterpretation, the original documents have been kept in Spanish.  
