# Dual-Mode Financial Distress Management System

A dual‑mode Streamlit app for **Personal Finance** and **Enterprise Risk Management (CAMELS)**.

---

## Features

- 💰 **PERSONAL FINANCE**
  - Daily dashboard with income vs spending
  - Manual entry of transactions
  - Screenshot OCR logic (from filename)
  - Monthly budget planner with sliders and visualizations
  - Generate and download HTML reports

- 🏢 **ENTERPRISE FINANCE**
  - CAMELS analysis (Capital, Assets, Management, Earnings, Liquidity, Sensitivity)
  - Small‑scale MSME / business loan analysis (DSCR, EMI, etc.)
  - Professional RBI‑style HTML reports (CAMELS + MSME)

---

## How to run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the app:
   ```bash
   streamlit run main.py
   ```

---

## Files
- `main.py` – main Streamlit application (includes both Personal and Enterprise modes)
- `requirements.txt` – required Python packages
