---
title: code
date: 2017-12-11 11:47:44 #文章生成時間
categories: C #文章分類目錄 可以省略
tags:
- C

description:  意想不到的c
---

```c++
  int a[10] = {2,3,4,5};
  int i = 3;  

  bool ok = (a[i] == i[a]);//ok == true
  /*
  a[i] == *(a+i) == *(i+a) == i[a]
  */
```
