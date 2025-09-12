# Experiment 15 : Recursion in C++

---

## Aim
- To study and implement **Recursion in C++**.  
- To understand how functions can **call themselves** to solve problems.  
- To demonstrate the use of recursion in **mathematical and algorithmic problems**.  

---

## Tools Used
- VS Code  
- Online C++ Compiler

---

## Objectives
- To understand the concept of **recursive functions**.  
- To identify **base case** and **recursive case** in a function.  
- To implement recursion for **factorial, Fibonacci series, and other examples**.  
- To learn the **advantages and disadvantages** of recursion.  
- To explore **tail recursion** and **non-tail recursion**.  

---

## Theory

### What is Recursion?
---

- Recursion is a programming technique where a function **calls itself** to solve smaller instances of a problem.  
- It simplifies complex problems by dividing them into **sub-problems**.  

---

### Key Concepts
---

- **Base Case:** The condition that terminates recursion.  
- **Recursive Case:** The part where the function calls itself with modified arguments.  
- **Call Stack:** Each recursive call is stored on the stack; execution resumes after the base case is reached.  

---

### Types of Recursion
---

- **Direct Recursion:** Function calls itself directly.  
- **Indirect Recursion:** Function A calls Function B, which eventually calls Function A.  
- **Tail Recursion:** Recursive call is the **last statement** in the function.  
- **Non-Tail Recursion:** Recursive call is followed by additional operations.  

---

### Why Recursion is Useful?
---

- Simplifies **algorithm design** for problems like trees, graphs, and divide-and-conquer.  
- Makes code **cleaner** and easier to read.  
- Enables **backtracking** for puzzles like N-Queens or maze problems.  
- Allows natural solution for **mathematical series** (factorial, Fibonacci, etc.).  

---

## Advantages of Recursion
---

- Reduces code complexity for problems with repetitive sub-problems.  
- Supports elegant solutions for mathematical and data structure problems.  
- Useful in **tree and graph traversals**.  
- Easier to implement **divide-and-conquer algorithms**.  

---

## Disadvantages of Recursion
---

- High memory usage due to call stack.  
- Risk of stack overflow for deep recursion.  
- Sometimes slower than iterative solutions.  
- May be harder to debug in complex scenarios.  

---

## Algorithm

### Program 1: Factorial of a Number
---

1. Start the program.  
2. Declare integer `n`.  
3. Prompt user to enter a number.  
4. Read `n`.  
5. Define a recursive function `factorial(n)`:  
   - If `n == 0` → return 1 (base case).  
   - Else → return `n * factorial(n-1)` (recursive case).  
6. Call the factorial function and display the result.  
7. End the program.

---  


## Applications
---

- **Mathematical problems:** Factorial, Fibonacci, GCD  
- **Data structures:** Tree and graph traversal  
- **Algorithms:** Merge Sort, Quick Sort  
- **Puzzle solving:** Tower of Hanoi, N-Queens  
- **Backtracking problems:** Maze solving, Sudoku  

---

## Concepts Used
---

- Recursive function calls.  
- Base case and recursive case.  
- Call stack mechanism.  
- Mathematical problem solving using recursion.  

---

## Conclusion
---

- Recursion is a powerful programming technique where a function calls itself to solve a problem.
- It helps in breaking complex problems into smaller, manageable sub-problems.
- Recursive solutions are often cleaner and easier to understand than iterative ones, especially for problems like factorial, Fibonacci series, tree traversal, and backtracking puzzles.
- Proper use of base case and recursive case is essential to prevent infinite recursion and stack overflow.
- While recursion simplifies problem-solving and code readability, it may have higher memory usage and sometimes lower performance compared to iteration.

---
