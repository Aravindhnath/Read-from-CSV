# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output.

## PROGRAM:
```
# Developed by: ARAVINDHNATH T R
# Register Number: 22009024

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Read from csv](https://user-images.githubusercontent.com/118790841/214722296-ea18c907-2a8f-4995-9aa9-755dd142794c.jpg)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
