# EX-NO-6-Pseudo-Random-Number

# AIM: 

Implementation of Pseudorandom Number Generation Using Standard library

```
NAME: shalini venkatesulu
REG NO: 212223220104

#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d ", random_number);
    }
    return 0;
}

```

![Screenshot 2024-11-11 115255](https://github.com/user-attachments/assets/e8a0b256-9dc5-4e26-b798-2e3e3a5e1e09)

RESULT
Thus the Implementation of Pseudorandom Number Generation Using Standard library was executed successfully.


