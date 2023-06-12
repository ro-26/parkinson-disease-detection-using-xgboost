## parkinson-disease-detection-using-xgboost 
This project aims to develop a Parkinson's Disease detection system using *XGBoost*, which stands for Extreme Gradient Boosting, is a scalable, distributed gradient-boosted decision tree (GBDT) machine learning library, and optimize its performance by tuning the hyperparameters. The project demonstrates the application of SVM for medical diagnosis and showcases the importance of hyperparameter optimization in achieving better recall and precision scores.

### Features:
- Utilizes a dataset containing a collection of diagnostic features from Parkinson's Disease patients and healthy individuals.
- Implements data preprocessing techniques such as feature selection, normalization using z-score, and scaling to prepare the data for classification.
- Trains an XGBoost classifier using the preprocessed dataset to distinguish between healthy and Parkinson's affected persons.
- Explores hyperparameter tuning technique(Grid search) to find the optimal combination of hyperparameters for the model.
- Uses recall-precision scores on validation dataset to find the optimum threshold for the problem.
- Generalize the performance by measuring the metrics on unseen test dataset. 
- Visualizes the results and performance metrics using plots and charts in Jupyter Notebook.

### Technologies and Libraries Used:
- Python
- Jupyter Notebook
- XGBoost
- Scikit-learn for hyperparameter tuning and performance metrics
- Pandas and NumPy for data manipulation and preprocessing
- Matplotlib and Seaborn for data visualization

### Installation and Usage:
1. Clone the repository: git clone https://github.com/ro-26/parkinson-disease-detection-using-machine-learning
2. Install the required dependencies
3. Open the Jupyter Notebook
4. Run the cells in the notebook to execute the data visualization, data preprocessing, and hyperparameter tuning steps.
5. Analyze the results, evaluate the model's performance, and explore the visualizations in the notebook.




