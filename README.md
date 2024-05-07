# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Start the python.
### Step 2:
Import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.
## PROGRAM:
```
import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head)
print(f.tail)
print('ROW:',len(f.axes[0]))
print('COl',len(f.axes[1]))

```
## OUTPUT:
![image](https://github.com/LATHIKESHWARAN/Read-from-CSV/assets/119393556/fb52d0d1-89ec-43ce-b8be-06a8ebb1f6a5)

## RESULT:
A python program to read data from CSV files has been created successfully.
