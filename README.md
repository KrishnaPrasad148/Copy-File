# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.

### Step 2:
Using keyword "with" to open the requied file.
 
### Step 3: 
Again using the with keyword to open the empty file.

### Step 4:  
The empty file is open by using 'W' which is used to write only.

### Step 5: 
The four function is used to take each line from the main file.

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
