
# 🚢 Titanic Survival Prediction using Logistic Regression

![Titanic](https://upload.wikimedia.org/wikipedia/commons/f/fd/RMS_Titanic_3.jpg)

## 📋 Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling Process](#modeling-process)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Training](#model-training)
  - [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## 📖 Introduction
This project applies **Logistic Regression** to predict the survival of passengers on the Titanic. It uses features such as **Age**, **Sex**, and **Passenger Class** to determine whether a passenger survived.

## 📊 Data
The dataset used includes:
- **Passenger Class (Pclass)**
- **Name**
- **Sex**
- **Age**
- **Siblings/Spouses Aboard (SibSp)**
- **Parents/Children Aboard (Parch)**
- **Ticket Number**
- **Fare**
- **Cabin**
- **Port of Embarkation (Embarked)**

## 🛠️ Installation
To run the notebook, install the required Python libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
Ensure **Jupyter Notebook** is installed to execute the `.ipynb` file.

## 🚀 Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/titanic-logistic-regression.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd titanic-logistic-regression
   ```
3. **Launch the Jupyter Notebook**:
   ```bash
   jupyter notebook "Titanic using Logistic Regression.ipynb"
   ```

## 🧠 Modeling Process

### 🔄 Data Preprocessing
- **Handling Missing Values**: Imputation techniques (mean, median, or mode) are applied to the `Age` column.
- **Encoding Categorical Variables**: Categorical variables like `Sex` and `Embarked` are converted into numerical values.

### 🤖 Model Training
A **Logistic Regression** model is trained using the dataset to predict whether a passenger survived.

### 📉 Model Evaluation
The model's performance is evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **Precision & Recall**

## 📈 Results
- **Accuracy**: The model achieved an accuracy of **[insert accuracy here]** on the test set.
- **Confusion Matrix**: The matrix below illustrates the model's ability to distinguish between survivors and non-survivors.

![Confusion Matrix](https://upload.wikimedia.org/wikipedia/commons/2/2b/Confusion_matrix_diagram.png)

## 🏁 Conclusion
The Logistic Regression model successfully predicts survival on the Titanic. Key features like **Passenger Class** and **Sex** are significant predictors.

## 📜 License
This project is licensed under the MIT License. See the `LICENSE` file for more details.


