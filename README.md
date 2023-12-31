# Read-from-CSV

## AIM:
To write the program to read from csv.

## ALGORITHM:
### Step 1:
Import the pandas library as "pd".
### Step 2:
Read the CSV file "cars.csv" using read_csv() method and assign it to the variable "df".
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns and 'shape' attribute to find the dimensions of the dataframe.
### Step 5:
Print the output and end the program.
## PROGRAM:
```
#Program to read contents from a csv file
#Developed by : Arun Kumar B
#RegisterNumaber : 212223230021
import pandas as pd
df=pd.read_csv('cars.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
print(df.shape)
```

## OUTPUT:
![Screenshot 2023-12-31 074957](https://github.com/Arun2005-create/Read-from-CSV/assets/138849356/72917b29-728c-4bc3-8500-edc01d3ef183)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
