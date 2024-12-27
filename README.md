# Credit Risk Analysis Using Bayesian Networks

## Overview
This project explores the use of **Bayesian Networks** to predict credit default risk. By leveraging probabilistic graphical models, we aim to provide insights into the relationships between key financial and demographic factors affecting credit behavior. The approach combines data-driven insights with interpretable probabilistic modeling, offering a robust alternative to traditional black-box machine learning models.

## Features
- **Probabilistic Modeling:** Implemented a Bayesian Network using structure learning methods like Hill Climb Search.
- **Data Preprocessing:** Includes feature engineering, discretization, and advanced feature selection techniques.
- **Model Evaluation:** Compared Bayesian Networks with models such as XGBoost on key performance metrics (e.g., ROC-AUC, F1 Score).
- **Explainability:** Visualized conditional dependencies and key drivers of credit default using graphical models.

## Key Components
1. **Data Preparation**
   - Cleaned and preprocessed raw financial and demographic data.
   - Engineered and discretized features for Bayesian Network compatibility.

2. **Modeling**
   - Applied structure learning techniques (Hill Climb Search, Maximum Likelihood Estimation).
   - Built and optimized a Bayesian Network to capture probabilistic dependencies.

3. **Evaluation**
   - Compared Bayesian Network performance against XGBoost using metrics like:
     - ROC-AUC
     - F1 Score
     - Confusion Matrix

4. **Visualization**
   - Generated dependency graphs to illustrate relationships between variables.
   - Created performance plots and evaluation charts.

## Technologies Used
- **Python**: Primary language for implementation.
- **pgmpy**: Library for building and analyzing Bayesian Networks.
- **pandas, numpy**: Data manipulation and analysis.
- **scikit-learn**: Feature selection and performance evaluation.
- **XGBoost**: Benchmarking against Bayesian Network.
- **Matplotlib, Seaborn**: Data visualization.

## Results
- Achieved strong predictive performance, balancing accuracy and interpretability.
- Demonstrated the Bayesian Network’s capability to model relationships and dependencies.
- Provided an interpretable model alternative for credit default prediction.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-risk-bayesian-network.git
   cd credit-risk-bayesian-network
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   Required libraries include:
   - pgmpy
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn
   - xgboost

3. Run the notebook:
   Open `CreditDefault_BayesianNetwork.ipynb` in your preferred Jupyter Notebook environment.

## Usage
1. Load the dataset by following the instructions in the notebook.
2. Run through the notebook cells to preprocess the data, build the Bayesian Network, and evaluate its performance.
3. Modify the model structure or evaluation metrics as needed for further experimentation.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
