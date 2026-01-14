# Ad-Click Prediction: From Biased Baseline to Robust Ensemble Learning

## 📌 Project Overview
Digital advertising relies on precision, delivering ads to users unlikely to engage results in high ad spend leakage and poor campaign Return on Investment. This project addresses the challenge of predicting user ad-clicks using a dataset where behavior is naturally imbalanced (65% Click vs. 35% No Click). The core objective is to move beyond a biased linear regression baseline model to a more sophisticated ensemble model that accurately identifies non-engaging users.

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Algorithms:** Logistic Regression, Random Forest Classifier

## 📊 Methodology & Model Evolution
The project follows a structured machine learning pipeline:

1. **Baseline Model:** Initially implemented **Logistic Regression**, which failed to capture the minority class, resulting in a **Recall of only 0.01** for "No Click" events.
2. **Refined Baseline:** Re-implemented Logistic Regression with **balanced class weights**, though performance remained inefficient for complex user patterns.
3. **Final Solution:** Deployed a **Random Forest Algorithm**. This ensemble approach successfully overcame the class imbalance, improving "No Click" Recall to **0.50** while maintaining an **0.80 Recall** for clicks.



## 💡 Key Insights
* **Feature Importance:** The model identified **Age** as the most critical predictor of engagement with an **importance score of 0.44**.
* **Probability Scores:** Instead of simple binary labels, the model generates granular probabilities. For instance, the **18–24 age group** showed a high click probability of **86.4%**.

## 📂 Project Structure
Following the required academic/professional structure:
* **Section 3: Model / System Design** - Justification for selecting Random Forest over Logistic Regression.
* **Section 4: Core Implementation** - Documented code for model training and weighting.
* **Section 5: Evaluation & Analysis** - Detailed comparison of confusion matrices and feature rankings.
* **Section 6: Ethical Considerations** - Addressing model bias and responsible AI practices.
* **Section 7: Conclusion & Future Scope** - Summary of findings and roadmap for deployment.

## 🚀 Future Scope
The next phase of this project involves deploying the **Random Forest model via Streamlit**. This would allow the model to process **real-time datasets**, providing marketers with an interactive dashboard for instant engagement predictions on live traffic.
