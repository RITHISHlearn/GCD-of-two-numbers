# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: RITHISH P
RegisterNumber:  212223230173
*/
```
Program to find the gcd of two number using function.

def gcd():

    n1, n2 = int(input()), int(input())
    

    if n1 > n2:
    
        smaller = n2
        
    else:
    
        smaller = n1
        

    hcf = 1
    

    for i in range(1, smaller + 1):
    
        if n1 % i == 0 and n2 % i == 0:
        
            hcf = i
            

    print("GCD of two numbers is:", hcf)
    


## Output:
 ![Screenshot 2024-03-26 011446](https://github.com/RITHISHlearn/GCD-of-two-numbers/assets/145446645/b0f27c12-3d10-4b53-8efb-3b5f87e47a7c)

![Screenshot 2024-03-26 011501](https://github.com/RITHISHlearn/GCD-of-two-numbers/assets/145446645/ba0060ef-f50b-4d94-8362-ccf3d4f65552)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
