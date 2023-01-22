# FIND THE SQUARE ROOT OF A NUMBER  :

## AIM :

To write a program to find the square root of a number.

## EQUIPMENTS REQUIRED : 

- Hardware – PCs
- Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHIM : 

1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## PROGRAM :
```

Program to find the square root for the given number(newton's method) using function.
Developed by: MIDHUN AZHAHU RAJA P 
RegisterNumber:  22008311

def newton_method(number,number_iters = 100):
    a = float(number)
    for i in range(number_iters):
        number = 0.5 * (number + a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))

```

## GIVEN INPUT :

![image](https://user-images.githubusercontent.com/118054670/213920702-e986a27c-9a71-42b7-8a7b-e7ff8f075455.png)

## OUTPUT :

![image](https://user-images.githubusercontent.com/118054670/213920738-324b5ae4-35c5-4ed7-827f-9f9f7b1edf5b.png)





## RESULT :

Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
