## Input with Scanner

```java
import java.util.Scanner;

Scanner sc = new Scanner(System.in);

System.out.print("Enter your name: ");
String name = sc.nextLine();

System.out.print("Enter age: ");
if (sc.hasNextInt()) {
    int age = sc.nextInt();
} else {
    System.err.println("Not a valid integer!");
}
```

---

### Useful Methods

- `hasNext()`, `hasNextInt()`, `hasNextDouble()`, `hasNextBoolean()`
- `next()`, `nextLine()`, `nextInt()`, `nextDouble()`, `nextBoolean()`

---

### ⚠️ Exception

Calling `nextInt()` when no `int` is available → throws **`InputMismatchException`**  
✅ Always guard it with `hasNextInt()` to avoid crashes.
