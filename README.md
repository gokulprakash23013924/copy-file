# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function.

## PROGRAM:
Program for copying the contents from one file to another file
Developed by: GOKUL PRAKASH M
RegisterNumber: 23013924

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
### OUTPUT:

![image](https://github.com/gokulprakash23013924/copy-file/assets/150231472/8455d1fe-b305-4402-89eb-3082ab0348df)
![image](https://github.com/gokulprakash23013924/copy-file/assets/150231472/75e0690c-f5a1-4597-be13-6375c744e9ac)
![image](https://github.com/gokulprakash23013924/copy-file/assets/150231472/43908db0-95ad-48b2-81b4-d785f0533d40)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
