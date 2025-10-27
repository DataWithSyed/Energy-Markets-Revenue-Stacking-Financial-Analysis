# 💰 Revenue Stacking & Financial Analysis for Battery Energy Storage Systems (BESS)

This repository presents a detailed **Revenue Stacking and Financial Analysis** model for **Battery Energy Storage Systems (BESS)** in modern energy markets.
It demonstrates how different **revenue streams** — such as energy arbitrage, frequency response, and capacity services — can be combined to improve the financial performance of a battery storage project.

The notebook includes calculations, visualizations, and analytical frameworks used to evaluate **profitability, payback period, and return on investment (ROI)** for storage assets operating under multiple market conditions.

---

## 📘 Project Overview

Energy storage systems, particularly **Battery Energy Storage Systems (BESS)**, play a crucial role in modern power grids by providing flexibility and stability.
However, their **economic viability** depends on how effectively they participate in **multiple markets** — a concept known as **revenue stacking**.

This project explores how combining several **ancillary services** and **energy market activities** can increase financial returns for BESS operators.
It integrates both **technical operation data** and **financial modeling** to assess the profitability of different market participation strategies.

---

## ⚙️ Objectives

* To model and analyze **multiple BESS revenue streams**.
* To perform **financial performance evaluation** using real or simulated market data.
* To calculate **profitability metrics** such as Net Present Value (NPV), ROI, and Payback Period.
* To visualize and compare results across different **market service combinations**.

---

## 📖 Key Concepts and Definitions

### 🔋 Battery Energy Storage System (BESS)

A **BESS** stores electrical energy in battery cells and releases it when needed.
It can charge when electricity prices are low and discharge when prices are high, helping to balance the power grid and generate revenue.

### 💡 Revenue Stacking

**Revenue stacking** is the practice of combining several income streams from different grid services to maximize profits.
Instead of participating in just one market (e.g., energy arbitrage), a BESS might provide:

* **Energy Arbitrage** – Buying low, selling high.
* **Frequency Regulation** – Helping stabilize the grid frequency.
* **Capacity Services** – Providing reserve capacity for reliability.
* **Demand Charge Reduction** – Reducing energy costs for end-users.

### 💸 Financial Analysis Metrics

| Metric                            | Description                                                                                  |
| --------------------------------- | -------------------------------------------------------------------------------------------- |
| **NPV (Net Present Value)**       | Measures the total value of future cash flows discounted to the present.                     |
| **ROI (Return on Investment)**    | Calculates profit relative to total investment cost.                                         |
| **IRR (Internal Rate of Return)** | The discount rate that makes NPV equal to zero — used to evaluate investment attractiveness. |
| **Payback Period**                | Time required for the project to recover its initial investment.                             |

---

## 🧮 Methodology

1. **Data Input**

   * Market price data (energy, frequency, capacity).
   * BESS operational parameters: capacity, efficiency, degradation rate, etc.

2. **Revenue Stream Modeling**

   * Calculate potential earnings from each service:

     * Energy Arbitrage
     * Frequency Response
     * Capacity Market
     * Other Ancillary Services

3. **Stacking Strategy**

   * Combine revenue streams based on operational constraints and market participation rules.
   * Evaluate different combinations for optimal financial performance.

4. **Financial Evaluation**

   * Apply cost and revenue models to determine:

     * Annual cash flow
     * Total revenue and expenses
     * Profitability metrics (NPV, ROI, Payback)

5. **Visualization**

   * Plot cumulative profits, revenue breakdowns, and comparative analysis between stacking strategies.

---

## 📊 Example Outputs

* **Stacked Revenue Distribution Chart**
  Displays the contribution of each revenue source (e.g., arbitrage, regulation, capacity).
* **Cumulative Cash Flow Curve**
  Shows how investment returns accumulate over time.
* **Sensitivity Analysis**
  Tests how profitability changes with variations in electricity prices, battery size, or efficiency.

---

## 🧰 Technologies Used

* **Python 3.10+**
* **Pandas** – Data processing and financial calculations
* **Matplotlib / Seaborn** – Visualization
* **NumPy** – Numerical computation
* **Jupyter Notebook** – Interactive analysis

---

## 🚀 How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/Revenue-Stacking-Financial-Analysis.git
   cd Revenue-Stacking-Financial-Analysis
   ```

2. **Install Required Packages**

   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Notebook**

   ```bash
   jupyter notebook "Revenue Stacking & Financial Analysis.ipynb"
   ```

---

## 🔒 Data Notice

> ⚠️ **Note:**
> The dataset used for this analysis is **confidential** and cannot be shared publicly.
> The repository includes **code, methodology, and visualizations only**.
> You can adapt the code to your own datasets for experimentation or educational use.

---

## 💡 Future Work

* Incorporate **battery degradation cost modeling**.
* Add **Monte Carlo simulations** for market uncertainty.
* Integrate **real-time optimization** for stacking strategy.
* Build a **dashboard (Plotly / Dash)** for interactive financial exploration.

---

## 📜 License

This project is released under the **MIT License**.
You are free to use, modify, and distribute it with attribution.

---
