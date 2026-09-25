# 🧠 Daily LeetCode Practice

Welcome to my **Daily LeetCode Practice** repository.

This repository contains my solutions and learning notes as I practice coding problems on **LeetCode** every day. My goal is to improve my problem-solving skills, strengthen my Python knowledge, and prepare myself for real-world software engineering and technical interviews.

## 🎯 Goals

- 🐍 Improve my Python programming skills
- 🧠 Develop better problem-solving skills
- 📚 Learn and understand Data Structures & Algorithms
- 💻 Solve at least one LeetCode problem every day
- 🔍 Learn different approaches to solving problems
- 🚀 Prepare for technical interviews
- 📈 Track my progress over time

## 🗂️ Repository Structure

```text
daily-leetcode-practice/
│
├── Easy/
│   ├── Two_Sum.py
│   ├── Palindrome_Number.py
│   └── ...
│
├── Medium/
│   ├── ...
│
├── Hard/
│   ├── ...
│
└── README.md
```

## 📅 Daily Practice

Each solution may contain:

- Problem name
- Problem number
- Difficulty
- Problem-solving approach
- Python solution
- Time complexity
- Space complexity
- Notes and lessons learned

### Example

```python
# Problem: Two Sum
# Difficulty: Easy

def twoSum(nums, target):
    seen = {}

    for i, num in enumerate(nums):
        difference = target - num

        if difference in seen:
            return [seen[difference], i]

        seen[num] = i
```

### Complexity

- **Time:** O(n)
- **Space:** O(n)

## 📊 Progress

| Difficulty | Solved |
|-----------|--------|
| 🟢 Easy | 7 |
| 🟡 Medium | 0 |
| 🔴 Hard | 0 |
| **Total** | **0** |

I will update this table as I solve more problems.

## 🧩 Topics I'm Learning

- Arrays
- Strings
- Hash Tables
- Two Pointers
- Sliding Window
- Stack
- Queue
- Linked Lists
- Binary Search
- Trees
- Graphs
- Recursion
- Dynamic Programming
- Sorting
- Searching
- Greedy Algorithms

## 📈 My Rule

> **Consistency over perfection.**

I don't need to solve every problem perfectly on the first attempt. The goal is to understand the problem, learn from mistakes, and become a better programmer every day.

## 🛠️ Language

My main programming language for this challenge is:

**Python 🐍**

## 🔥 Challenge

**1 Problem → Every Day → Keep Improving**

I will use this repository to track my progress and document what I learn throughout my journey toward becoming a better software engineer.

## 👨‍💻 Author

**Udeh Marvelous**

- GitHub: https://github.com/Udehmarvelous
- LinkedIn: https://www.linkedin.com/in/udeh-chibuike-977259375/

---

⭐ If you're also practicing LeetCode, feel free to use this repository as inspiration for your own learning journey.
