---
title: "sum of digits"
date: 2024-07-02
categories:
---
### sumofdigit.c

#include <stdio.h>

int main(void)

{

    int sum = 0;

    // Loop through all two-digit numbers (10 to 99)

    for (int i = 10; i <= 99; i++)

    {

        sum += i;

    }

    // Print the sum

    printf("The sum of all two-digit numbers is: %d\n", sum);


    return 0;
    
}