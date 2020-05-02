# MathJax

- [MathJax 快速参考](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)
- [前端整合MathjaxJS的配置笔记](https://www.linpx.com/p/front-end-integration-mathjaxjs-configuration.html)



## Catalog




## New Words
- **quad [kwɒd] --n.四方院子，四组，空铅**
- **square [skweə] --n.广场，平方，正方形。 --adj.方，平方**
    + a square(n) of cloth. 方形的布
    + square(adj) root 平方根
    + It is neither round nor square. 这既不是圆的也不是方的。
- sqrt: square root 平方根
- **binomial [baɪ'nəʊmɪəl] --n.二项式. --adj.二项式的** 
    + binomial theorem 二项式定理
- **fraction ['frækʃ(ə)n] --n.分数**
- **sum [sʌm] --n.和, 总和**



## Content

### 上下标:
|名称 |数学表达式| markdown公式|
|:---: |:---:| :---: |
| 上标  | $a^b$ | `$a^b$` |
| 下标  | $a_b$ | `$a_b$` |

### 分数: 有 3 种表示方法
- (1) **`\frac{}{}` 或 `\dfrac{}{}` 或 `\tfrac{}{}`**
    + 第一个`{}`写分子，第二个`{}`写分母。
    + `\dfrac` means that the fraction is set in **d**isplaystyle（块级展示）
    + `\tfrac` means that the fraction is set in **t**extstyle（行级展示）
    + with `\frac`: the actual context implies the decision above 
      (实际情况根据上面的决定)
    + 示例: 
        - $\frac ab$ $\quad$ `$\frac ab$` (Tip: 分子分母只有一个字母，可以省略大括号)
        - $\frac{3+8a}{5b+6}$ $\quad$ `$\frac{3+8a}{5b+6}$` 
        - `$ x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a} $` <br/>
          $$
            x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}
          $$
- (2) **`{\over}`**
    
    + 示例:  ${a+1 \over b+1}$ $\quad$ `${a+1 \over b+1}$` 
- (3) **`\cfrac{}{}`**: is useful for continued fractions (连续分数很有用) 。
  (Tips:不知道这个连续分数是什么) 
  

### 累加: `\sum_{ }^{ }` 累加的连续式积分.
- 累加号的上标下标的前后顺序可以互换。

|名称 |数学表达式| markdown公式|
|:---: |:---:| :---: |
| 求和 | $\sum{3x^n}$ | `$\sum{3x^n}$` |
|带范围求| $\sum_{i=0}^N i^2 = \frac{(n^2+n)(2n+1)}{6}$ | `$\sum_{i=0}^N i^2 = \frac{(n^2+n)(2n+1)}{6}$` |


### 累乘: `\prod_{ }^{ }` (prod)
|名称 |数学表达式| markdown公式|
|:---: |:---:| :---: |
|  求乘号 |$\prod{3x^n}$  |  `$\prod{3x^n}$` |
|  带范围求乘 | $\prod_{n=1}^N{3x^n}$ | `$\prod_{n=1}^N{3x^n}$` |

### 开方: `\sqrt[]{ }` (平方根 Square root)
- `[]`中写的是开几次方, `{}`中写的是需要开方的数值。

|名称 |数学表达式| markdown公式|
|:---: |:---:| :---: |
| 开方号 | $\sqrt[5]{100}$ | `$\sqrt[5]{100}$` |


### 积分: `\int_{ }^{ }`
|名称 |数学表达式| markdown公式|
|:---: |:---:| :---: |
|  积分 | $\int^5_1{f(x)}{\rm d}x$ | `$\int^5_1{f(x)}{\rm d}x$`  |
| 二重积分 | $\iint^5_1{f(x)}{\rm d}x$ | `$\iint^5_1{f(x)}{\rm d}x$`  |
| 三重积分 | $\iiint^5_1{f(x)}{\rm d}x$  | `$\iiint^5_1{f(x)}{\rm d}x$`  |


### 二项式
-  数学表达式: `${n+1 \choose 2k}$ 或者 \binom{n+1}{2k}`
-  展示: $\binom{n+1}{2k}$ 


### 极限
- 块级表达式
    + $$
        \lim_{n\to +\infty} n
      $$
- 行级表达式:  $\lim_{n\to +\infty} n$
- Markdown 公式:  `$$\lim_{n\to +\infty} n$`


### 运算符:  
- Tips:  $\angle x'O'y' = 45^\circ$
- **关系运算符**
    + 大于等于:  $\geq$ $\quad$ `$\geq$` (greater than or equal to)
    + 小于等于:  $\leq$ $\quad$ `$\leq$` (less than or equal to)
    + 包含于:   $\subset$ $\quad$ `$\subset$`
    + 包含:    $\supset$ $\quad$ `$\supset$`
    + 属于:    $\in$ $\quad$ `$\in$`
- **二元运算符**
    + 加减:    (plus minus)
    + 点乘:  $\cdot$ $\quad$ `$\cdot$`
    + 乘:  $\times$ $\quad$ `$\times$`
    + 除:  $\div$ $\quad$ `$\div$` (division)
- **否定关系运算符**
    + 不等于:  $\not=$ / $\neq$ $\quad$ `$\not=$` / `$\neq$`
    + 不小于:  $\not<$ $\quad$ `$\not<$`
    + 不包含:  $\not\supset$ $\quad$ `$\not\supset$`
- **对数运算符**
    + $\log$ $\quad$ `$\log$`
    + $\log_2{18}$ $\quad$ `$\log_2{18}$`
    + $\ln$ $\quad$ `$\ln$`
- **三角运算符**
    + 垂直:  $\bot$ $\quad$ `$\bot$`
    + 角:  $\angle$ $\quad$ `$\angle$`
    + 30度角:  $30^\circ$ $\quad$ `$\30^\circ$`
    + 正弦:  $\sin$ $\quad$ `$\sin$`
    + 余弦:  $\cos$ $\quad$ `$\cos$`
    + 正切:  $\tan$ $\quad$ `$\tan$`
    + 更多见同级目录中的: MathJax-symbols.pdf
- **箭头运算符**
    + 左箭头:  $\leftarrow$  $\quad$  `$\leftarrow$`
    + 右箭头:  $\rightarrow$ $\quad$ `$\rightarrow$`
    + 长箭头:  $\longrightarrow$ $\quad$ `$\longrightarrow$`
    + 上箭头:  $\uparrow$ $\quad$ `$\uparrow$`
    + 下箭头:  $\downarrow$ $\quad$ `$\downarrow$`
- **Common Math Symbols**
    + 略:  $\dots$ $\quad$ `$\dots$`
    + 小于等于: $\leqslant$ $\quad$ `$\leqslant$`
    + 大于等于: $\geqslant$ $\quad$ `$\geqslant$`
    + 约等于: $\approx$ $\quad$ `$\approx$`
    + 三横: $\equiv$ $\quad$ `$\equiv$`
    + : $\cong$ $\quad$ `$\cong$`
    + : $\simeq$ $\quad$ `$\simeq$`
    + : $\partial$ $\quad$ `$\partial$`
    + 无穷: $\infty$ $\quad$ `$\infty$`
    + : $\nabla$ $\quad$ `$\nabla$`
    + : $\aleph$ $\quad$ `$\aleph$`
    + : $\ell$ $\quad$ `$\ell$`
    + 命题的或运算: $\vee$ $\quad$ `$\vee$`
    + 命题的与运算: $\wedge$ $\quad$ `$\wedge$`
    + 德尔塔: $\forall$ $\quad$ `$\forall$`
    + : $\exists$ $\quad$ `$\exists$`
    + 加减: $\pm$ $\quad$ `$\pm$`
    + 加减: $\mp$ $\quad$ `$\mp$`
    + 乘: $\times$ $\quad$ `$\times$`
    + 除: $\div$ $\quad$ `$\div$`
    + 集合的并运算: $\cup$ $\quad$ `$\cup$`
    + 集合的交运算: $\cap$ $\quad$ `$\cap$`
    + 属于: $\in$ $\quad$ `$\in$`
    + 不属于: $\notin$ $\quad$ `$\notin$`
    + 反斜杠: $\setminus$ $\quad$ `$\setminus$`
    + : $\varnothing$ $\quad$ `$\varnothing$`
    + : $\subset$ $\quad$ `$\subset$`
    + : $\supset$ $\quad$ `$\supset$`
    + 点: $\cdot$ $\quad$ `$\cdot$`
    + 圆: $\circ$ $\quad$  `$\circ`
    + 中间的点: $\centerdot$ $\quad$ `$\centerdot$`
    + copyrights: $\copyright$ $\quad$ `$\copyright$`
    + : $\maltese$ $\quad$ `$\maltese$`
    + 到: $\to$ $\quad$ `$\to$`
    + 等价: $\iff$ $\quad$ `$\iff$`
    + 美元符号: $\$$ $\quad$ `$\$$`
    + : $\pounds$ $\quad$ `$\pounds$`

    + : $\ast$ $\quad$ `$\ast$`
    + 型号: $\dag$ $\quad$ `$\dag$`
    + : $\ddag$ $\quad$ `$\ddag$`
    + 大的实心点: $\bullet$ $\quad$ `$\bullet$`
    + 竖波浪线: $\wr$ $\quad$ `$\wr$`
- **希腊字母 （Greek Letters）**
    + $\alpha$ $\quad$ `\alpha`
    + $\beta$ $\quad$ `$\beta$`
    + $\gamma$ $\quad$ `$\gamma$`
    + $\delta$ $\quad$ `$\delta$`
    + $\epsilon$ $\quad$ `$\epsilon$`
    + $\zeta$ $\quad$ `$\zeta$`
    + $\eta$ $\quad$ `$\eta$`
    + $\theta$ $\quad$ `$\theta$`
    + $\iota$ $\quad$ `$\iota$`
    + $\kappa$ $\quad$ `$\kappa$`
    + $\lambda$ $\quad$ `$\lamda$`
    + $\mu$ $\quad$ `$\mu$`
    + $\nu$ $\quad$ `$\nu$`
    + $\xi$ $\quad$ `$\xi$`
    + $\omicron$ $\quad$ `$\omicron$`
    + $\pi$ $\quad$ `$\pi$`
    + $\rho$ $\quad$ `$\rho$`
    + $\sigma$ $\quad$ `$\sigma$`
    + $\tau$ $\quad$ `$\tau$`
    + $\upsilon$ $\quad$ `$\upsilon$`
    + $\phi$ $\quad$ `$\phi$`
    + $\chi$ $\quad$ `$\chi$`
    + $\psi$ $\quad$ `$\psi$`
    + $\omega$ $\quad$ `$\omega$`
- **矢量/重音/变音 符号**
    + 向量 (`\vec`):  示例如下: 
        - $\vec a$ $\quad$ `$\vec a$`
        - $\overrightarrow{xy}$ $\quad$ `$\overrightarrow{xy}$`
        - $\overleftrightarrow{xy}$ $\quad$ `$\overleftrightarrow{xy}$`  
    + 重音符（`\hat`）: 
        - $\hat x$ $\quad$ `$\hat x$`      
    + 变音符（`\widehat`）:
        - $\widehat {xy}$ $\quad$ `$\widehat {xy}$`
    + 逻辑表示 Not (`\bar`）:
        - $\bar xyz$ $\quad$ `$bar xyz$` 
 - **空格**
    + 小空格 
        - $a b$ $\quad$ `$a b$`
    + 四字格 (`\quad`)
        - $a \quad b$ $\quad$ `$a \quad b$`
- **更多字符**: 
    + 见同级目录中的: MathJax-symbols.pdf


### 矩阵: 
+ (1)、Use `$$\begin{matrix}...\end{matrix}$$` In between the `\begin` and 
    `\end`, put the matrix elements. End each matrix row with `\\`, and 
    separate matrix elements with `&`. For example:
    +  ```
        $$
            \begin{matrix}
            1 & x & x^2 \\
            1 & y & y^2 \\
            1 & z & z^2 \\
            \end{matrix}
        $$
        ```
        $$
            \begin{matrix}
            1 & x & x^2 \\
            1 & y & y^2 \\
            1 & z & z^2 \\
            \end{matrix}
        $$
    + MathJax will adjust the sizes of the rows and columns(列) so that 
        everything fits.
+ (2)、To add brackets(/'brækɪt/ n.支架，括号), either use `left...\right`
    as in section 6 of the tutorial, or replace
    - `matrix` with `pmatrix`
        + ```
            $$
                \begin{pmatrix}
                1 & 2 \\
                3 & 4 \\
                \end{pmatrix}
            $$
            ```
            $$
                \begin{pmatrix}
                1 & 2 \\
                3 & 4 \\
                \end{pmatrix}
            $$
    - `bmatrix` (Tip: 方括号 bracket)
        + ```
            $$
                \begin{bmatrix}
                1 & 2 \\
                3 & 4 \\
                \end{bmatrix}
            $$
            ```
            $$
                \begin{bmatrix}
                1 & 2 \\
                3 & 4 \\
                \end{bmatrix}
            $$
    - `Bmatrix`
        +  ```
            $$
                \begin{Bmatrix}
                1 & 2 \\
                3 & 4 \\
                \end{Bmatrix}
            $$
            ```
            $$
                \begin{Bmatrix}
                1 & 2 \\
                3 & 4 \\
                \end{Bmatrix}
            $$
    - `vmatrix`
        +  ```
            $$
                \begin{vmatrix}
                1 & 2 \\
                3 & 4 \\
                \end{vmatrix}
            $$
            ```
            $$
                \begin{vmatrix}
                1 & 2 \\
                3 & 4 \\
                \end{vmatrix}
            $$
    - `Vmatrix`
        +  ```
            $$
                \begin{Vmatrix}
                1 & 2 \\
                3 & 4 \\
                \end{Vmatrix}
            $$
            ```
            $$
                \begin{Vmatrix}
                1 & 2 \\
                3 & 4 \\
                \end{Vmatrix}
            $$
+ (3)、Use `\cdots ⋯ \ddots ⋱ \vdots`: when you want to omit(省略) some of 
  the entries(条目): 
    - ```
        $$
            \begin{pmatrix}
            1 & a_1 & a_1^2 & \cdots & a_1^n \\
            1 & a_2 & a_2^2 & \cdots & a_2^n \\
            \vdots & \vdots & \ vdots & \ddots & \vdots \\
            1 & a_m & a_m^2 & \cdots & a_m^n
            \end{pmatrix}  
        $$
      ```
      $$
            \begin{pmatrix}
            1 & a_1 & a_1^2 & \cdots & a_1^n \\
            1 & a_2 & a_2^2 & \cdots & a_2^n \\
            \vdots & \vdots & \ vdots & \ddots & \vdots \\
            1 & a_m & a_m^2 & \cdots & a_m^n
            \end{pmatrix}  
      $$
+ (4)、For horizontally 'augmented' matrices, put parentheses or brackets 
  around a suitably-formatted table;  对于水平“增强”矩阵，将括号或括号放在适当
  格式的表格周围; see `arrays` below for details. Here is an example: 
    - ```
        $$
            \left[
            \begin{array}{cc|c}
            1 & 2 & 3 \\
            4 & 5 & 6
            \end{array}
            \right]
        $$
      ```
      $$
            \left[
            \begin{array}{cc|c}
            1 & 2 & 3 \\
            4 & 5 & 6
            \end{array}
            \right]
      $$
    - The `cc|c` is the crucial part here; it says that there are there
      centered columns with a vertical bar between the second and third.
+ (5)、For vertically 'augmented' matrices, use `\hline`. For example
    - ```
         $$
            \begin{pmatrix}
                a & b \\
                c & d \\
            \hline
                1 & 0 \\
                0 & 1
            \end{pmatrix}
         $$
      ```
+ (6)、For small inline matrices use `\bigl(\begin{smallmatrix})...\end{smallmatrix}\bigr`, e.g. :
    - ```
        $$
            \bigl(\begin{smallmatrix}
            a & b \\
            c & d 
            \end{smallmatrix}) \bigr
        $$
      ```
        Typora 不支持

### 阵列
- 需要 array 环境:  起始、结束处以 {array} 声明
- 对齐方式:  在 {array} 后以 {} 逐行统一声明
    + 对齐:  `l`左对齐；`c`居中；`r`右对齐
    + 竖直线:  在声明对齐方式时，插入 `|` 建立竖直线
- 插入水平线:  `\hline`    
- 示例: 
    + ```
        $$
            \begin{array}{c|}
            {\downarrow} & {a} & {b} & {c} \\
            \hline
            {R_1} & {c} & {b} & {a} \\
            {R_2} & {b} & {c} & {c} \\
            \end{array}
        $$
      ```
      $$
            \begin{array}{c|}
            {\downarrow} & {a} & {b} & {c} \\
            \hline
            {R_1} & {c} & {b} & {a} \\
            {R_2} & {b} & {c} & {c} \\
            \end{array}
      $$



### 分段函数:  Definitions([defɪ'nɪʃ(ə)n]n.定义，精确度) by cases (piecewise functions)
- Use `\begin{cases}...\end{cases}`. End each case with a `\\`, and use `&`
  before parts that should be aligned. For example: 
    + ```
        $$
            f(x) = 
            \begin{cases}
                -x, & x < 0 \\
                x^2 & 0 
            \end{cases}  
        $$
      ```
      $$
           f(x) = 
            \begin{cases}
                -x, & x < 0 \\
                x^2, & 0 \leq x \leq 1 \\
                1, x > 1
            \end{cases}  
      $$

### 其他
- 中心圆点 : `$\cdot$`: $x \cdot y$ $\quad$ `$x \cdot y$` 

