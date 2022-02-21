# Read-from-CSV

## AIM:
To write a python program to read contents from the csv file

## ALGORITHM:
### Step 1:
Import pandas library using import statement.
### Step 2:
Read the csv file using read_csv method
### Step 3:
Use head and tail method to get the required contents from the file
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output

## PROGRAM:
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("No of rows",len(df.axes[0]))
print("No of columns",len(df.axes[1]))

## OUTPUT:
![image](https://user-images.githubusercontent.com/93427238/154994424-9bef6d80-8420-4247-bfef-15d486f3adb0.png)


## RESULT:
Thus the python program to read contents from a csv file is successfully executed.
