## Read-from-CSV

## AIM:
  To write a python program for reading the csv file content.

## ALGORITHM:
### Step 1:
   Load the CSV into a DataFrame.
   
### Step 2:
   Print the number of contents to be displayed using df.head().

### Step 3:
   The number of rows returned is defined in Pandas option settings.

### Step 4:
   Check your system's maximum column with the pd.options.display.max_column statement.
   
### Step 5:
   Increase the maximum number of rows to display the entire DataFrame.


## PROGRAM:
##Developed by:Alagu Nachiyar K


##REGISTER NUMBER: 22002084
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```



## OUTPUT:

![Screenshot from 2022-10-11 13-36-24](https://user-images.githubusercontent.com/113497340/195255151-0c057880-7b3b-4b21-9074-6b53853ffff5.png)



## RESULT:

Thus the program is written to read the csv file.
