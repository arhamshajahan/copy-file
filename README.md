# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.

### Step 2: 
 Write some lines in that file.
 
### Step 3: 
Create a python file.

### Step 4:  
Write a code to copy the content of the file to a new file.

### Step 5: 
Run the program.

### Step 6: 
Display the output.

## PROGRAM:
```
with open("text.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)

```


### OUTPUT:
![py1](https://github.com/arhamshajahan/copy-file/assets/127313881/4f4d7d13-04b0-4c4e-9c7f-4aa7928ccc81)

![py2](https://github.com/arhamshajahan/copy-file/assets/127313881/aff75fb7-7ddd-4591-abf4-95bd3e057a8f)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
