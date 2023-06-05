# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2: 
 Open the file with sys.argv[1]
### Step 3: 
Use the for loop to select the content in file
### Step 4:  
Use split function to to separate the file content into words or strings
### Step 5: 
Count the length of the words using len
### Step 6: 
Print the number of words
## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: NARESH.V
RegisterNumber: 212222110027

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```
### OUTPUT:
![image](https://github.com/NARESHVB/command-line-arguments-to-count-word/assets/119393642/32383a0d-9aaa-4d86-8830-bc34e92c5422)
![image](https://github.com/NARESHVB/command-line-arguments-to-count-word/assets/119393642/be0443ab-2189-43a4-a279-6fc16cdb14fe)
![image](https://github.com/NARESHVB/command-line-arguments-to-count-word/assets/119393642/6f69fa60-3551-4910-a069-35e77c492491)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
