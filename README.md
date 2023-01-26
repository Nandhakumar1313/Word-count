# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import numpy as np

### Step 2:
enter the correct input values
 
### Step 3: 
write a python program for getting the word count from the contents of a file using command 
line argument

### Step 4:
use command line argument

### Step 5:
end the program

## PROGRAM:
'''
Developed by:G.R.Nandhakumar

Reference no:22001737

'''

num_words=0
with open('text.txt','r') as f1:
    for i in f1:
        word = i.split()
        num_words += len(word)
print("Number of words in the file = {}".format(num_words))  


### OUTPUT:
![copy](https://user-images.githubusercontent.com/120230694/214786835-3ea3e5ee-c4f4-4e46-8aac-3dbb1733aed5.png)




## RESULT:
Thus the program is written to find the word count from a text.
