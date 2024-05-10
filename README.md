# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
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
Increase the maximum number of rows to display the entire DataFrame

### Step 6: 
End the program.

## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: Krishna Prasad.S
#Register Number: 212223230108
```
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

### OUTPUT:
![image](https://github.com/KrishnaPrasad148/Copy-File/assets/147332763/e3b3346d-0baf-45ac-9762-46d1383af279)

![329156316-f0a48c59-392e-4aa2-be43-326dca874b38](https://github.com/KrishnaPrasad148/Copy-File/assets/147332763/1ed58dda-c1f3-4d17-aa32-57242880a5e5)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
