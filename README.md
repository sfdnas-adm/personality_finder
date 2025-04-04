# Personality Predictor (Big Five)

This is a simple project where I analyzed a dataset based on the Big Five personality traits (Extraversion, Emotional Stability, Agreeableness, Conscientiousness, and Openness). 
The idea is to take raw survey data and generate a basic personality report using average scores.

---

## Dataset used

I used this dataset from Kaggle:  
(https://www.kaggle.com/datasets/tunguz/big-five-personality-test)

It contains answers to 50 questions (on a scale of 1 to 5) — 10 questions for each of the five personality traits.

---

## What I did in the notebook

1. **Loaded the dataset**  
   Used pandas to load the `.csv` file which is tab-separated.

2. **Computed scores**  
   For each trait like Extraversion, I calculated the average of the 10 related columns (EXT1 to EXT10, and similarly for EST, AGR, CSN, and OPN).

3. **Generated a text report**  
   I wrote a function that takes the average scores and creates a readable personality summary like:
   - “You are quite extraverted.”
   - “You are emotionally stable and resilient.”
   - etc.

   The function just uses basic `if-else` conditions to decide what kind of sentence to include.





