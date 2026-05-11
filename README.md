# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int i, n;

    printf("Enter how many random numbers: ");
    scanf("%d", &n);

    srand(time(0));

    printf("Random Numbers are:\n");

    for(i = 1; i <= n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}
```
# OUTPUT:
<img width="1897" height="1027" alt="image" src="https://github.com/user-attachments/assets/253630e5-fdc0-450e-b93b-018cd13a4bda" />


# RESULT:
