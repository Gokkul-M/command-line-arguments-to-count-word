# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2:
Then decleare count is equal to 0
### Step 3:
read the file with python file name
### Step 4:
Splitting the word
### Step 5:
After splitting count the number of words in the line
### Step 6:
In last statement give the print statement
## PROGRAM:
```
Developed by : Gokkul M
Register no : 212223240039
```
```
fname=input("enter the file name")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words: ",num_words)
```
### OUTPUT:
![image](https://github.com/Gokkul-M/command-line-arguments-to-count-word/assets/144870543/4bf83ef5-2350-467d-a04c-fe627d3a7351)
![image](https://github.com/Gokkul-M/command-line-arguments-to-count-word/assets/144870543/0f138124-5d69-499e-8b45-fd2dc8f2ad80)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
