# Java Basics

---

## Literals

- **Integer**: `1234`, `0xFF` (hex), `0b1010` (binary), `077` (octal)
- **Floating-point**: `3.14`, `2.71f` (float), `1.0e-9`
- **Boolean**: `true`, `false`
- **Char**: `'A'`, `'\n'`, `'\u20AC'`
- **String**: `"Hello\nJava"`

---

## Variables

### Declaration + Initialization

```java
int count = 0;
final double PI = 3.14159;  // constant
```

- **Scope**: local vs. instance vs. static  
- **Exception**: Uninitialized local variables cause compile-time error.

---

## Data Types & Sizes

| Type    | Size (bits) | Range                        |
|---------|-------------|------------------------------|
| byte    | 8           | –128 to 127                  |
| short   | 16          | –32,768 to 32,767            |
| int     | 32          | –2³¹ to 2³¹–1                |
| long    | 64          | –2⁶³ to 2⁶³–1                |
| float   | 32          | ~±3.4e38 (7 digits precision)|
| double  | 64          | ~±1.7e308 (16 digits precision)|
| char    | 16          | `'\u0000'` to `'\uFFFF'`     |
| boolean | —           | `true` or `false`            |

---

## Arithmetic Operators & Order

- **Operators**: `+` `-` `*` `/` `%`

### Order of Evaluation (from highest to lowest):
1. Parentheses `()`
2. Unary `+` `-` `++` `--`
3. Multiplicative `*` `/` `%`
4. Additive `+` `-`
5. Relational `<` `<=` `>` `>=`
6. Equality `==` `!=`
7. Logical `&&` `||`
8. Assignment `=`, `+=`, `-=`, ...

---

## String Concatenation & Special Characters

```java
String greeting = "Hello, " + "world!\n";  // "Hello, world!" + newline
System.out.print("Col1\tCol2");            // tab between columns
```
