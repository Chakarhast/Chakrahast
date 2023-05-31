# **AVL Trees**
> AVL is based on G. M. **A**delson-**V**elskii and E. M. **L**andis.

## **Why Were Binary Trees Not Sufficient?**
1. Height of Trees depend on `input sequence` of numbers. 
2. If input is either sorted or reverse-sorted then the tree is essentially a linked list. Worst case search complexity: `O(n)`
3. We want to take advantage of the `O(logn)` search time that a balanced tree can provide.

## **Some Definitions**

 Keyword | Defintion |
| ------ | ----------- |
| Full binary tree  | A full binary tree is one in which all nodes have either two children or none. |
| Complete binary tree | Every level, except possibly the last,is completely filled, and all nodes in the last level are as far left as possible.|
| Balanced tree | Left subtree of the root node is same depth as the Right subtree. But perfectly balanced tree is `restrictive`.|
