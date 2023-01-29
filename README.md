# Exploratory Data Analysis
Exploratory Data Analysis (EDA) is an important process that helps to gain a deeper understanding of the data. The goal of EDA is to identify patterns, trends, and relationships within the data, while also addressing issues such as missing values and outliers. This step is essential in preparing the data for modeling and analysis. The outcome of EDA is a cleaned and refined dataset that is ready for use in training and testing models.

## Life Cycle of a Machine Learning Project
- Data Analysis
- Feature Engineering
- Feature Selection
- Model Building
- Model Deployment

# Data Analysis:
Data analysis in machine learning refers to the process of examining, cleaning, and transforming data in order to prepare it for use in training a machine learning model. This can include tasks such as identifying missing or incorrect data, removing outliers, and transforming the data into a format that can be used by a machine learning algorithm. The goal of data analysis is to ensure that the model is trained on high-quality, representative data that will allow it to make accurate predictions on new, unseen data.


There are following steps that we need to perform in this phase:
- Check for the columns having null values 

![image](https://user-images.githubusercontent.com/92606737/215234656-d83f3230-0da5-49d5-a931-36c8279fb853.png)

- Determine the percentage of the null values in each column 

![image](https://user-images.githubusercontent.com/92606737/215234703-5a1f1cf0-aceb-49cf-8946-84623c2a9b10.png)


- Check the reltionship of null and non null values with the target variable

![image](https://user-images.githubusercontent.com/92606737/215234745-a3bd5a1a-1bea-4aab-a25a-d976b74eeddd.png)


- Check the Numerical variables but putting condition dtype != 'O'

![image](https://user-images.githubusercontent.com/92606737/215234918-32a0833f-73de-41ae-ba8c-61a5679e5852.png)

- Check for Temporal Variables (That include date time or year data). In our case we have 'Yr' and 'Year' in columns for temporal data 
  so we use this to find them.
  
![image](https://user-images.githubusercontent.com/92606737/215235013-5366d867-deed-4be6-a11c-9412dc899548.png)

- Check the relationship between the temporal variables and the target variables

![image](https://user-images.githubusercontent.com/92606737/215303171-6799f506-f25c-43a1-b78a-671c4df5c439.png)



