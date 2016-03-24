# Hello-Word

###任务说明
初级班

初级班和中级班的任务内容基本一致，但是在细节要求和时间要求上会不一样。

任务一：HTML、CSS基础

初级班：11天左右
####创建一个HTML文件，比如task0001.html文件，在里面实现一些代码，完成你的第一个网页。

这个页面中，需要有以下内容：
```html
一个一级标题，内容是你的Github账号
<h1>你的Github账号</h1>

一个无序列表，包括2个项目，里面每一个项目是一个链接，分别链接到task0001.html以及你的微博（或其他什么网站）
<ul><li>链接</li><li>链接</li></ul>

一个二级标题，内容随意（不能违法、反动、色情等）
<h2>happy</h2>

一个段落，内容随意（不能违法、反动、色情等）
<p></p>

一个图片（不能违法、反动、色情等）
<img src="" alt="">
```
####完成task0001.html

####2.1 任务描述

面向零基础同学
```css
学习以下CSS是怎么运作的，然后创建一个task0001.css的文件，
并在task0001.html中引入它，然后我们对task0001.html做一些让他变得花哨一点的事情：

让一级标题的文字颜色变成蓝色
h1{
color: blue;
}

二级标题的文字大小变成14px
h2{
font-size: 14px;
}

段落的文字大小变成12px，文字颜色是黄色，带一个黑色的背景色
P{
font-size: 12px;
color: yellow;
background-color: black;
}

图片有一个红色的，2px粗的边框
img{
border: 2px solid red;
}

```
####在你的task0001.html中，快速实践以下文本相关的所有属性内容：
```css
text-indent       文本缩进
text-transform    控制文本大小写
text-decoration   文本指定其他风格
text-align        文本水平对齐方式（排列）
word-spacing      字间距拉近拉远
white-space       如何处理元素内的空白
color             颜色
line-height       行间距 行高
font              字体属性
font-family       指定字体
font-size         字体大小
font-weight       字体粗细
font-face         引入新字体（电脑里没有的）自定义字体

【掌握文本、文字、链接相关的样式属性
a:link - 普通的、未被访问的链接
a:visited - 用户已访问的链接
a:hover - 鼠标指针位于链接的上方
a:active - 链接被点击的时刻
:focus   伪类 /* 获得焦点时 */
【掌握背景属性 
color（英文色：可能有的浏览器不支持；红绿蓝16进制色；RGB色）；background-color（元素背景色）；background（背景图，默认重复）
【掌握列表相关的样式属性

CSS ul有三种标记样式：
disc    实心圆点
circle  空心圆点
square  实心方块
在有序列表中，每个列表项都被标记了不同的序号。

用list-style 属性指定标记样式：

decimal     数字1.2.3……
lower-roman 小写罗马
upper-roman 大写罗马
lower-latin a.b.c……
upper-latin A.B.C……

【深入了解行高属性（行高 半行距）
默认line-height状态1.0-1.2 ；想自定义又灵活继承（纯数字1.5）不会忽略font-size
```
在`task0001.html`中，实践以下内容：

- 用两种方法来实现一个背景色为`红色`、宽度为`960px`的`<DIV>`在浏览器中居中
- 有的圆角矩形是复杂图案，无法直接用border-radius，请在不使用border-radius的情况下实现一个可复用的高度和宽度都自适应的圆角矩形 ![示例](img/task0001_7.png)
- 用两种不同的方法来实现一个两列布局，其中左侧部分宽度固定、右侧部分宽度随浏览器宽度的变化而自适应变化 ![示例](img/task0001_3.jpg)
- 用两种不同的方式来实现一个三列布局，其中左侧和右侧的部分宽度固定，中间部分宽度随浏览器宽度的变化而自适应变化
- 实现一个浮动布局，红色容器中每一行的蓝色容器数量随着浏览器宽度的变化而变化 ![示例1](img/task0001_4.jpg) ![示例2](img/task0001_5.jpg)

任务二：JavaScript基础

初级班：13天左右

任务三：深入学习JavaScript语言的一些特性、以及相关的一些设计模式等知识。实践一个小型的to-do项目实践，巩固学习知识

初级班：10天左右

任务四：关于移动、node.js、ES6、CSS预处理、CSS后处理、JavaScript模块化、前端工程化，掌握目前前端主流技术。并通过to-do大型项目实践，做一个移动+PC的大型项目，学习如何做技术选项，如何做大型项目设计架构

初级班：30天左右
