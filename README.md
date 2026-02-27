# PalindromeCheckerApp

## Objective
This project is a simple Java console app that checks whether a word or phrase is a palindrome. It uses a **Deque** to efficiently compare characters from the start and end of the string.

## How It Works
1. The user enters a string.
2. The app converts it to lowercase and removes spaces.
3. Each character is added to a **Deque**.
4. The app compares characters from the front and back until the string is fully checked.
5. It tells the user whether the input is a palindrome or not.

## Use Case (UC7)
We specifically use a **Deque** to make the comparison faster and more memory-efficient — no need to reverse the string manually.

---
