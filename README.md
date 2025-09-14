# Codes
Data structures and algorithms 
# Assignment 1 – Palindrome Number

**Problem Statement:**
Given an integer `x`, return `true` if `x` is a palindrome, and `false` otherwise.

A palindrome is a number that reads the same backward as forward.

**Examples:**
- Input: 121 → Output: true
- Input: -121 → Output: false
- Input: 10 → Output: false
- 
def is_palindrome(x: int) -> bool:
    # Negative numbers are not palindrome
    if x < 0:
        return False
    
    # Convert number to string and compare with reverse
    return str(x) == str(x)[::-1]


# Test cases
print(is_palindrome(121))   # True
print(is_palindrome(-121))  # False
print(is_palindrome(10))    # False
