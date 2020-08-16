---
title: regexRepl(原始数据的首位空格，正则表达式，子字符串)
tags:
---

## 定义正则替换函数, 注意是全局替换
## '''
function regexRepl(orig_str, regex_str, subst_str) {
	const regex = new RegExp(regex_str, 'g');
	return orig_str.replace(regex, subst_str);
}
'''
