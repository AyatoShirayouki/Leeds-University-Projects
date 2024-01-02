# Data Science Project

#### This project needs to focus on the task of analyzing datasets from an insurance company in order to predict whether a customer poses a risk of committing insurance fraud. The goal is to develop, train, and validate 2 different models that can flag potential cases of fraud for further investigation and maintain a balanced error rate.

##### Main Objectives

* 1. Utilize a group of historical datasets that indicate cases of insurance fraud. The aim is to predict the likelihood of a customer committing insurance fraud.
* 2. Help the business by reducing the number of incorrect fraud predictions (both false positives and negatives). They could have direct financial implications - false positives lead to customer dissatisfaction and loss, while false negatives result in direct financial loss due to undetected fraud.
* 3. The insurance company requires an unbiased predictive model with a target error rate of 5%. The model should be able to flag potential fraud cases efficiently.

__Aims and objectives:__

Develop a predictive model that identifies potential insurance fraud by analyzing the provided datasets in order to understand the characteristics of insurance fraud. We will Apply two machine learning techniques in order to identify fraud detection and then evaluate the models' performance in order to find out which approach is better suited for the task. Since this is a classification problem we are going to use classification models - RandomForest and KNN.

We will first prepare the data so that it can be easily fed to the prediction models, we will find the properties that are most closely correlated to the ReportedFraud and finally, we will fix any existing class imbalance before finally training the models.

The main objective of this project is to develop models that can accurately predict insurance fraud for our client, thus saving on operational costs and preserving customer relationships.

In this data science project, we have successfully created and evaluated two machine learning models—RandomForest and KNN—to address the issue of insurance fraud detection. The RandomForest model demonstrated a strong performance with high precision and recall. This shows its strength in detecting fraudulent claims. The KNN model may be slightly less precise but still performed admirably and showed that it could offer faster prediction times due to the simplicity of its nature.

On the flip side, the project faced challenges. The perfection of scores on the training set for both models raises concerns about overfitting, although cross-validation results suggest that the models still generalize well. The question is whether these models would maintain their high performance on a completely unseen dataset, as real-world data could present patterns not captured in the training phase.

Lastly, due to the 2 model limitation listed in the assignment brief, the project has not explored alternative models that could potentially provide better insight or computational efficiency. Ensemble methods other than RandomForest, deep learning approaches, or anomaly detection algorithms might offer improved or more cost-effective results.

In summary, the project's success lies in demonstrating the feasibility of using machine learning for fraud detection and providing a solid foundation for further refinement. The need for continued improvement remains, particularly in addressing potential overfitting and exploring a wider array of models to enhance predictive performance.
