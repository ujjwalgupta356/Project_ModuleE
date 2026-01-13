Ad Click Prediction Analysis
This project explores an advertising dataset to predict whether a user will click on an ad based on various demographic and behavioral features. The analysis transitions from a baseline classification model to a refined Random Forest approach to improve predictive accuracy.

Project Overview
The goal of this analysis was to build a binary classifier to identify potential ad-clickers. The project documents the process of identifying model failure, improving performance through ensemble learning, and interpreting which features drive user engagement.

Key Findings
Initial Model Failure: The baseline model suffered from a severe class bias, achieving a high recall for the majority class but a 0.01 recall for Class 0 (non-clickers).

Model Improvement: Implementing a Random Forest Algorithm significantly balanced the model, increasing the overall accuracy and drastically improving the F1-score for the minority class.

Feature Importance: Through Random Forest feature analysis, we identified the primary drivers of ad clicks (e.g., Daily Internet Usage and Age), providing actionable insights into the target audience.

Technologies Used
Python 3.x

Jupyter Notebook

Scikit-Learn (Machine Learning & Evaluation)

Pandas & NumPy (Data Manipulation)

Matplotlib & Seaborn (Data Visualization)

Conclusion
The analysis concludes that user behavior—specifically their level of digital activity—is a far stronger predictor of ad engagement than demographic factors alone.

Daily Internet Usage: This emerged as the most significant predictor.

Age: There is a clear correlation between age and engagement.

Daily Time Spent on Site: Higher site engagement time correlates with higher click probability.
