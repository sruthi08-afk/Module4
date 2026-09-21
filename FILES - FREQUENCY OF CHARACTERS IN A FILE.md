# Exp.No:18  
## FILES - FREQUENCY OF CHARACTERS IN A FILE

---

### AIM  
To write a Python program that reads a file and counts the frequency of each character in it.

---

### ALGORITHM

1. Begin the program.  
2. Define the function `create_file()` that accepts two arguments:  
   - `file_path`: The path to the file.  
   - `content`: The string content to be written into the file.  
3. Open the file specified by `file_path` in write mode (`'w'`), and write the provided `content` into the file.  
4. Close the file (this is automatically done when exiting the `with` block).  
5. Define the function `character_frequency()` that accepts one argument:  
   - `file_path`: The path to the file whose character frequency is to be calculated.  
6. Open the file specified by `file_path` in read mode (`'r'`), and read its content into the variable `content`.  
7. Initialize an empty dictionary (`d1`) to store the frequency of each character using `defaultdict(int)`.  
8. Loop through each character in the `content`:  
   - For each character `ch`, increment its corresponding frequency in the dictionary `d1`.  
9. Return the dictionary `d1`, which contains the frequency of each character in the file.  
10. Terminate the program.

---

### PROGRAM

```
#Reg.NO 212223020026
#Name SRUTHI.K
from collections import defaultdict
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

def char_frequency(file_path):
    with open(file_path,'r') as f1:
        content=f1.read()
    d1=defaultdict(int)
    for ch in content:
        d1[ch]+=1
    return d1



```


### OUTPUT

![image](https://github.com/user-attachments/assets/00d339d2-8c23-4e63-8a67-da61e1bbc83d)
![image](https://github.com/user-attachments/assets/e36a8b45-3e45-495a-a1bb-32a6544cc204)
![image](https://github.com/user-attachments/assets/b13de0f3-c2b3-4c40-bdc5-e2cab3efb479)
![image](https://github.com/user-attachments/assets/18db26eb-0b5b-4b4e-b044-5b50af4e85e5)


### RESULT
Thus the Python program that reads a file and counts the frequency of each character in it is executed successfully.
