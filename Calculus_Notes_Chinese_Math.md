

####   取整函数

$$y=[x]$$

其中$[x]$ 表示不超过$x$的最大整数，例如，$[\frac{5}{7}]=0$, $[-0.2]=-1$

##### 求和符号用法

$ \sum_{i=5}^{200} i=5+6+7+...+200$



#### 对数运算法则

| $\alpha^{log_\alpha x}=x$                              |
| ------------------------------------------------------ |
| $e^{lnx}=x$                                            |
| $\log_\alpha b \cdot \log_b \alpha=1 $                 |
| $\log_\alpha m + \log_\alpha n=\log_\alpha(m\cdot n) $ |
| $\log_\alpha m - \log_\alpha n=\log_\alpha(m/n) $      |
| $\log_\alpha({1/m}) =-\log_\alpha m $                  |
| $\log_\alpha b=\frac{\log_c b}{\log_c \alpha}$         |
| $\log_\alpha (m\cdot n) =\log_\alpha m+\log_\alpha n $ |

#### 三角函数

| $sin(A+B)=sinAcosB+cosAsinB$                   | $cos(A+B)=cosAcosB-sinAsinB$                  |
| ---------------------------------------------- | --------------------------------------------- |
| $cosA-cosB=-2sin\frac{A+B}{2}sin\frac{A-B}{2}$ | $cos2A=2cos^2A-1$                             |
| $sinA+sinB=2sin\frac{A+B}{2}cos\frac{A-B}{2}$  | $cosA+cosB=2cos\frac{A+B}{2}cos\frac{A-B}{2}$ |
| $sinA-sinB=2cos\frac{A+B}{2}sin\frac{A-B}{2}$  | $cosA-cosB=2sin\frac{A+B}{2}sin\frac{A-B}{2}$ |
| $secx=\frac{1}{cos}$                           | $tan^2=sec^2-1$                               |
| $cscx=\frac{1}{sinx}$                          | $cosAcosB=\frac{1}{2}[cos(A+B)+cos(A-B)]$     |
| $sinAcosB=\frac{1}{2}[sin(A+B)+sin(A-B)]$      | $sinAsinB=-\frac{1}{2}[cos(A+B)-cos(A-B)]$    |
| $sin(-x)=-sinx$                                | $sin^2x=\frac{1}{2}(1-cos2x)$                 |
|                                                |                                               |
|                                                |                                               |

##### 一些以前学过的公式

| $\frac{k^3-1}{k^3+1}=\frac{(k-1)\cdot(k^2+k+1)}{(k+1)(k^2-k+1)}$ | $a^n-1=(a-1)(a^{n-1}+a^{n-2}+...+a+1)$ |
| ------------------------------------------------------------ | -------------------------------------- |
| $\frac{1}{(x+a)(x-a)}=\frac{1}{2a}\cdot(\frac{1}{x-a}-\frac{1}{x+a})$ | $(x+1)^3=x^3+3x^2+3x+1$                |
| 球的体积： $V=\frac{4}{3}\pi r^3$                            |                                        |
| 等比数列                                                     | $a+ar+ar^2+...+ar^{(n-1)}$             |
| 等比数列的和                                                 | $S=a(\frac{1-r^n}{1-r})$               |
| 立方和公式                                                   | $(a+b)(a^2-ab+b^2)=a^3+b^3$            |
| 立方                                                         | $(x-a)^3=x^3-ax^2+3a^2x-a^3$           |
##### 二项式定理
| $(a+b)^n$ | $=C^0_{n}a^n+C^1_{n}a^{n-1}b+\cdot \cdot \cdot +C^n_{n}b^n $ |
| --------- | ------------------------------------------------------------ |
| $C^r_{n}$ | $=\frac{n!}{(n-r)!(r!)}$                                     |

##### 变量的含义

因变量：dependent variable, 即 y

参变量：parameter variable, 即 r

自变量：independent variable，即x



#### 两个重要极限

| ==$\lim_{x\to0}\frac{sin(x)}{x}=1$==                         |
| :----------------------------------------------------------- |
| $\lim_{x\to0}\frac{tan(x)}{x}=1$                             |
| $\lim_{x\to0}\frac{sin\alpha x}{x}=\alpha$ $(\alpha \not=0)$ |
| $\lim_{x\to0}\frac{1-cosx}{x^2}=\frac{1}{2}$                 |
| $\lim_{x\to0}\frac{sin3x}{sin5x}=\frac{3}{5}$                |
| $\lim_{x\to0}\frac{arctanx}{x}=1$                            |
| ==$\lim_{n\to\infty}(1+\frac{1}{n})^n=e$==                   |
| 变换： $\lim_{？\to\infty}(1+\frac{1}{？})^?=e$ ，注意其中 $?$ 的可替换位置 |



####  无穷小的比较
+ 高阶无穷小：$lim\frac{f(x)}{g(x)}=0$ 则 $f(x)$ 是比 $g(x)$ 高阶的无穷小，计作  $f(x) =o( g(x))$
+ 低阶无穷小：$lim\frac{f(x)}{g(x)}=\infty$ 则 $f(x)$ 是比  $g(x)$ 低阶的无穷小 
+ 同阶无穷小：$lim\frac{f(x)}{g(x)}=c\not=0$，则 $f(x)$ 与 $g(x)$ 同阶，当  $c=1$时， $f(x)$ 与 $g(x)$ 等价无穷小，记做 $f(x)～ g(x)$
| 当$x\to0$时 （注：分子或分母之比可替换，加减不可替换） |
| :----------------------------------------------------- |
| $tanx\sim x$                                           |
| $1-cos \sim \frac{1}{2}x^2$                            |
| $arctanx \sim x$                                       |
| $ln(1+x) \sim x$                                       |
| $e^x-1 \sim x$                                         |
| $\sqrt[n]{1+x}-1\sim \frac{1}{n}x$                     |
| $(1+x)^\alpha -1 \sim \alpha x$ $(\alpha \not=0)$      |



#### 反函数
$y=f(x)$的反函数 $x=f^{-1}(y)$

反函数图像关于 y=x 对称

单调函数的反函数的特别性质：

$f[f^{-1}(x)]=f^{-1}[f(x)]=x$ 

#### 极限四则运算法则
加减乘除都行，除法要保证  $\frac{a}{b}$ 里$b\not=0$.

#### 间断点
第一类间断点：左右极限==都存在==（跳跃间断点、可去间断点）
第二类间断点：左右极限==不存在==（无穷间断点、震荡间断点）

##### 一点可导
函数 $y=f(x)$ 在  $x_0$ 可导的充要条件是在  $x_0$点左右导数存在且相等。

#### 求导数

导数含义

$\lim_{x\to x_0}\frac{f(x)-f(x_0)}{x-x_0}$

*导数几何含义：一笔画且光滑*

1、当 $f(x)=x^2$ 则 $f'(x)=2x$,

2、当 $f(x)=x^n$ 则 $f'(x)=nx^{n-1}$ ，其中 $n$ 取正整数

3、当 $f(x)=c$ 则 $f'(x)=0$

4、对于任意实数 $\alpha$, 有 $(x^\alpha)'=\alpha x^{\alpha-1}$

5、$y=sinx$,则 $(sinx)'=cosx$ ，类似地 $cos(x)'=-sinx$

6、当 $y=\log_\alpha x (\alpha >0,\alpha\not=1)$ ，$(\log_\alpha x)'=\frac{1}{x}(\log_\alpha^e)$，特别地，当$\alpha=e$ 时，有 $(lnx)'=\frac{1}{x}$

当$y=\alpha^x(\alpha>0,\alpha\not =1)$ 有 $(\alpha^x)'=\alpha^xln\alpha$，特别地，当 $\alpha=e$ 时，有 $(e^x)'=e^x$

**基本初等函数的导数公式**

| 函数                                     | 导函数                                                       |
| ---------------------------------------- | ------------------------------------------------------------ |
| $x^n$                                    | $f'(x)=nx^{n-1}$                                             |
| $c$                                      | $f'(x)=0$                                                    |
| $(x^\alpha)$                             | $(x^\alpha)'=\alpha x^{\alpha-1}$                            |
| $sinx$                                   | $(sinx)'=cosx$                                               |
| $cos(x)$                                 | $(cosx)'=-sinx$                                              |
| $\log_\alpha x (\alpha >0,\alpha\not=1)$ | $(\log_\alpha x)'=\frac{1}{x}(\log_\alpha^e)=\frac{1}{xln\alpha}$ |
| $\log_e x$                               | $(lnx)'=\frac{1}{x}$                                         |
| $\alpha^x(\alpha>0,\alpha\not =1)$       | $(\alpha^x)'=\alpha^xln\alpha$                               |
| $e^x$                                    | $(e^x)'=e^x$                                                 |
|                                          | $(tanx)'=sec^2(x)= \frac{1}{cos^2}$                          |
|                                          | $(cotx)'=-csc^2x$                                            |
|                                          | $(secx)'=secx \times tanx$                                   |
|                                          | $(csc)'=-cscx \times cotx$                                   |




#### 求导法则
**1、代数和**

当 $u=u(x)$, $v=v(x)$在 $x$ 点可导，则 $y=u(x)\pm v(x)$ 在$x$可导，且
$$(u(x)\pm v((x))'=u'(x) \pm v'(x)$$

推广到任意==有限个==函数的代数和，有：

$$(u_1(x)\pm u_2(x)\pm...\pm u_n(x))'=u_1'(x) \pm u_2(x)...\pm u_n(x)$$

**2、乘积的导数**
当 $u=u(x)$, $v=v(x)$在 $x$ 点可导，则 $y=u(x)v(x)$ 在$x$可导，且
$$(u(x)v((x))'=u'(x)v(x)+u(x)v'(x)$$
特别地，当 $v(x)=c$ $c$ 为常数，有
$$(cu(x)'=cu'(x)$$
 ——系数、常数求导，==系数直接朝外提==。

积的求导法则可以推广到任意==有限个==函数之积的情形：

$$(u_1u_2u_3...u_n)'=u_1'u_2u_3...u_n+u_1u_2'u_3...u_n+...+u_1u_2u_3...u_n$$

当 $u_1=u_2=u_3=...=u_n=f(x)$时，有

$$(f^n(x))'=nf^{n-1}(x)f'(x)$$ 

注：$f^n(x)$ 表示$f(x)$ 的 $n$ 次方。

**3、商的导数**
当 $u=u(x)$, $v=v(x)$在 $x$ 点可导，且 $v(x)\not=0$ 时，则 $y=\frac{u(x)}{ v(x)}$ 在$x$可导，且

$$(\frac{u(x)}{v(x)})'=\frac{u'(x)v(x)-u(x)v'(x)}{v^2(x)}$$

注意相减顺序：==分子先导，分母后导==，中间减，分母是平方

| 代数和       | $(u(x)\pm v((x))'=u'(x) \pm v'(x)$                           |
| ------------ | :----------------------------------------------------------- |
| 有限个代数和 | $(u_1(x)\pm u_2(x)\pm...\pm u_n(x))'=u_1'(x) \pm u_2(x)...\pm u_n(x)$ |
| 乘积的导数   | $(u(x)v((x))'=u'(x)v(x)+u(x)v'(x)$                           |
|              | $(u(x)v(x)w(x))'=u'(x)v(x)w(x)+u(x)v'(x)w(x)+u(x)v(x)w'(x)$  |
| 商的导数     | $(\frac{u(x)}{v(x)})'=\frac{u'(x)v(x)-u(x)v'(x)}{v^2(x)}$其中$v\not=0$ |
|              |                                                              |

##### 反函数：两个互为反函数的函数，它们的导数互为倒数。

| 反函数        | $[f^{-1}(y)]'=\frac{1}{f'(x)}$ （分母不为 $0$） |
| ------------- | ----------------------------------------------- |
| $(arcsinx)' $ | $\frac{1}{\sqrt{1-x^2}}$ $(-1<x<1)$             |
| $(arccosx)'$  | $-\frac{1}{\sqrt{1-x^2}}$ $(-1<x<1)$            |
| $(arctanx)'$  | $\frac{1}{1+x^2}$  $(-\infty<x<+\infty)$        |
| $(arccotx)'$  | $-\frac{1}{1+x^2}$ $(-\infty<x<+\infty)$        |

##### 复合函数求导

 链式法则：复合函数对自变量的导数，等于复合函数对中间变量的导数乘以中间变量对自变量对导数。

$$\frac{dy}{dx}=\frac{dy}{du} \cdot \frac{du}{dx}$$   

##### 对数求导法- 步骤

+ 某些场合，比如对于幂指函数 $y=[f(x)]^{g(x)}$求导比通常的方法简便些

+ 先将函数 $y=f(x)$两边取自然对数，得到

  $$lny=lbf(x)$$

+ 然后利用隐函数求导法求导，最后代入 $y=f(x)$得到$y'$

##### 高阶导数

| 二阶导数写法 | $f''(x)$   ,$\frac{d^2y}{dx^2}$                       |
| ------------ | ----------------------------------------------------- |
| 三阶导数     | $f'''(x)$,  $\frac{d^3y}{dx^3}$                       |
| 四阶导数     | $y^{(n)},  f^{(n)}(x)   $,$\frac{d^{(n)}y}{dx^{(n)}}$ |

| 初等函数的$n$阶导数                  |
| ------------------------------------ |
| $(e^x)^{(n)}=e^x$                    |
| $(sinx)^{(n)}=sin(x+\frac{n\pi}{2})$ |
| $(cosx)^{(n)}=cos(x+\frac{n\pi}{2})$ |

高阶导数运算法则

| 若 $u=u(x),v=v(x)$都 $n$阶可导，则                           |
| ------------------------------------------------------------ |
| $(u\pm v)^{(n)}=u^{(n)} \pm v^{(n)}$                         |
| $(cu)^{(n)}=cu^{(n)}$ c 为常数                               |
| $(uv)^{(n)}=\sum_{i=0}^n C^i_{n}u^{(n-i)v^{(i)}}$ （其中$u^{(0)}=u, v^{(0)}=v$）是二项式求和 |

由参数方程确定的函数的**高阶导数**，当：
$$
\begin{cases}
 x=\psi(t) \\
y=\phi(t)
\end{cases}
$$
则，$y'=\frac{dy}{dx}=\frac{\phi'(x)}{\psi'(x)}$

$y''=\frac{d(\frac{dy}{dx})}{dx}=y'\cdot \frac{1}{\psi'(x)}$



#### 微分

可微必可导，可导必可微

+ $$\Delta y=A\Delta x +o(\Delta x)$$    
+ $dy=A\Delta x $ 也即 $dy=f'(x)\Delta x $  ，其中 $f'(x)$ 就是函数的导数，而$\Delta y\approx dy$
+ 导数也称为**微商**，即 $\frac{dy}{dx}=f'(x)$

可导：光滑的（函数的可导性与可微性是等价的）

##### 微分公式与运算法则

| $dc=0$ ，c 为常数，d 代表「微分」（diffenrential）    | $dx^\alpha =\alpha x^{\alpha -1}dx$  $ \alpha $为实数 |
| ----------------------------------------------------- | ----------------------------------------------------- |
| $da^x=a^xlnadx$  其中$ (a>0,a \not=0)$                | $de^x=e^xdx$                                          |
| $dlog_a x=\frac{1}{x}log_a edx$ 其中$ (a>0,a \not=0)$ | $dlnx=\frac{1}{x}dx$                                  |
| $dsinx=cosxdx$                                        | $dcosx=-sinxdx$                                       |
| $dtanx=sec^2(x)dx= \frac{1}{cos^2}dx$                 | $dcotx=-csc^2xdx$                                     |
| $dsecx=secxtanxdx$                                    | $dcsc=-cscxcotxdx$                                    |
| $darcsinx=\frac{1}{\sqrt{1-x^2}}dx$                   | $darccosx=-\frac{1}{\sqrt{1-x^2}}dx$                  |
| $darctanx=\frac{1}{1+x^2}dx$                          | $darccotx=-\frac{1}{1+x^2}dx$                         |

**微分的四则运算**

| 设$u(x),v(x)$可导，则                                        |
| ------------------------------------------------------------ |
| $d(u \pm v)=(u'+v')dx=du \pm dv$                             |
| $d(uv)=(u'v+uv')dx=vdu+udv$                                  |
| $d(cu)=cdu$ ，其中c为常数                                    |
| $d(\frac{u}{v})=\frac{u'v-uv'}{v^2}dx=\frac{vdu-udv}{v^2}$ ，注意 $vdu$ 不要写成$duv$ |
| $d(uvw)=vwdu+uvdw+uwdv$                                      |

**近似计算公式**：当$\Delta x$ 取很小时

+ $$f(x_0 + \Delta x) \approx f(x_0)+f'(x_0)\Delta x$$
+ $$f(x) \approx f(x_0)+f'(x_0)(x-x_0)$$
+ 接上式中，$f(x)$在点$x=0$ 附近点的函数值的近似值：$f(x) \approx f(0)+f'(0)x$ （条件是 $|x|$ 很小）

一次近似，其误差是  $|\Delta x|$的高阶无穷小 ，可以说  $|\Delta x|$越小，用 $dy$ 作为 $|\Delta y|$的近似值的近似程度越好

当==$|x|$很小时==，一些常用的近似公式

| $\sqrt[n]{1\pm x} \approx 1\pm \frac{x}{n}$ | $sinx \approx x$           |
| ------------------------------------------- | -------------------------- |
| $tanx \approx x$                            | $e^x \approx 1+x$          |
| $ln(1+x)\approx x$                          | $\frac{1}{1+x}\approx 1-x$ |
| $arcsinx \approx x$                         | $arctanx \approx x$        |

误差估计

+ $y$ 的**绝对**误差约为：$\delta_y=|y'|\delta_x $     ，$\delta_x$为绝对误差的上界值
+ $y$ 的**相对**误差约为：$\frac{\delta_y}{|y|}=|\frac{y'}{y}|\delta_x$ ，用百分比表示

> 做题看来的公式：

  $arcsinx+arxcos= \frac{\pi}{2}(-1\leq x \leq 1)$ 恒成立
#### 中值定理

| 定理 | 罗尔定理                                                     | 拉格朗日定理                                                 | 柯西定理                                                     |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 条件 | 1、在闭区间$[a,b]$上连续，<br/>2、在开区间 $(a,b)$ 上可导，<br/>3、$f(a)=f(b)$，则至少存在一点 $\xi  \in ((a,b))$使得  $f'(\xi )=0$ | 1、在闭区间$[a,b]$上连续，<br/>2、在开区间 $(a,b)$ 上可导<br/> | 1、在闭区间$[a,b]$上连续，<br/>2、在开区间 $(a,b)$ 上可导，且在$(a,b)$ 内每一点有$g'(x) \not= 0 $，则至少存在一点$\xi  \in ((a,b))$ 使得 |
| 公式 |                                                              | $f'(\xi)=\frac{f(a)-f(b)}{a-b}$                              | $\frac{f(a)-f(b)}{g(a)-g(b)}=\frac{f'(\xi)}{g'(\xi )}$       |
| 推论 |                                                              | 1、若$f(x)$在区间$I$上每一点的导数都为0，则$f(x)$在区间$I$上是一个常数，<br/>2、若 2 个函数$f(x),g(x)$ 在区间$I$上每一点的导数都相等，即 $f'(x)=g'(x),x\in I$，则在区间 $I$ 上这 2 个函数最多只相差一个常数，即：$f(x)=g(x)+c$ |                                                              |

**泰勒定理** 

| 若$f(x)$ 在含有  $x_0$ 的开区间 $(a,b)$内具有直到$n+1$阶导数，<br/>则在区间$(a,b)$上，$f(x)$可以表示为==$(x-x_0)$的 n 次多项式与一个余项$R_n(x)$的和==： |
| ------------------------------------------------------------ |
| **泰勒公式**：$f(x)=f(x_0)+f'(x_0)(x-x_0)+ \frac{f''(x_0)}{2!}(x-x_0)^2+...+\frac{f^{(n)}(x_0)}{n!}(x-x_0)^n+R_n(x)$,<br/> $ x\in(a,b), 且 x_0 需要接近 x 真实值 ,其中$<br/> $R_n(x)=\frac{f^{(n+1)}(\xi)}{(n+1)!}(x-x_0)^{(n+1)}$ |
| 误差估计： $|R_n(x)|\leq \frac{M}{(n+1)!}|x-x_0|^{(n+1)}$<br/> 其中 $|f^{(n+1)}(x)|\leq M，M 为常数$ |
| **马克劳林公式**：在泰勒公式中，若$x_0=0，则 \xi 在0 与 x之间。令\xi =\theta x(0<\theta <1) $，则有：<br/> $f(x)=f(0)+f'(0)x+\frac{f''(0)}{2!}x^2+....+\frac{f^{(n)}(0)}{n!}x^n+\frac{f^{(n+1)}(\theta x)}{(n+1)!}$ |
| 马克劳林公式在点 0 附近的近似表达式：<br/> $f(x)\simeq f(0)+f'(0)x+\frac{f''(0)}{2!}x^2+...+\frac{f^{(n)}(0)}{n!}x^n $<br/>误差估计相应地为：<br/> $|R_n(x)|\leq \frac{M}{(n+1)!}|x|^{(n+1)}$ |
|                                                              |

#### 洛必达法则

| 定理                                                         | 公式                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 函数 $f(x),g(x)$ 满足，<br/>1、 $lim_{x\to x_0}f(x)=lim_{x\to x_0}g(x)=0$ <br/>2、在点$x_0$的某邻域内（$x_0$ **可**除外）可导，且$g'(x)\not = 0$<br/>3、 $lim_{x\to x_0}\frac{f'(x)}{g'(x)}=a(或 \infty)$，则—— | $lim_{x\to x_0}\frac{f(x)}{g(x)}=lim_{x\to x_0}\frac{f'(x)}{g'(x)}=a(或 \infty)$ |
| 洛必达法则可以 N 次求导，但==每一步都要关注函数是不是不定式== | $lim_{x\to x_0}\frac{f(x)}{g(x)}=lim_{x\to x_0}\frac{f'(x)}{g'(x)}=lim_{x\to x_0}\frac{f''(x)}{g''(x)}$ |
| 洛必达法则适用于 $\frac{0}{0} \frac{\infty}{\infty}$ <br/> 当$lim\frac{f'(x)}{g'(x)}$ 不存在也不是  $\infty$时，不能断言$lim\frac{f(x)}{g(x)}$不存在 |                                                              |

 **其他类型不定式**

| 其他类型不定式                 | 转化成标准不定式                                     |
| ------------------------------ | ---------------------------------------------------- |
| $\infty \pm \infty$            | 通分                                                 |
| $0 \cdot \infty$               | $lim\frac{f(x)}{\frac{1}{g(x)}}$                     |
| $0^0, 1^{\infty}, \infty ^{0}$ | $limf(x)^{g(x)}=lime^{g(x)lnf(x)}=e^{limg(x)lnf(x)}$ |

一些小知识点

| $lim_{x\to + \infty}\frac{lnx}{x^a}=0 ,(a>0 )$               |
| ------------------------------------------------------------ |
| $lim_{x\to + \infty}\frac{x^n}{e^{\lambda x}}=0 ,(\lambda>0 ,n>0)$ |
|                                                              |

#### 函数单调性

$$单调性=\begin{cases} f'(x)>0：单调增\\ f'(x)<0:单调减 \end{cases}$$

**分界点**=$$\begin{cases} 当导数存在：驻点\\导数不存在 \end{cases}$$

**曲线凹凸性判断**

| 凹凸性 | 设函数$f(x)$在区间$I$内连续，对于任意的$x_1,x_2 \in I $ | 设函数$f(x)$在区间$I$内二阶导数存在 |
| ------ | ------------------------------------------------------- | ----------------------------------- |
| 凹     | $f(\frac{x_1+x_2}{2})<\frac{f(x_1)+f(x_2)}{2}$          | $f''(x)>0$                          |
| 凸     | $f(\frac{x_1+x_2}{2})>\frac{f(x_1)+f(x_2)}{2}$          | $f''(x)<0$                          |

**拐点**：函数经过该点时，改变了凹凸性；经过拐点前后，$f''(x)$符号改变

**拐点**可能是=$$\begin{cases} f''(x)=0 \\二阶导数不存在 \end{cases}$$

#### 函数极值和最值

**1、极值**是邻域内的局部性质，极值不唯一

**极值**=$$\begin{cases} 极大值 (local  maxium)\\极小值 (local  minium) \end{cases}$$

费马定理：若函数$f(x)$在点$x_0$可导，且在点$x_0$出取得极值，则$f'(x_0)=0$

这告诉我们：1、可导函数的极值点必定是驻点，2、驻点不一定是极值点，3、导数不存在点也可能是极值点

综上所述：**极值点一定是驻点或导数不存在点，但驻点、导数不存在点不一定是极值点**

**判断一点是不是极值点**：设函数$f(x)$在点 $x_0$ 的某邻域 $(x_0-\delta,x_0+\delta )$ 内连续，在此邻域内 $(x_0 点可除外)$ 可导，且 $f'(x_0)=0$ 或 $f'(x_0)$不存在 ——

| 判断     | 当$x\in (x_0-\delta ,x_0)$时， | 当$x\in (x_0 ,x_0+\delta )$时， |
| -------- | ------------------------------ | ------------------------------- |
| 极大值   | $f'(x)>0$                      | $f'(x)<0$                       |
| 极小值   | $f'(x)< 0$                     | $f'(x)>0$                       |
| 不是极值 | 不变号                         | 不变号                          |

*简单来说*：左增右减极大值，左减右增极小值

==确定函数$y=f(x)$可能存在的极值点步骤==

+ 确定定义域，求出驻点、导数不存在的点，它们可能是极值点
+ 考察$f'(x)$再可能的极值点左右的符号，确定极值点
+ 求出极值点的函数值

**用二阶导数判断极值**：设函数$f(x)$在点 $x_0$ 处有二阶导数，且$f'(x_0)=0，f''(x_0)\not=0$ 

则有$$\begin{cases} 若f''(x_0)<0，则f(x_0)为极大值 \\若f''(x_0)>0，则f(x_0)为极小值\end{cases}$$

若$f'(x_0)=0 且 f''(x_0)=0$ 时，$f''(x_0)=0$可能是极大也可能是极小也可能不是极值。

**2、最值**有全局性，指$f(x)$在区间上的最大值或最小值

+ 最值唯一，最值点不唯一
+ 若最值在 $(a,b)$ 点内达到，则一定是极值，极值点又只可能是驻点或导数不存在的点
+ 求闭区间$[a,b]$上连续函数的最值，只须计算
  + $[a,b]$ 内的所有驻点、导数不存在点、以及端点 $a,b$处的函数值
  + 加以比较，最大的就是最大值，最小者就是最小值

####  函数作图

曲线的渐近线：水平渐近线、垂直渐近线、斜渐近线

| 渐近线 | 公式                                                         |
| ------ | ------------------------------------------------------------ |
| 水平   | 若$lim_{x\to \infty}f(x)=b，则渐近线为 y=b$                  |
| 垂直   | 若$lim_{x\to c}f(x)=\infty，则渐近线为 x=c$ （一般分母=0，产生间断点） |
| 斜渐进 | 若$lim_{x\to\infty}\frac{f(x)}{x}=a, lim_{x\to \infty}[f(x)-ax] =b,则渐近线为  y=ax+b$ |

==**函数的微分作图法**==

1. 明确定义域、不连续点、与坐标轴相交情况
2. 讨论奇偶性、周期性（ 一般比较少涉及奇偶）
3. 讨论渐近线，确定图形延展到无穷时的形态
4. 求出使得$f'(x)=0 与 f''(x)=0 的点及 f'(x) 与 f''(x) 不存在的点 $ ，列表确定极值、升降、凹凸、拐点
5. 描出曲线上已求得的特殊点，并按（1）（2）（3）（4）得到的信息逐段绘图

####  导数在经济学中的应用

| 概念              | 含义                                                         | 公式                                                         |
| ----------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 边际变化          | 瞬时变化率：边际函数值$f'(x_0)$ 近似等于函数在 $x=x_0$ 处当 x 产生一个单位的改变时，相应的函数改变量。（经济学中解释边际函数值具体意义时略去“近似”） | $$\Delta y|_{x=x_0 , \Delta x=1}  \approx dy|_{x=x_0,x=1}=f'(x)\Delta x|_{x=x_0, x=1} $$ |
| 边际成本          | 当生产水平达到Q个单位前最后增加的那个单位产品（或在Q单位水平上再增加 1 个单位产品）所增加的成本 | $C'(Q)$                                                      |
| 边际收益          | 当销量达到 Q 个单位时，多销售1个单位或少销售 1 个单位产品所增加或减少的收益 | $R'(Q)=P(Q)+QP'(Q)$ ，（其中 P(Q) 是价格变随销量变化函数，Q 是销量） |
| 边际利润          | 生产水平达到 Q 时，再增加 1 单位产品所增加或减少的利润       | $L'(Q)=R'(Q)-C'(Q)$ ，(其中R(Q) 是 收益函数，C(Q)是成本函数) |
| 弹性 （或弧弹性） | 因变量 y 的相对变化与自变量 x 的相对变化之比，称为 y 对 x 的弹性 | $$\frac{\Delta y}{y_0}/\frac{\Delta x}{x_0}$$                |
| 点弹性            | 当自变量在点$x_0$处产生 1% 点改变，y *（近似地）*改变 n%，即函数在一点的弹性反应了 y 对 x 的变化对敏感度 | $$\frac{Ef(x_0)}{Ex}=lim_{\Delta x\to 0}\frac{\Delta y}{\Delta x} \cdot \frac{x_0}{y_0} =f'(x_0)\frac{x_0}{f(x_0)} $$，（简称为弹性函数） |
| 需求的价格弹性    | 商品在价格为 $P_0$ 处的需求量对价格的弹性，即价格变化 1%，需求量将变化 $|\eta|$% | $$\eta =f'(P) \frac{P_0}{f(P_0)} , P 表示价格，f(P)表示需求量与价格的变化函数$$ |
| 收益的价格弹性    | 商品在价格为 $P_0$ 处的收益对价格的弹性，即价格变化 1%，收益将变化的幅度 | $$\eta = R'(P) \cdot \frac{P}{R(P)} , P 表示价格，R(P)表示收益与价格的变化函数$$ |

**基于边际收益的发现**

+ 企业的最优产量是边际收益等于边际成本的产量

**基于需求的价格弹性的发现：**

+ $\eta <-1$ 时：富有弹性，价格变化引起需求量较大变化
+ $\eta =-1$ 时：有单位弹性，价格上升的百分位数与需求下降的百分位数相同
+ $-1<\eta <0$ 时：缺乏弹性，价格变化对需求量影响不大

**提价或降价对总收益的影响：**

设价格对需求量的影响函数为 $Q=f(p)$，总收益函数为 $R=QP=Pf(P)$

又因需求价格弹性为 $\eta = \frac{dQ}{dP} \cdot \frac{P}{Q}$ 于是 $PdQ=\eta QdP$ 

当价格有微小变化 $\Delta P$ 时，总收益改变量：$\Delta R \approx  d(QP)=(1+ \eta )Q \Delta P $

+ 对需求量对价格富有弹性的商品，降价会使总收益增加，提价使总收益减少
+ 对具有单位弹性的商品，提价和降价不影响总收益
+ 对需求对价格缺乏弹性的商品，提价会使总收益增加，降价会使总收益减少

####  极值在经济学中的应用

+ 在平均成本等于边际成本的生产水平处平均成本最小

+ 最大利润原则：

  $设生产 x 单位的产品，总收益 R(x),总成本 C(x),总利润 L(x)= R(x)-C(x)，$

  $按照极值理论，L(x)在 L'(x)=0（即 R'(x)=C'(x)) ，且  L''(x)<0  (即 R''(x)<C''(x) ) 时$==总利润最大==

#### 不定积分

定义：$\int f(x)dx=F(x)+c $ $，F(x)是原函数，f(x)是导函数，c 是积分常数$

**性质描述**：

1、知道了原函数，导函数有无穷多个

2、积分运算与求导运算互逆

3、被积函数中不为 0 的常数因子，可提到积分号外面

4、有限个（不能是无限个）函数和的不定积分，等于各个函数的不定积分加和

**基本积分公式**：

| 求不定积分                     | 结果                      |
| ------------------------------ | ------------------------- |
| $\int x^ndx$                   | $=\frac{1}{n+1}x^{n+1}+c$ |
| $\int 0dx$                     | $=c$                      |
| $\int kdx$                     | $=kx+c$                   |
| $\int \frac{1}{x}dx$           | $=ln|x|+c$                |
| $\int x^adx,(a \neq 0 )$       | $=\frac{1}{a+1}x^{a+1}+c$ |
| $\int a^xdx$                   | $=\frac{1}{lna}a^x+c$     |
| $\int e^xdx$                   | $=e^x+c$                  |
| $\int sinxdx$                  | $=-cosx+c$                |
| $\int cosxdx$                  | $=sinx+c$                 |
| $\int sec^2xdx$                | $=tanx+c$                 |
| $\int csc^2dx$                 | $=-cotx+c$                |
| $\int \frac{dx}{\sqrt{1-x^2}}$ | $=arcsinx+c$              |
| $\int \frac{dx}{ 1+x^2}$       | $=arctanx+c$              |
| $\int secx\cdot tanxdx$        | $=secx+c$                 |
| $\int cscx\cdot cotxdx$        | $=-cscx+c$                |
| $\int tan^2dx$                 | $=tanx-x+c$               |
| $\int e^{-x}dx$                | $-e^{-x}$                 |
|                                |                           |

**积分法**

**第一换元积分法：** 重点是 ==凑==，把 dx 外面的某项拿到 d 里面变成原函数，$d(x+c)里的常数项可以随意加减$

**第二换元积分法：**重点是把dx 里的 x 朝外拿，求x 变成 t 之后的导函数，一般表达式变量带了根号且难以直接积出来

**分部积分法：** $\int udv=uv-\int vdu$ 重点是哪个函数放在 d 后面，然后方便积出来，一般表达式是花样多的变量相✖️

**衍生积分公式**：

| 求不定积分                             | 结果                                                         |
| -------------------------------------- | ------------------------------------------------------------ |
| $\int \frac{dx}{a^2+x^2}$              | $=\frac{1}{a}arctan\frac{x}{a}+c$                            |
| $\int \frac{dx}{\sqrt{a^2-x^2}},(a>0)$ | $=arcsin\frac{x}{a}+c$                                       |
| $\int tanxdx$                          | $=-ln|cosx|+c$                                               |
| $\int cotxdx$                          | $=ln|sinx|+c$                                                |
| $\int cscxdx$                          | $=ln|tan\frac{x}{2}|+c, 或 ln|cscx-cotx|+c$                  |
| $\int secxdx$                          | $=ln|secx+tanx|+c$                                           |
| $\int \sqrt{a^2-x^2}dx,其中(a>0)$      | $=\frac{a^2}{2}arcsin\frac{x}{a}+\frac{x}{2}\sqrt{a^2-x^2}+c$ |
| $\int \frac{1}{x^2-a^2}dx$             | $=\frac{1}{2a}ln|frac{x-a}{x+a}|+c$                          |
| $\int \frac{dx}{\sqrt{x^2\pm a^2}}$    | $=ln|x+\sqrt{x^2\pm a^2}|+c$                                 |
| $\int lnxdx$                           | $=xlnx-x+c$                                                  |
|                                        |                                                              |

$sinx ,cosx $的**第一换元法**技巧：

1、被积函数是$sin^{2n+1}x$时，分出一个因子与 dx 凑微分

2、被积函数是$sin^{2n}x$时，利用倍角公式降幂

3、被积函数是$sinmxcosnx$时，利用积化和差公式变形

**第二换元法**技巧：

1、当被积函数是$\sqrt{a^2+x^2}时，令 x=a\cdot tant 其中(-\frac{\pi}{2}<t<\frac{\pi}{2}) $

2、当被积函数是$\sqrt{x^2-a^2}时，令 x=a\cdot sect，其中(0<t<\frac{\pi}{2}) $ 

**分部积分法**技巧：

u 与 dv 的正确选择是应用的关键，优先顺序依次是：

1、有 $e^x$ 优先把它作为 dv 

2、第二优先级是 $sinx,cosx$

3、第三优先级是 $x^n$

4、第四优先级是$lnx,arctanx$

用分部积分法时，当要求的「东西」又出现了，只要系数非1，都是正常的；当系数为 1，一定是算错了

### 有理函数

有理函数（有理分式）：2 个实系数多项式的商 $\frac{P(x)}{Q(x)}$ （假定分子分母没有公因式）

当分子的最高次小于分母的最高次时，是真分式，否则是假分式

**有理函数求解方法分类**

| 不定积分形式                    | 判别式      | 方法                       |
| ------------------------------- | ----------- | -------------------------- |
| $\int \frac{dx}{ax^2+bx+c}$     | $b^2-4ac<0$ | 配方，代公式               |
| $\int \frac{dx}{ax^2+bx+c}$     | $b^2-4ac=0$ | 凑微分                     |
| $\int \frac{dx}{ax^2+bx+c}$     | $b^2-4ac>0$ | 分解为部分分式，待定系数法 |
| $\int \frac{kx+e}{ax^2+bx+c}dx$ | $b^2-4ac<0$ | 拆开后凑微分               |
| $\int \frac{kx+e}{ax^2+bx+c}dx$ | $b^2-4ac=0$ | 凑微分                     |
| $\int \frac{kx+e}{ax^2+bx+c}dx$ | $b^2-4ac>0$ | 分解为部分分式，待定系数法 |
|                                 |             |                            |

### 定积分

#### 定义

$\int_{a}^{b} f(x)dx=\lim_{\Delta x \to 0}\sum_{i=1}^{n} f(\xi_i)\Delta x_i$

- 其中$f(x)$是被积函数，$f(x)dx$称为被积表达式，x 为积分变量，$[a,b]$为积分区间，a 为积分下限，b 为积分上限。

- 定积分$\int_{a}^{b} f(x)dx$ 是一个数值，仅与被积函数$f(x)$ 和积分区间$[a,b]$有关，与积分变量用什么字母无关

  函数$f(x)$ 在区间$[a,b]$可积的充分条件：

  1、函数$f(x)$ 在区间$[a,b]$上连续

  2、函数$f(x)$ 在区间$[a,b]$上有界且仅有有限个间断点

#### 基本性质

| 1、$\int_{a}^{b} kf(x)dx=k\int_{a}^{b} f(x)dx$ ， (k为常数)  |
| ------------------------------------------------------------ |
| 2、$\int_{a}^{b} (f(x)\pm g(x))dx=\int_{a}^{b} f(x)dx \pm \int_{a}^{b} g(x)dx$ |
| 3、  $\int_{a}^{b} f(x)dx=\int_{a}^{c}f(x)dx+\int_{c}^{b}f(x)dx$ |
| 4、若 $f(x)\leq g(x), x \in [a,b]$ 则，$\int_{a}^{b} f(x)dx \leq \int_{a}^{b} g(x)dx$ |
| 5、若$f(x)=1, x \in [a,b]$ 则，$\int_{a}^{b} f(x)dx =b-a$    |
| 6、**估值定理**：设 M 与 m 为 $f(x)$在区间$[a,b]$上的最大值与最小值，则 $m(b-a)\leq \int_{a}^{b} f(x)dx \leq M(b-a)$ |
| 7、$\left|\int_{a}^{b} f(x)dx \right|\leq \int_{a}^{b} \left|f(x) \right| dx  $ |
| 8、**积分中值定理：** 若函数$f(x)$ 在区间$[a,b]$上连续，则至少存在一点$\xi\in [a,b] $使 $\int_{a}^{b} f(x)dx =f(\xi)(b-a)$ |

####  积分上限函数

##### 定义

$P(x)=\int_{a}^{x} f(t)dt,x \in [a,b] $

- x 在 P(x) 里是变量，在$\int_{a}^{x}$  里 x 是常量 t 是变量（积分值最终与 t 无关）

| 积分上限函数的性质                                           |
| ------------------------------------------------------------ |
| $P'(x)=f(x)$ 区间$[a,b]$上的连续函数一定有原函数，积分上限函数就是它的一个原函数 |
| $\frac{d}{dx} \int^{\phi (x)}_{\psi(x)}f(t)dt=f(\phi (x))\phi '(x)-f(\psi(x))\psi'(x)$ |
| // 积分上限函数上限是 $\phi (x)$，1、直接代入被积函数，2、$\phi '(x)$ ；积分上限函数下限是$\psi(x)$,1、代入$\psi(x)$, 2、$\psi'(x)$,3 、加负号 |

#### 牛顿-莱布尼兹公式（微积分基本公式）

设函数$ f(x)$ 在 区间$[a,b]$上连续，$ F(x)$ 是 $ f(x)$的一个原函数，则

$\int_{a}^{b} f(x)dx=F(b)-F(a)$

$\int_{a}^{b} f(x)dx=F(x)|^{b}_{a}$

牛顿-莱布尼兹公式揭示了**定积分与不定积分**的内在联系，把求定积分的问题化为求$ f(x)$ 的原函数的问题

#### 定积分换元积分法

**定积分换元公式**

设函数数$ f(x)$ 在 区间$[a,b]$上连续，若函数 $x=\phi (x)$满足

- $\phi (x)$在 区间$[a,b]$上单调且有连续导数 $ \phi' (x)$ （为了好代换积分上下限）
- $a \leq x=\phi (x)\leq b ,其中 \phi (\alpha)=a,  \phi (\beta)=b $ 

则，$\int_{a}^{b} f(x)dx= \int_{\alpha}^{\beta} f[ \phi (t)] \phi '(t)dt$

==注意：上下限也变，原变量下限对新变量下限，原变量上限对新变量上限==

**定积分**相关公式

| $\int_{0}^{a} \sqrt{a^2-x^2} dx= \frac{1}{4} \pi a^2(a>0)$   | 表示四分之一个圆形 |
| ------------------------------------------------------------ | ------------------ |
| $\int_{-a}^{a} f(x)dx= 2\int_{0}^{a} f(x)dx $                | f(x)是偶函数       |
| $\int_{-a}^{a} f(x)dx= 0 $                                   | f(x)是奇函数       |
| $\int_{0}^{  \frac{2}{\pi}} sin^n xdx= \int_{0}^{  \frac{2}{\pi}} cos^n xdx，n 是正整数 $ |                    |

#### 定积分分部积分法

设函数$u=u(x),v=v(x)在区间[a,b]上有连续的导函数，则$

$uv'=(uv)'-u'v$ 从而 ==$\int_{a}^{b} udv=(uv)|^{b}_{a}-\int_{a}^{b} vdu $==

#### 定积分的应用

**一、求面积**

| 连续曲线$y=f(x)\geq 0$，直线$x=a,x=b$及$x$轴围城的梯形面积 | $S=\int_{b}^{a}f(x)dx$  |
| ---------------------------------------------------------- | ----------------------- |
| 连续曲线$y=f(x)\leq 0$，直线$x=a,x=b$及$x$轴围城的梯形面积 | $S=-\int_{b}^{a}f(x)dx$ |



1、画图

2、判断是 X 型还是 Y 型（看边缘垂直于哪个轴）

3、x 型：尺子垂直于 X 轴，从最左边开始移动，看上边的函数和下边的函数分别是谁（分区间看）

​      Y型：尺子垂直于Y轴，从上而下看上边和下边的函数分别是谁（分区间看），函数表达式改成 x 是 y 的函数$x=g(y)$

| X 型 | $S=\int_{a}^{b}|f(x)|dx$         |
| ---- | -------------------------------- |
| Y 型 | $S=\int_{c}^{d} |\phi(y)|dy= 0 $ |

**二、求体积**

- 平行截面面积已知的立体：一个立体被垂直于 x 轴的截面所截的面积 A(x) 为 x 的连续函数，$\Delta x$ 是小立方体的高，立体的体积为 

$V=lim_{\Delta x\to 0}\sum A(x)dx=\int_{a}^{b} A(x)dx $

- 旋转体的体积：垂直于x轴的截面面积是圆面， $A(x)=\pi f^2(x)dx$，立体的体积为

$V= \pi \int_{a}^{b} f^2(x)dx $

同理可得，垂直于 y 轴的旋转体体积（==记得把 x 写成 y 的函数==）：

$V= \pi \int_{c}^{d} \phi^2(y)dy $

**三、经济应用问题**

现值法：把不同时间里的货币都换算成现在的价值，

说明：$t 表示时间，P(0)为现值，P(t) 为时间 t 时的货币额，按年利率 r 做连续复利的计算$

| $P(0)在 t 年后的货币额$     | $P(t)=P(0)e^{rt}$  |
| --------------------------- | ------------------ |
| t 年后货币额 $P(t)$的现值为 | $P(0)=P(t)e^{-rt}$ |

***收益流量***

说明：$R_n 表示第 n 年末的收益流量，即投资第 t 年的货币额$

***离散型*** 

| n 年末投资的总收益现值 | $R=\sum_{i=1}^n \frac {R_i}{(1+r)^i}$      |                                      |
| ---------------------- | ------------------------------------------ | ------------------------------------ |
| 均匀收益率时：         | $R=A\cdot  \sum_{i=1}^n \frac{1}{(1+r)^i}$ | $=\frac{A}{r}[1-\frac{1} {(1+r)^n}]$ |

***连续型*** 

| n 年末投资的总收益现值 | $R=\int_{0}^{n}R(t)e^{-rt}dt $  |                             |
| ---------------------- | ------------------------------- | --------------------------- |
| 均匀收益率时：         | $R=A \int_{0}^{n}R(t)e^{-rt}dt$ | $ = \frac{A}{r}(1-e^{-rt})$ |

* 纯收益现值=总收益流量现值-本金现值

### 广义积分

#### 无穷限积分

##### 定义

函数$fa(x)$在区间$[a,+\infty)$上有定义，且对任意实数$b(b>a)$，在[a,b]上可积，称记号$\int_{a}^{+\infty}$为$f(x)$在区间上的**广义积分**

| 三种广义积分       | 表达式                           | 收敛时的极限值                                      |
| ------------------ | -------------------------------- | --------------------------------------------------- |
| 上限无穷广义积分   | $\int_{a}^{+\infty}f(x)dx$       | $lim_{b\to\infty}\int_{a}^{b}f(x)dx$                |
| 下限无穷广义积分   | $\int_{-\infty}^{b}f(x)dx$       | $lim_{a\to-\infty}\int_{a}^{b}f(x)dx$               |
| 上下限无穷广义积分 | $\int_{-\infty}^{+\infty}f(x)dx$ | $\int_{-\infty}^{c}f(x)dx+\int_{c}^{+\infty}f(x)dx$ |

收敛：若极限存在，则称广义积分收敛，并把此极限值称为积分的值

发散：若极限不存在，则称广义积分发散



计算无穷限积分时，也可以采用**牛顿-莱布尼兹公式**的记法：

$F(x)$是 $f(x)$的一个原函数，且$F(+\infty)=lim_{x\to+\infty}F(x)$存在

| 无穷限积分                       | 极限值                  |
| -------------------------------- | ----------------------- |
| $\int_{a}^{+\infty}f(x)dx$       | $F(+\infty)-F(a)$       |
| $\int_{-\infty}^{b}f(x)dx$       | $F(b)-F(-\infty)$       |
| $\int_{-\infty}^{+\infty}f(x)dx$ | $F(+\infty)-F(-\infty)$ |

 

##### 性质

| 性质                                                         | 表达式                                                       | 备注             |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------- |
| 若$\int_{a}^{+\infty}f(x)dx$ 收敛，则$\int_{a}^{+\infty}kf(x)dx$ 也收敛，且>> | $\int_{a}^{+\infty}kf(x)dx=k\int_{a}^{+\infty}f(x)dx$        | $k$为常数        |
| 若$\int_{a}^{+\infty}f(x)dx$ 与$\int_{a}^{+\infty}g(x)dx$都收敛，则$\int_{a}^{+\infty}[f(x)dx \pm g(x)]dx$ 也收敛， 且>> | $\int_{a}^{+\infty}[f(x)dx \pm g(x)]dx=\int_{a}^{+\infty} f(x)dx \pm \int_{a}^{+\infty} g(x)dx$ | 反之，不一定成立 |

##### 收敛判定

**收敛即有界**：设 $f(x) \geq 0$，$\int_{a}^{+\infty}f(x)dx$收敛的充要条件为$P(x)=\int_{a}^{+\infty}f(t)dt$是有界函数

-  （本人推测）如果$f(x)<0$时会收敛，但不一定原函数有界，or 原函数有界但广义积分不一定收敛

**比较判别法**：设$0 \leq f(x) \leq g(x)$，则有

- 当$\int_{a}^{+\infty}g(x)dx$收敛时，$\int_{a}^{+\infty}f(x)dx$收敛
- 当$\int_{a}^{+\infty}f(x)dx$发散时，$\int_{a}^{+\infty}g(x)dx$发散

- 注：这个条件一定要有，不然$f(x)$有可能趋于负无穷

**绝对收敛 & 条件收敛：**设$\int_{a}^{+\infty}f(x)dx$收敛，如果：

| $\int_{a}^{+\infty}|f(x)|dx$收敛，则                     | 绝对收敛 |
| -------------------------------------------------------- | -------- |
| $\int_{a}^{+\infty}|f(x)|dx$发散（也就是正负相抵了），则 | 条件收敛 |

**绝对收敛必收敛**：绝对收敛的无穷限积分必收敛



#### 瑕积分（improper integral）

**定义**：设$f(x)$函数$[a,b)$在区间的任一闭子区间上可积，且$lim_{x\to b^-}f(x)= \infty$ ，称记号$\int_{a}^{b}f(x)dx$ 为函数$f(x)$在$[a,b)$上的==广义积分==，

取$\varepsilon >0$，若极限$lim_{\varepsilon\to 0^+}\int_{a}^{b-\varepsilon}f(x)dx $ 存在，则称广义积分$\int_{a}^{b}f(x)dx$ **收敛**，并把此极限值称为广义积分$\int_{a}^{b}f(x)dx$ 的值，即有$\int_{a}^{b}f(x)dx=lim_{\varepsilon\to 0^+}\int_{a}^{b-\varepsilon}f(x)dx $，

若极限不存在，则称广义积分**发散**。

**瑕点**：如果函数$f(x)$在点$a$上趋于无穷，则$a$是$f(x)$的瑕点。

**3 种无界函数的广义积分（瑕积分）**

| 区间               | 瑕点 | 广义积分的值                                             |
| ------------------ | ---- | -------------------------------------------------------- |
| $[a,b)$            | b    | $lim_{\varepsilon\to 0^+}\int_{a}^{b-\varepsilon}f(x)dx$ |
| $(a,b]$            | a    | $lim_{\varepsilon\to 0^+}\int_{a+\varepsilon}^{b}f(x)dx$ |
| $[a,b] 上除了点 c$ | c    | $\int_{a}^{c}f(x)dx + \int_{c}^{b}f(x)dx$                |

**需要注意**：瑕积分与定积分在记号形式上是相同的，在计算中需要区分。

- 先判断是否有瑕点
- 再判断是瑕积分，还是定积分，还是无穷限积分



小知识点：

判断$\int_{0}^{1} \frac{1}{x^p}dx,(p>0)$敛散性

| $0<p \leq 1$ | $\frac{1}{1-p}$ |
| ------------ | --------------- |
| $p \geq 1 $  | 发散            |

判断$\int_{1}^{+\infty} \frac{1}{x^p}dx$敛散性

| $p>1$      | $\frac{1}{p-1}$ |
| ---------- | --------------- |
| $p \leq 1$ | 发散            |

#### $\Gamma$函数和 $\beta$ 函数

##### 广义积分 $\Gamma$函数：是参变量$r$ 的函数，即：

$\Gamma (r)=\int_{0}^{+\infty}x^{r-1}e^{-x}dx (r>0) $ 

当 r>0  时，$\Gamma$函数是收敛的，

$\Gamma$函数性质：

| $\Gamma(r+1)=r\Gamma(r)(r>0)$ |
| ----------------------------- |
| $\Gamma(n+1)=n!(n为整数)$     |

$\Gamma$函数特点：

- 0 到正无穷
- e 的-x次方
- x 的n次方

##### $\beta$ 函数：是参变量 p，q 的二元函数

$\beta(p,q)=\int_{0}^{1}x^{p-1}(1-x)^{p-1}dx (p>0,q>0)$

当 p>0,q>0  时，$\beta$函数是收敛的，

$\beta$函数性质：

| $ \beta(p,q)=\beta(q,p) $                            |
| ---------------------------------------------------- |
| $\beta(p+1,q+1)=\frac{q}{p+q+1}\beta(p+1,q)$         |
| $\beta (p,q)=\frac{\Gamma(p)\Gamma(q)}{\Gamma(p+q)}$ |

==定积分做题技巧：==

- 判断是否无穷限积分：看上下限
- 判断是否瑕积分：瑕点
- 判断积分区间是否关于原点对称：奇函数可以消掉
- 普通定积分：换元积分、分部积分

#### 多元函数微积分（Multivariable calculus）

##### 空间解析几何（Space Analytic Geometry）

**空间直角坐标系**：

| 右手系规定 | 拇指向上为 oz 的正方向，其余四指先通过 x轴再通过 y 轴 |
| ---------- | ----------------------------------------------------- |
| 坐标轴     | x轴 y轴 z轴                                           |
| 坐标平面   | xoy平面 yoz 平面 xoz平面                              |
| 卦限       | 三个坐标轴把空间分成 8 个卦限                         |
| 坐标       | $M(a,b,c)$ 对应（x轴，y轴，z轴）                      |

 **空间两点间距离**

空间两点 $M_1(x_1,y_1,z_1),M_2(x_1,y_2,z_2)$之间的距离：

$|M_1M_2|=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2} $

点$M(x,y,z)$与坐标原点$O(0,0,0)$的距离公式为

$|OM|=\sqrt{x^2+ y ^2+ z ^2} $



**曲面方程**（equation for a surface ）

**定义**：若曲面上 S 任意一点的坐标满足方程$F(x,y,z)=0,$而不在曲面s上的点的坐标都不满足方程$F(x,y,z)=0$，则方程$F(x,y,z)=0$称为曲面的方程，而曲面称为方程的图形

| 空间任意一个==平面==的方程为三元一次方程 | $Ax+By+Cx+D=0$, 其中$A,B,C,D$均为常数且不全为0 |
| ---------------------------------------- | ---------------------------------------------- |
| $xOz$ 平面方程                           | $y=0,(x,0,z)$                                  |
| $yOz$平面方程                            | $x=0,(0,y,z)$                                  |
| $xOy$平面方程                            | $z=0,(x,y,0)$                                  |

 **球形**：球心为原点$O(0,0,0)$时，半径为 R 的球面方程

| 球面   | $x^2+y^2+z^2=R^2$        |
| ------ | ------------------------ |
| 上半部 | $z=\sqrt{R^2-x^2+ y^2}$  |
| 下半部 | $z=-\sqrt{R^2-x^2+ y^2}$ |

**圆柱面**：

| 圆心在原点O，半径为 R | $x^2+y^2=R^2$         |
| --------------------- | --------------------- |
| 准线                  | $xOy$面上的圆         |
| 母线                  | 平行于 z 轴的直线 $l$ |

**旋转抛物面**：（paraboloid of revolution）：

$z=x^2+y^2$

**双曲抛物面（也叫“鞍面”）**（hyperbolic paraboloid）：

$z=y^2-x^2$



#### 多元函数的基本概念（Multivariable calculus）

##### 邻域与平面区域

| 概念                                | 含义                                                         | 表达公式                                                     |
| ----------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 邻域（Neighbourhood）               | 以$P_0(x_0,y_0)$点为圆心，以$\delta$为半径的圆的内部点$P(x,y)$的全体（不包括边缘） | $U(P_0,\delta)=\{(x,y)|\sqrt{(x-x_0)^2+(y-y_0)^2}<\delta\}$  |
| 去心邻域（punctured neighbourhood） | $U(P_0,\delta)$中除去点$P_0(x_0,y_0)$后所剩部分              | $\mathring{U}(P_0,\delta)=\{ (x,y)|0<\sqrt{(x-x_0)^2+(y-y_0)^2}<\delta\}$ |
| 内点                                | 在点集里面的点                                               |                                                              |
| 边界点                              | 在点集边界的点                                               |                                                              |
| 开集                                | 点集的点都是内点，不包含边界                                 | 例如 $E=\{(x,y)|1< x^2+y^2 < 4 \}$                           |
| 闭集/闭区域                         | 开区域（内部各点都连通的开集）包含边界一起                   | 例如 $E=\{(x,y)|1\leq x^2+y^2 \leq 4 \}$                     |
| 无界点集                            | 点集无限延伸                                                 |                                                              |
| 有界点集                            | （点集有边界）点集 E 内一切点与其中一定点的距离都有小于某个值 |                                                              |

##### 二元函数( *function* of two variables)

$z$由$x,y$两个自变量取值决定，记作 $z=f(x,y)$

| 概念       | 含义                     | 表达式                         |
| ---------- | ------------------------ | ------------------------------ |
| 函数定义域 | $x,y$的取值范围          | $D_f$                          |
| 值域       | 全体函数值的集合         | $R_f$                          |
| 函数值     | 因变量$z$的值            | $f(x_0,y_0),z|_{x=x_0 y=y_0 }$ |
| 二元函数   | 空间中的曲面（几何含义） |                                |

 ##### 二元函数的极限

对于$z=f(x,y)$二元函数，如果在点 $P(x,y)$趋于点$P_0(x_0,y_0)$的过程中，其函数值$f(x,y)$无限地接近一个确定的常数$a$，我们就称常数$a$是函数$z=f(x,y)$当$(x,y) \to (x_0,y_0)$ 时的极限，二元函数的极限也叫==二重极限==

$lim_{x \to x_0 ~\\ y\to y_0}f(x,y)=a$

1、点$P(x,y)$以任何方式趋于点$P_0(x_0,y_0)$时，都趋于 $a$

2、极限不存在的判断：

- 不同方式趋于点$P_0(x_0,y_0)$，值不同
- 某种方式趋于点$P_0(x_0,y_0)$，没有极限

##### 二元函数的连续性

二元函数连续的几何意义：**曲面不断开**；

函数在点处连续，需满足三个条件：

1、函数$f(x,y)$在点$(x_0,y_0)$处有定义

2、$lim_{x \to x_0,y \to y_0}f(x,y)$存在

3、$lim_{x \to x_0,y \to y_0}f(x,y)=f(x_0,y_0)$



**二元函数的性质**

| 二元连续函数的和、差、积，仍为连续函数                       |
| ------------------------------------------------------------ |
| 分母不为零处，二元函数的商是连续函数                         |
| 二元连续函数的复合函数也是连续函数                           |
| **有界性：** 若$f(x,y)$函数在有界闭区域$D$上连续，则$f(x,y)$在$D$上有界 |
| **最值性**：若函数$f(x,y)$在有界闭区域上连续，则$f(x,y)$在$D$上取得最大值和最小值 |
| **介值性**：若函数$f(x,y)$在有界闭区域$D$上连续，$m$和$M$分别为函数$f(x,y)$在$D$上的最大值和最小值，则对介于$m$和$M$之间的任一实数$c$，至少存在一点$(x_0,y_0) \in D$使$f(x_0,y_0)=c$ |

