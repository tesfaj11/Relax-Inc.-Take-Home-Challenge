# Relax-Inc.-Take-Home-Challenge
## Overview

This project is my solution to the Relax Take-Home Data Science Challenge. The goal of the challenge was to identify which users are most likely to become "adopted" based on their usage activity and profile information.

An **adopted user** is defined as someone who logged into the product on **three or more separate days within a 7-day period**.

---

## Files

- `takehome_user_engagement.csv`: Daily login activity for users.
- `takehome_users.csv`: User metadata, including signup source and account creation details.
- `Relax_Challenge_Solution.ipynb`: The main Jupyter Notebook containing my analysis, feature engineering, modeling, and conclusions.

---

## Key Steps

1. **Data Loading and Exploration**  
   I imported both datasets and explored their structure to understand the schema and missing values.

2. **Label Creation**  
   I wrote a function to identify users who logged in at least three times within a 7-day window and labeled them as adopted.

3. **Data Cleaning and Feature Engineering**  
   I merged the login activity with user metadata and prepared the features by removing irrelevant columns and encoding categorical variables.

4. **Modeling**  
   I trained a Random Forest Classifier to predict user adoption. I evaluated the model using classification metrics and examined the most important features influencing adoption.

5. **Insights and Recommendations**  
   I found that users invited through organizations or personal projects were more likely to become adopted. Being included in marketing campaigns also had a positive effect on adoption.

---

## Conclusion

I concluded that **social features (such as invites)** and **early engagement via marketing** play a significant role in long-term user adoption. I recommended optimizing onboarding, team invites, and engagement campaigns during the first week of a user’s experience.

