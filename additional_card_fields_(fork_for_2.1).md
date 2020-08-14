---
title: Additional Card Fields (Fork for 2.1)
tags:anki插件
---
## 描述
### 给卡片模板添加特殊的字段，如下图所示 [image](http://tuchuang.lifeupnote.com/blog/20200814/63bi9KErxTP5.png?imageslim)
### - {{info-FirstReview:}}。- 这张卡片首次复习的时间
- {{info-LastReview:}}. - 最后一次复习的时间
- {{info-TimeAvg:}}. - 该卡的平均使用时间
- {{info-TimeTotal:}}. - 总时间
- {{info-overdue_fmt:}}。- 逾期天数（格式化）
- {{info-overdue_days:}}. - 逾期天数
- {{info-Ord:}} - 模板的编号，第一个模板的编号为0，第二个模板的编号为1，以此类推。第一个模板的编号为0，第二个模板的编号为1，等等。例如，对于那些你想让Javascript代码在某些卡片上有不同表现的clozed卡片，就很有用。
- {{info-Did:}} - 卡片ID
- {{info-Due:}} - 卡片到期日期
- {{info-Id:}} - 卡片id
- {{info-Ivl:}} - 当前间隔
- {{info-Queue:}} - 0=新增，1=学习，2=逾期，3=(重新)学习--第二天或以后，-1=暂停，-2=用户埋没，-3=计划埋没。
- {{info-eviews:}}. - 您对某张卡的评价次数
- {{info-Lapses:}} - 失误次数
- {{info-Type:}} - 0=暂停，1=学习，2=正常，3=重新学习。
- {{info-Nid:}} - note id
- {{info-Mod:}} - 最后修改日期
- {{info-Usn:}} - 通用序列号，每次上传至AnkiWeb时都会递增。
- {{信息因素:}} - 一张卡的易用性，比如2500就是250%。
- {{info-Ease:}} - 卡片的易用性，例如，250是Anki对新卡的默认值。更易读的 "Factor "版本
- {{info-Review?} - 这张卡正在被审查吗？
- {{info-New?:}}这张卡是新卡吗？- 这张卡是新卡吗？
- {{info-Learning?:}}这张卡是否正在学习？- 这张卡正在学习吗？
- {{info-TodayLearning?:}}这张卡正在学习吗？- 如果这张卡在学习中，并且在队列1中，则显示该卡。
- {{info-DayLearning?} - 如果卡片在学习中，并且在队列中，则显示为3。
- {{info-Young:}} - 如果卡片处于 "审查 "状态且间隔时间少于21天，则显示为 "审查"。
- {{info-Mature:}} - 如果卡片处于 "审查 "状态且间隔时间超过21天，则显示为 "审查"。
- {{info-Date_Created:}}。- 卡片创建日期（格式化）
