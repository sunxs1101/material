参考：LaTeX新人教程，30分钟从完全陌生到基本入门

http://wenku.baidu.com/link?url=iEuf9uIParekjPmi-HfWUOVek-zkzq000pxopqxdq1wvGCVbotYifkiSVJ2qiNzSn5Sf_1jloXFsfmUnh-Qqz41sCBytK_VQ7uE4swng2-e
```
2.第一个文档
打开WinEdt，建立一个新文档，将以下内容复制进入文档中，保存，保存类型选择为UTF-8。

\documentclass{article}
\begin{document}
hello, world
\end{document}

然后在WinEdt的工具栏中找到编译按钮（在垃圾桶和字母B中间），在下拉菜单中选择XeTeX，并点击编译。
如果顺利的话，我们就可以顺利生成出第一个pdf文件，点击工具栏中的放大镜按钮就可以快速打开生成的pdf文件。
```
### 中文支持
只需要把开头的\documentclass{atricle}换成\documentclass{ctexart}就可以了。
### 宏包
\package{}用来调用包，通常在\documentclass{article}之后，\begin{document}之前，将所需要的宏包写上，常用的有以下包
```
编辑数学公式的宏包：\usepackage{amsmath}和 \usepackage{amssymb}
编辑数学定理和证明过程的宏包：\usepackage{amsthm}
插入图片的宏包：\usepackage{graphicx}
复杂表格的宏包：\usepackage{multirow}
```
### 模版
模版就是documentcluss{}中大括号的内容。

ppt：beamer包

