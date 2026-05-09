# Addressing Modes using GDB

---

# Overview

This project demonstrates various addressing modes in C programming and analyzes them using the GNU Debugger (GDB). It helps in understanding how data is accessed from memory, registers, arrays, pointers, and stack during program execution.

---

# Aim

To implement and study different addressing modes in C programming and observe their behavior using the GNU Debugger (GDB).

---

# Addressing Modes Covered

- Immediate Addressing
- Direct Addressing
- Register Addressing
- Indirect Addressing
- Register Indirect Addressing
- Indexed Addressing
- Base Register Addressing
- Relative Addressing
- Auto Increment Addressing
- Auto Decrement Addressing
- Stack Addressing

---

# Code Implementation

## Code (`addressing.c`)

```c
#include <stdio.h>

// Direct Addressing (global variable)
int global_var = 50;

void function_example() {

    int x = 5, y = 10;       // Stack Addressing

    int a = 20;              // Immediate Addressing
    int b = a;               // Register Direct Addressing

    int *p = &a;             // Indirect Addressing
    int c = *p;              // Register Indirect Addressing

    int arr[5] = {1,2,3,4,5}; // Indexed Addressing
    int d = arr[2];

    int *base = arr;         // Base Register Addressing
    int e = *(base + 3);

    for(int i = 0; i < 3; i++) { // Relative Addressing
        x += i;
    }

    int f = 0;               // Auto Increment Addressing
    f = arr[f++];

    int g = 2;               // Auto Decrement Addressing
    g = arr[--g];

    printf("%d %d %d %d %d %d %d\n", b, c, d, e, f, g, global_var);
}

int main() {
    function_example();
    return 0;
}
