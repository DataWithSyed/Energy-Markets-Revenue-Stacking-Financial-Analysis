# 📈 Updates: Revenue Stacking & Financial Analysis — Sensitivity Analysis Extension

This repository expands upon the original **Revenue Stacking & Financial Analysis** project by introducing an advanced **Sensitivity Analysis module**.
The new notebook — `Revenue Stacking & Financial Analysis - Sensitivity Analysis.ipynb` — builds on the original financial modeling framework to explore **how changes in key variables affect project profitability** for Battery Energy Storage Systems (BESS).

---

## 🔄 What’s New in This Version

### 1. 🔍 Sensitivity Analysis Integration

A new section has been added to assess the **impact of input variable uncertainty** on financial metrics such as **Net Present Value (NPV)**, **ROI**, and **Payback Period**.

#### Parameters Tested:

* **Energy Price Variability:** Evaluates profitability across different wholesale market price scenarios.
* **Battery Efficiency:** Tests system performance under different charge/discharge efficiency rates.
* **Investment Cost:** Analyzes how CapEx fluctuations influence financial feasibility.
* **Revenue Stream Contribution:** Measures how changing revenue proportions (e.g., arbitrage vs. frequency response) affects total returns.

#### Key Methods:

* Parameter sweeping using `for` loops and controlled input perturbations.
* Visualization of results through multi-scenario comparative plots.
* Identification of **most sensitive financial drivers** impacting overall profitability.

---

### 2. 📊 Enhanced Visualization

The new notebook includes improved visualization features for financial interpretation:

| Visualization Type             | Description                                                           |
| ------------------------------ | --------------------------------------------------------------------- |
| **Tornado Chart**              | Ranks key parameters by their impact on NPV or ROI.                   |
| **Scenario Comparison Plots**  | Displays performance across multiple what-if scenarios.               |
| **Surface Plot (optional)**    | Visualizes two-variable sensitivity interactions.                     |
| **Profit Distribution Graphs** | Illustrates expected return ranges under uncertain market conditions. |

These visualizations help analysts quickly identify which input assumptions have the greatest effect on investment outcomes.

---

### 3. 💸 Extended Financial Model Features

Additional financial enhancements include:

* Dynamic recalculation of **NPV, ROI, and Payback Period** across multiple test cases.
* Optional inclusion of **battery degradation cost** in profitability estimates.
* Ability to model **multi-year revenue projections** under variable market conditions.

---

### 4. 🧠 Analytical Insights

The sensitivity module helps answer strategic questions such as:

* *How sensitive is my ROI to changes in battery cost?*
* *What happens if energy market prices fall by 15%?*
* *Which parameter has the highest influence on NPV?*

These insights are crucial for **investment risk assessment** and **policy evaluation** in renewable energy and storage economics.

---

## ⚙️ Methodological Additions

| Step                    | Description                                              |
| ----------------------- | -------------------------------------------------------- |
| **Parameter Variation** | Define a range for each financial or technical variable. |
| **Model Iteration**     | Re-run financial calculations for each variation.        |
| **Result Aggregation**  | Store NPV/ROI results in dataframes for analysis.        |
| **Visualization**       | Generate comparative plots to interpret results.         |

Example (pseudo-code snippet):

```python
for price_factor in [0.8, 1.0, 1.2]:
    adjusted_prices = base_prices * price_factor
    npv = calculate_npv(adjusted_prices, other_parameters)
    results.append({'Price Factor': price_factor, 'NPV': npv})
```

---

## 🧮 Outputs Added

* **Sensitivity Table** showing variable ranges and corresponding financial outcomes.
* **NPV vs. Parameter Curves** for trend visualization.
* **Profitability Risk Summary** highlighting optimal and critical scenarios.

---

## 🚀 How to Use the Sensitivity Analysis Notebook

1. **Ensure the base financial model notebook is set up.**

   * `Revenue Stacking & Financial Analysis.ipynb`

2. **Run the extended notebook:**

   ```bash
   jupyter notebook "Revenue Stacking & Financial Analysis - Sensitivity Analysis.ipynb"
   ```

3. **Adjust parameter ranges** in the configuration section to test different assumptions.

4. **View visual outputs** for comparative scenario insights.

---

## 📊 Example Visualization

*(Placeholder for tornado chart / parameter sensitivity figure)*

```
| Parameter             | Impact on NPV |
|------------------------|---------------|
| Energy Price (+10%)    | +12%          |
| Battery Efficiency (-5%) | -8%         |
| Investment Cost (+15%) | -14%          |
```

---

## 💡 Purpose of the Update

This enhancement provides **decision support** for:

* **Investors** assessing risk-return trade-offs.
* **Policy analysts** modeling incentive impacts.
* **System planners** evaluating robustness of BESS business models.

By quantifying uncertainty, the model transitions from a static financial tool into a **dynamic simulation framework** for real-world investment planning.

---

## 📜 License

This update follows the same licensing as the main repository — **MIT License**.

---
