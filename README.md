### Heart Stroke Predictor

This project aims to predict the likelihood of a patient having a heart stroke based on various health parameters. A web application has been developed using Streamlit to provide an interactive interface for users to get predictions.

### Problem Statement

Heart disease is a leading cause of death globally. Early prediction of heart stroke can significantly aid in providing timely medical intervention. This project addresses the need for an automated system to predict heart stroke risk, leveraging machine learning to analyze medical data and identify patterns.

### Methodology

The project follows a standard data science workflow:

1.  **Exploratory Data Analysis (EDA):** Initial analysis was performed to understand the data, identify relationships between variables, and prepare the data for modeling.
2.  **Model Building:** Several classification algorithms were employed to build predictive models.
3.  **Model Evaluation:** The performance of each model was assessed using Accuracy and F1-score to determine the most effective model.
4.  **Deployment:** A user-friendly web application was created with Streamlit to make the prediction model accessible.

### Models & Performance

Five different machine learning models were trained and evaluated for this prediction task. The performance of each model is summarized below:

| Model                 | Accuracy | F1 Score |
| --------------------- | -------- | -------- |
| Logistic Regression   | 0.8696   | 0.8857   |
| K-Nearest Neighbors (KNN) | 0.8641   | 0.8815   |
| Naive Bayes           | 0.8533   | 0.8683   |
| Support Vector Machine (SVM) | 0.8478   | 0.8679   |
| Decision Tree         | 0.7554   | 0.7805   |

Based on the results, **Logistic Regression** provided the best performance with an accuracy of approximately 87% and an F1-score of about 89%.

### Technologies Used

*   **Programming Language:** Python
*   **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
*   **Web Framework:** Streamlit

### How to Use the App

To run the Streamlit application locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```
2.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the Streamlit app:**
    ```bash
    streamlit run app.py
    ```

This will launch the application in your web browser, where you can input the required health parameters to get a stroke prediction.

### Future Scope

Future enhancements could include:
*   Integrating additional relevant health features to improve model accuracy.
*   Deploying the application on a cloud platform for wider accessibility.
*   Exploring more advanced machine learning and deep learning models.
