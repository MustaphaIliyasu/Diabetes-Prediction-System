{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "71349337-c052-44a4-8896-95b678063f91",
   "metadata": {},
   "outputs": [],
   "source": [
    "# Diabetes Prediction System\n",
    "\n",
    "A Machine Learning project to predict whether a patient is diabetic based on health data.\n",
    "\n",
    "\n",
    "🔍 Project Overview\n",
    "This project focuses on building a predictive model for diabetes using patient medical data. It involves data cleaning, exploratory data analysis, handling class imbalance, feature engineering, and building machine learning models to maximize the detection of diabetic cases.\n",
    "\n",
    "\n",
    "🧠 Key Features\n",
    "- Data cleaning: Handled invalid zero values and missing data  \n",
    "- Exploratory Data Analysis (EDA): Identified key features affecting diabetes such as Glucose and BMI  \n",
    "- Class imbalance handling: Used techniques to improve recall for diabetic patients  \n",
    "- Models built:\n",
    "  - Logistic Regression  \n",
    "  - Random Forest (non-linear model with higher recall)  \n",
    "\n",
    "\n",
    "\n",
    "📊 Results\n",
    "| Model                | Accuracy | Recall (Diabetic Class) |\n",
    "|---------------------|----------|------------------------|\n",
    "| Logistic Regression  | 69%      | 0.71                   |\n",
    "| Random Forest        | 73%      | 0.78                   |\n",
    "\n",
    "Insight: Random Forest improved detection of diabetic patients compared to Logistic Regression, even though overall accuracy changed slightly. Recall is prioritized for healthcare predictions.\n",
    "\n",
    "\n",
    "⚡ Key Learnings\n",
    "- Accuracy alone is not enough; recall is crucial for healthcare applications  \n",
    "- Feature importance helps understand which factors affect predictions most  \n",
    "- Handling class imbalance improves detection of minority class  \n",
    "\n",
    "\n",
    "🛠️ Technologies Used\n",
    "- Python  \n",
    "- Pandas, NumPy, Matplotlib, Seaborn  \n",
    "- Scikit-learn  \n",
    "- Jupyter Notebook  \n",
    "\n",
    "\n",
    "🗂️ Project Structure"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.9"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
