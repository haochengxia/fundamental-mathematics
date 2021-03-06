# Primary Probability Theory Note

> Author: Haocheng Xia
> Created Date: 2021/12/02

## 01 随机事件及其运算

1. 样本空间 $\Omega$，样本空间中单个元素组成的子集为基本事件，其本身为必然事件；
2. 事件间的关系：包含、相等、互不相容（基于事件中的样本点）；
3. 事件间的运算：
   1. 并：$A \cup B$；
   2. 交：$A \cap B$，简记为$AB$，并交运算可推广到有限个或可列个事件；
   3. 差：$A - B$；
   4. 余：略。
4. 事件的运算性质：满足交换律、结合律、分配律、对偶律（可推广到有限个或可列个事件）；
5. 事件域：样本空间中某些子集及其运算结果， 又称$\sigma$域或$\sigma$代数；$\Omega = R \rightarrow$Borel事件域，其中的元素（集合）被称为Borel集或称为可测集。
6. 确定概率的方法：
   * 频率方法：记录$n(A)$为n次试验中事件A的频数，则事件A的频率为$f_n = \frac{n(A)}{n}$
   * 古典方法：通过事件A和$\Omega$中分别包含的样本点数目$k$和$n$来确定，$P(A)=\frac{k}{n}$
   * 几何方法：$P(A)=\frac{S_A}{S_\Omega}$
   * 主观方法：主观概率
7. 概率的性质：
   * 可加性：有限可加性；
   * 单调性；
   * 加法公式（抽屉原理）$\rightarrow$ 半可加性；
   * 连续性：对于单调不减的事件序列$F_1 \subset F_2 \subset \cdots \subset F_n \subset \cdots$，称可列并$\cup_{n=1}^\infty F_n$为$\{F_n\}$的极限事件。对于单调不增的事件序列$E_1 \supset E_2 \supset \cdots \supset E_n \supset \cdots$，称可列并$\cap_{n=1}^\infty E_n$为$\{E_n\}$的极限事件。
