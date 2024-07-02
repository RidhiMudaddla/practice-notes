---
title: "even of odd"
date: 2024-07-02
categories:
---
### evenorodd.c

```c

#include <stdio.h>

int main(void)
{
    int num;

    // Get the number from the user
    printf("Enter a number: ");
    scanf("%d", &num);

    // Check if the number is even or odd
    if (num % 2 == 0)
    {
        printf("%d is even\n", num);
    }
    else
    {
        printf("%d is odd\n", num);
    }

    return 0;
}

```