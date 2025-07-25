# 🌍 Global Suicide Rate Analysis (1979–2016)

A beginner-friendly data science project exploring suicide trends across countries, age groups, and genders using a real-world dataset from the World Health Organization (WHO).

---

## 📌 Project Overview

This project analyzes global suicide data from **141 countries** between **1979 and 2016** to identify key trends and risk factors.  
The goal is to understand which populations are most affected and why — through data cleaning, visualization, and storytelling.

---

## 🧰 Tools & Libraries Used

- **Language:** Python 3
- **Notebook:** Jupyter
- **Libraries:**  
  - `pandas` – data handling  
  - `matplotlib`, `seaborn` – visualizations  
  - `numpy` – numerical support

---

## 📊 Dataset Information

- **Source:** WHO Global Suicide Statistics  
- **Records:** 43,776  
- **Features:**  
  - `country`, `year`, `sex`, `age`  
  - `suicides_no`, `population`

We engineered a new column:
- **`suicide_rate_per_100k`** = (suicides_no / population) × 100,000

---

## 📈 Visualizations

- 📉 Suicide trends over time
- 📊 Suicide rates by gender
- 📊 Suicide rates by age group
- 🔥 Heatmaps of suicide rates across **countries & age**, separately for **males** and **females**

---

## 🔍 Key Insights (Humanized)

### 👴 1. Older adults face the highest risk  
> People over 75 had the **highest suicide rates** globally. This highlights how **loneliness, illness, and lack of social support** in old age can heavily impact mental health.

---

### 👨 2. Men are more affected than women  
> Across all countries and age groups, **men are 3–4x more likely** to die by suicide than women. Cultural norms and emotional stigma may prevent many men from seeking help.

---

### 📉 3. The world is improving, but slowly  
> Suicide rates peaked in the **1990s**, but declined gradually. Still, recent years show **fluctuations**, proving that global progress isn't even or guaranteed.

---

### 🌍 4. Country and culture matter  
> Countries like **Russia, Lithuania, and Kazakhstan** show **much higher suicide rates**, especially for older men. Economic stress, healthcare access, and cultural stigma play key roles.

---

### 🧒 5. Youth suicide is rare — but real  
> While the **5–14 age group** has the lowest numbers, even a few cases are heartbreaking. This shows the need for **early emotional support** in schools and homes.

---

## 🧠 What I Learned

- How to work with real-world messy data
- How to engineer new insights with calculated fields
- How to use **data visualization to tell powerful stories**
- How mental health is deeply shaped by age, gender, and geography

---
