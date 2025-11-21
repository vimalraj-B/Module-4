# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
## Developed By : VIMALRAJ B
## Register Number : 212224230304
```
import math
class cse:
    r=int(input())
    def mech(r):
        area=math.pi*r**2
        b='{:.2f}'.format(area)
        print(f"Area of circle: {b}")
    mech(r)
```

## Output

<img width="745" height="249" alt="image" src="https://github.com/user-attachments/assets/0eb6fa90-91c8-41fc-b1ec-d4e24308158b" />

   
## Result

Thus , the program was executed Successfully.
