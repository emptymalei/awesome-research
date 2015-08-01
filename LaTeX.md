---
layout: article
title: "LaTeX | How to Survive Research"
comments: true
---

## LaTeX

Useful tools are listed in [Cloud Services](Cloud-Services.html)

### Tips

[wikibooks - LaTeX](http://en.wikibooks.org/wiki/LaTeX) as a manual.

#### Symbols

1. [Detexify](http://detexify.kirelabs.org/classify.html): find out what the symbol is by drawing online


#### Graphing

1. [TeX Example](http://www.texample.net/) (Tikz/PGF)


#### Fonts

1. [Font Catalogue](http://www.tug.dk/FontCatalogue/seriffonts.html)

#### Templates

1. [LaTeX Templates](http://www.latextemplates.com/)


#### New Commands

##### New commands for QM

```
\newcommand{\ud}[1]{{#1^{\dagger}}}
\newcommand{\bra}[1]{\left\langle #1\right|}
\newcommand{\ket}[1]{\left| #1\right\rangle}
\newcommand\Tr{\mathrm{Tr}}
\newcommand{\braket}[2]{\langle #1 \mid #2 \rangle}
\newcommand\d{\mathrm{d}}
\newcommand\I{\mathbb{I}}
\newcommand{\avg}[1]{\left< #1 \right>}
```




### References

#### Math into Type

This is a great book for math related typography. Find it [here](ftp://ftp.ams.org/pub/author-info/documentation/howto/mit-2.pdf). This is copyright material. Please DO NOT redistribute.


### Chinese 中文

```
% !TEX program = xelatex

\documentclass[12pt,a4paper]{article}

\usepackage{amsthm,amsfonts,amssymb,bm}
\usepackage[fleqn]{amsmath}

% Page settings
\addtolength{\textheight}{2.0cm}
\addtolength{\voffset}{-2cm}
\addtolength{\hoffset}{-1.5cm}
\addtolength{\textwidth}{4.0cm}

%\allowdisplaybreaks

%\usepackage{subeqnarray}
\usepackage{mathrsfs}
%\usepackage{color}
%\usepackage{url}
%\usepackage{ulem}
\usepackage{indentfirst}   % Indent first line of a paragraph
%\usepackage{textcomp}




%%Here is the configuration for chinese. setmainfont is the default font of the text.
\usepackage[cm-default]{fontspec}
\usepackage{xunicode}
%\usepackage{xltxtra}
\setmainfont{"微软雅黑"}
%\setsansfont[BoldFont=SimHei]{KaiTi_GB2312}
%\setmonofont{NSimSun}



\XeTeXlinebreaklocale "zh"
%\XeTeXlinebreakskip = 0pt plus 1pt

% Figure, Diagram, Caption settings
%\usepackage{tikz}
%\usetikzlibrary{mindmap,trees}
\usepackage{graphicx}
%\usepackage{graphics}
%\usepackage[hang,small,bf]{caption}
%\setlength{\captionmargin}{50pt}

% Redefine some fonts.
\newfontfamily\heiti{"黑体"}
\newfontfamily\fs{"仿宋"}
\newfontfamily\yahei{"微软雅黑"}



\begin{document}
\title{\Huge\yahei 中文XeLaTeX}


\author{XXXXX}
%\maketitle

% Redefine some math commands and environments.

\newcommand{\dd}{\mathrm d}
%\newcommand{\HH}{\mathcal H}
%\newcommand{\CN}{{\it Cosmologia Notebook}}
\newenvironment{eqnset}
{\begin{equation}\left \bracevert \begin{array}{l}}
{\end{array} \right. \end{equation}}

\newenvironment{eqn}
{\begin{equation}\left \bracevert \begin{array}{l}}
{\end{array} \right. \end{equation}}



\section{设定字体测试}
\fs 仿宋

\textbf{\fs 仿宋粗体？好像没有。}

\yahei 微软雅黑

\textbf{\yahei 微软雅黑粗体}


\section{默认字体测试}

English

中文默认字体

\section{数学环境测试}

\begin{equation}
\alpha=\beta \qquad \text{中文注释, English Notes}
\end{equation}

\end{document}
```