# Stack Overflow 2025 Data Scientist Salary Analysis

This repository contains a **data analysis project** exploring the salaries, education levels, and career factors of Data Scientists using the 2025 Stack Overflow Developer Survey.

## 📊 Project Overview

- Dataset: Stack Overflow Developer Survey 2025 (~50,000 responses)
- Focus: Data Scientists, AI/ML Engineers, Data Engineers, and Data/Business Analysts
- Goals:
  1. Analyze the distribution of Data Scientists among developers.
  2. Examine salary differences by occupation.
  3. Explore the education levels of Data Scientists with >1 year experience.
  4. Build models to predict Data Scientist salaries based on experience, education, location, and skills.

---

## 📈 Key Findings

1. **Rarity of Data Scientists**: Only ~1.17% of respondents are Data Scientists or related roles.  
2. **Salary**: Data Scientists tend to earn slightly more than Full-Stack Developers.  
3. **Education**: 
   - 47% have a Master's degree  
   - 24% have a Bachelor's degree  
   - 23% have a PhD  
   - Only 4% without a Bachelor's or above  
4. **Salary Influencers**:
   - Working in advanced countries (e.g., USA)
   - More work experience
   - Higher education level
   - Knowledge of Snowflake, Databricks SQL, Microsoft SQL, Brew, and Bash Shell

---

## 💻 How to Run

> ⚠️ Note: The original dataset `survey_results_public.csv` is tracked using **Git LFS**.  
> You need Git LFS installed to clone this repository with the dataset:
> 
> ```bash
> git lfs install
> git clone https://github.com/weihuapan00/stackoverflow-2025-ds-salary.git
> python -m venv venv
> source venv/vin/activate # MacOS/ Linux
> venv\Scripts\activate # Windows
> pip install -r requirements.txt
> ```