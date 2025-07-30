\# Predictive Modelling for Breast Cancer Detection Using Logistic Regression



\##  Introduction to Breast Cancer



Breast cancer is one of the most common cancers affecting women worldwide. It originates in the cells of the breast, typically in the lining of the milk ducts or lobules. Early detection is crucial for effective treatment and improved survival rates. With the advancement of machine learning techniques, predictive models can assist in identifying cancer at early stages, thus aiding in timely medical intervention.



\## Project Overview



This project implements a logistic regression model to predict whether a tumor is \*\*benign\*\* (non-cancerous) or \*\*malignant\*\* (cancerous) using the \*\*Breast Cancer Wisconsin Diagnostic Dataset\*\*. Logistic regression, a statistical classification model, is suitable for binary outcomes and helps estimate the probability of class membership.



\## Objectives



\- To build a binary classification model using logistic regression.

\- To preprocess and scale the dataset for better performance.

\- To evaluate the model using key performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.



\##  Technologies Used



\- Python  

\- Pandas, NumPy  

\- Scikit-learn  

\- Matplotlib, Seaborn (for visualization)  

\- Jupyter Notebook



\## Data Preprocessing



\- Handled missing values (if any)

\- Applied standardization using `StandardScaler`

\- Split data into training and testing sets



\##  Model Evaluation



The model was evaluated using:



\- \*\*Accuracy\*\*

\- \*\*Precision \& Recall\*\*

\- \*\*F1-Score\*\*

\- 

\-



These metrics provided a comprehensive understanding of the model’s performance in correctly classifying benign and malignant cases.



\##  Project Structure

breast-cancer-logistic/

│

├── data/

│ └── breast\_cancer\_data.csv

├── notebooks/

│ └── Breast\_Cancer\_Classification.ipynb

├── images/

│ ├── README.md

└── requirements.txt



\## Future Scope



\- Try other classification algorithms like Random Forest, SVM, or Neural Networks.

\- Deploy the model using Flask/Django as a web app.

\- Integrate user-friendly front-end for healthcare professionals.



\## References



\- \[UCI Machine Learning Repository - Breast Cancer Wisconsin Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

\- \[Scikit-learn Documentation](https://scikit-learn.org/)

\- \[BreastCancer.org](https://www.breastcancer.org/)



\## How to Run



1\. Open the `Cancer Prediction\_Model.ipynb` file in Google Colab or Jupyter Notebook.

2\. Install dependencies (if needed).

3\. Run all cells step by step to see the prediction pipeline.



\##  Author



\- Rajesh Naitham  

&nbsp; Department of Pharmaceutical Engineering \& Technology  

&nbsp; IIT (BHU) Varanasi



