# Obesity-Level-Classification-using-Decision-Tree
 
 <B> Objective </B>
This project focuses on predicting obesity levels using a Decision Tree model based on various lifestyle and health-related factors.

1. FAVC (Frequent Consumption of High Calorie Food)
2. FCVC (Frequency of Consumption of Vegetables)
3. NCP (Number of Main Meals)
4. CAEC (Consumption of Food Between Meals)
5. CH2O (Daily Water Consumption)
6. SCC (Calories from Sweet Drinks)
7. FAF (Frequency of Physical Activity per Week)
8. TUE (Time Using Technology Devices)
9. CALC (Frequency of Alcohol Consumption)
10. MTRANS (Mode of Transportation)
11. family_history_with_overweight
12. Weight

<b> Combined Impact on Obesity:</B>
>> High FAVC + Low FCVC: Suggests an unhealthy diet, increasing obesity risk.<br>
>> Irregular NCP + High CAEC: Suggests poor eating patterns, which can disrupt metabolism and lead to weight gain.<br>
>> Low FAVC + High FCVC: Reflects a healthier lifestyle, possibly associated with normal weight or lower obesity risk

<b> 1. Data Loading & Understanding </B>
The dataset was imported and explored to understand its structure. We checked for missing values, data types, and overall shape. This helped identify potential issues such as inconsistent data formats, missing values, or class imbalances.

<b> Exploratory Data Analysis (EDA)  </B>
It was conducted to understand patterns, distributions, and correlations between variables.

1) Visualizing the distribution of obesity levels to see how balanced or imbalanced the dataset was.
2) Correlation analysis to identify relationships between variables and their impact on obesity classification.

<b> Data Preprocessing  </B>
To prepare the data for model training, the following steps were performed:

1) Handling missing values
2) Feature scaling: Standardization or normalization was applied to ensure that features had a similar range and impact on the model.
3) Encoding categorical variables: Categorical data was converted into numerical format to be used in machine learning models.
4) Addressing class imbalance: The dataset had imbalanced obesity levels, so SMOTE (Synthetic Minority Over-sampling Technique) was applied to improve model performance for minority classes.

<b> Model Selection & Training  </B>
A Decision tree classifier was chosen due to its ability to handle non-linear relationships and interpretability. The model was trained using the processed dataset.

Key steps:
1) Splitting the dataset into training and testing sets to evaluate performance.
2) and then train the model

<b> Model Evaluation  </B>
The trained model was evaluated using multiple performance metrics:

1) *Accuracy*: The overall classification accuracy was 84%, indicating strong predictive performance.
2) *Precision & Recall*: Precision and recall scores were examined to check model performance across different obesity levels.
3) *F1-Score*: Balanced assessment of model accuracy and recall.
4) *Confusion Matrix*: Used to identify misclassified instances, particularly in underrepresented obesity levels.

<b> Impact of SMOTE & Scaling  </B>
1) SMOTE improved recall for minority classes, especially for higher obesity levels, ensuring the model was fairer.
2) Feature scaling helped maintain consistency, preventing dominant features from affecting prediction results.

<b> So, overall accuracy of 84.0% suggests the model is fairly reliable. </B>
>> If you want even better results <br>
>> We can use Ensemble models (Random Forest/XGBoost) for better classification.<br>
>> and Hyperparameter tuning to further optimize performance <br>
