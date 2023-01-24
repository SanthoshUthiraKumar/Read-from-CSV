# Read-from-CSV

## AIM:
To write a python program to read the content from a CSV file

## ALGORITHM:
### Step 1:
import the library Pandas .
### Step 2:
Upload the CSV file and copy path of it.Read the CSV file using pd.read_filename

### Step 3:
Print the content in the file from start and from bottom

### Step 4:
Print the rows and columns from the file

### Step 5:
End the program

## PROGRAM:
```
''' 
Program to read the contents from CSV file
Developed by: Santhosh U
RegisterNumber: 22009224
'''
import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:
![CSVOutput](https://user-images.githubusercontent.com/119477975/214110022-7607649d-e1aa-45c9-aed8-509c3c03f1c7.png)

## RESULT:
Thus the program is written to read the content in a CSV file
