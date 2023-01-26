# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a jupyter notebook and open a new text file.

### Step 2: 
Write a sentence and save it with .txt extension.
 
### Step 3: 
Now,create a new python worksheet in jupyter.

### Step 4:
Get a text file name from user and open it.

### Step 5: 
Enter a code to split a words and count it.

### Step 6: 
Finally run a code to find the number of words in text file.

## PROGRAM:
```
#Developed by : Gokul J
#Reference no:22009062

fname = input('Enter file name: ')
num_words = 0
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        num_words += len(words)
print('Number of words: ', num_words)        
```        

### OUTPUT:
![Screenshot from 2023-01-26 17-16-57](https://user-images.githubusercontent.com/121165938/214827986-137a9637-8218-4679-bd8b-543fc04efb0c.png)



## RESULT:
Thus the program is written to find the word count from a text.
