# C Program to take two numbers as input from the user and then calculating the following with nested if statement.
# 1. check whether the number are equal or not.
# 2. find the largest of two numbers
## AIM:
Write a C Program to take two numbers as input from the user and then calculating the following with nested if statement.
1. check whether the number are equal or not.
2.  find the largest of two numbers
## ALGORITHM:
1. Include the standard input-output header file.
2. Define the main function.
3. Declare variables to store the two numbers.
4. Prompt the user to enter the first number and read the input.
5. Prompt the user to enter the second number and read the input.
6. Use nested if statements to perform the following tasks:
   a. Check if the numbers are equal:
      If the first number is equal to the second number, print that the numbers are equal.
   b. If the numbers are not equal, find the largest of the two numbers:
   If the first number is greater than the second number, print that the first number is the largest.
   If the second number is greater than the first number, print that the second number is the largest.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    int x,y;
    scanf("%d%d",&x,&y);
    if (x!=y)
    {
        printf("A is not equal to B");
        if (x>y)
        printf("\nA is larger than B");
        else
        printf("\nB is larger than A");
    }
    else
    {
        printf("A is equal to B");
    }
    return 0;
}
```
## OUTPUT;
![image](https://github.com/VerginJenifer/c-programming--8/assets/136251012/b87fd301-bb4c-4a1e-a05c-3f6946723e12)
## RESULT:
Thus, a C Program to take two numbers as input from the user and then calculating the following with nested if statement.
1. check whether the number are equal or not.
2.  find the largest of two numbers
was executed successfully.
