### 题目描述

输入一个链表，反转链表后，输出新链表的表头。

### 思路

假设翻转1->2->3->4->5，步骤如下：

```
head->4->3->2->1->5
               p  tp
```
- 1.我们将p的next指向tp的next
- 2.将tp的next指向head的next
- 3.将head的next指向tp
