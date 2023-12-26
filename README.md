# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file with .txt file extension.

### Step 2: 
Add some texts in that file.

### Step 3: 
Create a python file.

### Step 4:  
Write a code to count the number of words in that file.

### Step 5: 
Run the program.

### Step 6: 
Display the output.

## PROGRAM:
```
#Developed by: CHANDRU.P
#Register Number: 23007250
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
program()
```
### OUTPUT:
![Screenshot 2023-12-26 103107](https://github.com/chandru174642/Word-count/assets/139841798/2adc9cc6-8e67-410e-8f0b-6365467558c2)

![Screenshot 2023-12-26 103119](https://github.com/chandru174642/Word-count/assets/139841798/ecbe3de6-1859-4f0b-8def-98f106252790)

![Screenshot 2023-12-26 103153](https://github.com/chandru174642/Word-count/assets/139841798/0227c2f2-3724-49b0-9eb4-a1f1b1b7ce48)

## RESULT:
Thus the program is written to find the word count from a text.
