---
layout: page
permalink: /essays/echoes_of_eloquence/zhihu/coding/如何智能地在每个数字中间加一个「,」？/index.html
title: 如何智能地在每个数字中间加一个「,」？
---

```c
#include <stdio.h>
int main(void) {
    int a[6] = {1, 2, 3, 4, 5, 6}, i;
    for (i = 0; i < 6; i++) {
        printf(",%d" + !i, a[i]);
    }
    return 0;
}
```
  
一行输出，没有 if 语句，非常简洁
