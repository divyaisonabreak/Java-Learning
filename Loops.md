# Loops: for, while, do-while

```java
for (int i = 0; i < 5; i++) { … }         // use when count known

int i = 0;
while (i < 5) { … i++; }                  // condition first

do { … i++; } while (i < 5);               // runs at least once
```

---

### Auto-increment/decrement

- `i++` (post), `++i` (pre) — same effect in isolation, different when used inside expressions.

---

## Nested Loops Example (Multiplication Table)

```java
for (int r = 1; r <= 3; r++) {
    for (int c = 1; c <= 3; c++) {
        System.out.print(r * c + "\t");
    }
    System.out.println();
}
```

---

### Common Questions

- Detect prime numbers
- Find factorial
- Generate Fibonacci series

---
