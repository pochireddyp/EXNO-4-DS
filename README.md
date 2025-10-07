# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
# Feature Scaling:

<img width="1632" height="680" alt="image" src="https://github.com/user-attachments/assets/ed9572e0-5ee7-4a65-81d3-db5c7d309ff1" />
<img width="1634" height="713" alt="image" src="https://github.com/user-attachments/assets/778a9707-68bc-443e-b85d-c975be271c25" />
<img width="1634" height="708" alt="image" src="https://github.com/user-attachments/assets/70f8b4ba-25a0-49b8-a39a-597a9cf7ad45" />
<img width="1637" height="707" alt="image" src="https://github.com/user-attachments/assets/4c27155d-9ee0-4b1f-8d39-406c1c701213" />
<img width="1632" height="700" alt="image" src="https://github.com/user-attachments/assets/264dfd4a-3a7e-4436-9356-e1d2c7908479" />
<img width="1631" height="696" alt="image" src="https://github.com/user-attachments/assets/be7c40c6-0e1e-48fa-8225-1c8684a89ca3" />

# Feature Selection:
<img width="1179" height="686" alt="image" src="https://github.com/user-attachments/assets/7d0f7797-1792-4211-b5cc-8b51dc43d8e6" />
<img width="1177" height="646" alt="image" src="https://github.com/user-attachments/assets/6a17f756-4cab-4834-8609-2e6d18f3fb0b" />
<img width="1179" height="698" alt="image" src="https://github.com/user-attachments/assets/b2ab2378-d47f-4e46-8907-cea03c3bcc07" />
<img width="1180" height="436" alt="image" src="https://github.com/user-attachments/assets/a034759c-4c36-4072-9127-4e6ec96e899c" />
<img width="1179" height="458" alt="image" src="https://github.com/user-attachments/assets/59c77199-592f-418f-a340-f42231c13b14" />
<img width="1183" height="483" alt="image" src="https://github.com/user-attachments/assets/86699f14-9a2f-4de7-8e69-b1773a84ace6" />
<img width="1193" height="486" alt="image" src="https://github.com/user-attachments/assets/c4cbde52-f77b-4bc4-9a56-fb0e2af15851" />
<img width="1188" height="610" alt="image" src="https://github.com/user-attachments/assets/61b950c4-0c62-4783-8d43-5ec899f241ef" />
<img width="1186" height="764" alt="image" src="https://github.com/user-attachments/assets/67f92e83-606d-42d5-a2b3-a43bdc179862" />

# RESULT:
Thus, Feature selection and Feature scaling has been performed on the given dataset.
