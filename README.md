# Copy-File
## 
AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
load the csv into a DataFrame.
### Step 2: 
 print the number of contents to be displayed using df.head().
### Step 3: 
the number of rows returned is defined in pandas option settings
### Step 4:  
check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: 
increase the maximum number of rows to display the entire DataFrame
### Step 6: 
End the program
## PROGRAM:
```
#Developed by:sharika.R
#Register number:212223230204
def copy(fname,newfile):
    with open(fname) as fp:
        with open(newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("textfile1.txt","textfile2.txt")
```

### OUTPUT:
![Screenshot 2024-10-16 061654](https://github.com/user-attachments/assets/ae89b3e8-43f3-4ae3-bae9-05a53a6d33c7)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
