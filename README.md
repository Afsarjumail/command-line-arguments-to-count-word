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
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] += 1
print(count)
f.close()
```
### OUTPUT:
![image](https://github.com/Afsarjumail/command-line-arguments-to-count-word/assets/118343395/99c16b7c-f09f-4f65-81c4-4d40e757f5b0)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
