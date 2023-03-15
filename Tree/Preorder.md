## Preoder Traversal Of Tree

![image](https://user-images.githubusercontent.com/39462578/225216188-4edc1881-2c12-438a-81ab-4ba956753727.png)

## Approach 1 : Recursive Solution

**Intuition:** In preorder traversal, the tree is traversed in this way: root, left, right. When we visit a node, we print its value, and then we want to visit the left child followed by the right child. The fundamental problem we face in this scenario is that there is no way that we can move from a child to a parent. To solve this problem, we use recursion and the recursive call stack to locate ourselves back to the parent node when execution at a child node is completed.

**Approach:** In preorder traversal, the tree is traversed in this way: root, left, right.

The algorithm approach can be stated as:

- We first visit the root node and before visiting its children we print its value.
- After this, we recursively visit its left child.
- Then we recursively visit the right child.
- If we encounter a node pointing to NULL, we simply return to its parent.
