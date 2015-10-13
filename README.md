#IT项目管理文档

每人fork项目后，完成自己的部分后push, 再pull request给我。

**每人只需要修改自己负责的部分，不要修改其他文件**。

##编辑
原则上只使用`\section{}`, `\subsection{}`, `\subsubsection{}`三级。

里面需要使用图片的，为防止冲突，采用**文件名_编号**的方法命名, 如`part-one.tex`中的图片有`part-one-1.eps`, `part-one-2.png`等等。

文件内的内容，结构都可自由改动。确保以 `\newpage`开始，然后使用上面三层结构组织文字。如：

```
\newpage
\section{我是Section One}
\subsection{我是子Section}
我是子Section的内容
```

**保存为utf-8编码**。

##编译
使用的是XeLatex引擎，使用的是Mac上系统字体（中文宋体，英文Times New Roman），其他操作系统的同种字体可能名字不一样；如果想自己编译看效果的，可以修改字体名。


##其他
嫌麻烦的，也可以自己clone到本地后，把自己负责的那部分Tex文件发邮件给我。
