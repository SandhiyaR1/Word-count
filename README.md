# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
``` python
num_word=0
with open ("sample.txt",'r') as f:
    for i in f:
        word=i.split()
        num_word+=len(word)
print("number of words ={}".format(num_word))

```
### OUTPUT:
![output](/wordcount.png)



## RESULT:
Thus the program is written to find the word count from a text.
