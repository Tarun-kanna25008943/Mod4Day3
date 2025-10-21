# EX-03 Program to Find the Length of the String.

## AIM:
To write a C program that finds and displays the length of the string.

## ALGORITHM:

1. Start
2. Declare a character array Str[1000] to store the input string.
3. Declare an integer variable i.
4. Read the string from the user using scanf("%s", Str).
5. Use the built-in function strlen(Str) to find the length of the string and store it in i.
6. Print the length of the string using printf().
7. Stop

## PROGRAM:
```
#include <stdio.h>
#include <string.h>

  
int main()
{
    char Str[1000];
    int i;
    
    printf("Enter an string: ");
    scanf("%s", Str);
  
    i = strlen(Str);
    printf("Length of Str is %d", i);
  
    return 0;
}
``` 
## OUTPUT:
<img width="670" height="132" alt="image" src="https://github.com/user-attachments/assets/40a3a946-4371-44f4-8a99-d7d09387d070" />


## RESULT:
The program successfully finds and displays the length of the string.
