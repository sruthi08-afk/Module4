# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

---

### PROGRAM

```
#Reg.NO 212223020026
#Name SRUTHI.K

class umbrella:
    def __init__(self,r):
        self.r=r
        
    def rain(self):
        self.rain=3.141592*(self.r**2)
        print("Area of circle: {:.2f}".format(self.rain))
        
p = umbrella(int(input()))
p.rain()




```

### OUTPUT
![image](https://github.com/user-attachments/assets/53584422-42d3-4e11-8cde-1d04208ecc44)




### RESULT
Thus a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain` is executed successfully.
