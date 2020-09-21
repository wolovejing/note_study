---
title: w3cschool jQuery教程
---
# JQuery教程
## JQuery简介
### jQuery 库
#### 特性
##### 2.|JQuery库包含以下特性
##### 4.| 
1.HTML 元素选取
2.HTML 元素操作
3.CSS 操作
4.HTML 事件函数
5.JavaScript 特效和动画
6.HTML DOM 遍历和修改
7.AJAX
8.Utilities
### 向页面中添加jQuery库
#### 2.|如何向页面中添加jQuery库
#### 4.|
```clojure
<head>
<script type="text/javascript" src="jquery.js"></script>
</head>
<script> 标签应位于页面的head部分
```
## JQuery安装
### 添加JQuery到网页
#### 2.| 如何把JQuery添加到网页？
:PROPERTIES:
:custom_id: 5f63392f-3220-4f41-8f63-86efcf9c496d
:END:
#### 4.|
#### 1.下载JQuery库
   :PROPERTIES:
   :CUSTOM_ID: 5f4a017a-c84e-4634-8418-ba5201442c42
   :END:
   :PROPERTIES:
   :CUSTOM_ID: 5f4a0056-78a7-4bc6-8572-51627ce6be74
   :END:
#### 2. ��
### ((5f4a017a-c84e-4634-8418-ba5201442c4
#### 两版本可选择
##### 2.|
##### Production version - 用于实际的网站中，已被精简和压缩
##### Development version - 用于测试和开发（未压缩，是可读的代码）
##
## JQuery语法
##
###
### 基础语法
###
####
##
#### 2.| 基础语法是什么？
#### 4.|
#### 1. 美元符号定义 jQuery
#### 2. 选择符（selector）“查询”和“查找” HTML 元素
#### 3. jQuery 的 action() 执行对元素的操作
#### 5.|
```
<script type="text/javascript">
$(document).ready(function(){
  $("button").click(function(){
  $(this).hide();
});
});
</script>
``
#### 8.| <e>https://www.w3school.com.cn/tiy/t.asp?f=jquery_hide_this</e>
### 文档就绪函数
#### 作用？
##### 2.|文档就绪函数的作用是什么？
##### 4.| 为了防止文档在完全加载之前运行JQuery代码
   :PROPERTIES:
   :CUSTOM_ID: 5f4a0b9e-3866-4e7e-b7bf-4029d4affdb4
   :END:
#### 文档就绪函数的使用
##### 2.| 如何使用文档就绪函数?
##### 4.| 所有JQuery函数都位于一个document read函数中
##### 5.| 例子
```
$(document).ready(function(){

--- jQuery functions go here ----

});
```
#### ((5f4a0b9e-3866-4e7e-b7bf-4029d4affdb4)) 实例
##### 4.|
##### 1. 试图隐藏一个不存在的元素
##### 2. 获得未完全加载的图像的大小
####
##
