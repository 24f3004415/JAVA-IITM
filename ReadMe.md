1. Computers understand high level languages like Java, C.
Answer: False
Explanation: Computers only understand machine language (binary code consisting of `0`s and `1`s). High-level languages like Java and C are designed to be human-readable and must be translated into machine code using a compiler or interpreter before a computer can execute them.

---

2. An Algorithm is a set of instructions to accomplish a task.
Answer: True
Explanation: By definition, an algorithm is a finite, step-by-step set of well-defined instructions or rules designed to solve a specific problem or perform a computation.

---

3. Computer is smart enough to ignore incorrect syntax.
Answer: False
Explanation: Computers and compilers follow strict grammatical rules (syntax). Even a minor syntax mistake—such as a missing semicolon or misspelled keyword—will result in a syntax error (compile-time error), preventing the program from running.

---

4. Java was first released in 1992.
Answer: False
Explanation: While the Java project (originally called Oak) began in 1991, Sun Microsystems officially released Java 1.0 to the public in 1995 (with its initial alpha/beta announcements occurring in 1995 and full release in January 1996).

---

5. Java was named over a person who made good coffee.
Answer: False
Explanation: Java was named after Java coffee, a type of coffee grown on the Indonesian island of Java—not after a specific person. The creators at Sun Microsystems chose the name during a brainstorming session while drinking coffee.

---

6. ByteCode is platform independent.
Answer: True
Explanation: When Java source code (`.java`) is compiled, it turns into intermediate ByteCode (`.class`). This ByteCode can run on any operating system (Windows, macOS, Linux) that has a compatible Java Virtual Machine (JVM), giving Java its "Write Once, Run Anywhere" capability.

---

7. JDK is a part of JRE.
Answer: False
Explanation: It is the exact opposite: JRE (Java Runtime Environment) is a part of the JDK (Java Development Kit). The JDK contains the JRE plus development tools like the compiler (`javac`) and debugger needed to write and compile Java applications.

---

8. It's optional to declare main method as public.
Answer: False
Explanation: In standard Java applications, the `main` method must be declared as `public` (`public static void main(String[] args)`). Because the JVM invokes the `main` method from outside the class to start program execution, it requires `public` visibility to access it.

---

9. .class file contains machine code.
Answer: False
Explanation: A `.class` file contains Java ByteCode, not native machine code. The JVM reads this ByteCode and translates it into native machine code at runtime.

---

10. println adds a new line at the end of the line.
Answer: True
Explanation: In Java, `System.out.println()` prints the specified text to the console and then appends a line break (newline character), moving the cursor to the beginning of the next line. (In contrast, `System.out.print()` keeps the cursor on the same line.)