# 📘 Day 16: Exceptions - String to Integer | HackerRank 30 Days of Code

This repository contains the Python solution for **Day 16** of the HackerRank [30 Days of Code](https://www.hackerrank.com/domains/tutorials/30-days-of-code) challenge, which focuses on the concept of **exception handling** using Python's `try`/`except` structure.

## 🚀 Challenge Summary

-You are given a string input `S`.

-Your task is to convert it to an integer using `int(S)`. 

-If the conversion fails due to invalid input (e.g., alphabetic characters), catch the exception and print `"Bad String"`.

## 📝 Problem Statement

Complete a function that:

- Attempts to convert the string `S` to an integer.
  
- Uses exception handling (`try`/`except`) to catch conversion errors.
  
- Prints the integer value if successful, or `"Bad String"` if the conversion fails.

## 🔐 Constraints:
-1≤∣S∣≤6, where ∣S∣ is the length of string S.

-S is composed of either:

     -lowercase letters (a−z), or

     -decimal digits(0−9).

## 🔢 Sample Input

      3

## ✅ Sample Output

      3

### ❌ Invalid Input Example

      za

### ✅ Output

      Bad String

## 💡 Explanation

- For valid numeric input (e.g., `"3"`), `int(S)` succeeds and prints `3`.

- For invalid input (e.g., `"za"`), `int(S)` raises a `ValueError`, and the `except` block prints `"Bad String"`.
  
## 🧠 Concepts Practiced

- Exception Handling (`try`/`except`)
  
- Robust Input Parsing
  
- Clean Error Messages
  
- Avoiding program crashes due to invalid input
  
- Writing minimal, readable code

## 🛠 How to Run

Option 1: With input redirection

    python3 exceptions.py < input.txt

Option 2: Manual input

    python3 exceptions.py

Then, input a string manually and hit Enter.

## 🔗 HackerRank Challenge Link

HackerRank – Day 16: Exceptions – String to Integer

🏆 Challenge Completed

✅ Problem Solved

🎯 Points Earned: 30

## 📅 Completed On:

    28th May 2025

## 🔖 Tags

#Python #HackerRank #Exceptions #TryExcept #ErrorHandling #30DaysOfCode #ProblemSolving #Day16Challenge

## ✍ Author

    Harsha M  
    
    GitHub:   @Harshaharika7  
    
    LinkedIn: Harsha M
