# Perceived AI Threat by Coders

 This project analyzes how software developers perceive AI as a threat to their jobs, using data from the 2024 Stack Overflow Developer Survey.

---

## 🔍 Overview

This project investigates the perception of AI as a job threat among coders across different countries and experience levels. It aims to uncover whether factors like professional coding experience, age, education, and trust in AI affect how threatening developers find AI technologies.
The problem addresses growing concerns in the tech industry about AI’s impact on software jobs. This work is useful for researchers, policymakers, and organizations interested in workforce adaptation and AI acceptance. The project combines survey data analysis with multilevel statistical modeling.
> This is a data analysis and social research project focused on understanding perceptions of AI threat in the developer community.

---

## 🛠️ Tech Stack

- R
- Packages: lme4, glmmTMB, sjPlot, broom, gtsummary, dplyr, ggplot2  
- Data source: Stack Overflow Developer Survey 2024 (CSV)  
- Quarto

---

## 🚀 Features

- Multi-level mixed-effects regression modeling with varying intercepts by country  
- Comparative analysis between linear and logistic models on binary outcome  
- Visualizes country-level differences in AI threat perception  
- Handles survey data cleaning and recoding of categorical variables  
- Integrates demographic and attitudinal predictors for deeper insights

---

## 📈 Results

- Linear multilevel model showed better fit metrics with a linear model than logistic model despite binary outcome.  
- Years of coding experience had negligible negative effect on perceived threat.  
- Older coders more likely to perceive AI as a threat.  
- Higher education correlated with reduced perceived threat.  
- Trust in AI’s complex task capability unsurprisingly linked to higher threat perception.  
- Some geographic clustering found, but no clear global patterns.


---

## 🧠 What I Learned

- How to handle large survey datasets with complex coding schemes  
- Implementing multilevel modeling with varying intercepts in R  
- Evaluating model performance and choosing between linear vs logistic frameworks for binary outcomes  
- Interpreting effects of demographic and attitudinal variables on social perception  
- Visualizing cross-national differences in perception data

---

## 📦 Installation & Usage

```bash
git clone https://github.com/NathanielH-snek/StackOverflowAISentiment.git
cd StackOverflowAISentiment
```
Unzip data files
Open the project qmd file in Rstudio
Install packages as prompted
Run 
