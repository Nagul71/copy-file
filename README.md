# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file from one file to another file.


### Step 2: 
 Using key word "with" to open the required file
### Step 3: 
Use for loop to get content from firstfile
### Step 4:  
use write function to write on secondfile
### Step 5: 
exit the program

## PROGRAM:
```python
with open('f4.txt','r') as firstfile:
    with open('f5.txt','a') as secondfile:
        for line in firstfile:
            secondfile.write(line)

```

### OUTPUT:
![output](/output.png)
![output](/f4.png)
![output](/f5.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.