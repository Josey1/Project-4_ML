![image](https://github.com/Josey1/Project-4_ML/assets/14218202/89ede0fd-76e7-4fa4-9d18-cd7b8c18fd28)

# Project-4_ML
## Business Case/Task
The goal of this project is to build a predictive model that can determine whether an individual earns more than $50K annually based on the adult dataset. The model aims to assist businesses and organizations in identifying potential high-income earners, which can be valuable for targeted marketing, financial services, and other applications.
## Feature Engineering Approaches Applied/Tried
1. Handling Missing Values: Replaced missing values (represented as '?') with NaN and dropped rows with missing target values.
2.Encoding Categorical Variables: Used one-hot encoding to convert categorical variables into numerical form.
3. Standardization: Scaled the numerical features to have a mean of 0 and a standard deviation of 1.
4. Principal Component Analysis (PCA): Reduced the dimensionality of the dataset by extracting the top 3 principal components.
5. Clustering: Applied KMeans clustering to create cluster labels and added these labels as new features.
6. Feature Selection: Employed a RandomForest classifier to select important features based on their importance scores.

## Below are some of the visuals after data modeling;
### Visual 1
![image](https://github.com/Josey1/Project-4_ML/assets/14218202/2f1633b9-c880-46ef-a5ef-15a15e8a5bf2)
The above visual shows that Individuals earning >50k have a way higher average capital gain compared to those earning <=50k.
### Visual 2
![image](https://github.com/Josey1/Project-4_ML/assets/14218202/f0e38569-b65c-4e1e-8b3f-25533e3b4921)
Being married with a civil spouse is more prevalent among individuals earning >50K, implying that marital status could be a significant factor associated with higher income.



