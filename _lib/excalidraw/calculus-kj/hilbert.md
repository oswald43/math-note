---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠== You can decompress Drawing data with the command palette: 'Decompress current Excalidraw file'. For more info check in plugin settings under 'Saving'


# Excalidraw Data

## Text Elements
二元函数的泰勒展开 - 麦克劳林展开
多元函数 = 0次型 + 1次型 + 2次型 + ... ^rUA7PbRI

存在性证明 ^AblKfkRp

多元函数的变化规律 <- n元n次型的规律 <- 线性变换 / 矩阵 ^wEKiONj1

康托尔的超越数存在性证明
因为 代数数可数 实数不可数
所以 超越数存在 ^5EBKOCh5

二次型 距离公式 ^r62x77Pu

合同变换
合同矩阵 ^myAlnOzj

判别式
Delta = b^2 - 4ac
1. Delta>0 双曲线
2. Delta=0 抛物线
3. Delta<0 椭圆 ^j4FBp6ve

合同变换对曲线曲面进行变换后，Delta不变，称不变量
1. d 转化系数/生成系数 是变化的
2. (b^2 - 4ac) 基础生成元 ^dsyj8kx3

## Embedded Files
b79b96ba6cd0d6467eba0e0f72270383297fb965: $$\begin{align}
f(x, y) &= f(0, 0) + \left( x \frac{\partial f}{\partial x} + y \frac{\partial f}{\partial y} \right)_{(0,0)} \quad \text{微分公式} \\
& + \frac{1}{2!} \left( x^2 \frac{\partial^2 f}{\partial x^2} + 2xy \frac{\partial^2 f}{\partial x \partial y} + y^2 \frac{\partial^2 f}{\partial y^2} \right)_{(0,0)} \quad \text{二次型} \\
& + \frac{1}{3!} \left( x^3 \frac{\partial^3 f}{\partial x^3} + 3x^2y \frac{\partial^3 f}{\partial x^2 \partial y} + 3xy^2 \frac{\partial^3 f}{\partial x \partial y^2} + y^3 \frac{\partial^3 f}{\partial y^3} \right)_{(0,0)} \quad \text{三次型} \\
& + \cdots 
\end{align}$$

5ed7ca3882c17669ac57975031b7f635fe8068ef: $$\begin{align}
& ax^2 + bxy + cy^2 \\

& = \begin{bmatrix} x & y \end{bmatrix}
\begin{bmatrix}
a & \frac{b}{2} \\
\frac{b}{2} & c
\end{bmatrix}
\begin{bmatrix} x \\ y \end{bmatrix} \\

& = v^T \cdot A \cdot v
\end{align}$$

7e9a1b3c2d5fee4930a5d49c7d852e617b3d86c7: $$\begin{align}
x^2 + y^2 
= \begin{bmatrix} x & y \end{bmatrix}
\begin{bmatrix} x \\ y \end{bmatrix} 
\end{align}$$

7ebc48bdf81f883ddeb3dfcc2583d8724e4ab809: $$\begin{align}
& 2x^2 + 3xy + 4y^2 = \begin{bmatrix} x & y \end{bmatrix}
\begin{bmatrix}
2 & \frac{3}{2} \\
\frac{3}{2} & 4
\end{bmatrix}
\begin{bmatrix} x \\ y \end{bmatrix} \\

& = \begin{bmatrix} x & y \end{bmatrix}
\begin{bmatrix}
2x + \frac{3}{2}y & \frac{3}{2}x + 4y
\end{bmatrix}^T \\

& = 2x^2 + \frac{3}{2}xy + \frac{3}{2}xy + 4y^2 
= 2x^2 + 3xy + 4y^2
\end{align}$$

35aeaec9f0b63b82f51404af26bc3aa494224d67: $$\begin{align}
f = x^2 - y^2 
= \begin{bmatrix} x & y \end{bmatrix}
\begin{bmatrix}
1 & 0 \\
0 & -1
\end{bmatrix}
\begin{bmatrix} x \\ y \end{bmatrix} \\

g = x \cdot y 
= \begin{bmatrix} x & y \end{bmatrix}
\begin{bmatrix}
0 & \frac{1}{2} \\
\frac{1}{2} & 0
\end{bmatrix}
\begin{bmatrix} x \\ y \end{bmatrix}
\end{align}$$

46fba9149051a957cf8a7d666313f4c88e8726d0: $$\begin{align}
& A = \begin{bmatrix} 1 & 0 \\ 0 & -1 \end{bmatrix}, 
B = \begin{bmatrix} 0 & \frac{1}{2} \\ \frac{1}{2} & 0 \end{bmatrix}; \quad
P^T \cdot A \cdot P = B \\

& \begin{bmatrix} \frac{1}{2} & \frac{1}{2} \\ \frac{1}{2} & -\frac{1}{2} \end{bmatrix}
\begin{bmatrix} 1 & 0 \\ 0 & -1 \end{bmatrix}
\begin{bmatrix} \frac{1}{2} & \frac{1}{2} \\ \frac{1}{2} & -\frac{1}{2} \end{bmatrix}
= \begin{bmatrix} 0 & \frac{1}{2} \\ \frac{1}{2} & 0 \end{bmatrix} \end{align}$$

fdd82f1a1913425a4c84fa6924c9eb17a1fc93fc: $$\begin{align}
x^2 + y^2 & \quad \text{欧氏空间} \\
x^2 - y^2 & \quad \text{闵氏空间/狭义相对论} \\
xy & \quad \text{广义相对论}
\end{align}$$

f89c794e566358344c690aab6d71541ca47f09a1: $$\begin{align}
\Delta = d (b^2 - 4ac)
\end{align}$$

%%
## Drawing
```compressed-json
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
```
%%