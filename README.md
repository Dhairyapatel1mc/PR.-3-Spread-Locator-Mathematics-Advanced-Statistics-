# PR.-3-Spread-Locator-Mathematics-Advanced-Statistics-

<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:3776AB,100:F37626&height=200&section=header&text=Spread%20Locator&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Mathematics%20%26%20Advanced%20Statistics&descAlignY=55&descSize=18)

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&pause=1000&color=3776AB&center=true&vCenter=true&width=600&lines=Statistical+Distribution+Analysis;Bernoulli+%7C+Binomial+%7C+Poisson;Log-Normal+%7C+Power+Law+%7C+Box-Cox;Built+with+Python+%26+Jupyter+Notebook" alt="Typing SVG" />
</a>

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

</div>

---

## 📖 About the Project

**PR. 3 — Spread Locator** is a two-part statistics project that analyzes e-commerce customer transaction data to understand *how it's spread out* — its shape, variability, and underlying probability distribution. It combines statistical theory with hands-on Python analysis inside Jupyter notebooks.

| Part | Focus |
|------|-------|
| **Part A** | Foundational descriptive statistics and measures of spread on the transaction dataset |
| **Part B** | Distribution fitting & hypothesis testing — Bernoulli, Binomial, Poisson, Log-Normal, Power Law, Q-Q plots, Box-Cox transform, Z-scores, PDF/CDF analysis |

> 🏫 Prepared for **Red & White Skill Education** — Mathematics & Advanced Statistics module.

---

## 🗂️ Repository Structure

```
.
├── README.md                          # You are here
├── spread_locator_Part_A.ipynb        # Part A — Descriptive statistics & spread analysis
├── spread_locator_Part_B.ipynb        # Part B — Distribution fitting & hypothesis testing
├── spread_locator_dataset.xls         # Source transaction dataset
└── charts/                            # Exported chart images (PNG) from Part B
    ├── 01_bernoulli_binomial_fit.png
    ├── 02_poisson_fit.png
    ├── 03_lognormal_vs_powerlaw_fit.png
    ├── 04_qq_plot_normal.png
    ├── 05_boxcox_before_after_histograms.png
    ├── 06_qq_plot_boxcox_transformed.png
    ├── 07_zscore_threshold.png
    └── 08_pdf_cdf_lognormal.png
```

---

## 🎯 Part B — Tasks Covered

| # | Task | Method |
|---|------|--------|
| 1 | Transaction occurrence & weekly count | Bernoulli, Binomial |
| 2 | Transactions per customer per week | Poisson |
| 3 | Transaction amount modeling | Log-Normal, Power Law |
| 4 | Normality check | Q-Q Plot |
| 5 | Variance stabilization | Box-Cox Transform |
| 6 | Threshold probability analysis | Z-scores |
| 7 | Distribution visualization | PDF & CDF |
| 8 | Final results & conclusion | Summary Table |

---

## 📊 Dataset

| Column | Description |
|--------|-------------|
| `date` | Transaction date |
| `transaction_status` | Success / Fail outcome of the transaction |
| `transaction_count` | Number of transactions by a customer in a week |
| `transaction_amount` | Transaction value (₹) |

---

## 🔑 Key Findings

- **Transaction amounts** are best modeled by a **Log-Normal distribution** — the KS test fails to reject it (p ≈ 0.90), closely tracking both the empirical PDF and CDF.
- The **Power Law** fit is firmly rejected as a model for transaction amounts.
- The Q-Q plot confirms transaction amounts are **not Normally distributed** (right-skewed).
- The **Box-Cox transformation** meaningfully reduces skew, making the data suitable for models that assume Normality.

---

## ⚙️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)

</div>

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/Dhairyapatel1mc/PR.-3-Spread-Locator-Mathematics-Advanced-Statistics-.git
cd PR.-3-Spread-Locator-Mathematics-Advanced-Statistics-

# 2. Install dependencies
pip install numpy pandas matplotlib seaborn scipy jupyter

# 3. Launch Jupyter
jupyter notebook
```

Open `spread_locator_Part_A.ipynb` first, then `spread_locator_Part_B.ipynb`, and run all cells in order (**Cell → Run All**).

---

## 📌 Notes

- Every code cell that produces a graph is followed by a plain-English markdown explanation for readability.
- All Part B charts are also available pre-rendered as standalone PNGs in the `charts/` folder.

---

## 🌐 Connect with Me

<div align="center">

<!-- 🔧 Replace YOUR_USERNAME below with your actual handles -->

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Dhairyapatel1mc)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_USERNAME)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/YOUR_USERNAME)

</div>

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:F37626,100:3776AB&height=100&section=footer)

</div>
