# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.

### Step 2:
Read the text using read() function.

### Step 3:
Split the text using space separator.We assume that words in a sentance are separted by a space character.

### Step 4:
The length of the split list should equal the numbers of words in the test file.

### Step 5:
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6:
End the program. 

## PROGRAM:
```
Program to count the words in a file
Reg No:212222100018
Name:Kabilan V
fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print('Number of words:',num_words)
```

### OUTPUT:
![image](https://github.com/kabilan22000284/Word-count/assets/123469171/4787aade-4c9b-4696-8621-8ce908539a80)



## RESULT:
Thus the program is written to find the word count from a text.
