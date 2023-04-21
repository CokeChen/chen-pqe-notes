
# Markdown

## Latex
### 重定义围面积分
在obsidian里面，居然不支持围面积分符号？
$$
\oiint
$$
使用newcommand合成,在公式块加上：
\newcommand{\oiint}{\subset\kern{-3pt}\supset\kern{-16.5pt}\iint}
只要在仓库的任何一个公式块加入此语句，重启obsidian即可全局使用
$$
\newcommand{\oiint}{\subset\kern{-3pt}\supset\kern{-16.5pt}\iint}

\oiint
$$

### 矩阵虚实线
$$
\left[\begin{array}{cc:cc}
a & b & c & d\\
a & b & c & d\\
\hdashline
a & b & c & d\\
a & b & c & d\\
\end{array}\right]
$$
### 重定义上划线公式
$$
\newcommand{\overline}{\overset{\mathbf{\_\_}}}
\overset{\_\_}{A}
\qquad
\overset{\mathbf{\_\_}}{A}
\quad 
\overline{A}
$$

markdown支持latex打公式

\sqrt{} 开根号

````latex
=\!=\!=可以把等号延长
\quad     是间隔    \qquad   间隔加大
````

$$
=\!=\!=
$$


```latex
\to 普通右边箭头

\rightarrow 普通右边箭头

\leftarrow   普通左边箭头

\leftrightarrow   普通左边箭头

\xrightarrow[]{}  长箭头带文字[下划线文字]{上画线文字}	
\xleftarrow[]{}  左边箭头
```


$$
\begin{align*} 
&显示效果如下
\\
&\to
\\
&\rightarrow 
\\
&\leftarrow
\\
&\leftrightarrow
\\
&\xrightarrow[下划线文字]{上划线文字}
\\\\
&\xleftarrow[下划线文字]{上划线文字}

\end{align*} 
$$


```latex
公式推导时等号对其
\begin{align*}  

  * &= * \\
    &= * \\

    &= * 

\end{align*}
```


$$
\begin{align*}  

  * &= * \\
   &= * \\

   &= * 

\end{align*}
$$

````latex
大于等于\geq
小于等于\leq
不等于\neq
````

$$
大于等于\geq
\\
小于等于\leq
\\
不等于\neq
$$

```latex
积分\int_{a}^{b}
围线积分\oint_{a}^{b}
二重积分\iint_{D}
求和\sum_{k=a}^{b}
极限\lim_{x \to a}
积分竖线F(x)\big|_{a}^{b} 
```

$$
\begin{align*}
&积分\int_{a}^{b}
\\\\
&围线积分\oint_{a}^{b}
\\\\
&二重积分\iint_{a}^{b}
\\\\
&求和\sum_{k=a}^{b}
\\\\
&极限\lim_{x \to a}
\\\\
&积分竖线F(x)\big|_{a}^{b}

\end{align*}
$$




````latex
\color{red}{演示颜色红色}
\\
\color{blue}{演示颜色蓝色}
\\
\color{pink}{演示颜色粉色}
\\
\color{green}{演示颜色绿色}
````

$$
\begin{align*}
\color{red}{演示颜色红色}
\\
\color{blue}{演示颜色蓝色}
\\
\color{pink}{演示颜色粉色}
\\
\color{green}{演示颜色绿色}
\end{align*}
$$
```LaTex
🄌 ➊ ➋ ➌ ➍ ➎ ➏ ➐ ➑ ➒ ➓
⑴⑷⑵⑶⑷⑸⑹⑺⑻⑼⑽⑾⑿⒀⒁⒂
⒈⒉⒊⒋⒌⒍⒎⒏⒐⒑⒒⒓⒔⒕⒖
①②③④⑤⑥⑦⑧⑨ⅠⅡⅢⅣⅤⅥⅦⅧⅨ
₀₁₂₃₄₅₆₇₈₉
```

$$
\begin{align*}
&🄌 ➊ ➋ ➌ ➍ ➎ ➏ ➐ ➑ ➒ ➓
\\
&⑴⑷⑵⑶⑷⑸⑹⑺⑻⑼⑽⑾⑿⒀⒁⒂
\\
&⒈⒉⒊⒋⒌⒍⒎⒏⒐⒑⒒⒓⒔⒕⒖
\\
&①②③④⑤⑥⑦⑧⑨
\\
&ⅠⅡⅢⅣⅤⅥⅦⅧⅨ
\\
&₀₁₂₃₄₅₆₇₈₉
\end{align*}
$$


```LaTeX
Ⅰ、Ⅱ、Ⅲ、Ⅳ、Ⅴ、Ⅵ、Ⅶ、Ⅷ、Ⅸ、Ⅹ、Ⅺ
```

$$
Ⅰ、Ⅱ、Ⅲ、Ⅳ、Ⅴ、Ⅵ、Ⅶ、Ⅷ、Ⅸ、Ⅹ、Ⅺ
$$

```latex
输入单个点：\cdot

横向多个点：\cdots

竖向多个点：\vdots

斜向多个点：\ddots
```

$$
\begin{align*}
&输入单个点\quad \cdot
\\\\
&横向多个点\quad \cdots
\\\\
&竖向多个点\quad \vdots
\\\\
&斜向多个点\quad \ddots
\end{align*}
$$
```latex
\begin{array}{c|c c c}
1&2&3
\\  \hline
4&5&6
\end{array}


{c|}c的个数表示列的个数，代表数据居中，r代表右对齐，|代表在这列划竖线
\hline 表示画一条横线
&：用于分割每列之间的元素
\\：换行符
```

$$
\begin{array}{c|c c c}
1&2&3
\\  \hline
4&5&6
\end{array}
$$

