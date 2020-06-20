## 说明

本模板适用于 HKUST 经济学博士 thesis. 用户可下载 `HKUST-thesis-LaTeX-Template.zip` 本地运行，也可使用 overleaf [模板在线编译](https://www.overleaf.com/read/hbbwnvpyjskf)。建议使用 overleaf 在线编译，因为模板使用了 `chapterbib` 包，本地运行需进行多次编译。

本模板基于科大[数学系论文模板](https://www.math.ust.hk/intranet/pg.php)，进行了些许修改使它更符合经济系论文格式要求。已有经济系博士使用此模板，于 2019 年成功毕业。请放心使用。

## 使用方法

假设用户有三篇博士论文和相应 LaTeX 源码，并使用 natbib 生成参考文献。使用方法如下：

1. 打开 `preliminary.tex` 文件，修改你的名字、致谢等部分；

1. 将三篇论文的参考文献全部写入 `Thesis.bib` 文件；

1. 最后也是最关键的一部，将三篇论文的 LaTeX 源码按次序写入 `chapter1.tex`, `chapter2.tex`, `chapter3.tex`. 请根据模板格式，适当修改你的 LaTeX 文件。如文章标题不再是 `\title{name}`, 而是 `\chapter{name}`。

搞定。如果你只有两篇论文，在 `main.tex` 文件中删去 `\include{chapter3}` (Line 15) 即可。

## HKUST Thesis LaTeX Template

This thesis template might be used for the Economics PhD Thesis at HKUST. The `.zip` file contains all the files to run locally. It is adpated from the [Template provided by Math Department](https://www.math.ust.hk/intranet/pg.php) with the following modifications:
  - chapter-wise citation and bibliography using `natbib`,
  - add each References as a separate section, and
  - other small changes (say a compact table of contents, and so on).
  
The template is also [available on overleaf](https://www.overleaf.com/read/hbbwnvpyjskf). I find it thorny to run the code locally as it requires multiple compilings.

A suggested workflow is to have three LaTeXed essays, then import them to each chapter in the Template, and finally run them online.  
