# Week 1: Session 1

## Strings & Arrays

Students will be introduced to the foundational concepts of strings and arrays in Python, which are essential for solving common coding problems. They will also learn about the UPI method, a structured approach to planning and solving technical interview questions. The lesson will cover basic operations like accessing, iterating over, and modifying lists, as well as performing advanced string manipulation.

### Problem Set Version 1

- [ ] Problem 1: Hunny Hunt
- [ ] Problem 2: Bouncy, Flouncy, Trouncy, Pouncy
- [ ] Problem 3: T-I-Double Guh-Er II
- [ ] Problem 4: Non-decreasing Array
- [ ] Problem 5: Missing Clues
- [ ] Problem 6: Vegetable Harvest
- [ ] Problem 7: Eeyore's House
- [ ] Problem 8: Local Maximums
 
### Problem Set Version 2

- [ ] Problem 1: Words Containing Character
- [ ] Problem 2: HulkSmash
- [ ] Problem 3: Encode
- [ ] Problem 4: Good Samaritan
- [ ] Problem 5: Heist
- [ ] Problem 6: Smaller Than
- [ ] Problem 7: Diagonal
- [ ] Problem 8: Defuse the Bomb

# Problem Set Version 1

### Problem 1: Hunny Hunt

Write a function `linear_search()` to help Winnie the Pooh locate his lost items. The function accepts a list `items` and a `target` value as parameters. The function should return the first index of `target` in `items`, and `-1` if `target` is not in `items`. Do not use any built-in functions.

```python
def linear_search(items, target):
    pass
```

```python
items = ['haycorn', 'haycorn', 'haycorn', 'hunny', 'haycorn']
target = 'hunny'
linear_search(items, target)

items = ['bed', 'blue jacket', 'red shirt', 'hunny']
target = 'red balloon'
linear_search(items, target)
```

```shellcode
3
-1
```

## Problem 2 (Bouncy, Flouncy, Trouncy, Pouncy)

Tigger has developed a new programming language Tiger with only **four** operations and **one** variable `tigger`.

* `bouncy` and `flouncy` both **increment** the value of the variable `tigger` by `1`.
* `trouncy` and `pouncy` both **decrement** the value of the variable `tigger` by `1`.

Initially, the value of `tigger` is `1` because he's the only tigger around! Given a list of strings `operations` containing a list of operations, return the **final** value of `tigger` after performing all the operations.

```python
def final_value_after_operations(operations):
    pass
```

```python
operations = ["trouncy", "flouncy", "flouncy"]
final_value_after_operations(operations)

operations = ["bouncy", "bouncy", "flouncy"]
final_value_after_operations(operations)
```

```shellcode
2
4
```