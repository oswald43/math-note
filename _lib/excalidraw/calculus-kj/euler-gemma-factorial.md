---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠== You can decompress Drawing data with the command palette: 'Decompress current Excalidraw file'. For more info check in plugin settings under 'Saving'


# Excalidraw Data

## Text Elements
无穷积 ^YHQmRpOB

阶乘计算 ^9lEcgPN9

a+b为基
计算其阶乘 ^CNDSQ6Fq

二项式定理
(牛顿微积分起点) ^WkWj0jXZ

a+b为基
计算其n次方 ^U9o2aE9V

无穷大的阶乘 ^LWdb7fIF

沃里斯乘积 ^L1tiqtsy

代入值 ^tztAAHDh

阶乘运算的无穷积形式 ^0cw6v65U

Gemma函数的无穷积形式

Gemma函数的积分形式 ^Vi9Q3DhF

联立两式 ^fikRAgvG

沃里斯乘积 ^npfsfLwW

阶乘计算的解析函数
Gemma函数 ^DcwL3J35

## Embedded Files
8488b91688e8fff5e58fb1b5e2e504bbb49d3c84: $$\begin{align}
5! &= 5\times4\times3\times2\times1 = 120 \\
(-4)! &= Undefine \\
(\frac{1}{2})! &= \Gamma(\frac{1}{2}+1) = \frac{1}{2}\Gamma(\frac{1}{2}) = \frac{\sqrt{\pi}}{2} \\
(\frac{1}{3})! &= \Gamma(\frac{1}{3}+1) = \frac{1}{3}\Gamma(\frac{1}{3}) \approx 0.8929795115692 \\
(1 + 3i)! &= \Gamma(2 + 3i)=(1 + 3i)\Gamma(1 + 3i) \\
\lim_{m \to \infty} m! &=1\cdot2\cdot3\cdot4\cdot5\cdots \\
\end{align}$$

0c67f764ccaa49645b3f67bb147cd4cd78e8f268: $$(a+b)^n = 
\binom{n}{0}a^{n}b^{0}+\binom{n}{1}a^{n - 1}b^{1}+\binom{n}{2}a^{n - 2}b^{2}+\cdots+\binom{n}{n}a^{0}b^{n}$$

aac093a549135b10517171422d4a52d932216cf0: $$(a+b)!$$

f1e1b4d176774ac9956f6130b457c7ca5a45fd98: $$\begin{align*}
(n + m)! &= n! \cdot (n + 1)(n + 2)\cdots(n + m) \quad \text{(1)} \\
(m + n)! &= m! \cdot (m + 1)(m + 2)\cdots(m + n) \quad \text{(2)} \\
\end{align*}$$

602239e523418146a5aa393871ddd86d5c76227b: $$\begin{align*}
n! \cdot (n + 1)(n + 2)\cdots(n + m) &= m! \cdot (m + 1)(m + 2)\cdots(m + n) \\
n! &= \frac{m! \cdot (m + 1)(m + 2)\cdots(m + n)}{(n + 1)(n + 2)\cdots(n + m)} \\
&= \lim\limits_{m \to \infty} \frac{m! \cdot m^n}{(n + 1)(n + 2)\cdots(n + m)} \\
&= \Gamma(n+1) \\
\end{align*}$$

673b5316bf14d742dcef723b30c326783115c6a1: $$\Gamma(n+1)=\int_{0}^{\infty}t^{n}e^{-t}dt$$

8644c174f9388f3c45cfdcc7f9d72ce0191ed193: $$\Gamma(n+1) =
\lim\limits_{m \to \infty} \frac{m! \cdot m^n}{(n + 1)(n + 2)\cdots(n + m)}$$

e28a587b0540ac50a60dcdc5bb60f166fdc1d010: $$n = \frac{1}{2}$$

b4f2c293f0ed89bc29dbb818d093d3dc61acb306: $$\begin{align}
\frac{\pi}{2} &= \frac{2}{1}\cdot\frac{2}{3}\cdot\frac{4}{3}\cdot\frac{4}{5}\cdot\frac{6}{5}\cdot\frac{6}{7} \cdots \\
\frac{\pi}{2} &= \frac{2 \cdot 2 \cdot 4 \cdot 4 \cdot 6 \cdot 6}{1 \cdot 3 \cdot 3 \cdot 5 \cdot 5 \cdot 7} \cdots \\
\frac{\pi}{2} &= \frac{\lim\limits_{m \to \infty} 2^m \cdot (1 \cdot 2 \cdot 3 \cdots) \cdot 2^m \cdot (1 \cdot 2 \cdot 3 \cdots)}{1 \cdot 3 \cdot 3 \cdot 5 \cdot 5 \cdot 7 \cdots}  \\
\frac{\pi}{2} &= \frac{\lim\limits_{m \to \infty} 2^{2m} \cdot (m!)^2 }{1 \cdot 3 \cdot 3 \cdot 5 \cdot 5 \cdot 7 \cdots}  \\
\end{align}$$

0a9b7d0d88a393aabee8126b22bee36e62e3e982: $$\begin{align*}
\frac{\pi}{2} &= \lim\limits_{m \to \infty} 
\frac{2}{1}\cdot\frac{2}{3}\cdot\frac{4}{3}\cdot\frac{4}{5}\cdot\frac{6}{5}\cdot\frac{6}{7} \cdots \cdot\frac{2m}{2m-1} \cdot\frac{2m}{2m+1} \\

\frac{\pi}{2} &= \lim\limits_{m \to \infty} \frac{2^{2m} \cdot (m!)^2 }{3^2 \cdot 5^2 \cdot 7^2 \cdots (2m-1)^2 (2m+1)}  \\
\end{align*}$$

5989054fe63e992871c3481a22c137a0e7e03407: $$\begin{align*}
(\frac{1}{2})! &= \lim\limits_{m \to \infty} \frac{m! \cdot m^{\frac{1}{2}}}{(\frac{1}{2} + 1)(\frac{1}{2} + 2)\cdots(\frac{1}{2} + m)}\\
&=\lim\limits_{m \to \infty} \frac{m! \cdot m^{\frac{1}{2}}}{\frac{3}{2}\cdot\frac{5}{2}\cdots\frac{2m + 1}{2}}\\
&=\lim\limits_{m \to \infty} \frac{2^m\cdot m! \cdot m^{\frac{1}{2}}}{3\cdot5\cdots(2m + 1)} \\

[(\frac{1}{2})!]^2
&=\lim\limits_{m \to \infty} \frac{2^{2m}\cdot (m!)^2 \cdot m}{3^2 \cdot 5^2 \cdots (2m+1)^2} \\
&=\lim\limits_{m \to \infty} \frac{2^{2m}\cdot (m!)^2 }{3^2 \cdot 5^2 \cdots (2m+1)}
\cdot \lim\limits_{m \to \infty} \frac{m}{(2m+1)} \\
&= \frac{\pi}{2} \cdot \frac{1}{2} = \frac{\pi}{4} \\

(\frac{1}{2})! &= \frac{\sqrt{\pi}}{2} \\
\end{align*}$$

%%
## Drawing
```compressed-json
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=
```
%%