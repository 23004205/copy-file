# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
get the file name to create user

### Step 2:
give a new file name to create a copy of a file content

### Step 3:
read the file and close the file

### Step 4:
now the content in the new file

### Step 5:
when done print"File Copied Successfully"

### Step 6:
end the program
  
## PROGRAM:
```
'''
#Developed by: singamala venkata sai kumar reddy
#RegisterNumber:212223230208
'''
print("Enter the name of source file: ")
sFile=input()
print("Enter the name of target file: ")
tFile=input()
fileHandle=open(sFile,"r")
texts=fileHandle.readlines()
fileHandle.close()
fileHandle=open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!")
```
### OUTPUT:
![Screenshot 2023-12-30 145200](https://github.com/23004205/copy-file/assets/138971114/c9d0f91b-bb3b-424a-b7ff-469f0fd15055)

![image](https://github.com/23004205/copy-file/assets/138971114/10db2696-2f3a-4514-bed4-4f9df15bdbdc)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
