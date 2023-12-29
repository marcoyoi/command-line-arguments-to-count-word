# Command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest
### Step 2: 
On the same location as the text file, create a python program file.
### Step 3: 
In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4:  
using read() and split(), split the lines in the file into a sequence of words
### Step 5: 
using len() count the number of words in the text file
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output
## PROGRAM:
```
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: Meyyappan.T
RegisterNumber: 212223240086
import sys
count=0
with open(sys.argv[0],'r')as f:
    for line in f:
        word=line.split()
        count+=len(word)
print("Word count in the file",count)
```
### OUTPUT:
![image](https://github.com/marcoyoi/command-line-arguments-to-count-word/assets/128804366/faf4375c-b55f-4f63-aa8c-f0a137e068ed)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
