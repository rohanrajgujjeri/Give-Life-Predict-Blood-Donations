# Give-Life-Predict-Blood-Donations

Project Description:

"Blood is the most precious gift that anyone can give to another person — the gift of life." ~ World Health Organization

To complete the Project Give Life, you'll follow a structured workflow to predict whether a blood donor will donate within a specific time frame using the provided dataset. 

Project Tasks: 

Task 1: Inspecting transfusion.data File

Download the transfusion.data file from the Kaggle.
Open the file to understand its structure and content. It typically includes columns for attributes and a header row.

Task 2: Loading the Blood Donations Data

Use Python and pandas to load the data into a DataFrame.

Task 3: Inspecting Transfusion DataFrame

Check the first few rows, data types, and summary statistics of the DataFrame to understand its structure.

Task 4: Creating Target Column

Create a target column target where 1 indicates the donor donated blood within the given time window, and 0 otherwise.

Task 5: Checking Target Incidence

Check the incidence of the target variable to understand the class distribution.

Task 6: Splitting Transfusion into Train and Test Datasets

Split the data into training and testing sets for model evaluation.

Task 7: Selecting Model Using TPOT

Use the TPOT library to automate the model selection and hyperparameter tuning process.

Task 8: Checking the Variance

Assess the variance of numerical features to decide if normalization is needed.

Task 9: Log Normalization

If necessary, apply log normalization to features with high variance.

Task 10: Training the Logistic Regression Model

Train a logistic regression model using the normalized data and evaluate its performance.

Conclusion:

Summarize your findings and the performance of the model. Discuss any challenges and potential improvements.

By following these steps, you'll be able to predict blood donations effectively, leveraging automation tools like TPOT to optimize your machine learning pipeline. This project not only helps in understanding the data and modeling process but also contributes to solving a real-world problem of forecasting blood supply.


Forecasting blood supply is a serious and recurrent problem for blood collection managers: in January 2019, "Nationwide, the Red Cross saw 27,000 fewer blood donations over the holidays than they see at other times of the year." Machine learning can be used to learn the patterns in the data to help to predict future blood donations and therefore save more lives.

In this Project, I worked with the data collected from the donor database of Blood Transfusion Service Center in Hsin-Chu City in Taiwan. The center passes its blood transfusion service bus to one university in Hsin-Chu City to gather blood donated about every three months. The dataset, obtained from the UCI Machine Learning Repository, consists of a random sample of 748 donors. Our task will be to predict if a blood donor will donate within a given time window. We will look at the full model-building process: from inspecting the dataset to using the tpot library to automate your Machine Learning pipeline.

To complete this Project, I used Python, pandas, and logistic regression. We recommend one is familiar with the content in DataCamp's Manipulating DataFrames with pandas, Preprocessing for Machine Learning in Python, and Foundations of Predictive Analytics in Python course.
