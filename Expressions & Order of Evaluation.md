## Expressions & Order of Evaluation

- **Rule**: Evaluate left to right, respecting operator precedence.

### Example:

```java
int x = 2 + 3 * 4;      // = 2 + (3*4) = 14
int y = (2 + 3) * 4;    // = 5 * 4 = 20
```

---

### Pitfall: Mixing `int`s and `double`s can truncate — watch out for **integer division**:

```java
int a = 5 / 2;         // yields 2, not 2.5
double b = 5 / 2;      // also 2.0 — still integer division before assigning
double c = 5 / 2.0;    // yields 2.5 — one operand is a double
```
