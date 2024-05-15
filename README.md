# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
 
### Step 1:

Import numpy as np

### Step 2: 

Enter the input values
 
### Step 3: 

Write python program for getting the word count from the contents of a file using command line arguments

### Step 4:

Run the program

### Step 5: 

Input the values

### Step 6: 

End the program

## PROGRAM:

```
#Program to find the number of words in a text file
#DEVELOPED BY : MOHAMMED SAAJID S
#REGISTER NUMBER: 212223240093

num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:


![Screenshot 2024-05-15 230418](https://github.com/Pavithranmurugan13/Word-Count/assets/163802201/afa9aa83-0602-4671-8ec5-658c589a956f)

## RESULT:

Thus the program is written to find the word count from a text.
