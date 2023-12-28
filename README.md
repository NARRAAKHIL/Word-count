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
Developed by:narra akhil
Registered number: 23003406
'''
num_words=0
with open('text.txt','r') as f1:
    for i in f1:
        word=i.split()
        num_words += len(word)
print("Number of words in the file = {}".format(num_words))
```
### OUTPUT:
![image](https://github.com/NARRAAKHIL/Word-count/assets/144979843/7d70563e-77fa-48b2-bda6-88c4ff7713bf)
![image](https://github.com/NARRAAKHIL/Word-count/assets/144979843/70744189-1ca7-45f4-a820-0e7520009b1b)
## RESULT:
Thus the program is written to find the word count from a text.
