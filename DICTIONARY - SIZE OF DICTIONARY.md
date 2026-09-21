# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

---

### PROGRAM

```
#Reg.NO 212223020026
#Name SRUTHI.K
#Add Your Code Here
import sys

dic1 = {"A": 1, "B": 2, "C": 3} 
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
print("Size of dic1: {}bytes".format(sys.getsizeof(dic1)))
print("Size of dic2: {}bytes".format(sys.getsizeof(dic2)))
print("Size of dic3: {}bytes".format(sys.getsizeof(dic3)))


```

### OUTPUT
![image](https://github.com/user-attachments/assets/97907cbc-e74e-4ab3-ba7c-f7e79f846e89)


### RESULT
Thus the Python program to print the size of a dictionary using `getsizeof()` from the `sys` module is executed successfully.
