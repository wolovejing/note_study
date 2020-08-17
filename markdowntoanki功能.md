---
title: markdownToAnki功能
tags:
---

## 代码进行编码功能
 ```clojure
"    for(i=left;i<=right;i++)<br/>    {<br/>        path=0;<br/>        for(j=min(c1->y,c2->y)+1;j<max(c1->y,c2->y);j++)<br/>        {<br/>            path+=Board[i][j][0];<br/>            if(path>0) break;<br/>        }<br/>        if(path==0)<br/>        {<br/>            DrawPath(c1->x,c1->y,  i,c1->y,  i,c2->y,  c2->x,c2->y, LineColor);<br/>            delay(6000);<br/>            DrawPath(c1->x,c1->y,  i,c1->y,  i,c2->y,  c2->x,c2->y, BkGndColor);<br/>            return true;<br/>        }<br/>    }"
```
##