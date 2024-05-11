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
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: RANJANI A
#Register Number: 212223230170

with open ("text1.txt",'r') as fp:
     msg1=fp.read()
with open ("copytxt",'w') as fp1:
     fp1.write(msg1)
```
### OUTPUT:
![WhatsApp Image 2024-05-11 at 13 27 25_eceb2031](https://github.com/Ranjania2005/Copy-File/assets/151624950/3210ae70-5039-4ffc-b3d1-1cefbb9f7fb1)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
