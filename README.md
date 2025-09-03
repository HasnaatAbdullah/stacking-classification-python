# Stacking For Classification with Python

I have completed this project to implement **Stacking Ensemble Learning** using **Python** and **Scikit-learn**.  
In this project, I used the **Wine Dataset** to predict the **class of wine** based on 13 chemical analysis features.  
I created this repository to share my work, code, and learning from this project.

---

## Project Overview
In this project, I applied **Stacking** for classification.  
Stacking is an ensemble learning method where I combined multiple machine learning models (**base learners**)  
and used a **meta-model** to make the final prediction.  
The goal was to improve accuracy by leveraging the strengths of different classifiers.

---

## Objectives
- Understand the concept of **Stacking Ensemble Learning**
- Implement stacking using **Scikit-learn**
- Use multiple classifiers and combine their predictions
- Evaluate model performance on the **Wine Dataset**

---

## About the Dataset
I used the **Wine Dataset** from **Scikit-learn**, which contains data collected from wines produced in the same region in Italy.  
The dataset includes **13 chemical analysis features** used to classify wines into **three cultivars**.

**Features:**
1. Alcohol  
2. Malic acid  
3. Ash  
4. Alcalinity of ash  
5. Magnesium  
6. Total phenols  
7. Flavanoids  
8. Nonflavanoid phenols  
9. Proanthocyanins  
10. Color intensity  
11. Hue  
12. OD280/OD315 of diluted wines  
13. Proline

**Target:** Wine class (3 cultivars)

---

## Installation
To run this project locally, clone the repository and install the required dependencies.

```bash
git clone https://github.com/your-username/stacking-for-classification.git
cd stacking-for-classification
pip install -r requirements.txt
