# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.

### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3:
Read the file using read() method.

### Step 4:
Use split() method to split the file content into words.

### Step 5:
Use len() to find the total words.

### Step 6:
Use len() to find the total words. 

## PROGRAM:
```
#Program for getting word count from the contents of a file using command line arguments.
#Developed by: S Afsar jumail
#RegisterNumber: 212222240004

import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![image](https://github.com/Afsarjumail/command-line-arguments-to-count-word/assets/118343395/620d4d78-4382-40c6-95a2-0b5ffeccea84)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
