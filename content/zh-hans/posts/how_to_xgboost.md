---
author: Bazinga-0411
date: 2024-04-06T13:12:47+02:00
slug: how_to_xgboost
draft: false
toc: false
summary: 如何使用xgboost
tags:
  - Shortcodes
  - Hugo
categories:
  - Luna
---

# 如何使用xgboost


## 翻转链表
```python
class ListNode:
    def __init__(self, x):
        self.val = x
        self.next = None

def reverseList(head: ListNode) -> ListNode:
    if not head or not head.next:
        return head
    pre = None
    cur = head
    while cur:
        tmp = cur.next
        cur.next = pre
        pre = cur
        cur = tmp
    return pre
```