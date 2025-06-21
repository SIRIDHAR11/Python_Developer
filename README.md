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

## 🔐 Caesar Cipher – Custom Encryption & Decryption

### Approach
The Caesar Cipher is implemented manually to demonstrate the fundamentals of encryption. The user inputs plain text and a key (number of positions to shift), and the program returns encrypted or decrypted text depending on the mode.

### Challenges
- Ensuring correct handling of both uppercase and lowercase letters.
- Preserving special characters and spacing.
- Managing wrap-around when letters go beyond `'Z'` or `'z'`.

### Solution
- Used `ord()` to get ASCII value.
- Normalized position to 0–25 range using base values (`'A'` or `'a'`).
- Applied `(position + shift) % 26` for wrap-around.
- Converted result back to character using `chr()`.
- For decryption, used the same function with a negative shift.

---

## 📘 What I Learned

This project helped reinforce key programming skills such as:
- Writing clean and modular code using functions.
- Mastering loops, conditionals, and string manipulations.
- Understanding how basic encryption techniques work.

The Caesar Cipher task gave me hands-on experience with basic encryption and improved my ability to reflect and communicate technical solutions — a crucial skill for any future developer.

---

## ✅ Conclusion

This mini project was a great opportunity to strengthen Python fundamentals and explore real-world logic applications. It boosted both my coding skills and confidence in problem-solving and technical documentation.

