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
with open ("text.txt") as fp:
  with open("file.txt","w") as fp1:
    line= fp.read()
    fp1.write(line)
```

### OUTPUT:
![image](https://github.com/KrishnaPrasad148/Copy-File/assets/147332763/85d3a65c-ec03-4de9-8a0c-3a18f49acbf0)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
