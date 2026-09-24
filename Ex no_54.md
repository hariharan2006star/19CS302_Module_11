
# EX 54 D program to print all the letters of the English alphabet.
## DATE:
## AIM:
To write a C program to print all the letters of the English alphabet.

## Algorithm:

1. **Start**  
2. Initialize a character variable `ch` with `'A'`.  
3. Loop from `'A'` to `'Z'`:  
   - Print the character.  
   - Print a space after each character.  
4. End the loop once `'Z'` is printed.  
5. **End**  

 

## Program:
```c program
#include <stdio.h>

int main() {
    char ch;
    
    for (ch = 'A'; ch <= 'Z'; ch++) {
        printf("%c ", ch);
    }
    
    return 0;
}
```

## Output:

<img width="1265" height="181" alt="image" src="https://github.com/user-attachments/assets/5087fd08-1dc1-4e5e-a67a-ff582465516c" />


## Result:
Thus the program was executed and the output was verified successfully.
