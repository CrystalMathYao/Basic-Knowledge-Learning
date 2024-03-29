第一章学习的内容是n元线性方程组矩阵消元法和解的情况判别准则，在判断解情况的过程中需要将增广矩阵经过初等行变换化成阶梯型矩阵才能进行判断，这差不多是已经把解已经求出来了，因此提出一个问题：能否直接从线性方程组的系数和常数项判断它有没有解，有多少解？

为了研究这个问题，从一个二元一次方程组入手：

![二元一次方程组](https://github.com/CrystalMathYao/Basic-Knowledge-Learning/blob/master/Mathematical%20Theory/高等代数/图/二元一次方程组.png)

简洁的记作|A|，或者det A。

那么对于数域K上的n个方程的n元线性方程组有没有类似的结论？这就需要用到n阶行列式的概念。

从上图的2阶行列式的定义可知，它是由两项组成的表达式，其中一项带正号，一项带负号，如何决定这符号？观察这两项的的区别发现，这两项仅在于列指标的排列不同，一个是12，另外一个是21。因而，为了给出n阶行列式的概念，需要首先讨论n个自然数组成的全排列的性质。

n个不同的自然数的一个全排列称为一个n元排列，对于给定的n个不同的自然数，它们形成的全排列有n！个。

小的数在前，大的数在后，此时称这一对数构成一个顺序；大的数在前，小的数在后，此时称这一对数构成一个逆序。一个n元排列中逆序的总数称为逆序数，记作<a href="https://www.codecogs.com/eqnedit.php?latex=\tau(a_{1}&space;a_{2}\cdots&space;a_{n})" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\tau(a_{1}&space;a_{2}\cdots&space;a_{n})" title="\tau(a_{1} a_{2}\cdots a_{n})" /></a>

从而有，逆序数为奇数的排列称为奇排列，逆序数为偶数的排列称为偶排列。把排列2341的3和1互换位置，其余数字不动，得到新的排列2143，像这样的变换称为一个对换，记作(3,1)。

定理1   对换改变n元排列的奇偶性。

![对换奇偶性证明1](https://github.com/CrystalMathYao/Basic-Knowledge-Learning/blob/master/Mathematical%20Theory/高等代数/图/对换奇偶性证明1.png)

![对换奇偶性证明2](https://github.com/CrystalMathYao/Basic-Knowledge-Learning/blob/master/Mathematical%20Theory/高等代数/图/对换奇偶性证明2.png)

定理2   任一n元排列与排列123...n可以经过一系列对换互变，并且所作对换的次数与这个n元排列具有相同的奇偶性。

![对换定理2](https://github.com/CrystalMathYao/Basic-Knowledge-Learning/blob/master/Mathematical%20Theory/高等代数/图/对换定理2.png)



