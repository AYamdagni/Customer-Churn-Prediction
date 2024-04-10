### Customer Churn Prediction

This project aims to uncover insights about customer demographics and build ML models to accurately predict if the customer will leave the firm. This helps executives to focus their 
marketing and retention strategies thus increasing the overall reach and revenue for the organization.

#### Technologies Used

  * Jupyter Notebook - Python

#### Data Source

* The dataset we have selected for our project is [Bank Customer Churn Prediction](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset) from Kaggle.
* Additionally, to create new validation records for the finalized model, we have generated mock data using [Moackaroo](https://www.mockaroo.com/).

#### Data Dictionary

Here is the concise list of columns and its values available in the dataset - 

![image](https://github.com/AYamdagni/Customer-Churn-Prediction/assets/136560732/501eabf4-c4ad-4688-86c7-4ba3acfd2546)

#### Methodology

1. **Perform Exploratory Data Analysis** : Load the dataset and analyze the demographics, key values and identify any data discrepancies.
2. **Data Preprocessing and CleanUp** : Based on the findings, make relevant changes like updating categorical variables, filling/ removal of missing values, etc.
3. **Apply Predictive Models** : Train and test different modeling techniques like regression, KNN, Decision Tree, PCA for confirming the correct feature selection
4. **Check with mock data**: Predict the churn for new mock data

#### Inference and Future Scope

Descriptive Analytics revealed the following insights - 

 * 20.4% of the total customers Left the Bank
 * Only 7% of the churned customers re-engaged with the bank
 * Germany has highest Churn rate
 * 33.46% of Women left the banking services compared to 19.69% of Men
 * 58.9% of the middle aged adults switched banks

Predictive Analytics Findings -
 * Based on the PCA analysis - 10 features in the model will give optimum results
 * Logistic Regression model gave the most accurate result of 81.3% where our dependent bariable was categorical.

#### References and Acknowledgements

I would like to thank my professor, Dr.Peng Huang, at Robert H. Smith School of Business, University of Maryland - College Park for guiding me throughout the project and Data Processing and Analytics in Python course. I am grateful to other contributors on my project team - Aparna Raghavendra Rao, Arvind Kanhirampara Ravi, Charishma Jaladi, Nishanthi Ravichandran, Sai Arjun Madikonda for their inputs.









