# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
instalize the value for count as zero
#### Step 2:
using open command open the txt file to read
### Step 3:
use the split() command
### Step 4:
print the counted words
### Step 5:
end the program
## PROGRAM:
```
'''
##program to find the wword count.
##developed by:narra akhil
## register number:23003406
'''

num_words =0
with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))

```
### OUTPUT:
![image](https://github.com/NARRAAKHIL/Word-count/assets/144979843/a58fb5ba-8860-4728-8d88-c21612f61de9)

## RESULT:
Thus the program is written to find the word count from a text.
