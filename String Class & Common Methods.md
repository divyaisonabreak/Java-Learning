## String Class & Common Methods

```java
String s = "  Java Programming  ";

char c = s.charAt(2);                        // 'v'
boolean eq = s.equals("Java");              // false
boolean eqI = s.equalsIgnoreCase("java programming"); // true
int idx = s.indexOf("Prog");                // 7
int len = s.length();                       // 19
String low = s.toLowerCase();               // "  java programming  "
String high = s.toUpperCase();              // "  JAVA PROGRAMMING  "
String trimmed = s.trim();                  // "Java Programming"
```

---

### ⚠️ Pitfall

Calling `charAt()` on an out-of-range index throws **`StringIndexOutOfBoundsException`**.

---

### `substring()`

```java
String sub = s.substring(2, 6);  // from index 2 up to (but not including) 6
```

- ⚠️ **End index beyond `length()`** → will throw an exception.
