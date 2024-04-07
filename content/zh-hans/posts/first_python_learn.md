---
title: "我的python第一次记录"
author: Bazinga-0411
date: 2022-05-02T13:12:47+02:00
slug: first_python_learn
draft: false
toc: false
summary: 我的python第一次记录
tags:
  - Shortcodes
  - Hugo
categories:
  - Luna
---

# 我的python第一次记录

![first_python_learn](/posts/first_python_learn.png)

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