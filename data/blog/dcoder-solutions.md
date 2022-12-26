---
title: Dcoder App Solutions in Python3
date: '2016-03-08'
tags: ['Dcoder', 'Dcoder.tech', 'problems', 'solutions to problems', 'word problems', 'python']
draft: false
summary:
  Answers for solutions to problems on Dcoder.tech website and mobile application for iOS and Android.
  These solutions are coded in JavaScript or Python3
---

# [Dcoder](https://dcoder.tech) Solutions

Dcoder is a website and mobile application (for iOS and Android) that provide a REPL of HTML5, CSS3, and JavaScript (ES6). Also found on the site are world problems similar to what you would see on sites such as [HackerRank](https://www.hackerrank.com/) or [LeetCode](https://www.leetcode.com).

## Python3 problems:

1. INPUT: two integers A and B, a list of integers C
   1a. OUTPUT: a list of integers lst
   1b. first integer of input is length of list comprehension, second is target integer. Create a list comprehension with correct length using space seperated integers form C, use a for loop to iterate through, adding all the items matching target integer to return list.

```python
A = int(input())
B = int(input())

nums = [int(x) for x in input().split(" ")]
lst = []
for elem in nums:
    if B in nums:
        lst.push(B)
print(lst)
```
