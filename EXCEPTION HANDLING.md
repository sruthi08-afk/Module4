# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
#Reg.NO 212223020026
#Name SRUTHI.K

S=input()
L=S.split(',')
int_L =[]
try:
    for x in L:
        int_L.append(int(x))
except ValueError:
    print("The grades you entered were in an invalid format.")
    int_L=L
finally:
    print(int_L)

```

### OUTPUT
![image](https://github.com/user-attachments/assets/4e136fd8-0efd-40f1-8806-081f4f3a2370)



### RESULT
Thus the Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers is executed successfully.
