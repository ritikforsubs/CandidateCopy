

## Question 1 — Python DSA

Given a list of integers `nums` and an integer `target`, return the indices of the two numbers that add up to `target`.

Assume exactly one solution exists, and you may not use the same element twice.

**Example**

```
Input:  nums = [2, 7, 11, 15], target = 9
Output: [0, 1]
```


## Question 1B — Python DSA


Given a string `s` containing only the characters `(`, `)`, `{`, `}`, `[` and `]`, determine if the input string is valid.

A string is valid if:

1. Open brackets are closed by the same type of brackets  
2. Open brackets are closed in the correct order  
3. Every close bracket has a corresponding open bracket of the same type

**Examples**

```
Input:  s = "()"
Output: True

Input:  s = "()[]{}"
Output: True

Input:  s = "(]"
Output: False

Input:  s = "([)]"
Output: False
```
---

## Question 2 — SQL:
### Schema

```sql
students (id, name, class_id)
classes (id, class_name)
```

**Sample data**

| students | | |
|----------|--|--|
| id | name | class_id |
| 1 | Rahul | 1 |
| 2 | Priya | 1 |
| 3 | Amit | 2 |

| classes | |
|---------|--|
| id | class_name |
| 1 | Python |
| 2 | SQL |


Write a SQL query to show each **student's name** and their **class name**.

Example output:

```
Rahul   Python
Priya   Python
Amit    SQL
```
