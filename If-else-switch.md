# Decision Structures: if / switch

```java
int x = 2;
if (x > 0) {
    // …
} else if (x < 0) {
    // …
} else {
    // x == 0
}

switch (x) {
    case 1: System.out.println("One"); break;
    case 2: System.out.println("Two"); break;
    default: System.out.println("Other");
}
```

---

### ⚠️ Pitfall

Forgetting `break` → **fall-through** to the next case.

---
