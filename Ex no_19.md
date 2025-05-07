# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE:07/05/2025
## AIM:To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
#include <stdio.h>

int main() {
    int num, shift;

    // Input from user
    printf("Enter an integer: ");
    scanf("%d", &num);

    printf("Enter number of positions to shift: ");
    scanf("%d", &shift);

    // Left and Right Shift
    int leftShift = num << shift;
    int rightShift = num >> shift;

    // Output results
    printf("Original number      = %d\n", num);
    printf("After left shift     = %d\n", leftShift);
    printf("After right shift    = %d\n", rightShift);

    return 0;
}

/*
C program to perform basic left and right shift operations on a given integer and display the result.
Developed by: 
RegisterNumber:  
*/
```

## Output:
Original number      = 4
After left shift     = 8
After right shift    = 2


## Result:
Thus the program was executed and the output was verified successfully.
