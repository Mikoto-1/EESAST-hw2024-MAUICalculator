# EESAST-hw2024-MAUICalculator 作业

---

2024 THU EESAST 软件部暑期培训 MAUI作业

---

## 题目及要求

完善计算器calculator

> - 要求：
>   1. 添加DEL按钮，功能：删除上一个输入的数字字符或运算符；当上一个字符为"="时，按下DEL会清空显示屏但**不改变所存储的计算结果**（即lastNumber的值）
>   2. 考虑程序的鲁棒性，在原始代码中，当使用者重复按下运算符时，会将lastNumber作为第二个操作数进行计算，也即按下"AC"、 "1"、 "+"、 "任意运算符"后会显示2，按下 "AC"、 "/"、"任意运算符"会显示NaN，这在一定程度上是不合适的。希望进行如下修改（只考虑"+"、 "-"、 "*"、 "/"）：当重复输入运算符时，不进行运算，根据**最后输入**的运算符进行更新，直至用户输入数字字符。
>   3. 添加第二页面（复杂计算模式），选中该页面后，会添加乘方（$x^y$）、对数（$\lg x,\ln x$）、开根号（$\sqrt x$）、阶乘（$x!$）、三角函数（$\sin,\cos,\tan,...$）等运算符和$\pi$、$e$等数学常数；用户可以随时切换这两个页面并保持**各参数不变**（如displayLabel.Text、lastNumber等属性）
>   4. 如果能美化一下外观就更好啦o(=•ェ•=)m

## 提交方式

GitHub 提交

- fork 仓库：[https://github.com/Grange007/EESAST-hw2024-MAUICalculator](https://github.com/Grange007/EESAST-hw2024-MAUICalculator) 到个人仓库，按要求修改好后，从个人仓库提pr到原本的仓库，pr信息填写为：`calculator_姓名_班级` （如：`calculator_大佬_无30`）。

## 截止日期

由zfgg决定
