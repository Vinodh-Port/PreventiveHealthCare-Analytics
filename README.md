# PreventiveHealthCare-Analytics

An end-to-end data analytics and business intelligence project automating healthcare data pipelines to evaluate user registrations, nutrition engagements, and dietary preferences. This repository demonstrates data extraction, relational modeling, and advanced business logic visualization.

---

## 📊 Dashboard Insights & Performance Metrics

The analytical dashboard tracks high-level engagement metrics for the "Nutritionists vs Users" program across several core segments:

### 1. High-Level Dataset KPIs
* **Total Registrations:** 1.020456M (1,020,456 unique platform users).
* **Total Food Entries Recorded:** 1.966K unique diet log inputs.
* **Account Creation Pipeline:** Historical user tracing map from 17-09-2020 to 31-03-2026.

### 2. Gender Demographic Split
* **Male Users:** 777,930 registrations (76.23% profile share).
* **Female Users:** 242,526 registrations (23.77% profile share).
* *Insight: The dashboard shows a dominant male user acquisition rate, indicating a strategic avenue to optimize targeted health campaigns for female audiences.*

### 3. User Acquisition by Source (Registered Users)
Tracks the efficacy of different enrollment channels:
* **Target Group:** 962,435 registrations (95.11% acquisition dominance).
* **General Public:** 19,238 registrations (1.90%).
* **HFL:** 17,674 registrations (1.75%).
* **Social Media:** 11,326 registrations (1.12%).
* **Collaborations / Institutional / NTR Trust:** Combined remaining trailing margin (<0.20%).

### 4. Food Entries Breakdown by Channel
Evaluates where active food logging behavior originates:
* **Target Group:** 870 entries (44.25% logging share).
* **Social Media:** 587 entries (29.86% logging share).
* **General Public:** 481 entries (24.47% logging share).
* **Collaborations / Institutional / NTR Trust:** 28 remaining entries.

### 5. Dietary Preferences
* **Non-Veg:** 520,466 users (Highest consumer segment).
* **Veg:** 23,260 users.
* **Eggitarian:** 263 users.
* **Vegan:** 6 users.

### 6. Top Clinical & Health Condition Profiles
Voluntary user health matrices listed by risk and evaluation frequencies:
* **Well Being:** 309,988 cases
* **Weight Loss:** 248,963 cases
* **Diabetes:** 42,159 cases
* **Weight Gain:** 29,131 cases
* **Hypertension:** 27,751 cases
* **Gastritis:** 9,072 cases
* *Other tracked fields include: Thyroid (6,170), Type 1 Diabetes (3,492), Cholesterol (2,925).*

---

## 🛠️ Tech Stack & Analytical Ecosystem

* **Data Extraction & Ingestion (ETL):** Microsoft Excel and raw CSV formatting structures are utilized as primary inputs.
* **Relational Database Server:** Microsoft SQL Server Management Studio (SSMS).
* **Business Intelligence & Visualization:** Power BI Desktop transforms transactional health logs into complex star schemas, custom DAX metrics, and interactive visuals.

> 🔒 **Data Privacy & Compliance Note:** Due to strict data privacy policies and compliance constraints (NDA), the raw datasets and original `.pbix` configuration files are restricted. Only high-level dashboard architectures and verified data visualization structures are documented.
