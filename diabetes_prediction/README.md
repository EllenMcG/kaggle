
**Binary Logistic Regression for Diabetes Prediction**

In this repository Binary Logistic Regression was used to predict diabetes in patients who are pregnant (Pima Indians Diabetes Database collected by the National Institute of Diabetes and Digestive and Kidney Diseases) using SkiKit-Learn in Python. The 8 independent variables of this dataset are documented and discussed within the Jupyter Notebook.

In this repository the following files are found;
- diabetes.csv – The raw data used and sourced from [Kaggle](https://www.kaggle.com/datasets/kandij/diabetes-dataset)
- diabetes_clean.csv – The cleaned data used for data visualisation and logistic regression 
- Diabetes_Prediction.ipynb – Jupyter Notebook of initial data cleaning, EDA and logistic regression qith hyperparameter tuning of this dataset.
- README.md – a README file of this repository

For more on the logistic function refer to previous [Github repo](https://github.com/EllenMcG/Machine-Learning-In-Healthcare/tree/main/Binary%20Logistic%20Regression%20for%20Diabetes%20Prediction). Since this preious Jupyter Notebook the *sklearn.metrics.plot_confusion_matrix()* function is deprecated and in this Notebook, *sklearn.metrics.DisplayConfusionMatrix* was used instead with *sklearn.metrics.confusion_matrix*.  

This project is also hosted on [Kaggle](https://www.kaggle.com/code/ellenmcg/diabetes-prediction-using-logistic-regression)

Smith, J.W., Everhart, J.E., Dickson, W.C., Knowler, W.C., Johannes, R.S., 1988. Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. In: Proceedings of the Symposium on Computer Applications and Medical Care. IEEE Computer Society Press, pp. 261-265.