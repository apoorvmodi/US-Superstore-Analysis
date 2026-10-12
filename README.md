# US Superstore Sales & Profitability Analysis

An exploratory data analysis (EDA) project analyzing sales, profitability, discount impacts, and customer segmentation across United States retail operations.

---

## Project Overview
This project explores the **US Superstore** dataset (9,994 transactions) to uncover operational inefficiencies, revenue drivers, and regional trends. The analysis answers 25 core business questions covering category performance, customer value, regional profitability, and discounting behavior.

---

## Key Findings & Business Insights

- **Overall Performance:**
  - **Total Revenue:** ~$2.30 Million ($2,297,200.65)
  - **Average Order Value (AOV):** $458.61 across 5,009 unique orders
  - **Unique Customer Base:** 793 customers

- **Category & Product Performance:**
  - **Top Category by Sales:** **Technology** ($836,154.02), followed closely by Furniture ($741,999.73) and Office Supplies ($719,046.90).
  - **Top Sub-Categories:** **Phones** ($330,007.10) and **Chairs** ($328,449.10) drive the largest volume.
  - **Best-Selling Product:** *Canon imageCLASS 2200 Advanced Copier* ($61,599.83).

- **Customer Segmentation:**
  - **Consumer Segment** drives the majority of revenue (**50.6%** / ~$1.16M), followed by Corporate (**30.7%**) and Home Office (**18.7%**).
  - **Top Lifetime Customer:** Customer `TC-20980` ($8,981.32 total profit generated).

- **Regional & Profitability Challenges:**
  - **Top Sales Region:** **West** ($725,457.76), followed by East ($678,781.30).
  - **Severe Profit Sinkholes:** Several states show heavy cumulative losses despite high sales volume, primarily driven by aggressive discounting:
    - **Texas:** -$25,729.32
    - **Ohio:** -$16,971.38
    - **Pennsylvania:** -$15,560.06
    - **Illinois:** -$12,607.94

---

## Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Environment:** Jupyter Notebook / JupyterLab

---

## Project Structure
```text
├── data/
│   └── US Superstore.csv        # Dataset source file
├── US Superstore Analysis.ipynb  # Primary Jupyter notebook
├── requirements.txt              # Python library dependencies
└── README.md                     # Project documentation
```

## Author
- **Apoorava Modi**

