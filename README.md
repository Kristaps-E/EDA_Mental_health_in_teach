# Mental Health Survey Analysis (EDA)

This project explores a mental-health survey from Kaggle to understand who participated, which mental-health conditions are most common, and how respondents feel about discussing mental health at work. The goal is to support early product research for a mental‑health app.

---

## What This Project Does
- Loads and queries a historical tech‑industry mental‑health survey using SQLite  
- Cleans and standardizes key fields (age, gender, country, race)  
- Reports demographics and highlights dataset biases  
- Calculates prevalence of major mental‑health conditions with confidence intervals  
- Analyzes attitudes toward workplace mental‑health discussions  
- Provides data‑driven recommendations for product direction  

---

## Key Insights
- The dataset is **biased toward young white male U.S. tech workers**, limiting generalizability  
- Survey length strongly affects participation — **shorter surveys increase engagement**  
- ~33% report personal mental‑health challenges; ~50% report family history → strong need for **individual and family support features**  
- **Depression and anxiety** are the most common conditions; ADHD, PTSD, OCD, and BPD appear as secondary concerns  
- High non‑response to productivity‑related questions signals **workplace stigma** and a need for **privacy‑first product design**

---

## How It Works
The analysis relies on:

- **Pandas** for data manipulation  
- **NumPy** and **SciPy** for numerical analysis and confidence intervals  
- **SQLite** for structured querying  
- **Matplotlib** and **Seaborn** for visualizations  

Each notebook section explains the question being analyzed and includes a brief interpretation of results.

---

## How to Run It

```bash
pip install numpy pandas seaborn matplotlib scipy
jupyter lab
```

Open the notebook and run all cells.

---

## Suggestions for Future Work
- Obtain documentation from survey creators to clarify missing values and coding rules  
- Re‑analyze coded numerical fields once definitions are available  
- Integrate additional mental‑health datasets for broader market understanding  
- Apply predictive modeling and deeper statistical inference when more structured data is collected  
- Conduct new, targeted surveys across global tech companies to fill demographic gaps  

---

## Technologies Used
Python, Pandas, NumPy, SQLite, SciPy, Matplotlib, Seaborn
# EDA_Mental_health_in_teach
# EDA_Mental_health_in_teach
