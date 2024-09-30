# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
Step 1.Import pandas

Step 2.Import Decision tree classifier

Step 3.Fit the data in the model

Step 4.Find the accuracy score

## Program:
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: Ariya Viniya.G
RegisterNumber: 212223080005
```
/*
import pandas as pd
import matplotlib.pyplot as plt
data = pd.read_csv("/content/Mall_Customers.csv")
data.head()
data.info()
data.isnull().sum()
from sklearn.cluster import KMeans 
wcss = [] #Within-Cluster Sum of Square 
#It is the sum of the squared distance between each point and the centroid in the cluster 
for i in range(1,11):
  kmeans = KMeans(n_clusters = i, init = "k-means++")
  kmeans.fit(data.iloc[:,3:])
  wcss.append(kmeans.inertia_)
plt.plot(range(1,11),wcss)
plt.xlabel("No. of clusters")
plt.ylabel("wcss")
plt.title("Elbow method")
km = KMeans(n_clusters = 5)
km.fit(data.iloc[:,3:])
KMeans(n_clusters=5)
y_pred = km.predict(data.iloc[:,3:])
y_pred
data["cluster"]= y_pred
df0= data[data["cluster"]==0]
df1= data[data["cluster"]==1]
df2= data[data["cluster"]==2]
df3= data[data["cluster"]==3]
df4= data[data["cluster"]==4]
plt.scatter(df0["Annual Income (k$)"], df0["Spending Score (1-100)"],c="red", label="cluster0")
plt.scatter(df1["Annual Income (k$)"], df1["Spending Score (1-100)"],c="black", label="cluster1")
plt.scatter(df2["Annual Income (k$)"], df2["Spending Score (1-100)"],c="blue", label="cluster2")
plt.scatter(df3["Annual Income (k$)"], df3["Spending Score (1-100)"],c="green", label="cluster3")
plt.scatter(df4["Annual Income (k$)"], df4["Spending Score (1-100)"],c="magenta", label="cluster4")
plt.legend()
plt.title("Customer Segments")
*/
```
## Output:
![image](https://github.com/user-attachments/assets/81142455-7898-47ee-bf32-7a6a9c1dbecc)

## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
