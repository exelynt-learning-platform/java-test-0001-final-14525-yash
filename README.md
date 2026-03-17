# java-test-0001-final-14525-yash
Java Test 0001 - Diamond Pattern

📌 Project Description

This project implements a Java program to print a diamond pattern using stars ("*").
The pattern is generated using nested loops and follows a symmetric structure.

---

🎯 Objective

- To understand and implement nested loops in Java
- To generate a diamond pattern with 9 rows
- To maintain clean and readable code using constants

---

🧾 Pattern Output

    *
   * *
  * *
 * *
* *
 * *
  * *
   * *
    *

---

⚙️ Logic Used

- A constant "TOTAL_ROWS = 9" is used to define total rows (avoids magic numbers)
- The middle row is calculated using:
  mid = TOTAL_ROWS / 2
- For each row:
  - The distance from the middle is calculated using:
    Math.abs(mid - i)
  - Spaces are printed based on this distance
  - Stars ("*") are printed to form the diamond shape
- Top and bottom rows print a single "*"
- All other rows print "* *"

---

💻 Code Structure

- "main()" method controls the loop
- Uses:
  - "for" loops
  - "Math.abs()" function
- Clean and optimized logic with no redundancy

---

✅ Features

- No hardcoded values (uses constant)
- Symmetrical diamond pattern
- Easy to understand and well-structured code
- Suitable for beginners and academic assignments

---

🚀 How to Run

1. Open the project in any Java IDE (Eclipse / IntelliJ / VS Code)
2. Compile the program:
   javac DiamondPattern.java
3. Run the program:
   java DiamondPattern

---

📚 Concepts Covered

- Nested loops
- Conditional statements
- Pattern printing
- Code optimization using constants


