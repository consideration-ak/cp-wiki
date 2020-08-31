# 二分查找

二分查找是一个非常实用的算法。它的基本思想是，对于一个在某种意义上有序的数组，这个数组的前半部分满足某一条件，而后半部分不满足这一条件，我们不断选择区间中点，判断其是否满足条件，从而将区间不断折半，最后就可以找到数组中的转折点，也即满足这一条件的最后一个点，或不满足这个条件的第一个点。因为区间的大小每次都缩小为原来的一半，所以二分查找的复杂度是$O(\log N)$。

二分查找在CP中的一个常见应用是**二分答案**。在这一类题目中，我们往往需要求出满足条件的最大值或最小值。如果这一取值和条件的成立与否之间满足有序性，我们就可以通过对整个定义域进行二分查找，来找到我们需要的最值。

## 学习资源

### [ITMO Academy: pilot course](https://codeforces.com/edu/course/2/lesson/6)

来自Codeforces EDU。包括视频教程、图文教程和22道练习题。

## 练习题

### [SPOJ - AGGRCOW](https://www.spoj.com/problems/AGGRCOW/)

::: details 提示

如果把题目变成：要求任意两头牛之间的距离不小于$D$，最多能安排多少头牛，我们应该如何做？

:::

::: details 参考代码（C++）

<<<@/docs/basic/binary-search/src/SPOJ-AGGRCOW.cpp

:::

### [SNSS-2020 R2 - Meeting with readers](https://contest.yandex.com/snss2020/contest/19321/problems/D/)

::: details 提示

如果只选择不满意值不超过$W$的作家，能否覆盖会议所需要的时间段？

:::

::: details 参考代码（C++）

<<< @/docs/editorial/others/SNSS2020-R2/src/d.cpp

:::

<Utterances />
