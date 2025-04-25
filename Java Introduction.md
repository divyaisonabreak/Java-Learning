# Java Introduction

## What is Java and Why It Got Famous

### Definition
Java is a high-level, object-oriented programming language and computing platform first released by Sun Microsystems in 1995.

### "Write Once, Run Anywhere" (WORA)
Java programs compile to bytecode, which runs on any device equipped with a Java Virtual Machine (JVM).

---

### Compilation and Execution Flow

```bash
.java → javac → .class (bytecode) → JVM executes
```

---

## Key Strengths
- Strong standard library (collections, I/O, networking, GUI, concurrency...).
- Automatic memory management (garbage collection).
- Large community & ecosystem (Spring, Jakarta EE, Android).

---

## Common Pitfall
⚠️ **Beware of platform-specific libraries** (e.g., native OS calls) that can break the "Write Once, Run Anywhere" (WORA) promise.

---

# Java Program Running Process

1. Write source code (`Hello.java`).
2. Compile it using `javac Hello.java` → produces `Hello.class`.
3. Run using `java Hello`, which:
   - JVM loads bytecode,
   - Verifies it,
   - JIT-compiles frequently used ("hot") code to native machine code.

---

## Execution Flow
- **ClassLoader** → Loads classes at runtime.
- **Bytecode Verifier** → Ensures code correctness and security.
- **Interpreter / JIT Compiler** → Executes the program efficiently.
- **Garbage Collector** → Manages memory automatically.

---

# Basic Structure & Comments

```java
// Single-line comment

/*
 Multi-line comment
*/

/**
 * Javadoc comment
 * @author You
 */
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
```

💡 **Tip**: Always include Javadoc (`/** ... */`) on public classes and methods so IDEs and tools can generate clean, structured API documentation.
