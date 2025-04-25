## StringBuilder Class

```java
StringBuilder sb = new StringBuilder("Hello");

sb.append(", world!");
sb.insert(5, " Java");
sb.replace(0, 5, "Hi");
sb.reverse();

String result = sb.toString();
```

---

### ✅ Advantage

- **Mutable** and more **efficient** for many concatenations compared to `String`.

---

### ⚠️ Pitfall

- `StringBuilder` is **not thread-safe**.
- ➡️ Use **`StringBuffer`** if you need synchronized (thread-safe) operations.
