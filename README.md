# Banking-Customer-Churn
This project predicts customer churn in the telecom/banking sector using an Artificial Neural Network (ANN). It includes data preprocessing, feature scaling, model training, and a comprehensive visualization dashboard for performance evaluation using metrics like accuracy, confusion matrix, and ROC-AUC.
The model is trained using structured customer data and evaluated using multiple performance metrics along with visual insights.

## Objective
* Predict customer churn.
* Build a deep learning model using ANN.
* Analyze model performance using visualizations.

## Tech Stack
* Python
* NumPy & Pandas
* Matplotlib & Seaborn
* Scikit-learn
* TensorFlow / Keras

## Project Workflow
### 1. Data Preprocessing
* Loaded dataset using Pandas
* Encoded categorical features (Gender, Geography, etc.) using LabelEncoder
* Converted all object-type columns into numeric values
* Scaled features using StandardScaler

### 2. Train-Test Split
* Dataset split into:
  * 80% Training Data
  * 20% Testing Data

### 3. ANN Model Architecture
* Input Layer
* Hidden Layer 1: 128 neurons (ReLU)
* Hidden Layer 2: 64 neurons (ReLU)
* Output Layer: 1 neuron (Sigmoid)

### 4. Model Training
* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Epochs: 50
* Batch Size: 32
* Validation Split: 20%

### 5. Model Evaluation
* Accuracy Score
* Confusion Matrix
* ROC Curve & AUC Score

## Visualizations Dashboard
This project includes a complete performance dashboard:
* Training vs Validation Loss
* Training vs Validation Accuracy
* Confusion Matrix (Heatmap)
* ROC Curve (AUC Score)
* Probability Distribution of Predictions
* Churn Rate by Geography

## Dataset

* File: `Artificial_Neural_Network_Case_Study_data.csv`
* Contains customer features and churn status (`Exited` column)

## How to Run

### 1. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

### 2. Run the Project

```bash
python your_file_name.py
```

## Output
* Displays model accuracy in console.
* Generates a full visualization dashboard for performance analysis.

## 💡 Key Insights
* ANN effectively predicts customer churn.
* ROC-AUC provides deeper performance understanding beyond accuracy.
* Visualization helps interpret model behavior clearly.


## Author
**Payal kumari**

