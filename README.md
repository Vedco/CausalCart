# CausalCart - Causal inference system for measuring the true impact of retail promotions on sales.


![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Causal Inference](https://img.shields.io/badge/Causal%20ML-DoWhy%20%7C%20EconML-green)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--learn-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

---

# 📌 Overview

**RetailCausalImpact-ML** is an advanced data science project designed to measure the *true impact of promotional campaigns on retail sales* using causal inference techniques.

Traditional machine learning models focus on prediction, but they fail to answer a critical business question:

👉 *Do promotions actually cause an increase in sales?*

This project addresses that gap by applying causal modeling frameworks such as **DoWhy** and **EconML** to estimate the *causal effect* of promotions, rather than simple correlations.

---

# 🎯 Problem Statement

Retail businesses frequently run promotions and discounts, but measuring their effectiveness is challenging.

Key question:

```text
Do promotional campaigns genuinely increase sales,
or are they just correlated with high-performing periods?
```

This project builds a causal inference pipeline to:

* identify treatment and outcome relationships
* control for confounding variables
* estimate the true causal impact of promotions on sales

---

# 🧠 Key Concepts Used

* Causal Inference vs Correlation
* Treatment & Outcome Modeling
* Confounding Variables
* Average Treatment Effect (ATE)
* Propensity Score Matching
* Counterfactual Analysis

---

# 🏗 Project Workflow

```text
Retail Data
     ↓
Data Preprocessing
     ↓
Define Treatment (Promotion) & Outcome (Sales)
     ↓
Causal Graph Modeling (DoWhy)
     ↓
Effect Estimation (EconML)
     ↓
Refutation & Validation
     ↓
Business Insights & Impact Analysis
```

---

# ⚙️ Methodology

### 1. Data Preparation

* Cleaned and structured retail dataset
* Handled missing values and anomalies
* Selected relevant features affecting sales

---

### 2. Treatment & Outcome Definition

```text
Treatment  → Promotion / Discount
Outcome    → Sales
```

---

### 3. Causal Graph Construction

Using **DoWhy**, a causal graph is defined to model relationships between:

* promotions
* customer behavior
* seasonal effects
* sales

---

### 4. Effect Estimation

Causal effects are estimated using:

* Propensity Score Matching
* Double Machine Learning (EconML)
* Regression-based estimators

---

### 5. Refutation Testing

The model validates causal assumptions using:

* placebo tests
* random common cause checks
* data subset validation

---

# 📊 Example Output

```text
Estimated Promotion Impact on Sales: +18%

Confidence Level: High

Insights:
Promotions significantly increase sales for
new and low-frequency customers, while
showing minimal impact on repeat buyers.
```

---

# 🛠 Tech Stack

Python
Pandas & NumPy
Scikit-learn
DoWhy
EconML
Matplotlib / Seaborn

---

# 📂 Project Structure

```text
RetailCausalImpact-ML/

notebooks/
    promotion_impact_analysis.ipynb

data/
    dataset.csv

models/
    causal_model_outputs

requirements.txt
README.md
```

---

# 🚀 How to Run

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/RetailCausalImpact-ML.git
cd RetailCausalImpact-ML
```

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Run Notebook

Open:

```text
promotion_impact_analysis.ipynb
```

Run all cells to reproduce results.

---

# 💡 Use Cases

This system can be applied in:

* Retail promotion analysis
* Marketing campaign effectiveness
* Pricing strategy optimization
* Customer targeting decisions
* A/B testing evaluation

---

# 🎯 Why This Project Matters

Most machine learning projects focus on prediction.

This project goes further by answering:

```text
"What actually causes business outcomes?"
```

It demonstrates how data science can drive **decision-making**, not just forecasting.

---

# 📈 Future Improvements

* Integrate real-time data pipelines
* Build a Streamlit dashboard for visualization
* Extend to uplift modeling
* Deploy as an API service
* Add multi-campaign analysis

---

# 📜 License

MIT License

Copyright (c) 2026 Ved Bhatt

---

# 👤 Author

Ved Bhatt
Master’s in Data Science – Florida State University



---

# ⭐ Final Note

This project showcases the ability to go beyond traditional machine learning by applying **causal reasoning to real-world business problems**, a highly valuable skill in modern data science roles.

---

