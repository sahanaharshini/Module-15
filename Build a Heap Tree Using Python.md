# Ex. No: 15D - Build a Heap Tree Using Python

## AIM:
To write a Python program to build a heap tree using appropriate Python package and function.

---

## ALGORITHM:

1. **Start the program.**
2. Import the `heapq` module.
3. Define a function `heaptree(H)` that takes a list `H` as input.
4. Use `heapq.heapify(H)` to convert the list into a min-heap.
5. Print the created heap.
6. **End the program.**

---

## PROGRAM:

```
from binarytree import heapq,build,Node
def heaptree(H):
    nodes=H
    root=build(nodes)
    for i in root.values:
        print(i,"-->",end="")
    print("\nHeight : ",root.height)
    print("Is max heap? : ",root.is_max_heap)
    print("Is complete tree? : ",root.is_complete)

```

## OUTPUT
<img width="1213" height="239" alt="447325770-6b2fec2c-dca4-45a7-b2bc-4c5afe6d3ca1" src="https://github.com/user-attachments/assets/4c1b2a69-afb1-49ac-b70d-9a26cb6678ae" />

## RESULT
Thus, the Python program to build a heap tree using appropriate Python package and function was successfully implemented and verified.
