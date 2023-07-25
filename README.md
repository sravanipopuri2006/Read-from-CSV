# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the csv file using pd.raed_csv()
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output.

## PROGRAM:
```
#To read the content from the csv file
# Developed by: POPURI SRAVANI
# Register Number: 23006561

import pandas as pd
df = pd.read_csv('cars.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```

## OUTPUT:
![Alt text](<2023-07-25 (33)-2.png>)


## RESULT:
Thus the program written to read the csv file and to print the no.of rows and no.of columns.
