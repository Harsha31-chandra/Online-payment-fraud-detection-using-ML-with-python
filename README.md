# Online Payment Fraud Detection using Machine Learning

This project implements a machine learning solution to detect fraudulent online payment transactions. It utilizes classification algorithms to identify suspicious activities based on transaction features like type, amount, and balances.

## 🚀 Features
* **Data Visualization**: Includes interactive pie charts to show the distribution of transaction types using `Plotly`.
* **Preprocessing**: Handles categorical data mapping (e.g., converting transaction types to numerical values).
* **Multiple Models**: 
    * Logistic Regression (using `liblinear` solver).
    * Decision Tree Classifier.
* **Evaluation**: Provides accuracy scores and confusion matrices to measure performance.
* **Predictive System**: Includes an interactive section to input transaction details and get a fraud prediction.

## 📊 Dataset
The dataset used in this project is **not** included in this repository due to its size (178MB). 
You can download it from Kaggle here:
[**🔗 Link WILL BE UPLOADED SOON**](PASTE_YOUR_KAGGLE_LINK_HERE)

## 🛠️ Requirements
To run this notebook, you need the following Python libraries:
* `pandas`
* `numpy`
* `matplotlib`
* `plotly`
* `scikit-learn`

## 💻 How to Run
1. **Download the Data**: Get the `Online transactions data` from Kaggle.
2. **Open in Colab**: Upload the `OPFD-code.ipynb` to [Google Colab](https://colab.research.google.com/).
3. **Upload Dataset**: Upload your CSV file to the Colab session storage.
4. **Execute**: Run the cells in order. The final cell will prompt you for manual input to test the model.

## 📈 Model Performance
* **Decision Tree**: Evaluated using the `score` method on test data.
* **Logistic Regression**: Evaluated using `accuracy_score` and `confusion_matrix`.
