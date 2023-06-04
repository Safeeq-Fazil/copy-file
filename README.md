# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Create a text1.txt with some content in it

## Step 2:
Open the text1.txt file in read mode

## Step 3:
Create a copy.txt file using write mode

## Step 4:
Copy the content of text1.txt file to copy.txt using write function


## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: Safeeq Fazil.A
RegisterNumber: 212222240086
```
```
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:
![exp 5c 1](https://github.com/Safeeq-Fazil/copy-file/assets/118680361/e7e68731-5893-410d-b658-a51a23683698)
![exp 5c 2](https://github.com/Safeeq-Fazil/copy-file/assets/118680361/ba471232-7dc9-49da-b9d6-b77b6e7f28d4)
![exp 5c 3](https://github.com/Safeeq-Fazil/copy-file/assets/118680361/7b7cbfe9-ca27-4664-85c9-47e08b5560a5)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
