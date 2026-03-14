# LeetCode 算法进阶：医学图像算法工程师之路

本项目用于记录 LeetCode 刷题历程，重点侧重于医学图像处理相关的**矩阵运算、连通域搜索、信号处理**及**计算机视觉基础算法**。

## 🛠 技术栈
- **语言**: Python, C++
- **重点领域**: 图像分割、特征提取、空间几何变换

## 📅 刷题进度追踪

| 推荐顺序 | 优先级 | 题号   | 题目名称                                                                                                                                                 | 难度 | 知识点            | 状态     | 二刷 | 解法链接 |
| :--- | :-- | :--- | :--------------------------------------------------------------------------------------------------------------------------------------------------- | :- | :------------- | :----- | :- | :--- |
| 1    | S   | 1    | [Two Sum](https://leetcode.cn/problems/two-sum/)                                                                                                     | 简单 | 哈希             | 🟢 已完成 | ⬜  | [Python](./Hash/TwoSum.py)、[C++](./Hash/TwoSum.cpp)    |
| 2    | S   | 20   | [Valid Parentheses](https://leetcode.cn/problems/valid-parentheses/)                                                                                 | 简单 | 栈              | 🔴 待挑战 | ⬜  | -    |
| 3    | S   | 206  | [Reverse Linked List](https://leetcode.cn/problems/reverse-linked-list/)                                                                             | 简单 | 链表             | 🔴 待挑战 | ⬜  | -    |
| 4    | S   | 21   | [Merge Two Sorted Lists](https://leetcode.cn/problems/merge-two-sorted-lists/)                                                                       | 简单 | 链表             | 🔴 待挑战 | ⬜  | -    |
| 5    | S   | 141  | [Linked List Cycle](https://leetcode.cn/problems/linked-list-cycle/)                                                                                 | 简单 | 链表 / 快慢指针      | 🔴 待挑战 | ⬜  | -    |
| 6    | S   | 704  | [Binary Search](https://leetcode.cn/problems/binary-search/)                                                                                         | 简单 | 二分查找           | 🔴 待挑战 | ⬜  | -    |
| 7    | S   | 94   | [Binary Tree Inorder Traversal](https://leetcode.cn/problems/binary-tree-inorder-traversal/)                                                         | 简单 | 二叉树遍历          | 🔴 待挑战 | ⬜  | -    |
| 8    | S   | 104  | [Maximum Depth of Binary Tree](https://leetcode.cn/problems/maximum-depth-of-binary-tree/)                                                           | 简单 | 二叉树递归          | 🔴 待挑战 | ⬜  | -    |
| 9    | S   | 226  | [Invert Binary Tree](https://leetcode.cn/problems/invert-binary-tree/)                                                                               | 简单 | 二叉树递归          | 🔴 待挑战 | ⬜  | -    |
| 10   | S   | 70   | [Climbing Stairs](https://leetcode.cn/problems/climbing-stairs/)                                                                                     | 简单 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 11   | S   | 121  | [Best Time to Buy and Sell Stock](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/)                                                     | 简单 | 动态规划 / 贪心      | 🔴 待挑战 | ⬜  | -    |
| 12   | S   | 283  | [Move Zeroes](https://leetcode.cn/problems/move-zeroes/)                                                                                             | 简单 | 双指针            | 🔴 待挑战 | ⬜  | -    |
| 13   | A   | 217  | [Contains Duplicate](https://leetcode.cn/problems/contains-duplicate/)                                                                               | 简单 | 哈希             | 🔴 待挑战 | ⬜  | -    |
| 14   | A   | 242  | [Valid Anagram](https://leetcode.cn/problems/valid-anagram/)                                                                                         | 简单 | 哈希 / 计数        | 🔴 待挑战 | ⬜  | -    |
| 15   | A   | 169  | [Majority Element](https://leetcode.cn/problems/majority-element/)                                                                                   | 简单 | 哈希 / 摩尔投票      | 🔴 待挑战 | ⬜  | -    |
| 16   | A   | 26   | [Remove Duplicates from Sorted Array](https://leetcode.cn/problems/remove-duplicates-from-sorted-array/)                                             | 简单 | 双指针            | 🔴 待挑战 | ⬜  | -    |
| 17   | A   | 88   | [Merge Sorted Array](https://leetcode.cn/problems/merge-sorted-array/)                                                                               | 简单 | 双指针            | 🔴 待挑战 | ⬜  | -    |
| 18   | A   | 125  | [Valid Palindrome](https://leetcode.cn/problems/valid-palindrome/)                                                                                   | 简单 | 双指针 / 字符串      | 🔴 待挑战 | ⬜  | -    |
| 19   | A   | 14   | [Longest Common Prefix](https://leetcode.cn/problems/longest-common-prefix/)                                                                         | 简单 | 字符串            | 🔴 待挑战 | ⬜  | -    |
| 20   | A   | 28   | [Find the Index of the First Occurrence in a String](https://leetcode.cn/problems/find-the-index-of-the-first-occurrence-in-a-string/)               | 简单 | 字符串            | 🔴 待挑战 | ⬜  | -    |
| 21   | A   | 680  | [Valid Palindrome II](https://leetcode.cn/problems/valid-palindrome-ii/)                                                                             | 简单 | 双指针 / 字符串      | 🔴 待挑战 | ⬜  | -    |
| 22   | A   | 111  | [Minimum Depth of Binary Tree](https://leetcode.cn/problems/minimum-depth-of-binary-tree/)                                                           | 简单 | 二叉树递归          | 🔴 待挑战 | ⬜  | -    |
| 23   | A   | 101  | [Symmetric Tree](https://leetcode.cn/problems/symmetric-tree/)                                                                                       | 简单 | 二叉树递归          | 🔴 待挑战 | ⬜  | -    |
| 24   | A   | 110  | [Balanced Binary Tree](https://leetcode.cn/problems/balanced-binary-tree/)                                                                           | 简单 | 二叉树递归          | 🔴 待挑战 | ⬜  | -    |
| 25   | A   | 112  | [Path Sum](https://leetcode.cn/problems/path-sum/)                                                                                                   | 简单 | 二叉树路径          | 🔴 待挑战 | ⬜  | -    |
| 26   | A   | 35   | [Search Insert Position](https://leetcode.cn/problems/search-insert-position/)                                                                       | 简单 | 二分查找           | 🔴 待挑战 | ⬜  | -    |
| 27   | A   | 69   | [Sqrt(x)](https://leetcode.cn/problems/sqrtx/)                                                                                                       | 简单 | 二分查找           | 🔴 待挑战 | ⬜  | -    |
| 28   | A   | 703  | [Kth Largest Element in a Stream](https://leetcode.cn/problems/kth-largest-element-in-a-stream/)                                                     | 简单 | 堆              | 🔴 待挑战 | ⬜  | -    |
| 29   | B   | 27   | [Remove Element](https://leetcode.cn/problems/remove-element/)                                                                                       | 简单 | 双指针            | 🔴 待挑战 | ⬜  | -    |
| 30   | B   | 160  | [Intersection of Two Linked Lists](https://leetcode.cn/problems/intersection-of-two-linked-lists/)                                                   | 简单 | 链表 / 双指针       | 🔴 待挑战 | ⬜  | -    |
| 31   | B   | 234  | [Palindrome Linked List](https://leetcode.cn/problems/palindrome-linked-list/)                                                                       | 简单 | 链表             | 🔴 待挑战 | ⬜  | -    |
| 32   | B   | 232  | [Implement Queue using Stacks](https://leetcode.cn/problems/implement-queue-using-stacks/)                                                           | 简单 | 栈和队列           | 🔴 待挑战 | ⬜  | -    |
| 33   | B   | 225  | [Implement Stack using Queues](https://leetcode.cn/problems/implement-stack-using-queues/)                                                           | 简单 | 栈和队列           | 🔴 待挑战 | ⬜  | -    |
| 34   | B   | 415  | [Add Strings](https://leetcode.cn/problems/add-strings/)                                                                                             | 简单 | 字符串 / 模拟       | 🔴 待挑战 | ⬜  | -    |
| 35   | A   | 49   | [Group Anagrams](https://leetcode.cn/problems/group-anagrams/)                                                                                       | 中等 | 哈希分组           | 🔴 待挑战 | ⬜  | -    |
| 36   | S   | 128  | [Longest Consecutive Sequence](https://leetcode.cn/problems/longest-consecutive-sequence/)                                                           | 中等 | 哈希             | 🔴 待挑战 | ⬜  | -    |
| 37   | S   | 11   | [Container With Most Water](https://leetcode.cn/problems/container-with-most-water/)                                                                 | 中等 | 双指针            | 🔴 待挑战 | ⬜  | -    |
| 38   | S   | 15   | [3Sum](https://leetcode.cn/problems/3sum/)                                                                                                           | 中等 | 排序 / 双指针       | 🔴 待挑战 | ⬜  | -    |
| 39   | A   | 167  | [Two Sum II - Input Array Is Sorted](https://leetcode.cn/problems/two-sum-ii-input-array-is-sorted/)                                                 | 中等 | 双指针            | 🔴 待挑战 | ⬜  | -    |
| 40   | S   | 3    | [Longest Substring Without Repeating Characters](https://leetcode.cn/problems/longest-substring-without-repeating-characters/)                       | 中等 | 滑动窗口           | 🔴 待挑战 | ⬜  | -    |
| 41   | A   | 209  | [Minimum Size Subarray Sum](https://leetcode.cn/problems/minimum-size-subarray-sum/)                                                                 | 中等 | 滑动窗口           | 🔴 待挑战 | ⬜  | -    |
| 42   | A   | 438  | [Find All Anagrams in a String](https://leetcode.cn/problems/find-all-anagrams-in-a-string/)                                                         | 中等 | 滑动窗口           | 🔴 待挑战 | ⬜  | -    |
| 43   | A   | 567  | [Permutation in String](https://leetcode.cn/problems/permutation-in-string/)                                                                         | 中等 | 滑动窗口           | 🔴 待挑战 | ⬜  | -    |
| 44   | S   | 560  | [Subarray Sum Equals K](https://leetcode.cn/problems/subarray-sum-equals-k/)                                                                         | 中等 | 前缀和 / 哈希       | 🔴 待挑战 | ⬜  | -    |
| 45   | S   | 2    | [Add Two Numbers](https://leetcode.cn/problems/add-two-numbers/)                                                                                     | 中等 | 链表             | 🔴 待挑战 | ⬜  | -    |
| 46   | S   | 19   | [Remove Nth Node From End of List](https://leetcode.cn/problems/remove-nth-node-from-end-of-list/)                                                   | 中等 | 链表 / 双指针       | 🔴 待挑战 | ⬜  | -    |
| 47   | S   | 142  | [Linked List Cycle II](https://leetcode.cn/problems/linked-list-cycle-ii/)                                                                           | 中等 | 链表 / 快慢指针      | 🔴 待挑战 | ⬜  | -    |
| 48   | A   | 24   | [Swap Nodes in Pairs](https://leetcode.cn/problems/swap-nodes-in-pairs/)                                                                             | 中等 | 链表             | 🔴 待挑战 | ⬜  | -    |
| 49   | A   | 138  | [Copy List with Random Pointer](https://leetcode.cn/problems/copy-list-with-random-pointer/)                                                         | 中等 | 链表 / 哈希        | 🔴 待挑战 | ⬜  | -    |
| 50   | B   | 148  | [Sort List](https://leetcode.cn/problems/sort-list/)                                                                                                 | 中等 | 链表 / 归并排序      | 🔴 待挑战 | ⬜  | -    |
| 51   | S   | 155  | [Min Stack](https://leetcode.cn/problems/min-stack/)                                                                                                 | 中等 | 栈 / 设计         | 🔴 待挑战 | ⬜  | -    |
| 52   | A   | 394  | [Decode String](https://leetcode.cn/problems/decode-string/)                                                                                         | 中等 | 栈 / 字符串        | 🔴 待挑战 | ⬜  | -    |
| 53   | S   | 739  | [Daily Temperatures](https://leetcode.cn/problems/daily-temperatures/)                                                                               | 中等 | 单调栈            | 🔴 待挑战 | ⬜  | -    |
| 54   | A   | 496  | [Next Greater Element I](https://leetcode.cn/problems/next-greater-element-i/)                                                                       | 简单 | 单调栈            | 🔴 待挑战 | ⬜  | -    |
| 55   | B   | 503  | [Next Greater Element II](https://leetcode.cn/problems/next-greater-element-ii/)                                                                     | 中等 | 单调栈            | 🔴 待挑战 | ⬜  | -    |
| 56   | A   | 151  | [Reverse Words in a String](https://leetcode.cn/problems/reverse-words-in-a-string/)                                                                 | 中等 | 字符串            | 🔴 待挑战 | ⬜  | -    |
| 57   | S   | 5    | [Longest Palindromic Substring](https://leetcode.cn/problems/longest-palindromic-substring/)                                                         | 中等 | 字符串 / 中心扩展     | 🔴 待挑战 | ⬜  | -    |
| 58   | B   | 165  | [Compare Version Numbers](https://leetcode.cn/problems/compare-version-numbers/)                                                                     | 中等 | 字符串 / 模拟       | 🔴 待挑战 | ⬜  | -    |
| 59   | A   | 8    | [String to Integer (atoi)](https://leetcode.cn/problems/string-to-integer-atoi/)                                                                     | 中等 | 字符串 / 模拟       | 🔴 待挑战 | ⬜  | -    |
| 60   | A   | 144  | [Binary Tree Preorder Traversal](https://leetcode.cn/problems/binary-tree-preorder-traversal/)                                                       | 简单 | 二叉树遍历          | 🔴 待挑战 | ⬜  | -    |
| 61   | A   | 145  | [Binary Tree Postorder Traversal](https://leetcode.cn/problems/binary-tree-postorder-traversal/)                                                     | 简单 | 二叉树遍历          | 🔴 待挑战 | ⬜  | -    |
| 62   | S   | 102  | [Binary Tree Level Order Traversal](https://leetcode.cn/problems/binary-tree-level-order-traversal/)                                                 | 中等 | 二叉树 / BFS      | 🔴 待挑战 | ⬜  | -    |
| 63   | S   | 543  | [Diameter of Binary Tree](https://leetcode.cn/problems/diameter-of-binary-tree/)                                                                     | 简单 | 二叉树递归          | 🔴 待挑战 | ⬜  | -    |
| 64   | S   | 98   | [Validate Binary Search Tree](https://leetcode.cn/problems/validate-binary-search-tree/)                                                             | 中等 | BST            | 🔴 待挑战 | ⬜  | -    |
| 65   | A   | 235  | [Lowest Common Ancestor of a BST](https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/)                                      | 中等 | BST            | 🔴 待挑战 | ⬜  | -    |
| 66   | S   | 236  | [Lowest Common Ancestor of a Binary Tree](https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/)                                     | 中等 | 二叉树 / 最近公共祖先   | 🔴 待挑战 | ⬜  | -    |
| 67   | A   | 105  | [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | 中等 | 二叉树构造          | 🔴 待挑战 | ⬜  | -    |
| 68   | A   | 114  | [Flatten Binary Tree to Linked List](https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/)                                               | 中等 | 二叉树            | 🔴 待挑战 | ⬜  | -    |
| 69   | A   | 230  | [Kth Smallest Element in a BST](https://leetcode.cn/problems/kth-smallest-element-in-a-bst/)                                                         | 中等 | BST            | 🔴 待挑战 | ⬜  | -    |
| 70   | S   | 34   | [Find First and Last Position of Element in Sorted Array](https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/)     | 中等 | 二分查找           | 🔴 待挑战 | ⬜  | -    |
| 71   | S   | 33   | [Search in Rotated Sorted Array](https://leetcode.cn/problems/search-in-rotated-sorted-array/)                                                       | 中等 | 二分查找           | 🔴 待挑战 | ⬜  | -    |
| 72   | A   | 153  | [Find Minimum in Rotated Sorted Array](https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/)                                           | 中等 | 二分查找           | 🔴 待挑战 | ⬜  | -    |
| 73   | A   | 162  | [Find Peak Element](https://leetcode.cn/problems/find-peak-element/)                                                                                 | 中等 | 二分查找           | 🔴 待挑战 | ⬜  | -    |
| 74   | A   | 74   | [Search a 2D Matrix](https://leetcode.cn/problems/search-a-2d-matrix/)                                                                               | 中等 | 二分查找           | 🔴 待挑战 | ⬜  | -    |
| 75   | S   | 46   | [Permutations](https://leetcode.cn/problems/permutations/)                                                                                           | 中等 | 回溯             | 🔴 待挑战 | ⬜  | -    |
| 76   | S   | 78   | [Subsets](https://leetcode.cn/problems/subsets/)                                                                                                     | 中等 | 回溯             | 🔴 待挑战 | ⬜  | -    |
| 77   | S   | 39   | [Combination Sum](https://leetcode.cn/problems/combination-sum/)                                                                                     | 中等 | 回溯             | 🔴 待挑战 | ⬜  | -    |
| 78   | S   | 22   | [Generate Parentheses](https://leetcode.cn/problems/generate-parentheses/)                                                                           | 中等 | 回溯             | 🔴 待挑战 | ⬜  | -    |
| 79   | A   | 47   | [Permutations II](https://leetcode.cn/problems/permutations-ii/)                                                                                     | 中等 | 回溯 / 去重        | 🔴 待挑战 | ⬜  | -    |
| 80   | A   | 90   | [Subsets II](https://leetcode.cn/problems/subsets-ii/)                                                                                               | 中等 | 回溯 / 去重        | 🔴 待挑战 | ⬜  | -    |
| 81   | A   | 77   | [Combinations](https://leetcode.cn/problems/combinations/)                                                                                           | 中等 | 回溯             | 🔴 待挑战 | ⬜  | -    |
| 82   | A   | 40   | [Combination Sum II](https://leetcode.cn/problems/combination-sum-ii/)                                                                               | 中等 | 回溯 / 去重        | 🔴 待挑战 | ⬜  | -    |
| 83   | A   | 17   | [Letter Combinations of a Phone Number](https://leetcode.cn/problems/letter-combinations-of-a-phone-number/)                                         | 中等 | 回溯             | 🔴 待挑战 | ⬜  | -    |
| 84   | A   | 79   | [Word Search](https://leetcode.cn/problems/word-search/)                                                                                             | 中等 | 回溯 / DFS       | 🔴 待挑战 | ⬜  | -    |
| 85   | S   | 200  | [Number of Islands](https://leetcode.cn/problems/number-of-islands/)                                                                                 | 中等 | 图 / DFS / BFS  | 🔴 待挑战 | ⬜  | -    |
| 86   | A   | 695  | [Max Area of Island](https://leetcode.cn/problems/max-area-of-island/)                                                                               | 中等 | 图 / DFS / BFS  | 🔴 待挑战 | ⬜  | -    |
| 87   | A   | 994  | [Rotting Oranges](https://leetcode.cn/problems/rotting-oranges/)                                                                                     | 中等 | 图 / BFS        | 🔴 待挑战 | ⬜  | -    |
| 88   | A   | 133  | [Clone Graph](https://leetcode.cn/problems/clone-graph/)                                                                                             | 中等 | 图 / DFS / BFS  | 🔴 待挑战 | ⬜  | -    |
| 89   | S   | 207  | [Course Schedule](https://leetcode.cn/problems/course-schedule/)                                                                                     | 中等 | 图 / 拓扑排序       | 🔴 待挑战 | ⬜  | -    |
| 90   | A   | 210  | [Course Schedule II](https://leetcode.cn/problems/course-schedule-ii/)                                                                               | 中等 | 图 / 拓扑排序       | 🔴 待挑战 | ⬜  | -    |
| 91   | A   | 547  | [Number of Provinces](https://leetcode.cn/problems/number-of-provinces/)                                                                             | 中等 | 图 / 并查集        | 🔴 待挑战 | ⬜  | -    |
| 92   | A   | 684  | [Redundant Connection](https://leetcode.cn/problems/redundant-connection/)                                                                           | 中等 | 并查集            | 🔴 待挑战 | ⬜  | -    |
| 93   | S   | 198  | [House Robber](https://leetcode.cn/problems/house-robber/)                                                                                           | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 94   | A   | 213  | [House Robber II](https://leetcode.cn/problems/house-robber-ii/)                                                                                     | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 95   | A   | 62   | [Unique Paths](https://leetcode.cn/problems/unique-paths/)                                                                                           | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 96   | A   | 64   | [Minimum Path Sum](https://leetcode.cn/problems/minimum-path-sum/)                                                                                   | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 97   | S   | 322  | [Coin Change](https://leetcode.cn/problems/coin-change/)                                                                                             | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 98   | A   | 279  | [Perfect Squares](https://leetcode.cn/problems/perfect-squares/)                                                                                     | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 99   | S   | 300  | [Longest Increasing Subsequence](https://leetcode.cn/problems/longest-increasing-subsequence/)                                                       | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 100  | S   | 1143 | [Longest Common Subsequence](https://leetcode.cn/problems/longest-common-subsequence/)                                                               | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 101  | A   | 139  | [Word Break](https://leetcode.cn/problems/word-break/)                                                                                               | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 102  | A   | 416  | [Partition Equal Subset Sum](https://leetcode.cn/problems/partition-equal-subset-sum/)                                                               | 中等 | 动态规划 / 背包      | 🔴 待挑战 | ⬜  | -    |
| 103  | A   | 122  | [Best Time to Buy and Sell Stock II](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/)                                               | 中等 | 动态规划 / 贪心      | 🔴 待挑战 | ⬜  | -    |
| 104  | A   | 152  | [Maximum Product Subarray](https://leetcode.cn/problems/maximum-product-subarray/)                                                                   | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 105  | A   | 516  | [Longest Palindromic Subsequence](https://leetcode.cn/problems/longest-palindromic-subsequence/)                                                     | 中等 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 106  | S   | 215  | [Kth Largest Element in an Array](https://leetcode.cn/problems/kth-largest-element-in-an-array/)                                                     | 中等 | 堆 / 快速选择       | 🔴 待挑战 | ⬜  | -    |
| 107  | S   | 347  | [Top K Frequent Elements](https://leetcode.cn/problems/top-k-frequent-elements/)                                                                     | 中等 | 堆 / 哈希         | 🔴 待挑战 | ⬜  | -    |
| 108  | S   | 146  | [LRU Cache](https://leetcode.cn/problems/lru-cache/)                                                                                                 | 中等 | 设计 / 哈希 / 双向链表 | 🔴 待挑战 | ⬜  | -    |
| 109  | A   | 208  | [Implement Trie (Prefix Tree)](https://leetcode.cn/problems/implement-trie-prefix-tree/)                                                             | 中等 | 字典树 / 设计       | 🔴 待挑战 | ⬜  | -    |
| 110  | A   | 380  | [Insert Delete GetRandom O(1)](https://leetcode.cn/problems/insert-delete-getrandom-o1/)                                                             | 中等 | 设计 / 哈希        | 🔴 待挑战 | ⬜  | -    |
| 111  | S   | 76   | [Minimum Window Substring](https://leetcode.cn/problems/minimum-window-substring/)                                                                   | 困难 | 滑动窗口           | 🔴 待挑战 | ⬜  | -    |
| 112  | S   | 239  | [Sliding Window Maximum](https://leetcode.cn/problems/sliding-window-maximum/)                                                                       | 困难 | 滑动窗口 / 单调队列    | 🔴 待挑战 | ⬜  | -    |
| 113  | S   | 42   | [Trapping Rain Water](https://leetcode.cn/problems/trapping-rain-water/)                                                                             | 困难 | 双指针 / 单调栈      | 🔴 待挑战 | ⬜  | -    |
| 114  | A   | 25   | [Reverse Nodes in k-Group](https://leetcode.cn/problems/reverse-nodes-in-k-group/)                                                                   | 困难 | 链表             | 🔴 待挑战 | ⬜  | -    |
| 115  | A   | 84   | [Largest Rectangle in Histogram](https://leetcode.cn/problems/largest-rectangle-in-histogram/)                                                       | 困难 | 单调栈            | 🔴 待挑战 | ⬜  | -    |
| 116  | A   | 127  | [Word Ladder](https://leetcode.cn/problems/word-ladder/)                                                                                             | 困难 | 图 / BFS        | 🔴 待挑战 | ⬜  | -    |
| 117  | A   | 72   | [Edit Distance](https://leetcode.cn/problems/edit-distance/)                                                                                         | 困难 | 动态规划           | 🔴 待挑战 | ⬜  | -    |
| 118  | A   | 23   | [Merge k Sorted Lists](https://leetcode.cn/problems/merge-k-sorted-lists/)                                                                           | 困难 | 堆 / 链表         | 🔴 待挑战 | ⬜  | -    |
| 119  | A   | 295  | [Find Median from Data Stream](https://leetcode.cn/problems/find-median-from-data-stream/)                                                           | 困难 | 堆 / 设计         | 🔴 待挑战 | ⬜  | -    |
| 120  | B   | 713  | [Subarray Product Less Than K](https://leetcode.cn/problems/subarray-product-less-than-k/)                                                           | 中等 | 滑动窗口           | 🔴 待挑战 | ⬜  | -    |
| 121  | B   | 113  | [Path Sum II](https://leetcode.cn/problems/path-sum-ii/)                                                                                             | 中等 | 二叉树路径 / 回溯     | 🔴 待挑战 | ⬜  | -    |
| 122  | B   | 417  | [Pacific Atlantic Water Flow](https://leetcode.cn/problems/pacific-atlantic-water-flow/)                                                             | 中等 | 图 / DFS        | 🔴 待挑战 | ⬜  | -    |
| 123  | B   | 130  | [Surrounded Regions](https://leetcode.cn/problems/surrounded-regions/)                                                                               | 中等 | 图 / DFS / 并查集  | 🔴 待挑战 | ⬜  | -    |

## 💡 刷题心得总结
* **矩阵操作**: 医学图像坐标转换中，注意 `(x, y)` 与 `(row, col)` 的对应关系。
* **空间搜索**: 3D 连通域搜索（26邻域）是 2D（8邻域）的扩展，需注意边界控制。

## 图例说明

### 优先级
- **S**：必须掌握，面试高频核心题
- **A**：高频重点题，建议熟练掌握
- **B**：进阶补充题，有时间再补

### 状态
- **🔴 待挑战**：还没开始做
- **🟡 进行中**：做过或看过题解，但还不能稳定独立写出
- **🟢 已完成**：可以独立写出并通过
- **🔥 面试级**：能够口述思路并手撕无 bug

### 二刷
- **⬜**：未二刷
- **✅**：已完成二刷

### 解法链接
- 可填写本地题解文件路径，例如：
  - `./Hash/1_TwoSum.py`
  - `./DP/322_CoinChange.py`
- 如果暂时没有整理题解，可先写 `-`

### 使用建议
- 推荐先按 **推荐顺序** 刷题，再结合 **优先级** 安排复习重点
- 建议优先保证所有 **S 级题** 至少完成一遍
- 对于容易忘记或易错的题，完成后尽量补一次 **二刷**
- 如果某题已经能在限定时间内独立写出，可以把状态更新为 **🔥 面试级**