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
Copy the content of text1.txt file to copy.txt using write function


## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Developed by: RAGUNATH R
RegisterNumber: 212222240081
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
 ```

### OUTPUT:
![image](https://github.com/Ragu-123/copy-file/assets/113915622/7085f53a-cce3-4197-9cf0-4f74f5f83771)
![image](https://github.com/Ragu-123/copy-file/assets/113915622/81956b81-bfd5-4854-a98e-86c76786fa61)
![image](https://github.com/Ragu-123/copy-file/assets/113915622/1cf2761a-049c-4492-851f-b855d94971fc)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
