## README

[TOC]

This repository recodes solutions to the problems come from jianzhi offer. For every problem, we provide the python code. Some of problems may corresponding to LeetCode, we also provide the LeetCode link.

### 剑指 Offer 题目

#### 题目列表

下表划分了各题使用的算法与数据结构。由于题目可能存在多种解法，本表格只列举最优解法（时间与空间复杂度最低）的对应算法。

| 题目                                      |      算法分类      |  数据结构分类   |
|-------------------------------------------|:------------------:|:---------------:|
| 03. 数组中重复的数字                      |      查找算法      |      数组       |
| 05. 替换空格                              |                    |     字符串      |
| 06. 从尾到头打印链表                      |                    | 栈，队列，链表  |
| 07. 重建二叉树                            |      分治算法      |   树，哈希表    |
| 08. 二叉树的下一个节点                    |                    |       树        |
| 09. 用两个栈实现队列                      |                    |    栈 / 队列    |
| 10. 斐波那契数列                          |      动态规划      |                 |
| 11. 旋转数组的最小数字                    |      查找算法      |      数组       |
| 12. 矩阵中的路径                          | 回溯算法，搜索算法 |    数组，图     |
| 13. 机器人的运动范围                      | 回溯算法，搜索算法 |    数组，图     |
| 14. 剪绳子                                |   贪心算法，数学   |                 |
| 15. 二进制中 1 的个数                     |       位运算       |                 |
| 16. 数值的整数次方                        |  分治算法，位运算  |                 |
| 17. 打印从 1 到最大的 n 位数              |                    |      数组       |
| 18. 删除链表的节点                        |       双指针       |      链表       |
| 20. 表示数值的字符串                      |                    |     字符串      |
| 21. 调整数组顺序使奇数位于偶数前面（一）  |       双指针       |      数组       |
| 22. 链表中倒数第 k 个节点                 |       双指针       |      链表       |
| 24. 反转链表                              |       双指针       |      链表       |
| 25. 合并两个排序的链表                    |       双指针       |      链表       |
| 26. 树的子结构                            |      搜索算法      |       树        |
| 27. 二叉树的镜像                          |      搜索算法      |  栈 / 队列，树  |
| 29. 顺时针打印矩阵                        |        模拟        |      数组       |
| 30. 包含 min 函数的栈                     |        排序        |    栈 / 队列    |
| 31. 栈的压入、弹出序列                    |        模拟        |    栈 / 队列    |
| 32. 从上到下打印二叉树                    |      搜索算法      |  栈 / 队列，树  |
| 33. 二叉搜索树的后序遍历序列              |      分治算法      |  栈 / 队列，树  |
| 35. 复杂链表的复制                        |                    |      链表       |
| 36. 二叉搜索树与双向链表                  |  搜索算法，双指针  |       树        |
| 37. 序列化二叉树                          |      搜索算法      |       树        |
| 38. 字符串的排列                          |      回溯算法      | 字符串，哈希表  |
| 39. 数组中出现次数超过一半的数字          |                    |      数组       |
| 40. 最小的 k 个数                         |        排序        |    数组，堆     |
| 41. 数据流中的中位数                      |        排序        |       堆        |
| 43. 1 ～ n整数中 1 出现的次数             |        数学        |                 |
| 44. 数字序列中某一位的数字                |        数学        |                 |
| 45. 把数组排成最小的数                    |        排序        |     字符串      |
| 46. 把数字翻译成字符串                    |      动态规划      |     字符串      |
| 47. 礼物的最大价值                        |      动态规划      |      数组       |
| 48. 最长不含重复字符的子字符串            |  动态规划，双指针  |     哈希表      |
| 49. 丑数                                  |      动态规划      |                 |
| 50. 第一个只出现一次的字符                |                    |     哈希表      |
| 51. 数组中的逆序对                        |      分治算法      |      数组       |
| 52. 两个链表的第一个公共节点              |       双指针       |      链表       |
| 53. 数字在升序数组中出现的次数            |      查找算法      |      数组       |
| 54. 二叉搜索树的第 k 个节点               |      搜索算法      |       树        |
| 55. 二叉树的深度                          |      搜索算法      |       树        |
| 56. 数组中只出现一次的两个数字            |       位运算       |      数组       |
| 57. 和为 s 的两个数字                     |       双指针       |      数组       |
| 58. 左旋转字符串                          |                    |     字符串      |
| 59. 滑动窗口的最大值                      |        排序        | 数组，栈 / 队列 |
| 61. 扑克牌顺子                            |        排序        |  数组，哈希表   |
| 62. 圆圈中最后剩下的数字                  |        数学        |                 |
| 64. 求 1 + 2 + … + n                      |        数学        |                 |
| 65. 不用加减乘除做加法                    |       位运算       |                 |
| 66. 构建乘积数组                          |        数学        |      数组       |
| 68. 二叉搜索树的最近公共祖先              |      搜索算法      |       树        |
| 69. 跳台阶                                |      动态规划      |                 |
| 70. 矩形覆盖                              |      动态规划      |                 |
| 71. 跳台阶扩展问题                        |      动态规划      |                 |
| 73. 翻转单词序列                          |       双指针       |     字符串      |
| 74. 和为 S 的连续正数序列                 |                    |      数组       |
| 75. 字符流中第一个不重复的字符            |                    |     字符串      |
| 76. 删除链表中的重复节点                  |                    |      链表       |
| 78. 把二叉树打印成多行                    |                    |       树        |
| 79. 判断是不是平衡二叉树                  |                    |       树        |
| 81. 调整数组顺序使奇数位于偶数前面 （二） |        排序        |      数组       |
| 83. 剪绳子（进阶版）                      |   动态规划，数学   |                 |
| 84. 二叉树中和为某一值的路径（三）        |                    |       树        |
| 85. 连续子数组的最大和（二）              |  动态规划，双指针  |                 |
| 86. 在二叉树中找到两个节点的最近公共祖先  |      搜索算法      |       树        |

#### 按知识点分类

##### 链表

+ offer_06. 从尾到头打印链表
+ offer_18. 删除链表的节点
+ offer_22. 链表中倒数最后k个结点
+ offer_23. 链表中环的入口结点
+ offer_24. 反转链表
+ offer_25. 合并两个排序的链表
+ offer_35. 复杂链表的复制
+ offer_52. 两个链表的第一个公共结点
+ offer_76. 删除链表中重复的结点

##### 树

+ offer_07. 重建二叉树
+ offer_08. 二叉树的下一个结点
+ offer_26. 树的子结构
+ offer_27. 二叉树的镜像
+ offer_32. 从上往下打印二叉树
+ offer_33. 二叉搜索树的后序遍历序列
+ offer_36. 二叉搜索树与双向链表
+ offer_37. 序列化二叉树
+ offer_54. 二叉搜索树的第k个节点
+ offer_55. 二叉树的深度
+ offer_68. 二叉搜索树的最近公共祖先
+ offer_78. 把二叉树打印成多行
+ offer_79. 判断是不是平衡二叉树
+ offer_84. 二叉树中和为某一值的路径 (三)
+ offer_86. 在二叉树中找到两个节点的最近公共祖先

##### 队列和栈

+ offer_09. 用两个栈实现队列
+ offer_30. 包含min函数的栈
+ offer_31. 栈的压入、弹出序列
+ offer_59. 滑动窗口的最大值
+ offer_73. 翻转单词序列

##### 搜索算法

+ offer_11. 旋转数组的最小数字
+ offer_38. 字符串的排列
+ offer_44. 数字序列中某一位的数字
+ offer_53. 数字在升序数组中出现的字数

##### 动态规划

+ offer_10. 斐波那契数列
+ offer_46. 把数字翻译成字符串
+ offer_47. 礼物的最大价值
+ offer_48. 最长不含重复字符的子字符串
+ offer_69. 跳台阶
+ offer_70. 矩形覆盖
+ offer_71. 跳台阶扩展问题
+ offer_85. 连续子数组的最大和（二）

##### 回溯

+ offer_12. 矩阵中的路径
+ offer_13. 机器人的运动范围

##### 排序

+ offer_03. 数组中重复的数字
+ offer_40. 最小的 k 个数
+ offer_41. 数据流中的中位数
+ offer_51. 数组中的逆序对

##### 位运算

+ offer_15. 二进制中 1 的个数
+ offer_16. 数值的整数次方
+ offer_56. 数组中只出现一次的两个数字
+ offer_64. 求 1 + 2 + … + n
+ offer_65. 不用加减乘除做加法

##### 模拟

+ offer_20. 表示数值的字符串
+ offer_29. 顺时针打印矩阵
+ offer_61. 扑克牌顺子

##### 其他算法

+ offer_05. 替换空格
+ offer_14. 剪绳子
+ offer_17. 打印从 1 到最大的 n 位数
+ offer_21. 调整数组顺序使奇数位于偶数前面（一）
+ offer_39. 数组中出现次数超过一半的数字
+ offer_43. 1 ～ n整数中 1 出现的次数
+ offer_45. 把数组排成最小的数
+ offer_49. 丑数
+ offer_50. 第一个只出现一次的字符
+ offer_57. 和为 s 的两个数字
+ offer_58. 左旋转字符串
+ offer_62. 圆圈中最后剩下的数字
+ offer_66. 构建乘积数组
+ offer_74. 和为 S 的连续正数序列
+ offer_75. 字符流中第一个不重复的字符
+ offer_81. 调整数组顺序使奇数位于偶数前面（二）
+ offer_83. 剪绳子（进阶版）