# Read-from-CSV

## AIM:
To write a python program for reading content from CSV file
## ALGORITHM:
### Step 1:
import pandas as pd
### Step 2:
Read the CSV file using read_csv method
### Step 3:
Use head and tail method to get the required contents from the file
### Step 4:
Use len() method to get the number of  rows and columns
### Step 5:
Display the output
## PROGRAM:
```
##Developed by : Jyesvanthe v
##Register number : 23013991

To write a python program for reading content from CSV file
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print(Number of columns:",len(df.axes[1]))

```
## OUTPUT:

![Alt text](<Screenshot 2024-01-01 142132.png>)

## RESULT:
