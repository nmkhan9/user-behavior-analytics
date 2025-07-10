# 🧠 RFM Customer Segmentation

This project applies the **RFM (Recency, Frequency, Monetary)** model to segment customers based on purchasing behavior. The goal is to help businesses better understand their customer base and design more targeted, data-driven marketing strategies.

---

## 📊 What is RFM?

The RFM model evaluates customers based on three dimensions:

- **Recency (R):** How recently a customer made a purchase  
- **Frequency (F):** How often a customer makes purchases  
- **Monetary (M):** How much money the customer spends in total

Each customer receives a score from **1 (lowest)** to **5 (highest)** on each of the three metrics. These are combined to form a 3-digit **RFM Score** (e.g., `555`, `311`), which is then used to classify customers into distinct segments (e.g., "Champions", "Loyal", "At Risk", etc.).

---

## 📁 Project Structure

- `data/` — Raw and processed transaction data  
- `notebook/` — Python scripts and Jupyter notebooks for RFM calculation  
- `powerbi/` — Power BI `.pbix` report for customer segmentation  
- `reports/` — Exported reports (PDF/images) from the Power BI dashboard  
- `README.md` — Project overview and instructions  
