# Logical-operations-in-C-
#include <stdio.h>

int main() {
    int a = 10, b = 20, c = 30;

    // Logical AND
    if (a < b && b < c) {
        printf("Both conditions are true: a is less than b and b is less than c\n");
    }

    // Logical OR
    if (a > b || b < c) {
        printf("At least one condition is true: either a is greater than b or b is less than c\n");
    }

    // Logical NOT
    if (!(a > b)) {
        printf("Logical NOT: a is not greater than b\n");
    }

    return 0;
}

Output
Both conditions are true: a is less than b and b is less than c
At least one condition is true: either a is greater than b or b is less than c
Logical NOT: a is not greater than b
