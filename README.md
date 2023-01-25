# command-line-arguments-to-count-word

## AIM:

To write a python program for getting the word count from the contents of a file using command line arguments.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHM: 

### Step 1: 

Import the sys module

### Step 2: 

Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
 
### Step 3: 

Read the file using read() method.

### Step 4:  

Use split() method to split the file content into words.

### Step 5: 

Use len() to find the total words.

### Step 6: 

Run the program to determine the number of words in the file created.

## PROGRAM:
```python
Python program for getting the word count from the contents of a file using command line arguments.
Developed by: Jivan Karthec.B.S
RegisterNumber: 22004763

import sys
count = 0
with open (sys.argv[1],'r') as f1:
    for line in f1:
        word = line.split()
        count += len (word)
print("word count in file = ",count)

```

### OUTPUT:
![11](https://user-images.githubusercontent.com/121165867/214641373-51b6c130-78e3-482f-961a-24ed3a5f88a6.png)

![12](https://user-images.githubusercontent.com/121165867/214641471-df0f9988-38f7-4f4b-8900-7db192fffc80.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
