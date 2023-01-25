# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: Read the file and store in a variable.
 
### Step 3: Now create a new file in which we want to paste the content using write access mode. 

### Step 4: Use write function to copy the read file that has been stored in the variable.

### Step 5: The content in the original file will be copied in the new file.

### Step 6: End the program.

## PROGRAM:
```
'''
Developed by: Naveen M
Reference number: 22000748
'''
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```

### OUTPUT:

![expc](https://user-images.githubusercontent.com/117974950/214614706-675dd1c2-ca11-4186-b6f4-97a33d451744.png)

![sample1](https://user-images.githubusercontent.com/117974950/213993436-d06dd6cd-69ce-437d-81c8-2aca7852be14.png)

![Screenshot from 2023-01-23 13-45-02](https://user-images.githubusercontent.com/117974950/213993462-11309a34-fb54-4242-a5d9-ea908d16a872.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
