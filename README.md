# Personal Finance BI Report

## 📌 Project Overview
This project is one of my early Business Intelligence initiatives, focused on building a **personal finance reporting solution** using **Power BI**.

The main goal of the project is to visualize and analyze **personal income, expenses, profit, and balance**, while comparing **actual values against targets and expected amounts**.  
Despite its simplicity, the project applies solid BI fundamentals in data modeling, transformations, and metric calculation.

---

## 🎯 Project Objectives
- Monitor personal financial performance over time.
- Compare **actual vs expected** revenue, expenses, profit, and balance.
- Track budget, targets, and financial expectations.
- Provide clear visual indicators for positive and negative financial scenarios.
- Apply core BI concepts in modeling, calculations, and visualization.

---

## 🏗️ Architecture & Workflow
The project follows a structured BI workflow:

1. **Data Sources**
   - Excel files for financial records.
   - JSON files connected to Power BI for complementary data.

2. **Data Transformation**
   - Data preparation performed using **Power Query**.
   - Combination of multiple tables.
   - Column transformations and data cleansing.
   - Creation of a **calendar table** for time-based analysis.

3. **Data Modeling**
   - Implementation of a **Fact Constellation Schema** (Star Schema with shared dimensions).
   - Fact tables:
     - `Finanzas` (actual financial transactions)
     - `Expectativas` (targets, budget, and expected values)
   - Dimension tables:
     - `Calendario`
     - `Categorias`

4. **Analytical Layer**
   - DAX measures to calculate:
     - Actual amounts
     - Expected amounts
     - Variances between actuals and expectations

---

## 🧱 Data Model
The data model is designed to support comparative financial analysis:

### Fact Tables
- **Finanzas** – Stores actual revenue and expenses.
- **Expectativas** – Stores budget, targets, and expected values.

### Dimension Tables
- **Calendario** – Enables time-based analysis.
- **Categorias** – Groups financial records by category.

This structure enables consistent comparisons between actual and expected values.

---

## 📐 DAX & Calculations
The project uses **basic DAX measures** to:
- Calculate actual and expected financial metrics.
- Compare real values against targets.
- Support conditional formatting logic.

Although the DAX is intentionally simple, it is designed to be **clear, reusable, and filter-aware**.

---

## 📊 Data Visualization with Power BI
The Power BI report includes visualizations for:

- Revenue, expenses, profit, and balance.
- Actual vs expected comparisons.
- Budget and target monitoring.
- Conditional formatting to highlight:
  - Positive financial scenarios
  - Negative financial scenarios

The report focuses on clarity and usability rather than complexity.

---

## ⏱️ Data Refresh Monitoring
An additional table was created to compute and display:
- **Date and time of the latest data refresh**

This feature helps users understand data freshness and ensures transparency in reporting.


