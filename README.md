# Supervised-Learning
Medical research university X is undergoing a deep research on patients with certain conditions. University
has an internal AI team. Due to confidentiality the patient’s details and the conditions are masked by the
client by providing different datasets to the AI team for developing a AIML model which can predict the
condition of the patient depending on the received test results.
# Data Description:
The data consists of biomechanics features of the patients according to their current conditions. Each patient
is represented in the data set by six biomechanics attributes derived from the shape and orientation of the
condition to their body part. 
1. P_incidence
2. P_tilt
3. L_angle
4. S_slope
5. P_radius
6. S_degree
7. Class
# Project Objective:
Demonstrate the ability to fetch, process and leverage data to generate useful predictions by training
Supervised Learning algorithms.

# ● Steps and Tasks:
# 1. Data Understanding: 5
a. Read all the 3 CSV files as DataFrame and store them into 3 separate variables. [1 Mark]
b. Print Shape and columns of all the 3 DataFrames. [1 Mark]
c. Compare Column names of all the 3 DataFrames and clearly write observations. [1 Mark]
d. Print DataTypes of all the 3 DataFrames. [1 Mark] 1
e. Observe and share variation in ‘Class’ feature of all the 3 DaraFrames. [1 Mark]
# 2. Data Preparation and Exploration: 5
a. Unify all the variations in ‘Class’ feature for all the 3 DataFrames. [1 Marks]
For Example: ‘tp_s’, ‘Type_S’, ‘type_s’ should be converted to ‘type_s’
b. Combine all the 3 DataFrames to form a single DataFrame [1 Marks]
Checkpoint: Expected Output shape = (310,7)
c. Print 5 random samples of this DataFrame [1 Marks]
d. Print Feature-wise percentage of Null values. [1 Mark]
e. Check 5-point summary of the new DataFrame. [1 Mark]
# 3. Data Analysis: 10
a. Visualize a heatmap to understand correlation between all features [2 Marks]
b. Share insights on correlation. [2 Marks]
i. Features having stronger correlation with correlation value.
ii. Features having weaker correlation with correlation value.
c. Visualize a pairplot with 3 classes distinguished by colors and share insights. [2 Marks]
d. Visualize a jointplot for ‘P_incidence’ and ‘S_slope’ and share insights. [2 Marks]
e. Visualize a boxplot to check distribution of the features and share insights. [2 Marks]
# 4. Model Building: 6
a. Split data into X and Y. [1 Marks]
b. Split data into train and test with 80:20 proportion. [1 Marks]
c. Train a Supervised Learning Classification base model using KNN classifier. [2 Marks]
d. Print all the possible classification metrics for both train and test data. [2 Marks]
# 5. Performance Improvement: 4
a. Tune the parameters/hyperparameters to improve the performance of the base model. [2 Marks]
b. Clearly showcase improvement in performance achieved. [1 Marks]
For Example:
i. Accuracy: +15% improvement
ii. Precision: +10% improvement.
c. Clearly state which parameters contributed most to improve model performance.
What could be the probable reason? [1 Marks]
