# power-cal
- This little program can calculate powers.

## Needed
- A program to run C files
- or a online compiler with the output

## How to?
- Download the `power cal.c` from [here](https://github.com/RedEdge967/power-cal/releases) and run it.
- or you can copy the code given below and paste it on a online compiler and run it.

```c
#include <stdio.h>
int power(int n1, int n2);
int main() {
    int base, a, result;
    printf("Enter base number: ");
    scanf("%d", &base);
    printf("Enter power number(positive integer): ");
    scanf("%d", &a);
    result = power(base, a);
    printf("%d^%d = %d", base, a, result);
    return 0;
}

int power(int base, int a) {
    if (a != 0)
        return (base * power(base, a - 1));
    else
        return 1;
}
```
> ### You can use this for your any purposes and don't forget to give 💕 by 🌟 it...
