# AboutMarkdown
Markdown常用公式（GitHub编辑公式）

摘抄自：http://t.csdn.cn/iEjbB

# <center>Markdown 常用公式编辑</center>
每次编辑公式用word，然后截图迁移非常不方便，乘此学习下Markdown编辑器中用Latex语法来编辑公式提高效率。
# 1.  基本用法
## 1.1 呈现位置
`$...$` 用来在在文本中嵌入显示，比如`$\sum_{i=0}^N{X_i}$`的效果为： $\sum_{i=0}^N{X_i}$ 其是嵌入在文本中间来呈现的。而`$$....$$`则为隔行居中显示， `$$\sum_{i=0}^N{X_i}$$`的显示效果：$$\sum_{i=0}^N{X_i}$$

## 1.2 常用希腊字母表示
写法 | 表示
-------|-------
`$\alpha$`  |  $\alpha$    
`$\beta$`    |  $\beta$
`$\gamma$`| $\gamma$
`$\delta$`     |$\delta$
`$\epsilon$`  |$\epsilon$
`$\eta$`        |$\eta$
`$\theta$`     |$\theta$
`$\lambda$` |$\lambda$
`$\mu$`       |$\mu$
`$\omega$` |$\omega$
`$\pi$`        |$\pi$
`$\xi$`       | $\xi$
`$\tau$`    |  $\tau$
`$\phi$`    | $\phi$
`$\psi$`    | $\psi$
`$\upsilon$`|  $\upsilon$
`$\nu$`     |$\nu$


首字母大写即为大写表示:     `$\Nu$  ` $\Nu$  
加var前缀则斜体:   `$\vartheta$` $\vartheta$ 

## 1.3 上下标
_表示下标，^表示上标
写法|表示
----|----
`$I_i$` |  $I_i$ 
`$I^j$` |  $I^j$
`$I_i^{ka+b}$`| $I_i^{ka+b}$

## 1.4 矢量
利用\vec  和\overrightarrow （注意空格）
写法|表示
----|----
`$\vec {a}$` | $\vec {a}$
`$\vec {a+b}$` | $\vec {a+b}$
`$\overrightarrow {a+b}$` | $\overrightarrow {a+b}$

## 1.5 分组与括号
利用{}来进行分组，分组就是将{}内看做一个整体的意思， 比如不分组时`$10^20$` 效果为$10^20$
可以看到20被分隔开了，10的20次方正确的写法应该为`$10^{20}$`    效果：$10^{20}$
接下来是括号：
写法|表示
:----|----
小括号`$(a+b+c)$` |   $(a+b+c)$
中括号`$[a\ b\ c]$` |   $[a\ b\ c]$
无空格 `$[a b c]$` |   $[a b c]$
尖括号`$< \overrightarrow {xyz}>$` | $< \overrightarrow {xyz}>$

## 1.6   求和，极限，积分，分式，根式
写法|表示
:----|----
求和`$\sum_{i=1}^{N}{W_i*X_i+b_i}$`  |  $\sum_{i=1}^{N}{W_i*X_i+b_i}$
极限`$\lim_{x \to 0}{f(x)}$`|  $\lim_{x \to 0}{f(x)}$
积分`$\int_0^\infty{f(x)dx}$`| $\int_0^\infty{f(x)dx}$
分式`$\frac {x+y}{x_0+y_0}$`| $\frac {x+y}{x_0+y_0}$
根式`$\sqrt[x]{y}$` | $\sqrt[x]{y}$  

## 1.7  常用函数
写法|表示
----|----
`$\sin{(w*x+b)}$`   |    $\sin{(w*x+b)}$
`$\cos{(w*x+b)}$`   |    $\cos{(w*x+b)}$
`$\tan{(w*x+b)}$`   |    $\tan{(w*x+b)}$
`$\ln{(w*x+b)}$`   |    $\ln{(w*x+b)}$
`$\max{(w*x+b)}$`   |    $\max{(w*x+b)}$
`$\min{(w*x+b)}$`   |    $\min{(w*x+b)}$

其他函数就按自己想象写就行了比如softmax 函数:
`$$softmax(x_i) = \frac {e^{x_i}}{\sum_{j=0}^N{e^x_j}}$$`
$$softmax(x_i) = \frac {e^{x_i}}{\sum_{j=0}^N{e^x_j}}$$

##  1.8  算式与特殊符号
写法|表示
----|----
`$\pm$`| $\pm$
`$\div$`| $\div$
`$\times$`| $\times$
` $\sum$`| $\sum$
` $\prod$`| $\prod$
` $\leq$`| $\leq$
`$\neq$`| $\neq$
`$\geq$`| $\geq$
`$\infty$`|$\infty$
`$\cup$`|  $\cup$
`$\cap$`| $\cap$
`$\subset$`| $\subset$
`$\subseteq$`| $\subseteq$
`$\supset$`| $\supset$
`$\supseteq$`| $\supseteq$
`$\in$`| $\in$
`$\notin$`| $\notin$
`$\varnothing$`| $\varnothing$
`$\forall$`| $\forall$
`$\exist$`| $\exist$
`$\lnot$`| $\lnot$
`$\nabla$`| $\nabla$
`$\partial$`|$\partial$

## 1.9  矩阵
`\begin{matrix}` 标识开始
`\end{matrix}`   标识结束
`pmatrix` 小括号外框
`bmatrix` 中括号外框
`Bmatrix` 大括号外框
`vmatrix` 单竖线外框
`Vmatrix` 双竖线外框

`\\` 行结尾
`&`元素分割
`\cdots` 横向省略号
`\vdots` 竖向省略号
`\ddots` 斜向省略号

例1：
$$
\begin{bmatrix}
a_{00}&a_{01}\\
a_{10}&a_{11}\\
\end{bmatrix}
$$
例2：
$$
A_{mn}=
\begin{vmatrix}
a_{00}&a_{01}&{\cdots}&{a_{0n}}\\
a_{10}&a_{11}&{\cdots}&{a_{1n}}\\
{\vdots}&{\vdots}&{\ddots}&{\vdots}\\
a_{m0}&a_{m1}&{\cdots}&{a_{mn}}\\
\end{vmatrix}
$$
## 1.10  方程组
例：
$$
\begin{cases}
a_1x+b_1y+c_1z=d_1\\
a_2x+b_2y+c_2z=d_2\\
a_3x+b_3y+c_3z=d_3\\
\end{cases}
$$

## 1.11 添加图片

![avatar](/Entropy/ActivationFunction.png)








