# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
Start the program.
Take input of the number n from the user.
Define a function that takes an integer as an argument and returns the factorial of that number.
Call the factorial function with n and store the result.
Print the factorial and end the program.
## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by:Devesh V 
RegisterNumber:  212223060045
*/
#include <stdio.h>

int factorial(int n) {
    int fact = 1, i;
    for(i = 1; i <= n; i++) {
        fact *= i;
    }
    return fact;
}

int main() {
    int n, result;
    scanf("%d", &n);
    result = factorial(n);
    printf("%d\n", result);
    return 0;
}
```

## Output:
<img width="369" height="167" alt="445696783-1b876ec6-3233-428f-a46d-9573157a340f" src="https://github.com/user-attachments/assets/151cb5a2-2a36-49e3-9b2b-f879d5538ef9" />


## Result:
Thus the program was executed and the output was verified successfully.
