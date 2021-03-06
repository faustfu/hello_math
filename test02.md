# 導數可視為斜率
給定一連續曲線$y = f(x)$，曲線上有P點($x_0$,$y_0$)及Q點($x_1$,$y_1$)，<br/>求$y$的導函數$f'(x)$=?<br/>
平面上二點間斜率$m$<br/>
$$
m=\frac{y_1-y_0}{x_1-x_0}=\frac{\Delta y}{\Delta x}=\frac{\Delta f(x)}{\Delta x}=\frac{\Delta f}{\Delta x}簡寫
$$
若Q無限趨近於P，可取得P點的斜率$m=f'(x_0)$
$$
f'(x_0)=\lim_{\Delta x \to 0}\frac{\Delta f}{\Delta x}
=\lim_{\Delta x \to 0}\frac{f(x_0+\Delta x)-f(x_0)}{\Delta x}
$$
因曲線連續，$x_0$可簡寫為$x$<br/>
$$
f'(x)=\lim_{\Delta x \to 0}\frac{f(x+\Delta x)-f(x)}{\Delta x}
$$
>以上為導函數基本推導公式，但求導函數時有個困難點在於，由於$\Delta x$為分母，在帶入$\Delta x \to 0$之前，必須轉換掉或讓其不影響結果。<br/>

若$y=f(x)=x^n$，導函數$f'(x)=\frac{\partial y}{\partial x}=nx^{n-1}$<br/>

---
# 導數可視為變化率
斜率$m=\frac{\partial y}{\partial x}$<br/>
速度$v=\frac{\partial s}{\partial t}$<br/>
