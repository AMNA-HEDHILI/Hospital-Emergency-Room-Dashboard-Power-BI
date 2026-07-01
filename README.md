# Hospital-Emergency-Room-Dashboard-Power-BI

A clean, end-to-end Power BI dashboard designed to transform raw emergency room logs into intuitive operational insights. This project focuses on production-ready business intelligence development principles: intuitive UI/UX design, high data scannability, and clear data storytelling.

Instead of overcomplicating the analytics with unnecessary code, this solution prioritizes a highly organized multi-page interface that allows healthcare managers to navigate from high-level trends down to granular record audits effortlessly.

---

## 📸 Interface Analytics Views

### 1. Monthly Review
Utilizes the standardized core dashboard layout, explicitly scoped to short-term, granular monthly intervals (e.g., Month-to-Date view) to track daily trend densities, target variations, and immediate operational bottlenecks.
* **Visual Asset:** `monthly review.png`

### 2. ER Overview
Shares the identical structural design framework as the Monthly Review to maintain visual consistency, but operates as a macro-level longitudinal dashboard configured to analyze historical baseline shifts, demographic distributions, and long-term macro-level trends over the complete 19-month timeline.
* **Visual Asset:** `ER overview.png`

### 3. Patient Details
A granular lookup interface optimized for audit-level operations. Frontline supervisors can use this interactive matrix to filter individual patient records, wait-time categories, and triage pathways.
* **Visual Asset:** `Patients Details.png`

### 4. Key Takeaways
An integrated text narrative system that leverages built-in text-generation features to surface primary operational discoveries and data highlights directly on the canvas for busy stakeholders.
* **Visual Asset:** `Keytakeaways.png`

---

## 🛠️ Core Implementation & Design Details

* **App-Style Interface Layout:** Engineered a custom Left Navigation Menu utilizing reactive button states (Default, Hover, Active) to transform a standard report file into a modern web-app experience.
* **Inline KPI Conditional Alerts:** Configured structural formatting rules to embed status direction indicators (`▲`/`▼`) directly inside the card headers to optimize canvas real estate.
* **Chronological Sorting Logic:** Implemented background logical sorting indices to guarantee that multi-dimensional time matrices and day blocks align chronologically (Monday to Sunday) rather than alphabetically.
* **Production-Ready Theme:** Applied a cohesive, accessible Clinical Teal palette optimized for clarity and eye-strain reduction in live operational tracking environments.

---

## 📊 Dataset Specifications
* **Source:** Raw flat CSV file containing emergency room logs.
* **Volume:** 9,216 unique patient cases indexed across a 19-month timeline.
* **Data Prep:** Cleaned, formatted data types, and isolated a dedicated, continuous calendar system for robust filtering.

---

## ⚙️ How to Explore the Project
1. Clone this repository to your local machine.
2. Ensure you have the latest version of **Power BI Desktop** installed.
3. Open `Hospital Emergency Room Dashboard.pbix` to interact with the visual layers.
