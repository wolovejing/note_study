---
title: test
tags:
---
# 第一部分 看入人里

## 第一章 人际沟通入门
### 我们为什么要沟通？
#### 生理需求
```clojure
      for(i=left;i<=right;i++)
    {
        path=0;
        for(j=min(c1->y,c2->y)+1;j<max(c1->y,c2->y);j++)
        {
            path+=Board[i][j][0];
            if(path>0) break;
        }
        if(path==0)
        {
            DrawPath(c1->x,c1->y,  i,c1->y,  i,c2->y,  c2->x,c2->y, LineColor);
            delay(6000);
            DrawPath(c1->x,c1->y,  i,c1->y,  i,c2->y,  c2->x,c2->y, BkGndColor);
            return true;
        }
    }

```
### 代码需求
```clojure
      for(i=left;i<=right;i++)
    {
        path=0;
        for(j=min(c1->y,c2->y)+1;j<max(c1->y,c2->y);j++)
        {
            path+=Board[i][j][0];
            if(path>0) break;
        }
        if(path==0)
        {
            DrawPath(c1->x,c1->y,  i,c1->y,  i,c2->y,  c2->x,c2->y, LineColor);
            delay(6000);
            DrawPath(c1->x,c1->y,  i,c1->y,  i,c2->y,  c2->x,c2->y, BkGndColor);
            return true;
        }
    }

```