# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
To write a python program for getting the word count from a text file.

## Step 2:
Open the required file by using the function "with".

## Step 3:
Then use the for loop to assign the i value in the file.

## Step 4:
Using split function to spilt the words.

## Step 5:
Finding the given length of the words by using len() fuction.

## Step 6:
Calling the function and [rinting the number of words.

## PROGRAM:
num_word=0
with open('nachi.txt') as f6:
    for i in f6:
        word=i.split()
        num_word+=len(word)
print("Number of words:{}".format(num_word))

### OUTPUT:
![image](https://github.com/naren2704/Word-count/assets/118706984/e635218a-f03a-46b7-8ae4-24f379068cbb)




## RESULT:
Thus the program is written to find the word count from a text.
