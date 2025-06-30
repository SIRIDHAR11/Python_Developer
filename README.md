# 🐍 Python Mini Project – Core Programs

**Name:** Samanasa Hema Durga Siridhar  
**Branch:** IT  
**Year:** 2nd Year, Semester 4  
**Tool Used:** IntelliJ IDEA (Python)

---

## 📌 Overview

This mini project covers several foundational Python programs designed to strengthen understanding of key programming concepts like loops, functions, conditionals, and string operations. A custom implementation of the Caesar Cipher is also included to demonstrate basic encryption logic.

---

## 🔢 Core Programs

### 1. Sum of Two Numbers
- **Approach:**  
  Created a function that takes two integers and returns their sum.
- **Challenges:**  
  None — simple arithmetic.
- **Solution:**  
  Used `a + b` inside a function and returned the result.

### 2. Odd or Even
- **Approach:**  
  Checked if a number is divisible by 2.
- **Challenges:**  
  Straightforward logic.
- **Solution:**  
  Used the modulus operator `%` to check parity.

### 3. Factorial Calculation
- **Approach:**  
  Implemented both a manual loop and `math.factorial()` for factorial calculation.
- **Challenges:**  
  Understanding loop control for multiplication.
- **Solution:**  
  Used a `for` loop from 1 to `n`, multiplying iteratively, and also used the built-in function.

### 4. Fibonacci Sequence
- **Approach:**  
  Generated the sequence using two variables updated iteratively.
- **Challenges:**  
  Maintaining current and next terms correctly.
- **Solution:**  
  Used a `for` loop with `a, b = 0, 1` and then `a, b = b, a + b`.

### 5. Reverse a String
- **Approach:**  
  Utilized Python slicing to reverse the input string.
- **Challenges:**  
  None.
- **Solution:**  
  Returned `s[::-1]`.

### 6. Palindrome Check
- **Approach:**  
  Compared the original string with its reversed version.
- **Challenges:**  
  Could consider ignoring case and spaces in future versions.
- **Solution:**  
  Used `s == s[::-1]`.

### 7. Leap Year Check
- **Approach:**  
  Applied the standard leap year rule.
- **Challenges:**  
  Handling the 100-and-400 divisibility case correctly.
- **Solution:**  
  Used: `(year % 4 == 0 and year % 100 != 0) or (year % 400 == 0)`

### 8. Armstrong Number
- **Approach:**  
  Raised each digit to the power of the number of digits and checked the sum.
- **Challenges:**  
  Converting between integers and strings.
- **Solution:**  
  Used: `sum(int(d)**power for d in str(n)) == n`

---

### 9. Prime Number Check
**Approach:**  
Checked divisibility of number from 2 to √n.

**Challenges Faced:**  
Understanding loop range and efficiency.

**Learning:**  
Gained knowledge about prime number checking logic.

---

### 10. Sum of Digits
**Approach:**  
Converted number to string, iterated through digits, and summed them.

**Challenges Faced:**  
Handling negative numbers by using absolute value.

**Learning:**  
Learned digit-wise operations.

---

### 11. LCM and GCD
**Approach:**  
Used Python’s `math.gcd()` for GCD and formula for LCM.

**Challenges Faced:**  
Understanding GCD-LCM relationship.

**Learning:**  
Learned use of built-in math library and number theory basics.

---

### 12. List Reversal (Without Built-in reverse())
**Approach:**  
Reversed a list manually using two-pointer method.

**Challenges Faced:**  
Handling index swapping correctly.

**Learning:**  
Strengthened knowledge of list indexing.

---

### 13. Sort a List
**Approach:**  
Used Python’s built-in `sorted()` function to sort the list.

**Challenges Faced:**  
None.

**Learning:**  
Practiced use of built-in functions.

---

### 14. Remove Duplicates from List
**Approach:**  
Converted list to set and back to list to remove duplicates.

**Challenges Faced:**  
Preserving original order (could improve using collections in future).

**Learning:**  
Learned about Python sets and their properties.

---

### 15. String Length (Without len())
**Approach:**  
Manually counted characters in a string using a loop.

**Challenges Faced:**  
None.

**Learning:**  
Strengthened looping concepts.

---

### 16. Count Vowels and Consonants
**Approach:**  
Iterated through each character and checked if it’s a vowel or consonant.

**Challenges Faced:**  
Differentiating between vowels, consonants, and non-alphabet characters.

**Learning:**  
Improved string iteration and conditional checks.

---

### 17. Caesar Cipher (Encryption & Decryption)
**Approach:**  
Shifted each letter by a key value (both for encryption and decryption).

**Challenges Faced:**
- Handling wrap-around cases for 'z' and 'Z'.
- Maintaining case sensitivity.
- Ignoring special characters.

**Learning:**  
Learned basics of text encryption and decryption.

---

### 18. Maze Generator and Solver
**Approach:**  
Created a simple 2D maze using lists and solved it using depth-first search (DFS) or similar traversal.

**Challenges Faced:**
- Representing the maze grid.
- Finding a path from start to end.
- Handling boundary conditions.

**Learning:**  
Understood recursion and backtracking. Gained knowledge of problem-solving in grid-based environments.

---

## ✅ Conclusion:

This mini project helped me:

- Strengthen my core Python programming skills.
- Learn how to write clean functions.
- Practice loops, conditionals, string manipulation, list operations, and basic algorithms.
- Implement simple encryption techniques like Caesar Cipher.
- Work on logic building and problem-solving.

---