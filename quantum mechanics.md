[TOC]



# 第一章 波函数

1.1 薛定谔方程

微观粒子的状态由一个波函数描写，这个波函数通过解**薛定谔方程**得到：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image002.gif) （一维情况）

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image004.gif) （三维情况）

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image006.gif)是普朗克常数h除以![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image008.gif)：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image010.gif)

 

1.2 波函数的统计诠释

波恩关于波函数的统计诠释认为，当一个微观粒子处于状态![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image012.gif)时，在t时刻**r**处的体积V内发现这个粒子的概率为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image014.gif)

物理上的波函数必须满足**归一化条件**

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image016.gif)

波函数必须是平方可积的（即波函数处于希尔伯特空间中）。平方可积即为：单值、有限、连续。

 

1.3 力学量的期望

**期待值**是对含有相同体系的一个系综中不同体系的重复测量的平均值。对于一个处于![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image018.gif)态的粒子，其x的期待值是

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image020.gif)

动量p=mv的期待值是

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image022.gif)

计算物理量Q(x,p)的期待值

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image024.gif)

 

1.4 测量对波函数的影响

给定初始波函数，体系的波函数将按薛定谔方程演化，但是，如果对体系进行测量，将导致波函数的坍缩。对坐标进行测量，如果测量的结果是x0，波函数坍缩为x0处的一个尖峰。

**不确定原理**：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image026.gif)

**本章简单介绍了一些统计相关的知识和算符，使学生能够求解粒子在某一特定位置出现的概率以及确定任意一个可观测量的期待值，为后面的学习打下基础。**

 

**例题** **1**

一个粒子由下述波函数描述（t=0时刻）

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image028.gif)

(a)   确定归一化常数A。

(b)   x与p的期望值（t=0时刻）分别是多少？

(c)   分别求出x2和p2的期待值。

(d)   分别求出x和p的不确定。

(e)   验证所得结果符合不确定原理。

 

**解**

(a) 归一化

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image030.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image032.gif)

(b)  

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image034.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image036.gif)

(c)  

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image038.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image040.gif)

(d)  

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image042.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image044.gif)

(e)  

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image046.gif)

 

本题基本包含本章所学的全部内容，包括求归一化常数，各物理量的期待值以及不确定原理。

 

 

**例题** **2**

计算 ![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image048.gif)。

 

**解**

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image050.gif)

利用薛定谔方程

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image052.gif)

并带入![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image054.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image056.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image058.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image060.gif)

对第一项分部积分两次, 并利用边界条件 (当![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image062.gif) 时, 波函数及其导数为零), 前面两 项相互抵消, 最后有

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image064.gif)

 

本题包含上题遗漏的算符计算，因此作为补充也被添加为例题。

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

# 第二章 定态薛定谔方程

2.1 定态

求解薛定谔方程

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image066.gif)

假设V是不依赖时间的，则方程可以用分离变量法求解，寻求简单乘积形式的解

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image068.gif)

薛定谔方程可以转化为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image070.gif)

得到**定态薛定谔方程**，

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image072.gif)

此时波函数为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image074.gif)

它们是**定态**的。尽管波函数本身与时间有关，但概率密度

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image076.gif)

不依赖于时间，时间因子被相互抵消。 计算任何动力学变量算符的期待值也不依赖于时间，因此可以用![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image078.gif)来代替![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image018.gif)。

它们是具有**确定总能量**的态。经典力学中总能量（动能加势能）称为**哈密顿量：**

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image080.gif)

对应的哈密顿算符为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image082.gif)

代入定态薛定谔方程

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image084.gif)

总能量的期待值为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image086.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image088.gif)

计算可得H的标准差为0，即表明分离变量解的性质：总能量的每次测量结果是确定的值E。

一般解是分离变量解的**线性组合**

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image090.gif)

 

2.2 典型例子

1.一维无限深势阱

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image092.gif)

能量本征函数和能量本征值为

 

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image094.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image096.gif)

2.一维简谐振子

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image098.gif)

能量本征函数和能量本征值为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image100.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image102.gif)

 

3.一维自由粒子

定态薛定谔方程为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image104.gif)

能量本征函数和能量本征值为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image106.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image108.gif)

 

4.一维![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image110.gif)函数势阱

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image112.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image114.gif)只有一个束缚态，能量本征函数和能量本征值为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image116.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image118.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image120.gif)定态薛定谔方程的解为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image122.gif)

 

反射系数

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image124.gif)

透射系数

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image126.gif)

反射系数R与透射系数T之和为1，即

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image128.gif)

**本章由分离变量法引出定态薛定谔方程，并介绍了几个典型例子，使学生能求出能量测量的可能结果及其出现的概率。**

 

**例题**

一个处于谐振子势的粒子初始状态为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image130.gif)

(a) 求出A。

(b) 给出![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image132.gif)和![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image134.gif)。

(c) 计算![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image136.gif)和![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image138.gif)。用![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image140.gif)代替![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image142.gif)，结果怎样？验证恩费斯脱定理![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image144.gif)对此波函数成立。

(d) 如果测量这个粒子的能量，有哪些可能的值？各自出现的概率是多少？

 

**解**

(a) 归一化![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image146.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image148.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image150.gif)

所以

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image152.gif)

 

(b)  

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image154.gif)

其中，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image156.gif)，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image158.gif)是谐振子基态和第一激发态的能量。

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image160.gif)

 

 

 

 

 

 

 

(c)  

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image162.gif)

利用

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image164.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image166.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image168.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image170.gif)

或者

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image172.gif)

由恩费斯脱定理

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image174.gif)

代入谐振子势能![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image176.gif)及![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image138.gif)，有

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image178.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image180.gif)

显然满足恩费斯脱定理，如果用![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image140.gif)代替![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image142.gif)，则有

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image182.gif)

其中![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image184.gif)，重复上面的计算，有

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image186.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image188.gif)

显然此时，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image144.gif)仍然满足。

当不同的谐振子定态叠加时，只有叠加态中有相邻态时，即有![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image190.gif)态时，必须还有![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image192.gif)态，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image136.gif)才会以![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image194.gif)的形式振荡。

 

(d) 测量能量得到![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image156.gif)的概率是![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image196.gif)，得到![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image158.gif)的概率是![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image198.gif)。

 

本题选取本章典型粒子中的谐振子态，运用了升降阶算符，同时与上一章的例题2也有联系。

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

# 第三章 形式理论

3.1 力学量算符与其本征函数

量子力学中力学量（可观测量）用**厄密算符**表示，厄密算符满足

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image200.gif)

f，g为任意满足平方可积条件的函数。

厄密算符具有实本征值的本征函数（系），具有不同本征值的本征函数相互正交，若本征值为分立谱，本征函数可归一化，是物理上可实现的态。若本征值为连续谱，本征函数可归一化为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image110.gif)函数，这种本征函数不是物理上可实现的态，但是它们的组合可以是物理上可实现的态。

一组相互对易的厄密算符有共同的本征函数系。而两个不对易的厄密算符没有共同的本征函数系，它们称为不相容力学量。对任意态测量不相容力学量![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image202.gif)和![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image204.gif)，不可能同时得到确定值，它们的标准差满足不确定原理

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image206.gif)

 

3.2 广义统计诠释

设力学量![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image202.gif)具有**分立谱**的正交归一本征函数系![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image208.gif)本征值为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image210.gif)，即

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image212.gif)

或

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image214.gif)

这个本征函数系是完备的，即![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image216.gif)，任意一个波函数可以用这个本征函数系展开

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image218.gif)

展开系数为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image220.gif)

对![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image222.gif)态测量力学量Q，得到的结果必然是Q本征值中的一个，得到![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image224.gif)的概率为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image226.gif)。

 

如果力学量![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image202.gif)具有**连续谱**的本征函数系

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image228.gif)

任意一个波函数可以用这个本征函数系展开为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image230.gif)

由于q连续变化，展开系数![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image232.gif)是q的函数。对![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image222.gif)态测量力学量Q，得到结果处于q到q+dq之间的概率为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image234.gif)。

 

3.3 表象理论

对任意一个物理态![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image236.gif)可以用一个力学量的**本征态**展开。当力学量![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image204.gif)的本征态为分立谱![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image238.gif)时，

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image240.gif)

在![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image204.gif)表象中，可以用矩阵形式来表示各种量子力学的公式。

 

**本章引入线性代数相关知识，使学生可以计算测量的可能结果及其概率，这和薛定谔方程一起构成量子力学的基础，还具体介绍了不确定原理。**

 

**例题** **1**

(a) 从第二章中列举一个仅具有分立谱线的哈密顿量（谐振子除外）。

(b) 从第二章中列举一个仅具有连续谱的哈密顿量（自由粒子除外）。

(c) 从第二章中列举一个既有分立谱又有连续谱的哈密顿量（有限深方势阱除外）。

 

**解**

易知（a）（b）（c）的答案分别为：无限深方势阱，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image110.gif)-函数势垒，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image110.gif)-函数势阱。

 

本题主要考核对概念的理解。

 

**例题** **2**

谐振子的相干态。在谐振子定态中仅n=0的态符合不确定原理的极限；一般情况下，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image242.gif)。但某些线性组合（所谓的相干态）也会减小不确定原理中的积。它们是湮灭算符的本征函数：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image244.gif)

（这里本征值![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image246.gif)可以是任何复数）。

(a) 对态![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image248.gif)计算![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image136.gif)，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image250.gif)，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image138.gif)，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image252.gif)。

(b) 求出![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image254.gif)和![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image256.gif)，证明![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image258.gif)。

(c) 像其他的波函数一样，相干态可以用能量本征态展开

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image260.gif)

证明展开系数是

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image262.gif)

(d) 由归一化![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image248.gif)确定![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image264.gif)。

(e) 现在加入时间因子：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image266.gif)

证明![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image268.gif)仍然是![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image270.gif)的本征态，但是本征值随时间变化

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image272.gif)

因此，一个相干态维持相干，并继续减小不确定原理中的积。

(f) 基态（![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image274.gif)）本身是相干态吗？如果是，它的本征值是什么？

 

**解**

(a) 因为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image276.gif)是![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image270.gif)的厄密共轭，所以有

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image278.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image280.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image282.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image284.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image286.gif)

(b)  

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image288.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image290.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image292.gif)

(c) 由

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image294.gif)

所以

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image296.gif)

(d) 归一化：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image298.gif)

所以

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image300.gif)

(e)  

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image302.gif)

所以，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image268.gif)仍然是![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image270.gif)的本征态，其本征值为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image304.gif)。

(f) 因为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image306.gif)，所以基态![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image308.gif)是![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image310.gif)的本征值为0的本征态，因此是相干态。

 

本题既考察了前面所学的内容，也运用了本章新学的算符和理论，虽然复杂但是考察全面。

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

# 第四章 三维空间中的量子力学

4.1 球坐标系中的薛定谔方程

当势能仅是到原点距离的函数时，应用球坐标求解将较为方便。球坐标系下的**拉普拉斯算符**的形式为：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image312.gif)

在球坐标系下，**定态薛定谔方程**可写为：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image314.gif)

与第一章类似，要寻求**分离变量解**![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image316.gif)，分离常数写做![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image318.gif)，得到

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image320.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image322.gif)

 

将上式两边同乘![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image324.gif)并将其分离变量

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image326.gif)

除以![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image328.gif)后将分离常数写做![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image330.gif)，得到

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image332.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image334.gif)

关于![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image336.gif)的方程

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image338.gif)    关于![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image340.gif)的方程

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image342.gif)

解为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image344.gif)

径向方程：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image346.gif)

 

4.2 氢原子

氢原子由一个质量较大、相对静止的带正电荷e的质子和一个质量较小带负电荷e的电子组成, 电子绕质子运动，由库仑定理，势能为 

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image348.gif)

氢原子**径向方程**为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image350.gif)

**径向波函数**为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image352.gif)

其中玻尔半径![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image354.gif)。

求解得到**玻尔公式**（氢原子能级公式）：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image356.gif)

对n能级，角动量量子数l可取0到n-1共n个值，对每个l，量子数可取l到-l共2l+1个值，所以氢原子能级的简并度为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image358.gif)（不考虑自旋时），考虑电子自选时为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image360.gif)。

当电子从高能级跃迁到低能级时会辐射出一个光子，光的频率为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image362.gif)

 

4.3 角动量

空间角动量算符

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image364.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image366.gif)

对易关系

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image368.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image370.gif)与![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image372.gif)的共同本征函数为球谐函数![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image374.gif)。 

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image376.gif)

 

4.4 自旋

每一种基本粒子都有内禀的自旋角动量从而有自旋磁矩，自旋角动量满足与轨道角动量一样的对易关系，即：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image378.gif)

电子自旋量子数为1/2，即![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image380.gif)本征值为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image382.gif)，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image384.gif)本征值为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image386.gif)。

两个角动量![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image388.gif)，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image390.gif)可以叠加一个总角动量![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image392.gif)，叠加出来的总角动量的量子数可能的取值为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image394.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image388.gif)，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image390.gif)相互独立，它们是对易的。但![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image396.gif)与![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image388.gif)，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image390.gif)不对易。可以由克莱布希-高登系数联系无耦合表象与耦合表象。

 

**本章大量运用数学物理方法，将所探讨的问题从一维扩展为三维，同时讲述了一个最简单的系统：氢原子，由其引出角动量与自旋，**

 

**例题**

一个粒子处在自旋态

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image398.gif)

(a) 求出归一化常数A。

(b) 求出![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image400.gif)，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image402.gif)和![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image404.gif)的期望值。

(c) 求出![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image406.gif)，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image408.gif)和![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image410.gif)的“不确定度”。

(d) 证明结果符合不确定原理。

 

解

(a) 归一化

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image412.gif)

(b)  

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image414.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image416.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image418.gif)

(c) 由于![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image420.gif)**，**![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image422.gif)**，**![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image424.gif)只有一个本征值![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image426.gif)，所以对任何自旋态都有

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image428.gif)

这样标准差为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image430.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image432.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image434.gif)

 

 

 

(d)  

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image436.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image438.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image440.gif)

满足不确定原理。

 

本题依旧遵循归一化-求期待值-求不确定度-验证不确定原理的模版，但引入矩阵计算，加入了本章新学的内容。

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

# 第五章 全同粒子

5.1 双粒子体系

单粒子![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image012.gif)是空间坐标![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image442.gif)和时间t的函数（暂时忽略自旋），而双粒子体系的态则是粒子1的坐标（![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image444.gif)）、粒子2的坐标（![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image446.gif)）和时间的函数：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image448.gif)

质量、电荷、自旋等固有属性完全相同的微观粒子称为全同粒子。在一个量子体系中全同粒子是不可区分的，两全同粒子相互交换不会引起物理性质的改变（全同性原理）。但可以构造一个波函数

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image450.gif)

这样理论上将允许两种全同粒子：**玻色子**（Bosons），取正号；**费米子**（Fermions）, 取负号。

具体的来看：

玻色子：自旋为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image452.gif)整数倍的粒子。

费米子： 自旋为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image454.gif)奇数倍的粒子。

两个全同费米子不可能占据相同的态（泡利不相容原理）

 

5.2 交换力

若体系的波函数可以表示为空间部分和自旋部分之积，则对称和反对称的空间波函数为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image456.gif)

这种波函数对称化的要求会使两粒子之间出现**交换力**。固体中的共价键即为交换力的表现。

 

5.3 量子统计

在零开，一个物理系统将处在它的能量最低状态（体系的基态）。温度提高，随机的热激发将开始占据激发态，热平衡时，微观粒子在能态的分布（相对概率）为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image458.gif)

 

 

 

 

 

 

 

 

 

**本章继续扩展所学原理，从单粒子推广到双粒子体系，由分辨粒子困难引出全同粒子的概念，在此基础上举出原子、固体等实例，运用原理解释元素周期表，最后简单讲述了量子统计力学，作为原理部分的收尾。**

 

**例题**

想象两个无相互作用，质量均为m，处于无限深方势阱中的粒子。如果一个粒子处于![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image190.gif)态，另一个粒子处于![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image460.gif)态，计算![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image462.gif)。假定：(a) 粒子是可分辨的。(b) 粒子为全同玻色子。(c) 粒子为全同费米子。

 

解

(a) 粒子可分辨时

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image464.gif)

其中

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image466.gif)

同理，

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image468.gif)

同理，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image470.gif)，所以

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image472.gif)

(b) 全同玻色子时

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image474.gif)

其中

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image476.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image478.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image480.gif)

最后一项只有当n和l具有相反的奇偶性时才成立。

(c) 全同费米子时

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image482.gif)

最后一项只有当n和l具有相同的奇偶性时才成立。

 

本题以第二章的无限深方势阱作大背景，深化了对全同粒子的理解。

# 第六章 不含时微扰理论

6.1 非简并微扰理论

设体系的哈密顿量为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image484.gif)，其中![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image486.gif)的本征函数已知，但是H的严格解无法求 出，若![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image488.gif)对应的能量远小于![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image486.gif)对应的能量，这时可由微扰理论近似求解H的能量本征值和 本征函数。一级近似下 (近似到![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image488.gif)一次项)，能量本征值为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image490.gif)

能量本征函数为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image492.gif)

其中![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image494.gif)是![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image486.gif)本征值为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image496.gif)的本征函数；![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image498.gif)是微扰哈密顿量在![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image486.gif)表象中的矩阵元。二级近似下能量本征值为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image500.gif)

 

6.2 简并微扰理论

如果无微扰状态是简并的，前面的理论就不再适用。若![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image486.gif)的某个能量是k度简并的，即有k本征函数![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image502.gif)对应同一个能量本征值E，要求能量的一级修正，首先在简并子空间，即![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image504.gif)为基矢的表象，求出微扰哈密顿![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image488.gif)的矩阵元![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image506.gif)，然后解![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image488.gif)的本征方程，可以求出k个能量一级修正![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image508.gif)(可能有重根, 表示简并仅部分消除)，再把得到的每个![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image508.gif)代人本征方程，对每个![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image508.gif)可以得到![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image510.gif)，对应的零级近似波函数为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image512.gif)

 

6.3 氢原子的精细结构

若在氢原子哈密顿量中考虑相对论修正和自旋一轨道耦合，由此产生的对氢原子能级的修正称为**精细结构**。相对论微扰哈密顿量为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image514.gif)，由此带来的能量一级修正为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image516.gif)

其中，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image518.gif)为无微扰时氢原子能级。自旋-轨道耦合哈密顿量为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image520.gif)

由此得到的能量一级修正为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image522.gif)

其中j是总角动量 (自旋 +轨道) 量子数。精细结构修正为两者之和

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image524.gif)

 

6.4 塞曼效应

当一个原子被置于均匀外磁场![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image526.gif)中时, 由于自旋和轨道磁矩与外磁场的相互作用，能级将发生改变。这个现象被称为塞曼效应。微扰哈密顿量为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image528.gif)

塞曼效应的特性关键取决于外磁场和内磁场的相对强度。

在**弱场**情况下![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image530.gif)，精细结构起主导作用，能量的一级修正为（取![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image526.gif)沿z轴方向)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image532.gif)

其中![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image534.gif)是玻尔磁子；![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image536.gif)为朗道g因子；![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image538.gif)是总动量的磁量子数。总能量一级修正是精细结构部分和塞曼效应部分之和。    在**强场**情况下![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image540.gif)，塞曼效应起主要作用，精细结构可以被当作微扰来处理。能量的一级修正为（忽略精细结构）为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image542.gif)

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

**本章给出了一种求解薛定谔方程的方法。微扰理论可以由无微扰情况下的精确解求出有微扰时的近似解，同时给出两个例子，第一个为最简单的原子****-****氢原子，第二个为原子置于均匀外磁场。**

 

**例题**

考虑一个带电粒子位于一维谐振子势中。假设我们加入一个微弱的电场（![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image544.gif)），从而使势能大小产生了![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image546.gif)的偏移。

(a) 证明能量一级修正为零，并计算出能量的二级修正。

(b) 在这个例子中，薛定谔方程是可以直接求解的，只要将变量变成![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image548.gif)。给出能量的精确值，并证明它们和微扰理论是一致的。

 

(a) 利用产生与湮灭算符，能量的一级修正为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image550.gif)

能量的二级修正为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image552.gif)

(b) 定态薛定谔方程为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image554.gif)

作变量代换![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image556.gif)，方程换为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image558.gif)

可以得到能量的精确解为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image560.gif)

可以看出，一级微扰为零，二级微扰为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image562.gif)，这与微扰理论得到的结果一致。

 

本题将本章新学的微扰理论进行实际应用，提升了求解的熟练度。

 

 

 

 

 

 

 

 

 

 

# 第七章 变分原理

7.1 变分原理

假设需要计算一个哈密顿量为H的体系的基态能量![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image564.gif)，但不能从（定态）薛定谔方程求解，将用到变分原理。设有任意试探波函数![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image566.gif)，其中![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image568.gif)为可调参数, 变分原理指出, 用这个波函数求出的能量期望值一定大于等于体系的基态能量, 即![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image570.gif)，因此, 改变可调参数使![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image572.gif)达到最小值, 即令![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image574.gif)，可以得到基态能量的上限。

7.2 氦原子基态

体系哈密顿量为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image576.gif)

选取试验波函数为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image578.gif)

其中Z为可调参数, 计算出能量期望值

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image580.gif)

其中，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image582.gif)为氢原子基态能量。令![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image584.gif)，求出当![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image586.gif)时，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image572.gif)最小为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image588.gif)

由变分原理, 氦原子基态能量![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image590.gif)（实验值为-79 ![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image592.gif)）。

 

7.3 氢分子离子

哈密顿量为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image594.gif)

考虑如下形式的试探波函数

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image596.gif)

 

归一化试探波函数，得到

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image598.gif)

被称为**交叠**积分，

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image600.gif)

被称为**直接**积分，

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image602.gif)

被称为**交换**积分，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image604.gif)，最后得到

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image606.gif)

根据变分原理，基态能量比![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image572.gif)小。这仅为电子的能量，还存在有关质子与质子相排斥的势能：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image608.gif)

令![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image610.gif)，以![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image612.gif)为单位表示能量，因此系统的总能量小于

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image614.gif)

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

**本章介绍了变分原理及其两个应用，分别为氦原子基态与氢分子离子。该原理有助于求出某些复杂分子的基态能量。算法容易，但只能求出一个上限。**

 

**例题**

取一个高斯函数试探函数求以下两种情况的基态能量的最优上限。

(a) 线性势能：![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image616.gif)；

(b) 四次方势能：![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image618.gif)。

 

解

取高斯函数作为试探波函数

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image620.gif)

其中b为常数；A由归一化确定

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image622.gif)

动能项

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image624.gif)

(a)   势能项

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image626.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image628.gif)

对任意b，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image572.gif)必大于等于![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image564.gif)。为了得到最佳上限，求![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image572.gif)的最小值：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image630.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image632.gif)

(b)   势能项

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image634.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image636.gif)

求![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image572.gif)的最小值：

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image638.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image640.gif)

 

本题作为本章的第一道习题，基础但很好的训练了对变分原理的使用。

 

 

 

 

 

# 第八章 WKB近似

8.1 WKB近似

**WKB**方法是得到一维定态薛定谔方程近似解的一种技术（它的基本思想同样可以应用于三维薛定谔方程的径向部分），此方法对计算束缚态能量和势垒穿透率都是非常有用的。    它的基本思想是: 如果势能![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image642.gif)在远大于波函数波长的区域内变化非常缓慢, 则在粒子能量大于势能![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image644.gif)的经典区域，波函数的近似解可以表示为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image646.gif)

其中动量![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image648.gif)。在粒子能量小于势能![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image650.gif)的非经典区域（动量为 虚数），波函数的近似解可以表示为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image652.gif)

(要依据波函数的标准条件取舍系数)在经典区和非经典区连接处，WKB近似不再适用，但是可以通过引入在转折点附近的修补波函数，再利用波函数连续的条件把经典区域和非经典 区域的波函数联系起来, 即把系数A，B，C，D联系起来。

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

**本章给出了一种求解一维定态薛定谔方程近似解的方法，并给出了不同条件下波函数的近似解的表达式。**

 

**例题**

利用以下形式的WKB近似

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image654.gif)

估算氢的束缚态能量。

 

解

在径向方程中的有效势为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image656.gif)

所以

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image658.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image660.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image662.gif)

其中

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image664.gif)

因为拐点![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image666.gif)和![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image668.gif)是根号下一元二次式的两个根，有

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image670.gif)

所以积分可以写为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image672.gif)

利用题目所给积分公式

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image674.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image676.gif)

由

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image678.gif)

可知

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image680.gif)

所以

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image682.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image684.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image686.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image688.gif)

当![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image690.gif)和![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image692.gif)时，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image694.gif)，回到玻尔能级。

 

本题利用WKB近似，加入等效势能中的离心力部分，估算了氢的束缚态能量，本章的大体内容为WKB近似，本题则很好地锻炼了运用该近似的能力。

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

# 第九章 含时微扰理论

9.1 含时微扰理论

如果允许在两个不同能级之间的跃迁（量子跃迁），必须引入含时势函数，即**量子动力学**。当哈密顿量的含时部分与不含时部分相比很小的时候，可以把含时部分当作微扰。设体系哈密顿量为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image696.gif)，其中![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image698.gif)与时间无关，仅微扰部分![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image700.gif)与时间有关。在微扰作用下体系可由![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image698.gif)的一个定态跃迁到另一个定态，含时微扰理论是要近似求出跃迁概率。将t时刻的波函数![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image702.gif)按![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image698.gif)的定态波函数![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image704.gif)展开成![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image706.gif)，代入![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image702.gif)满足的含时薛定谔方程，可以求出

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image708.gif)

其中，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image710.gif)是微扰矩阵元，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image712.gif)是体系从![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image518.gif)能级跃迁到![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image714.gif)能级的玻尔频率。这个方程等价于含时薛定谔方程，是含时薛定谔方程在![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image698.gif)表象中的矩阵表示形式。设微扰在![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image716.gif)时开始引入，这时体系处于![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image698.gif)的第k个本征态![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image718.gif)，即![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image720.gif)，则在一级近似下有

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image722.gif)

所以，体系在微扰作用下由初态![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image718.gif)跃迁到![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image724.gif)的概率为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image726.gif)

 

9.2 正弦微扰情况

设微扰对时间的依赖关系具有余弦形式![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image728.gif)则有

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image730.gif)

其中，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image732.gif)。如果驱动频率(![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image734.gif))和玻尔频率![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image736.gif)非常接近，则上式方括号中第二项起主要作用（若![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image738.gif)，则第一项起主要作用）

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image740.gif)

所以，若粒子初始时处在![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image742.gif)态, 经时间t后，发现它处在态![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image744.gif)的概率是

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image746.gif)

 

9.3 光的发射和吸收

原子在单位时间内由高能级![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image714.gif)自发地向低能级![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image748.gif)跃迁的概率称为自发发射系数![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image750.gif)。设作用于原子的光波在![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image752.gif)频率范围内的能量密度是![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image754.gif)，则在单位时间内原子由高能级![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image714.gif)向低能级![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image748.gif)跃迁的概率（同时发射一个能量为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image756.gif)的光子）为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image758.gif)称为受激发射系数，在单位时间内原子由低能级![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image748.gif)跃迁到高能级![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image714.gif)的概率（同时吸收一个能量为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image756.gif)的光子）为![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image760.gif)称为吸收系数。在一级近似下（同时仅考虑光波中的电场的作用，称为偶极近似）

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image762.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image764.gif)

由于![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image766.gif)为电子的电偶极矩，由![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image768.gif)决定的跃迁称为偶极跃迁。

9.4 选择定则 

在光波作用下，要实现原子在![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image770.gif)与![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image772.gif)态之间的跃迁，必须满足![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image774.gif)的条件，不能实现的跃迁称为禁戒跃迁。要使矩阵元不为零，两态之间的角量子数和磁量子数必须满足

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image776.gif)

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

**在本章以前，我们处理的问题都是不显含时间的，第九章开始就引入了含时势函数。将含时部分当作微扰，就引出本章的主要内容：含时微扰理论。本章除了介绍该理论外，还介绍了两个应用：原子辐射的吸收或发射。**

 

**例题**

质量为m的一个粒子在（一维）无限深方势阱中，开始时处于基态。在t=0时把一块“砖”丢到势阱中，因此势变成

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image778.gif)

其中![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image780.gif)。经过时间T后，测量粒子的能量，求得![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image782.gif)的概率（在一级微扰理论中）。

 

解

对一维无限深方势阱

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image784.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image096.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image780.gif)，可把势的变化看做微扰，微扰矩阵元为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image786.gif)

当微扰去掉后

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image788.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image790.gif)

 

本题为含时微扰理论求解的例子，结合前面所学的无限深方势阱，题目简洁，但求解问题所需要的知识与本章很切合。

 

 

 

 

 

 

 

 

# 第十章 绝热近似

10.1 绝热定理

假设体系的哈密顿量随时间的变化非常缓慢（绝热变化），当体系的哈密顿量由初值![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image792.gif)逐渐变化到终值![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image794.gif)，**绝热定理**指出：如果粒子开始时处在![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image792.gif)的第n阶本征态，它将演化至![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image794.gif)的第n阶本征态（演化按薛定谔方程）。即若设![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image796.gif)是哈密顿量![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image798.gif)在每一时刻的本征态，在t=0时体系处在 ![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image800.gif)，则在以后时刻体系处在态

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image802.gif)

这个态与![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image796.gif)仅差一对相因子，所以仍然是![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image798.gif)的本征态。式中

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image804.gif)

称为动力学相因子，

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image806.gif)

称为几何相因子。

 

10.2 几何 (贝瑞) 相

如果哈密顿量随时间的变化可以表示为N个参数![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image808.gif)的变化，则在 这种情况下，

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image810.gif)

这里![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image812.gif)是对这些参量求梯度。几何相因子可以表示为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image814.gif)

如果经过时间T之后，哈密顿量回到初始形式，那么，最终的几何相是

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image816.gif)

当参数空间是三维时，![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image818.gif)，可以类比磁矢势**A**、磁场、磁通量之间的关系。贝瑞相可以看做通过参数空间（闭合）路径一个“磁场”

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image820.gif)

的“通量”，即贝瑞相可以写为一个面积分

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image822.gif)

 

10.3 阿哈拉诺夫-博姆效应

在经典电动力学中，势（![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image824.gif)和![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image826.gif)）是不可直接测量的量——物理量是电场和磁场，基本定律不含势，所以在经典理论中在**E**和**B**为零的区域没有电磁场的影响。但是在量子力学中，因为哈密顿量是用![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image824.gif)和![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image826.gif)表示

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image828.gif)

矢势可以影响带电粒子的量子行为，即便是它在场为零的区域中运动。阿哈拉诺夫一博姆效应就是几何相的一个例子。

 

 

 

**本章为本学期量子力学所学内容的最后一章。本章继续扩展所学理论，探讨了系统哈密顿量随时间变化极度缓慢的情况。值得一提的是，贝瑞项有其拓扑学意义，在量子霍尔效应等现象中有重要意义。**

 

**例题**

(a) 当无限深方势阱的宽度![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image830.gif)绝热变化到![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image832.gif)时，计算其几何相，并讨论结果。

(b) 当宽度匀速变化时（![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image834.gif)），对于这个过程动力学相变化如何?

(c) 如果势阱缩小到初始宽度，对于这个循环贝瑞相是如何变化的?

 

解

(a) 一维无限深势阱的第n本征态为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image836.gif)

 

取阱宽w为参数，则在阱内

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image838.gif)

因此

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image840.gif)

因此几何相

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image842.gif)

(b) 由已知阱宽

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image844.gif)

因此，动力学相为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image846.gif)

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image848.gif)

 

(c) 由于仅有一个变化参量w，经过一段时间后当w回到初始值，几何相为

![img](file:///C:/WINDOWS/TEMP/msohtmlclip1/01/clip_image850.gif)

 

我选择的题目大多为无限深势阱与当前章节的结合。就像本题目，以无限深势阱为背景计算了本章新学的内容。

 