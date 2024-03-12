### Air Quality Prediction Project
**Overview**  
This repository contains the code and documentation for a project focused on predicting air quality (specifically PM2.5 concentration) using machine learning models. The project aimed to develop models that could accurately predict PM2.5 concentrations at different locations and explore the factors influencing model performance.

**Essential Steps**
1. Data Preparation and Wrangling
Load necessary packages and the dataset.
Split the data into training and testing sets.
2. Model Development
Develop four different models: Linear Regression, K-Nearest Neighbors, Decision Tree, and Random Forest.
Optimize each model's hyperparameters using cross-validation.
3. Model Evaluation
Assess the performance of each model using the root mean squared error (RMSE) metric on the testing dataset.
Employ cross-validation to evaluate model generalization.
4. Answering Primary Questions
Investigate the performance of models at different locations.
Identify factors influencing model performance.
Evaluate the impact of numerical models (e.g., CMAQ) and satellite-based observations (e.g., AOD) on prediction accuracy.
Discuss the potential performance of the models in states not included in the dataset.  

**Conclusion**  
Overall, the Random Forest model demonstrated the best predictive performance with the lowest RMSE on the testing dataset. The analysis revealed variability in model performance across locations, potentially influenced by factors such as monitoring resources and environmental characteristics. Incorporating additional variables, such as the number of monitors in each region, could enhance model accuracy. Furthermore, the evaluation of numerical models like CMAQ and satellite-based observations like AOD highlighted their impact on predicting PM2.5 concentrations. While CMAQ showed promising performance when included in the model, excluding both CMAQ and AOD resulted in improved model accuracy, indicating the effectiveness of ground-based predictors. Finally, it's important to note that the model's performance in states not included in the dataset, such as Alaska and Hawaii, may vary due to differences in environmental conditions and monitoring infrastructure.


**Contributors**  
Dan Le  
Reigne Evangelista
