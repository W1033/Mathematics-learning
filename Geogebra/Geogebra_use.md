# GeoGebra


## Table Of Contents



### New Words
- **graph [grɑːf] --n.图表, 曲线图**
- **graphing [] --n.图表；示意图. --v.绘制（graph的 ing 形式）**
    + --> Graphing Tools 图形化工具
    + --> graphing method 作图法
- **algebra ['ældʒɪbrə] --n.代数学, 代数**
- **calculator ['kælkjʊleɪtə] --n.计算器**
- **calculation [kælkjʊ'leɪʃ(ə)n] --n.计算, 打算**
- **calculate ['kælkjʊleɪt] --v.计算**
    + calculate the cost of a journey. 计算旅行费用.
    + calculate the velocity of light. 计算光的速度. 
- **geometry [dʒɪ'ɒmɪtrɪ] --n.几何<学>**
    + analytic geometry. 解析几何



## Content

### 1. Geogebra 是设么?
- GeoGebra是一款**开源的动态几何软件**. 其绘图的基本元素包括点, 直线, 线段, 多边形,
  向量, 圆锥曲线和函数. GeoGebra 3.2及以后的版本还加入了电子表格和正在不断完善的数据处理功能.

  GeoGebra 可以完成大量初高等数学中的绘图工作, 比如直接绘制圆锥曲线, 对函数求导数,
  积分, 对多项式函数求极值和拐点等, 这些极大的方便了教师们制作教学材料.

  GeoGebra 这几年逐渐形成风潮, 最大的原因在, 它允许使用者自己下指令扩充功能.
  使用者也可以加入翻译或是开发志工协助开发推展, 这是很多付费软件做不到的事.
  它有自己的程式语法`GeoGebraScript`, 也可以用 JavaScript 做进阶操控, 增加功能,
  如此将使用者的用法由原设计者所制定的框架中释放出. 使用者得以自由灿烂的设计自己的作品. 
  另一个优点是, GeoGebra 并不局限在几何的范围. 它还可以制作微积分, 线性代数等,
  也有符号运算的功能.
- `GeoGebra (Classic)` 6.0.528.0. GeoGebra
  项目目前也提供在线版和两个拆分出来的独立版本(`Graphing Calculator` and
  `Geogebra Geometry`).

### 2. 主界面 中-英 对照
- Graphing Calculator   -- 图形计算器
- Geometry              -- 几何
- 3D Calculator         -- 3D计算器
- Scientific Calculator -- 科学计算器
- GeoGebra Classic      -- GeoGebra 经典


### 3. Geogebra 运算符号与函数
- abs(x): 绝对值函数
- sqrt(x): 表示二次方根
- cbrt(x): 表示三次方根
- sgn(x)
- 对于 $y = \sqrt[q]{p}$ 可以转化为 $y = \frac{p}{x^q}$ 通过输入 $x^\frac{p}{q}$
  的方式得到, 也可以通过特定字母组合 "nroot(x, n)" 得到, 这里字母组合 "nroot(x, n)" 表示
  $x^n$
- 绝对值函数 $y = |x|$ 用 $abs(x)$ 表示, 这个字母组合与复数的模式一样的, 例如输入 
  "abs(2 + i)", 在代数区会出现数值 a = 2.24, 这是复数 2 + i 模的近似值, 默认情况下, 
  这个数值前是"空心", 如果点实了话会在绘图区出现相应的滑杆, 这个滑杆参数值是可以拖动的, 但
  已不是原复数 2 + i 的模了.在 Geogebar 中输入: abs(2 + i) 测试.