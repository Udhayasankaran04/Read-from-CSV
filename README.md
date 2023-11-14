# Read-from-CSV

## AIM:

## ALGORITHM:

### Step 1:Import pandas module as pd.

### Step 2:Using pd.read_csv() method read the CSV file

### Step 3:Using df.head() print the first 10 rows of the CSV file.

### Step 4:Using df.tail() print the last 5 of the CSV file.

### Step 5:Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head(10))
print(f.tail())
print(f.head())
print('Row: ',len(f.axes[0]))
print('Col: ',len(f.axes[1]))

```
## OUTPUT:
![image](https://github.com/Udhayasankaran04/Read-from-CSV/assets/119393933/1ac58296-d928-4db0-a4e9-edb78213abcf)

## RESULT:
Hence the program is executed successfully!
