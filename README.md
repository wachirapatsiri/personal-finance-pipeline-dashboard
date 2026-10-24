# 💰 Personal Finance Data Pipeline & Interactive Dashboard

## 📌 Project Overview
An automated data pipeline and interactive Gradio dashboard designed to clean, consolidate, and visualize messy personal transaction records for optimized budget planning.

## 🎯 Business Problem
Tracking personal finances manually through raw bank exports is time-consuming and prone to manual entry errors. Merchant names are often spelled inconsistently, making accurate monthly spending analysis difficult. 

## 🛠️ Solution & Action (Tech Stack: Python, Pandas, TheFuzz, Gradio)
* **Data Extraction & Cleaning:** Built a Python script to ingest and standardize **2,188** raw transaction records, handling missing values and date reformatting.
* **Fuzzy Matching:** Implemented Levenshtein distance algorithms (via `thefuzz` library) to automatically detect and group misspelled or inconsistent merchant names.
* **Deployment:** Designed a user-friendly web UI using Gradio, allowing users to instantly generate categorized spending visualizations.

## 📈 Key Results
* Successfully consolidated **400** messy, raw merchant names into **10** clean, unique entities, eliminating manual data entry tasks.
* Delivered a real-time tracking dashboard that categorizes income and expenses, enabling clear visibility into monthly cash flow.

## 💻 Live Demo & UI
<img width="1458" height="769" alt="image" src="https://github.com/user-attachments/assets/6f857507-0cee-4608-8d3e-16894d4b00b4" />

