---
title: "高等代数2 每周一题 2017S01"
categories:
 - Math
tags:
- Math
- Algebra
- Exercises
---

## 题目
来自谢启鸿老师的[每周一题](http://www.cnblogs.com/torsor/p/6500781.html)
**问题2017S01** 设 $$A$$ 是 $$n$$ 阶对合阵, 即 $$A^2=I_n$$, 证明: $$n-\mathrm{tr}(A)$$ 为偶数, 并且 $$\mathrm{tr}(A)=n$$ 的充要条件是 $$A=I_n$$.

## 解答
### 前一小问
由 $$A^2=I_n$$, 结合定理 6.1.2, 知 $$\exists P$$ 非异, 使得 $$P A P^{-1} P A P{-1} = P I_n P^{-1}$$, 且 $$B = P A P^{-1}$$ 为上三角阵, 显然, $$A$$ 与 $$B$$ 的特征值相同, 以下不妨只讨论 $$B$$. 由上, $$B^2=I_n$$. 由矩阵乘积的定义, 知 $$B$$ 的特征值 $$ \lambda_i ^2 = 1, \lambda_i = ±1$$. $$\mathrm{tr}(B)$$ 与 $$n$$ 的奇偶相同, 故 $$n-\mathrm{tr}(B)$$ 为偶数.  
### 后一小问
充分性显然.  
$$\mathrm{tr}(B)=n$$ 时，$$\lambda_i = 1$$. 由 $$I_n$$ 中 $$I_{1 2} = 0$$, $$b_{1 2} * 1 = 0$$ 故 $$b_{1 2} = 0$$. 依此类推 $$\forall b_{i j} (i < j)$$, 有 $$b_{i j} = 0$$. 必要性得证.  