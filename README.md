# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2:
Open the file with sys.argv[1]
### Step 3:
Use the for loop to select the content in file
### Step 4:
Use split function to to separate the file content into words or strings
### Step 5:
Count the length of the words using len
### Step 6:
Print the number of words

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: SWETHA N
RegisterNumber: 212222110050
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![image](https://github.com/Swetha733N/command-line-arguments-to-count-word/assets/122199934/95d0e917-ec85-4e72-a52c-8ab12e114be3)
![image](https://github.com/Swetha733N/command-line-arguments-to-count-word/assets/122199934/bf78f6a0-f99d-41e0-b7da-fe3bcdeeaee9)
![image](https://github.com/Swetha733N/command-line-arguments-to-count-word/assets/122199934/84e21d8f-2d1a-475b-a91b-0cb2e1cc1cce)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
