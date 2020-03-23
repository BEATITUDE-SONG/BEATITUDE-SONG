---
title: Markdown 语法
date: 2020-03-23 13:02:28
author: 摇曳的风铃
categories: 技术
tags:
  - Markdown
---

* content
{:toc}

## Markdown  
1.  markdown 可以直接添加html标记语句  如\<pre\>\<code\>
2.  \# 1-6空格 6级标题  
3.  \> 文本前面>标示引用句子  
4.  []() 插入链接。前面加！插入图片   
5.  \*字\*斜体，\**字\**粗体,\***字\***斜粗体 \~带删除线
6.  \-无序列表  
7.  数字. 有序列表 
8.  \-\-\-分隔符  
9.  换行前一行末尾两个空格换行  
10. 四空格缩进或使用html标记代码块  
11. \$\$TeX 或 LaTeX 格式的数学公式\$\$  
12. \* content\{\:toc\}生成目录  
13. \<\> 显示括号中的地址，并生成超链接
14. 表格
    
        title1|title2|title3
        :--|--:|:--:
        c1|c2|c3

## GFM
01. 显示地址并生成超链接 直接输入无需括号  
02. \'\'\'name \'\'\' 代码块，bash, cmake, cpp, go, java, json, lua, markdown, perl, python, sql。 单个\'在文本中插入代码  
03. 对变量命中带_线的单词不会解析为粗体  