# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
Read the file and store in a variable.
 
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.

### Step 4:  
Use write function to copy the read file that has been stored in the variable.

### Step 5: 
The content in the original file will be copied in the new file.

### Step 6: 
End the program.

## PROGRAM:
```
#Developed by: AJITH KUMAR A
#Register number: 23002150

with open('text1.txt','r')as fp:
     msg1=fp.read()
with open('copytext.txt','a')as fp1:
     fp1.write(mgs1)
        
```

### OUTPUT:

![image](https://github.com/Ajith1413/copy-file/assets/139842524/90192d88-5a6e-49d3-83b8-81b2e485a189)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
