# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```
from binarytree import build
node=[1,2,3,4,5,6,7,8,None,None,None,9,10]
root=build(node)
for i in root.values:
    print(i,"--> ",end="")
print("\nThe postorder is ",root.postorder)
```

## OUTPUT
<img width="658" height="160" alt="447325596-c8491a2c-08ff-4ee6-90b7-49aa8243358c" src="https://github.com/user-attachments/assets/02082cdd-ccc7-4156-b751-ffc3ed310801" />

## RESULT
Thus, the Python program to build the given expression tree and print the inorder and postorder traversals was successfully implemented and verified.
