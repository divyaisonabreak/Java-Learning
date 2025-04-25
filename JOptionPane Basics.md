## JOptionPane Basics

```java
import javax.swing.JOptionPane;

String name = JOptionPane.showInputDialog("Enter your name:");
JOptionPane.showMessageDialog(null, "Hello, " + name + "!");
```

---

### ⚠️ Note

Running in a **console-only environment** will throw a **`HeadlessException`**  
✅ Make sure the environment supports a **Graphical User Interface (GUI)**.
