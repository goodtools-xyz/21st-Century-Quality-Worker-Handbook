# LaTeX 数学公式参考

## 参考来源

- [ProcessOn LaTeX 符号参考](https://www.processon.com/latex-symbol)
- [KaTeX 支持的 LaTeX 命令](https://katex.org/docs/supported)
https://www.mathjax.org/


### 一、函数、符号及特殊字符
#### 1. 声调/变音符号
| 效果           | 语法           |
|----------------|----------------|
| $\dot{a}$      | `\dot{a}`      |
| $\ddot{a}$     | `\ddot{a}`     |
| $\acute{a}$    | `\acute{a}`    |
| $\grave{a}$    | `\grave{a}`    |
| $\check{a}$    | `\check{a}`    |
| $\breve{a}$    | `\breve{a}`    |
| $\tilde{a}$    | `\tilde{a}`    |
| $\bar{a}$      | `\bar{a}`      |
| $\hat{a}$      | `\hat{a}`      |
| $\widehat{abc}$| `\widehat{abc}`|
| $\vec{a}$      | `\vec{a}`      |
| $\overrightarrow{AB}$ | `\overrightarrow{AB}` |
| $\widetilde{ac}$| `\widetilde{ac}`|
| $\utilde{AB}$  | `\utilde{AB}`  |
| $\widecheck{ac}$| `\widecheck{ac}`|
| $\mathring{g}$ | `\mathring{g}` |
| $\underline{X}$| `\underline{X}`|

#### 2. 标准函数


| LaTeX语法                | 符号效果                |
|--------------------------|-------------------------|
| `\exp_a b = a^b`         | $\exp_a b = a^b$        |
| `\exp b = e^b`           | $\exp b = e^b$          |
| `10^m`                   | $10^m$                  |
| `\ln c`                  | $\ln c$                 |
| `\lg d = \log_{10} d`    | $\lg d = \log_{10} d$   |
| `\log_{10} f`            | $\log_{10} f$           |
| `\sin a`                 | $\sin a$                |
| `\cos b`                 | $\cos b$                |
| `\tan c`                 | $\tan c$                |
| `\cot d`                 | $\cot d$                |
| `\sec e`                 | $\sec e$                |
| `\csc f`                 | $\csc f$                |
| `\arcsin a`              | $\arcsin a$             |
| `\arccos b`              | $\arccos b$             |
| `\arctan c`              | $\arctan c$             |
| `\operatorname{arccot} d`| $\operatorname{arccot} d$|
| `\arcsec e`              | $\arcsec e$             |
| `\arccsc f`              | $\arccsc f$             |
| `\sinh a`                | $\sinh a$               |
| `\cosh b`                | $\cosh b$               |
| `\tanh c`                | $\tanh c$               |
| `\coth d`                | $\coth d$               |
| `\cosec`                 | $\cosec$                |
| `\arctg`                 | $\arctg$                |
| `\cotg`                  | $\cotg$                 |
| `\arcctg`                | $\arcctg$               |
| `\ctg`                   | $\ctg$                  |
| `\cth`                   | $\cth$                  |
| `\operatorname{sh}k`     | $\operatorname{sh}k$    |
| `\operatorname{ch}l`     | $\operatorname{ch}l$    |
| `\operatorname{th}m`     | $\operatorname{th}m$    |
| `\operatorname{coth}n`   | $\operatorname{coth}n$  |
| `\operatorname{argsh}o`  | $\operatorname{argsh}o$ |
| `\operatorname{argch}p`  | $\operatorname{argch}p$ |
| `\operatorname{argth}q`  | $\operatorname{argth}q$ |
| `\operatorname{sgn}r`    | $\operatorname{sgn}r$   |
| `\left\vert s \right\vert` | $\left\vert s \right\vert$ |
| `\min(x,y)`              | $\min(x,y)$             |
| `\max(x,y)`              | $\max(x,y)$             |
| `\operatorname{f}`       | $\operatorname{f}$      |
| `\operatorname*{f}`      | $\operatorname*{f}$     |

#### 3. 极限


| LaTeX语法       | 符号效果       |
|-----------------|----------------|
| `\min x`        | $\min x$       |
| `\max y`        | $\max y$       |
| `\inf s`        | $\inf s$       |
| `\sup t`        | $\sup t$       |
| `\lim u`        | $\lim u$       |
| `\liminf v`     | $\liminf v$    |
| `\limsup w`     | $\limsup w$    |
| `\dim p`        | $\dim p$       |
| `\deg q`        | $\deg q$       |
| `\det m`        | $\det m$       |
| `\ker\phi`      | $\ker \phi$    |
| `\arg\max`      | $\arg \max$    |
| `\injlim`       | $\injlim$      |
| `\varinjlim`    | $\varinjlim$   |
| `\arg\min`      | $\arg \min$    |
| `\plim`         | $\plim$        |
| `\varliminf`    | $\varliminf$   |
| `\varlimsup`    | $\varlimsup$   |
| `\projlim`      | $\projlim$     |
| `\varprojlim`   | $\varprojlim$  |

#### 3. 投射

| LaTeX语法                | 符号效果                |
|--------------------------|-------------------------|
| `\Pr j`                  | $\Pr j$                 |
| `\hom l`                 | $\hom l$                |
| `\lVert z \rVert`        | $\lVert z \rVert$       |
| `\arg z`                 | $\arg z$                |

#### 4.微分及导数

| LaTeX语法                                  | 符号效果                  |
|--------------------------------------------|---------------------------|
| `dt`                                       | $dt$                      |
| `\mathrm{d}t`                              | $\mathrm{d}t$             |
| `\partial t`                               | $\partial t$              |
| `\nabla\psi`                               | $\nabla\psi$              |
| `dy/dx`                                    | $dy/dx$                   |
| `\mathrm{d}y/\mathrm{d}x`                  | $\mathrm{d}y/\mathrm{d}x$ |
| `\frac{dy}{dx}`                            | $\frac{dy}{dx}$           |
| `\frac{\mathrm{d}y}{\mathrm{d}x}`          | $\frac{\mathrm{d}y}{\mathrm{d}x}$ |
| `\frac{\partial^2}{\partial x_1\partial x_2}y` | $\frac{\partial^2}{\partial x_1\partial x_2}y$ |
| `\prime`                                   | $\prime$                  |
| `\backprime`                               | $\backprime$              |
| `f^\prime`                                 | $f^\prime$                |
| `f'`                                       | $f'$                      |
| `f''`                                      | $f''$                     |
| `f^{(3)}`                                  | $f^{(3)}$                 |
| `\dot y`                                   | $\dot y$                  |
| `\ddot y`                                  | $\ddot y$                 |

#### 5.类字母符号及常数

| LaTeX语法       | 符号效果       |
|-----------------|----------------|
| `\infty`        | $\infty$       |
| `\aleph`        | $\aleph$       |
| `\complement`   | $\complement$  |
| `\backepsilon`  | $\backepsilon$ |
| `\eth`          | $\eth$         |
| `\Finv`         | $\Finv$        |
| `\hbar`         | $\hbar$        |
| `\Im`           | $\Im$          |
| `\imath`        | $\imath$       |
| `\jmath`        | $\jmath$       |
| `\Bbbk`         | $\Bbbk$        |
| `\ell`          | $\ell$         |
| `\mho`          | $\mho$         |
| `\wp`           | $\wp$          |
| `\Re`           | $\Re$          |
| `\circledS`     | $\circledS$    |
| `\S`            | $\S$           |
| `\P`            | $\P$           |
| `\Reals`        | $\Reals$       |
| `\text{ØE}`     | $\text{ØE}$    |
| `\image`        | $\image$       |
| `\text{\o}`     | $\text{\o}$    |
| `\weierp`       | $\weierp$      |
| `\text{\O}`     | $\text{\O}$    |
| `\alefsym`      | $\alefsym$     |
| `\cnums`        | $\cnums$       |
| `\text{\aa}`    | $\text{\aa}$   |
| `\text{\i}`     | $\text{\i}$    |
| `\Complex`      | $\Complex$     |
| `\text{\AA}`    | $\text{\AA}$   |
| `\text{\j}`     | $\text{\j}$    |
| `\text{\ae}`    | $\text{\ae}$   |
| `\real`         | $\real$        |
| `\text{\AE}`    | $\text{\AE}$   |
| `\hslash`       | $\hslash$      |
| `\text{\oe}`    | $\text{\oe}$   |


#### 6.模算数

| LaTeX语法                      | 符号效果              |
|--------------------------------|-----------------------|
| `s_k \equiv 0 \pmod{m}`        | $s_k \equiv 0 \pmod{m}$|
| `a \bmod b`                    | $a \bmod b$           |
| `\gcd(m, n)`                   | $\gcd(m,n)$           |
| `\operatorname{lcm}(m, n)`     | $\operatorname{lcm}(m,n)$ |
| `\mid`                         | $\mid$                |
| `\nmid`                        | $\nmid$               |
| `\shortmid`                    | $\shortmid$           |
| `\nshortmid`                   | $\nshortmid$          |


#### 7.根号

| LaTeX语法                  | 符号效果                  |
|----------------------------|---------------------------|
| `\surd`                    | $\surd$                   |
| `\sqrt{2}`                 | $\sqrt{2}$                |
| `\sqrt[n]{}`               | $\sqrt[n]{}$              |
| `\sqrt[3]{\frac{x^3+y^3}{2}}` | $\sqrt[3]{\frac{x^3+y^3}{2}}$ |


#### 8.运算符

| LaTeX语法          | 符号效果          |
|--------------------|-------------------|
| `+`                | $+$               |
| `\pm`              | $\pm$             |
| `\mp`              | $\mp$             |
| `\dotplus`         | $\dotplus$        |
| `\times`           | $\times$          |
| `\div`             | $\div$            |
| `\divideontimes`   | $\divideontimes$  |
| `/`                | $/$               |
| `\backslash`       | $\backslash$      |
| `\cdot`            | $\cdot$           |
| `* \ast`           | $* \ast$          |
| `\star`            | $\star$           |
| `\circ`            | $\circ$           |
| `\bullet`          | $\bullet$         |
| `\boxplus`         | $\boxplus$        |
| `\boxminus`        | $\boxminus$       |
| `\boxtimes`        | $\boxtimes$       |
| `\boxdot`          | $\boxdot$         |
| `\oplus`           | $\oplus$          |
| `\ominus`          | $\ominus$         |
| `\otimes`          | $\otimes$         |
| `\oslash`          | $\oslash$         |
| `\odot`            | $\odot$           |
| `\circleddash`     | $\circleddash$    |
| `\circledcirc`     | $\circledcirc$    |
| `\circleddast`     | $\circleddast$    |
| `\biguplus`        | $\biguplus$       |
| `\bigotimes`       | $\bigotimes$      |
| `\bigodot`         | $\bigodot$        |
| `\vdotp`           | $\vdotp$          |
| `\rhd`             | $\rhd$            |
| `\ldotp`           | $\ldotp$          |
| `\unlhd`           | $\unlhd$          |
| `\unrhd`           | $\unrhd$          |
| `\doublecap`       | $\doublecap$      |
| `\doublecup`       | $\doublecup$      |
| `\pm \text{or} \plusmn` | $\pm \text{or} \plusmn$ |

#### 9.运算符

| LaTeX语法          | 符号效果          |
|--------------------|-------------------|
| `\{ \}`            | $\{ \}$           |
| `\emptyset`        | $\emptyset$       |
| `\varnothing`      | $\varnothing$     |
| `\in`              | $\in$             |
| `\notin`           | $\notin$          |
| `\ni`              | $\ni$             |
| `\not\ni`          | $\not\ni$         |
| `\cap`             | $\cap$            |
| `\Cap`             | $\Cap$            |
| `\sqcap`           | $\sqcap$          |
| `\bigcap`          | $\bigcap$         |
| `\cup`             | $\cup$            |
| `\Cup`             | $\Cup$            |
| `\sqcup`           | $\sqcup$          |
| `\bigcup`          | $\bigcup$         |
| `\bigsqcup`        | $\bigsqcup$       |
| `\uplus`           | $\uplus$          |
| `\biguplus`        | $\biguplus$       |
| `\setminus`        | $\setminus$       |
| `\smallsetminus`   | $\smallsetminus$  |
| `\times`           | $\times$          |
| `\subset`          | $\subset$         |
| `\Subset`          | $\Subset$         |
| `\sqsubset`        | $\sqsubset$       |
| `\supset`          | $\supset$         |
| `\Supset`          | $\Supset$         |
| `\sqsupset`        | $\sqsupset$       |
| `\subseteq`        | $\subseteq$       |
| `\nsubseteq`       | $\nsubseteq$      |
| `\subsetneq`       | $\subsetneq$      |
| `\varsubsetneq`    | $\varsubsetneq$   |
| `\sqsubseteq`      | $\sqsubseteq$     |
| `\supseteq`        | $\supseteq$       |
| `\nsupseteq`       | $\nsupseteq$      |
| `\supsetneq`       | $\supsetneq$      |
| `\varsupsetneq`    | $\varsupsetneq$   |
| `\sqsupseteq`      | $\sqsupseteq$     |
| `\subseteqq`       | $\subseteqq$      |
| `\nsubseteqq`      | $\nsubseteqq$     |
| `\subsetneq`       | $\subsetneq$      |
| `\varsubsetneq`    | $\varsubsetneq$   |
| `\supseteqq`       | $\supseteqq$      |
| `\nsupseteqq`      | $\nsupseteqq$     |
| `\supsetneq`       | $\supsetneq$      |
| `\varsupsetneq`    | $\varsupsetneq$   |
| `\overgroup{AB}`   | $\overgroup{AB}$  |
| `\undergroup{AB}`  | $\undergroup{AB}$ |

#### 10.关系符号

| LaTeX语法                          | 符号效果                  |
|------------------------------------|---------------------------|
| `=`                                | $=$                       |
| `\ne`                              | $\ne$                     |
| `\neq`                             | $\neq$                    |
| `\equiv`                           | $\equiv$                  |
| `\not\equiv`                       | $\not\equiv$              |
| `\doteq`                           | $\doteq$                  |
| `\doteqdot`                        | $\doteqdot$               |
| `\overset{\underset{\mathrm{def}}{}}{=}` | $\overset{\underset{\mathrm{def}}{}}{=}$ |
| `:=`                               | $:=$                      |
| `\sim`                             | $\sim$                    |
| `\nsim`                            | $\nsim$                   |
| `\backsimeq`                       | $\backsimeq$              |
| `\thicksim`                        | $\thicksim$               |
| `\sineq`                           | $\sineq$                  |
| `\backsimeq`                       | $\backsimeq$              |
| `\eqsim`                           | $\eqsim$                  |
| `\cong`                            | $\cong$                   |
| `\ncong`                           | $\ncong$                  |
| `\approx`                          | $\approx$                 |
| `\thickapprox`                     | $\thickapprox$            |
| `\approxeq`                        | $\approxeq$               |
| `\asymp`                           | $\asymp$                  |
| `\propto`                          | $\propto$                 |
| `\varpropto`                       | $\varpropto$              |
| `<`                                | $<$                       |
| `\nless`                           | $\nless$                  |
| `\ll`                              | $\ll$                     |
| `\not\ll`                          | $\not\ll$                 |
| `\lll`                             | $\lll$                    |
| `\not\lll`                         | $\not\lll$                |
| `\lessdot`                         | $\lessdot$                |
| `>`                                | $>$                       |
| `\ngtr`                            | $\ngtr$                   |
| `\gg`                              | $\gg$                     |
| `\not\gg`                          | $\not\gg$                 |
| `\ggg`                             | $\ggg$                    |
| `\not\ggg`                         | $\not\ggg$                |
| `\gtrdot`                          | $\gtrdot$                 |
| `\le`                              | $\le$                     |
| `\leq`                             | $\leq$                    |
| `\nleq`                            | $\nleq$                   |
| `\leqq`                            | $\leqq$                   |
| `\nleqq`                           | $\nleqq$                  |
| `\nleq`                            | $\nleq$                   |
| `\lvertneq`                        | $\lvertneq$               |
| `\ge`                              | $\ge$                     |
| `\geq`                             | $\geq$                    |
| `\ngeq`                            | $\ngeq$                   |
| `\geqq`                            | $\geqq$                   |
| `\ngeqq`                           | $\ngeqq$                  |
| `\gneq`                            | $\gneq$                   |
| `\gvertneq`                        | $\gvertneq$               |
| `\lessgtr`                         | $\lessgtr$                |
| `\lesseqgtr`                       | $\lesseqgtr$              |
| `\gtreqless`                       | $\gtreqless$              |
| `\lesseqqgtr`                      | $\lesseqqgtr$             |
| `\leqqslant`                       | $\leqqslant$             |
| `\nleqqslant`                      | $\nleqqslant$            |
| `\eqslantless`                     | $\eqslantless$            |
| `\geqqslant`                       | $\geqqslant$            |
| `\ngeqqslant`                      | $\ngeqqslant$           |
| `\eqslantgtr`                      | $\eqslantgtr$             |
| `\lesssim`                         | $\lesssim$                |
| `\lnsim`                           | $\lnsim$                  |
| `\lessapprox`                      | $\lessapprox$             |
| `\lnapprox`                        | $\lnapprox$               |
| `\gtrsim`                          | $\gtrsim$                 |
| `\gnsim`                           | $\gnsim$                  |
| `\gtrapprox`                       | $\gtrapprox$              |
| `\gnapprox`                        | $\gnapprox$               |
| `\prec`                            | $\prec$                   |
| `\nprec`                           | $\nprec$                  |
| `\preceq`                          | $\preceq$                 |
| `\npreceq`                         | $\npreceq$                |
| `\precneqq`                        | $\precneqq$               |
| `\succ`                            | $\succ$                   |
| `\nsucc`                           | $\nsucc$                  |
| `\succeq`                          | $\succeq$                 |
| `\nsucceq`                         | $\nsucceq$                |
| `\succneqq`                        | $\succneqq$               |
| `\preccurlyeq`                     | $\preccurlyeq$            |
| `\curlyeqprec`                     | $\curlyeqprec$            |
| `\succcurlyeq`                     | $\succcurlyeq$            |
| `\curlyeqsucc`                     | $\curlyeqsucc$            |
| `\precsim`                         | $\precsim$                |
| `\precnsim`                        | $\precnsim$               |
| `\precapprox`                      | $\precapprox$             |
| `\precnapprox`                     | $\precnapprox$            |
| `\succsim`                         | $\succsim$                |
| `\succnsim`                        | $\succnsim$               |
| `\succapprox`                      | $\succapprox$             |
| `\succnapprox`                     | $\succnapprox$            |


#### 11.几何符号

| LaTeX语法                | 符号效果                |
|--------------------------|-------------------------|
| `\parallel`              | $\parallel$             |
| `\nparallel`             | $\nparallel$            |
| `\shortparallel`         | $\shortparallel$        |
| `\nshortparallel`        | $\nshortparallel$       |
| `\perp`                  | $\perp$                 |
| `\angle`                 | $\angle$                |
| `\sphericalangle`        | $\sphericalangle$       |
| `\measuredangle`         | $\measuredangle$        |
| `45^\circ`               | $45^\circ$              |
| `\Box`                   | $\Box$                  |
| `\blacksquare`           | $\blacksquare$          |
| `\diamond`               | $\diamond$              |
| `\Diamond`               | $\Diamond$              |
| `\lozenge`               | $\lozenge$              |
| `\blacklozenge`          | $\blacklozenge$         |
| `\bigstar`               | $\bigstar$              |
| `\bigcirc`               | $\bigcirc$              |
| `\triangle`              | $\triangle$             |
| `\bigtriangleup`         | $\bigtriangleup$        |
| `\triangledown`          | $\triangledown$         |
| `\blacktriangle`         | $\blacktriangle$        |
| `\blacktriangledown`     | $\blacktriangledown$    |
| `\blacktriangleleft`     | $\blacktriangleleft$    |
| `\blacktriangleright`    | $\blacktriangleright$   |
| `\overlinesegment{AB}`   | $\overlinesegment{AB}$  |
| `\underlinesegment{AB}`  | $\underlinesegment{AB}$ |

#### 12.逻辑符号

| LaTeX语法                | 符号效果                |
|--------------------------|-------------------------|
| `\forall`                | $\forall$               |
| `\exists`                | $\exists$               |
| `\nexists`               | $\nexists$              |
| `\therefore`             | $\therefore$            |
| `\because`               | $\because$              |
| `\And`                   | $\And$                  |
| `\lor`                   | $\lor$                  |
| `\vee`                   | $\vee$                  |
| `\curlyvee`              | $\curlyvee$             |
| `\bigvee`                | $\bigvee$               |
| `\land`                  | $\land$                 |
| `\wedge`                 | $\wedge$                |
| `\curlywedge`            | $\curlywedge$           |
| `\bigwedge`              | $\bigwedge$             |
| `\bar{q}`                | $\bar{q}$               |
| `\bar{abc}`              | $\bar{abc}$             |
| `\overline{q}`           | $\overline{q}$          |
| `\overline{abc}`         | $\overline{abc}$        |
| `\lnot`                  | $\lnot$                 |
| `\neg`                   | $\neg$                  |
| `\not\operatorname{R}`   | $\not\operatorname{R}$  |
| `\bot`                   | $\bot$                  |
| `\top`                   | $\top$                  |
| `\vdash`                 | $\vdash$                |
| `\dashv`                 | $\dashv$                |
| `\Vdash`                 | $\Vdash$                |
| `\Vvdash`                | $\Vvdash$               |
| `\models`                | $\models$               |
| `\nvdash`                | $\nvdash$               |
| `\nVdash`                | $\nVdash$               |
| `\nvDash`                | $\nvDash$               |
| `\nVDash`                | $\nVDash$               |
| `\ulcorner`              | $\ulcorner$            |
| `\urcorner`              | $\urcorner$             |
| `\llcorner`              | $\llcorner$             |
| `\lrcorner`              | $\lrcorner$             |
| `\impliedby`             | $\impliedby$            |

#### 13.箭头

| LaTeX语法                | 符号效果                |
|--------------------------|-------------------------|
| `\Rightarrow`            | $\Rightarrow$           |
| `\Leftarrow`             | $\Leftarrow$            |
| `\rightarrow`            | $\rightarrow$           |
| `\nRightarrow`           | $\nRightarrow$          |
| `\Longrightarrow`        | $\Longrightarrow$       |
| `\implies`               | $\implies$              |
| `\leftarrow`             | $\leftarrow$            |
| `\nLeftarrow`            | $\nLeftarrow$           |
| `\Longleftarrow`         | $\Longleftarrow$        |
| `\Leftrightarrow`        | $\Leftrightarrow$       |
| `\nLeftrightarrow`       | $\nLeftrightarrow$      |
| `\Longleftrightarrow`    | $\Longleftrightarrow$   |
| `\iff`                   | $\iff$                  |
| `\Uparrow`               | $\Uparrow$              |
| `\Downarrow`             | $\Downarrow$            |
| `\Updownarrow`           | $\Updownarrow$          |
| `\rightarrow`            | $\rightarrow$           |
| `\to`                    | $\to$                   |
| `\nrightarrow`           | $\nrightarrow$          |
| `\longrightarrow`        | $\longrightarrow$       |
| `\leftarrow`             | $\leftarrow$            |
| `\gets`                  | $\gets$                 |
| `\nleftarrow`            | $\nleftarrow$           |
| `\longleftarrow`         | $\longleftarrow$        |
| `\leftrightarrow`        | $\leftrightarrow$       |
| `\nleftrightarrow`       | $\nleftrightarrow$      |
| `\longleftrightarrow`    | $\longleftrightarrow$   |
| `\uparrow`               | $\uparrow$              |
| `\downarrow`             | $\downarrow$            |
| `\updownarrow`           | $\updownarrow$          |
| `\nearrow`               | $\nearrow$              |
| `\swarrow`               | $\swarrow$              |
| `\nwarrow`               | $\nwarrow$              |
| `\searrow`               | $\searrow$              |
| `\mapsto`                | $\mapsto$               |
| `\longmapsto`            | $\longmapsto$           |
| `\rightharpoonup`        | $\rightharpoonup$       |
| `\rightharpoondown`      | $\rightharpoondown$     |
| `\leftharpoonup`         | $\leftharpoonup$        |
| `\leftharpoondown`       | $\leftharpoondown$      |
| `\upharpoonleft`         | $\upharpoonleft$        |
| `\upharpoonright`        | $\upharpoonright$       |
| `\downharpoonleft`       | $\downharpoonleft$      |
| `\downharpoonright`      | $\downharpoonright$     |
| `\rightleftharpoons`     | $\rightleftharpoons$    |
| `\leftrightharpoons`     | $\leftrightharpoons$    |
| `\curvearrowleft`        | $\curvearrowleft$       |
| `\circlearrowleft`       | $\circlearrowleft$      |
| `\Lsh`                   | $\Lsh$                  |
| `\upuparrows`            | $\upuparrows$           |
| `\rightrightarrows`      | $\rightrightarrows$     |
| `\rightleftarrows`       | $\rightleftarrows$      |
| `\rightarrowtail`        | $\rightarrowtail$       |
| `\looparrowright`        | $\looparrowright$       |
| `\curvearrowright`       | $\curvearrowright$      |
| `\circlearrowright`      | $\circlearrowright$     |
| `\Rsh`                   | $\Rsh$                  |
| `\downdownarrows`        | $\downdownarrows$       |
| `\leftleftarrows`        | $\leftleftarrows$       |
| `\leftrightarrows`       | $\leftrightarrows$      |
| `\leftarrowtail`         | $\leftarrowtail$        |
| `\looparrowleft`         | $\looparrowleft$        |
| `\hookrightarrow`        | $\hookrightarrow$       |
| `\hookleftarrow`         | $\hookleftarrow$        |
| `\multimap`              | $\multimap$             |
| `\leftrightsquigarrow`   | $\leftrightsquigarrow$  |
| `\rightsquigarrow`       | $\rightsquigarrow$      |
| `\twoheadrightarrow`     | $\twoheadrightarrow$    |
| `\twoheadleftarrow`      | $\twoheadleftarrow$     |
| `\underleftarrow{AB}`    | $\underleftarrow{AB}$   |
| `\overleftharpoon{ac}`   | $\overleftharpoon{ac}$  |
| `\underleftrightarrow{AB}` | $\underleftrightarrow{AB}$ |
| `\underrrightarrow{AB}`  | $\underrrightarrow{AB}$ |
| `\overrightharpoon{AB}`  | $\overrightharpoon{AB}$ |

#### 14.特殊符号

| LaTeX语法          | 符号效果          |
|--------------------|-------------------|
| `\amalg`           | $\amalg$          |
| `\S`               | $\S$              |
| `\%`               | $\%$              |
| `\dagger`          | $\dagger$         |
| `\ddagger`         | $\ddagger$        |
| `\ldots`           | $\ldots$          |
| `\cdots`           | $\cdots$          |
| `\smile`           | $\smile$          |
| `\frown`           | $\frown$          |
| `\wr`              | $\wr$             |
| `\triangleleft`    | $\triangleleft$   |
| `\triangleright`   | $\triangleright$  |
| `\diamondsuit`     | $\diamondsuit$    |
| `\heartsuit`       | $\heartsuit$      |
| `\clubsuit`        | $\clubsuit$       |
| `\spadesuit`       | $\spadesuit$      |
| `\Game`            | $\Game$           |
| `\flat`            | $\flat$           |
| `\natural`         | $\natural$        |
| `\sharp`           | $\sharp$          |

#### 15.上标、下标及积分

| LaTeX语法                          | 符号效果                  |
|------------------------------------|---------------------------|
| `a^2`                              | $a^2$                     |
| `a_2`                              | $a_2$                     |
| `a^{2+2}`                          | $a^{2+2}$                 |
| `a_{i,j}`                          | $a_{i,j}$                 |
| `x^{2/3}`                          | $x^{2/3}$                 |
| `{}_{1}^{2}\!X_{3}^{4}`            | ${}_{1}^{2}\!X_{3}^{4}$   |
| `x_1^2=x_1 \times x_1`             | $x_1^2=x_1 \times x_1$    |
| `x'`                               | $x'$                      |
| `x^\prime`                         | $x^\prime$                |
| `x\prime`                          | $x\prime$                 |
| `\intop`                           | $\intop$                  |
| `\smallint`                        | $\smallint$               |
| `\dot{x}`                          | $\dot{x}$                 |
| `\ddot{y}`                         | $\ddot{y}$                |
| `\vec{c}`                          | $\vec{c}$                 |
| `\overleftarrow{ab}`               | $\overleftarrow{ab}$      |
| `\overrightarrow{cd}`              | $\overrightarrow{cd}$     |
| `\overleftrightarrow{ab}`          | $\overleftrightarrow{ab}$ |
| `\widehat{efg}`                    | $\widehat{efg}$           |
| `\overset{\frown}{AB}`             | $\overset{\frown}{AB}$    |
| `\overline{hij}`                   | $\overline{hij}$          |
| `\underline{klm}`                  | $\underline{klm}$         |
| `\overbrace{1+2+\cdots+100}`       | $\overbrace{1+2+\cdots+100}$ |
| `\overbrace{1+2+\cdots+100}^{5050}` | $\overbrace{1+2+\cdots+100}^{5050}$ |
| `\underbrace{a+b+\cdots+z}`        | $\underbrace{a+b+\cdots+z}$ |
| `\underbrace{a+b+\cdots+z}_{26}`   | $\underbrace{a+b+\cdots+z}_{26}$ |
| `\sum_{k=1}^N k^2`                 | $\sum_{k=1}^N k^2$        |
| `\begin{matrix} \sum_{k=1}^N k^2 \end{matrix}` | $\begin{matrix} \sum_{k=1}^N k^2 \end{matrix}$ |
| `\prod_{i=1}^N x_i`                | $\prod_{i=1}^N x_i$       |
| `\begin{matrix} \prod_{i=1}^N x_i \end{matrix}` | $\begin{matrix} \prod_{i=1}^N x_i \end{matrix}$ |
| `\coprod_{i=1}^N x_i`              | $\coprod_{i=1}^N x_i$     |
| `\begin{matrix} \coprod_{i=1}^N x_i \end{matrix}` | $\begin{matrix} \coprod_{i=1}^N x_i \end{matrix}$ |
| `\lim_{n \to \infty} x_n`          | $\lim_{n \to \infty} x_n$ |
| `\begin{matrix} \lim_{n \to \infty} x_n \end{matrix}` | $\begin{matrix} \lim_{n \to \infty} x_n \end{matrix}$ |
| `\int_{-N}^N e^x \mathrm{d}x`      | $\int_{-N}^N e^x \mathrm{d}x$ |
| `\begin{matrix} \int_{-N}^N e^x \mathrm{d}x \end{matrix}` | $\begin{matrix} \int_{-N}^N e^x \mathrm{d}x \end{matrix}$ |
| `\iint_D^W \mathrm{d}x \mathrm{d}y`| $\iint_D^W \mathrm{d}x \mathrm{d}y$ |
| `\iiint_E^W \mathrm{d}x \mathrm{d}y \mathrm{d}z` | $\iiint_E^W \mathrm{d}x \mathrm{d}y \mathrm{d}z$ |
| `\oint_C x^3 \mathrm{d}x + 4y^2 \mathrm{d}y` | $\oint_C x^3 \mathrm{d}x + 4y^2 \mathrm{d}y$ |
| `\varointclockwise_C 7^x \mathrm{d}x + e^y \mathrm{d}y` | $\varointclockwise_C 7^x \mathrm{d}x + e^y \mathrm{d}y$ |
| `\varointctrclockwise_C 7^x \mathrm{d}x + e^y \mathrm{d}y` | $\varointctrclockwise_C 7^x \mathrm{d}x + e^y \mathrm{d}y$ |
| `\oiint_S f \mathrm{d}A`           | $\oiint_S f \mathrm{d}A$  |
| `\oiiint_E f \mathrm{d}V`          | $\oiiint_E f \mathrm{d}V$ |
| `\bigcap_1^k p`                    | $\bigcap_1^k p$           |
| `\bigcup_1^k p`                    | $\bigcup_1^k p$           |

#### 16.上标、下标及积分

| LaTeX语法                          | 符号效果                  |
|------------------------------------|---------------------------|
| `a^2`                              | $a^2$                     |
| `a_2`                              | $a_2$                     |
| `a^{2+2}`                          | $a^{2+2}$                 |
| `a_{i,j}`                          | $a_{i,j}$                 |
| `x^{2/3}`                          | $x^{2/3}$                 |
| `{}_{1}^{2}\!X_{3}^{4}`            | ${}_{1}^{2}\!X_{3}^{4}$   |
| `x_1^2=x_1 \times x_1`             | $x_1^2=x_1 \times x_1$    |
| `x'`                               | $x'$                      |
| `x^\prime`                         | $x^\prime$                |
| `x\prime`                          | $x\prime$                 |
| `\intop`                           | $\intop$                  |
| `\smallint`                        | $\smallint$               |
| `\dot{x}`                          | $\dot{x}$                 |
| `\ddot{y}`                         | $\ddot{y}$                |
| `\vec{c}`                          | $\vec{c}$                 |
| `\overleftarrow{ab}`               | $\overleftarrow{ab}$      |
| `\overrightarrow{cd}`              | $\overrightarrow{cd}$     |
| `\overleftrightarrow{ab}`          | $\overleftrightarrow{ab}$ |
| `\widehat{efg}`                    | $\widehat{efg}$           |
| `\overset{\frown}{AB}`             | $\overset{\frown}{AB}$    |
| `\overline{hij}`                   | $\overline{hij}$          |
| `\underline{klm}`                  | $\underline{klm}$         |
| `\overbrace{1+2+\cdots+100}`       | $\overbrace{1+2+\cdots+100}$ |
| `\overbrace{1+2+\cdots+100}^{5050}` | $\overbrace{1+2+\cdots+100}^{5050}$ |
| `\underbrace{a+b+\cdots+z}`        | $\underbrace{a+b+\cdots+z}$ |
| `\underbrace{a+b+\cdots+z}_{26}`   | $\underbrace{a+b+\cdots+z}_{26}$ |
| `\sum_{k=1}^N k^2`                 | $\sum_{k=1}^N k^2$        |
| `\begin{matrix} \sum_{k=1}^N k^2 \end{matrix}` | $\begin{matrix} \sum_{k=1}^N k^2 \end{matrix}$ |
| `\prod_{i=1}^N x_i`                | $\prod_{i=1}^N x_i$       |
| `\begin{matrix} \prod_{i=1}^N x_i \end{matrix}` | $\begin{matrix} \prod_{i=1}^N x_i \end{matrix}$ |
| `\coprod_{i=1}^N x_i`              | $\coprod_{i=1}^N x_i$     |
| `\begin{matrix} \coprod_{i=1}^N x_i \end{matrix}` | $\begin{matrix} \coprod_{i=1}^N x_i \end{matrix}$ |
| `\lim_{n \to \infty} x_n`          | $\lim_{n \to \infty} x_n$ |
| `\begin{matrix} \lim_{n \to \infty} x_n \end{matrix}` | $\begin{matrix} \lim_{n \to \infty} x_n \end{matrix}$ |
| `\int_{-N}^N e^x \mathrm{d}x`      | $\int_{-N}^N e^x \mathrm{d}x$ |
| `\begin{matrix} \int_{-N}^N e^x \mathrm{d}x \end{matrix}` | $\begin{matrix} \int_{-N}^N e^x \mathrm{d}x \end{matrix}$ |
| `\iint_D^W \mathrm{d}x \mathrm{d}y`| $\iint_D^W \mathrm{d}x \mathrm{d}y$ |
| `\iiint_E^W \mathrm{d}x \mathrm{d}y \mathrm{d}z` | $\iiint_E^W \mathrm{d}x \mathrm{d}y \mathrm{d}z$ |
| `\oint_C x^3 \mathrm{d}x + 4y^2 \mathrm{d}y` | $\oint_C x^3 \mathrm{d}x + 4y^2 \mathrm{d}y$ |
| `\varointclockwise_C 7^x \mathrm{d}x + e^y \mathrm{d}y` | $\varointclockwise_C 7^x \mathrm{d}x + e^y \mathrm{d}y$ |
| `\varointctrclockwise_C 7^x \mathrm{d}x + e^y \mathrm{d}y` | $\varointctrclockwise_C 7^x \mathrm{d}x + e^y \mathrm{d}y$ |
| `\oiint_S f \mathrm{d}A`           | $\oiint_S f \mathrm{d}A$  |
| `\oiiint_E f \mathrm{d}V`          | $\oiiint_E f \mathrm{d}V$ |
| `\bigcap_1^k p`                    | $\bigcap_1^k p$           |
| `\bigcup_1^k p`                    | $\bigcup_1^k p$           |

#### 17.分数、矩阵和多行列式

| LaTeX语法                          | 符号效果                  |
|------------------------------------|---------------------------|
| `\frac{2}{4}=0.5`                  | $\frac{2}{4}=0.5$         |
| `\frac{a+b}{a-b}`                  | $\frac{a+b}{a-b}$         |
| `\tfrac{2}{4}=0.5`                 | $\tfrac{2}{4}=0.5$        |
| `\cfrac{2}{c+\cfrac{2}{d+\cfrac{2}{4}}}=a` | $\cfrac{2}{c+\cfrac{2}{d+\cfrac{2}{4}}}=a$ |
| `\dfrac{2}{4}=0.5 \quad \dfrac{2}{c+\dfrac{2}{d+\dfrac{2}{4}}}=a` | $\dfrac{2}{4}=0.5 \quad \dfrac{2}{c+\dfrac{2}{d+\dfrac{2}{4}}}=a$ |
| `\binom{n}{r}=\binom{n}{n-r}=C_n^r=C_n^{n-r}` | $\binom{n}{r}=\binom{n}{n-r}=C_n^r=C_n^{n-r}$ |
| `\left(n-r,n^{2^n},\frac{n}{a-b+c+d},\binom{n}{0}+\binom{n}{1}\right)` | $\left(n-r,n^{2^n},\frac{n}{a-b+c+d},\binom{n}{0}+\binom{n}{1}\right)$ |
| `\tbinom{n}{r}=\tbinom{n}{n-r}=C_n^r=C_n^{n-r}` | $\tbinom{n}{r}=\tbinom{n}{n-r}=C_n^r=C_n^{n-r}$ |
| `\dbinom{n}{r}=\dbinom{n}{n-r}=C_n^r=C_n^{n-r}` | $\dbinom{n}{r}=\dbinom{n}{n-r}=C_n^r=C_n^{n-r}$ |
| `\begin{matrix} x & y \\ z & v \end{matrix}` | $\begin{matrix} x & y \\ z & v \end{matrix}$ |
| `\begin{vmatrix} x & y \\ z & v \end{vmatrix}` | $\begin{vmatrix} x & y \\ z & v \end{vmatrix}$ |
| `\begin{Vmatrix} x & y \\ z & v \end{Vmatrix}` | $\begin{Vmatrix} x & y \\ z & v \end{Vmatrix}$ |
| `\begin{bmatrix} 0 & \dots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \dots & 0 \end{bmatrix}` | $\begin{bmatrix} 0 & \dots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \dots & 0 \end{bmatrix}$ |
| `\begin{Bmatrix} x & y \\ z & v \end{Bmatrix}` | $\begin{Bmatrix} x & y \\ z & v \end{Bmatrix}$ |
| `\begin{pmatrix} x & y \\ z & v \end{pmatrix}` | $\begin{pmatrix} x & y \\ z & v \end{pmatrix}$ |
| `\bigl(\begin{smallmatrix} a&b \\ c&d \end{smallmatrix}\bigr)` | $\bigl(\begin{smallmatrix} a&b \\ c&d \end{smallmatrix}\bigr)$ |
| `f(n)=\begin{cases} n/2, & \text{if }n\text{ is even} \\ 3n+1, & \text{if }n\text{ is odd} \end{cases}` | $f(n)=\begin{cases} n/2, & \text{if }n\text{ is even} \\ 3n+1, & \text{if }n\text{ is odd} \end{cases}$ |
| `\begin{align} f(x) &= (m+n)^2 \\ &= m^2 + 2mn + n^2 \end{align}` | $\begin{align} f(x) &= (m+n)^2 \\ &= m^2 + 2mn + n^2 \end{align}$ |
| `\begin{align} 3^{6n+3}+4^{6n+3} &\equiv (3^3)^{2n+1}+(4^3)^{2n+1} \\ &\equiv 27^{2n+1}+64^{2n+1} \\ &\equiv 27^{2n+1}+(-27)^{2n+1} \\ &\equiv 27^{2n+1}-27^{2n+1} \\ &\equiv 0 \pmod{91} \end{align}` | $\begin{align} 3^{6n+3}+4^{6n+3} &\equiv (3^3)^{2n+1}+(4^3)^{2n+1} \\ &\equiv 27^{2n+1}+64^{2n+1} \\ &\equiv 27^{2n+1}+(-27)^{2n+1} \\ &\equiv 27^{2n+1}-27^{2n+1} \\ &\equiv 0 \pmod{91} \end{align}$ |
| `\begin{array}{lcl} z & = & a \\ f(x,y,z) & = & x+y+z \end{array}` | $\begin{array}{lcl} z & = & a \\ f(x,y,z) & = & x+y+z \end{array}$ |
| `\begin{array}{lcr} z & = & a \\ f(x,y,z) & = & x+y+z \end{array}` | $\begin{array}{lcr} z & = & a \\ f(x,y,z) & = & x+y+z \end{array}$ |
| `\begin{cases} 3x+5y+z \\ 7x-2y+4z \\ -6x+3y+2z \end{cases}` | $\begin{cases} 3x+5y+z \\ 7x-2y+4z \\ -6x+3y+2z \end{cases}$ |
| `\begin{array}{|c||c|c|} a & b & S \\ \hline 000&0&1 \\ 001&1&1 \\ 100&1&1 \\ 101&0&0 \end{array}` | $\begin{array}{|c||c|c|} a & b & S \\ \hline 000&0&1 \\ 001&1&1 \\ 100&1&1 \\ 101&0&0 \end{array}$ |
| `\begin{array}{cc} a & b \\ c & d \end{array}` | $\begin{array}{cc} a & b \\ c & d \end{array}$ |
| `\def\arraystretch{1.5} \begin{array}{:c:c:c:} a & b & c \\ 1.5d & e & f \\ g & h & i \end{array}` | $\def\arraystretch{1.5} \begin{array}{:c:c:c:} a & b & c \\ 1.5d & e & f \\ g & h & i \end{array}$ |
| `\begin{rcases} a & \text{if }b \\ c & \text{if }d \end{rcases}\implies\cdots` | $\begin{rcases} a & \text{if }b \\ c & \text{if }d \end{rcases}\implies\cdots$ |

#### 18.其他

| LaTeX语法          | 符号效果          |
|--------------------|-------------------|
| `\digup`           | $\digup$          |
| `\centerdot`       | $\centerdot$      |
| `\ltimes`          | $\ltimes$         |
| `\rtimes`          | $\rtimes$         |
| `\lefthreetimes`   | $\lefthreetimes$  |
| `\righthreetimes`  | $\righthreetimes$ |
| `\eqcirc`          | $\eqcirc$         |
| `\circeq`          | $\circeq$         |
| `\triangleq`       | $\triangleq$      |
| `\bumpeq`          | $\bumpeq$         |
| `\Bumpeq`          | $\Bumpeq$         |
| `\doteqdot`        | $\doteqdot$       |
| `\risingdotseq`    | $\risingdotseq$   |
| `\fallingdotseq`   | $\fallingdotseq$  |
| `\intercal`        | $\intercal$       |
| `\barwedge`        | $\barwedge$       |
| `\veebar`          | $\veebar$         |
| `\doublebarwedge`  | $\doublebarwedge$ |
| `\between`         | $\between$        |
| `\pitchfork`       | $\pitchfork$      |
| `\vartriangleleft` | $\vartriangleleft$|
| `\ntriangleleft`   | $\ntriangleleft$  |
| `\vartriangleright`| $\vartriangleright$|
| `\ntriangleright`  | $\ntriangleright$ |
| `\trianglelefteq`  | $\trianglelefteq$ |
| `\ntrianglelefteq` | $\ntrianglelefteq$|
| `\trianglerighteq` | $\trianglerighteq$|
| `\ntrianglerighteq`| $\ntrianglerighteq$|
| `\not a`           | $\not a$          |


#### 19.希腊字体

| LaTeX语法       | 符号效果       |
|-----------------|----------------|
| `\Alpha`        | $\Alpha$       |
| `\Beta`         | $\Beta$        |
| `\Gamma`        | $\Gamma$       |
| `\Delta`        | $\Delta$       |
| `\Epsilon`      | $\Epsilon$     |
| `\Zeta`         | $\Zeta$        |
| `\Eta`          | $\Eta$         |
| `\Theta`        | $\Theta$       |
| `\Iota`         | $\Iota$        |
| `\Kappa`        | $\Kappa$       |
| `\Lambda`       | $\Lambda$      |
| `\Mu`           | $\Mu$          |
| `\Nu`           | $\Nu$          |
| `\Xi`           | $\Xi$          |
| `\Omicron`      | $\Omicron$     |
| `\Pi`           | $\Pi$          |
| `\Rho`          | $\Rho$         |
| `\Sigma`        | $\Sigma$       |
| `\Tau`          | $\Tau$         |
| `\Upsilon`      | $\Upsilon$     |
| `\Phi`          | $\Phi$         |
| `\Chi`          | $\Chi$         |
| `\Psi`          | $\Psi$         |
| `\Omega`        | $\Omega$       |
| `\alpha`        | $\alpha$       |
| `\beta`         | $\beta$        |
| `\gamma`        | $\gamma$       |
| `\delta`        | $\delta$       |
| `\epsilon`      | $\epsilon$     |
| `\zeta`         | $\zeta$        |
| `\eta`          | $\eta$         |
| `\theta`        | $\theta$       |
| `\iota`         | $\iota$        |
| `\kappa`        | $\kappa$       |
| `\lambda`       | $\lambda$      |
| `\mu`           | $\mu$          |
| `\nu`           | $\nu$          |
| `\xi`           | $\xi$          |
| `\omicron`      | $\omicron$     |
| `\pi`           | $\pi$          |
| `\rho`          | $\rho$         |
| `\sigma`        | $\sigma$       |
| `\tau`          | $\tau$         |
| `\upsilon`      | $\upsilon$     |
| `\phi`          | $\phi$         |
| `\chi`          | $\chi$         |
| `\psi`          | $\psi$         |
| `\omega`        | $\omega$       |
| `\varepsilon`   | $\varepsilon$  |
| `\digamma`      | $\digamma$     |
| `\varkappa`     | $\varkappa$    |
| `\varpi`        | $\varpi$       |
| `\varrho`       | $\varrho$      |
| `\varsigma`     | $\varsigma$    |
| `\vartheta`     | $\vartheta$    |
| `\varphi`       | $\varphi$      |
| `\varGamma`     | $\varGamma$    |
| `\varDelta`     | $\varDelta$    |
| `\varLambda`    | $\varLambda$   |
| `\varXi`        | $\varXi$       |
| `\varUpsilon`   | $\varUpsilon$  |
| `\varPsi`       | $\varPsi$      |
| `\varOmega`     | $\varOmega$    |
| `\thetasym`     | $\thetasym$    |

#### 20.希伯来符号

| LaTeX语法   | 符号效果   |
|-------------|------------|
| `\aleph`    | $\aleph$   |
| `\beth`     | $\beth$    |
| `\gimel`    | $\gimel$   |
| `\daleth`   | $\daleth$  |



#### 21.黑板粗体
| LaTeX语法                  | 符号效果                  |
|----------------------------|---------------------------|
| `\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}` | $\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$ |


#### 22.粗体
| LaTeX语法                  | 符号效果                  |
|----------------------------|---------------------------|
| `\mathbf{ABCDEFGHIJKLMNOPQRSTUVWXYZ}` | $\mathbf{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$ |
| `\mathbf{abcdefghijklmnopqrstuvwxyz}` | $\mathbf{abcdefghijklmnopqrstuvwxyz}$ |
| `\mathbf{0123456789}`      | $\mathbf{0123456789}$      |



### 23. 粗体希腊字母
| LaTeX语法                  | 符号效果                  |
|----------------------------|---------------------------|
| `\boldsymbol{\Alpha\Beta\Gamma\Delta\Epsilon\Zeta\Eta\Theta\Iota\Kappa\Lambda\Mu}` | $\boldsymbol{\Alpha\Beta\Gamma\Delta\Epsilon\Zeta\Eta\Theta\Iota\Kappa\Lambda\Mu}$ |
| `\boldsymbol{\Nu\Xi\Pi\Rho\Sigma\Tau\Upsilon\Phi\Chi\Psi\Omega}` | $\boldsymbol{\Nu\Xi\Pi\Rho\Sigma\Tau\Upsilon\Phi\Chi\Psi\Omega}$ |
| `\boldsymbol{\alpha\beta\gamma\delta\epsilon\zeta\eta\theta\iota\kappa\lambda\mu}` | $\boldsymbol{\alpha\beta\gamma\delta\epsilon\zeta\eta\theta\iota\kappa\lambda\mu}$ |
| `\boldsymbol{\xi\pi\rho\sigma\tau\upsilon\phi\chi\psi\omega\varepsilon\digamma}` | $\boldsymbol{\xi\pi\rho\sigma\tau\upsilon\phi\chi\psi\omega\varepsilon\digamma}$ |
| `\boldsymbol{\varkappa\varpi\varrho\varsigma\vartheta\varphi}` | $\boldsymbol{\varkappa\varpi\varrho\varsigma\vartheta\varphi}$ |




### 24. 斜体
| LaTeX语法                  | 符号效果                  |
|----------------------------|---------------------------|
| `\mathfrak{0123456789}`    | $\mathfrak{0123456789}$    |



### 25. 罗马体
| LaTeX语法                  | 符号效果                  |
|----------------------------|---------------------------|
| `\mathrm{ABCDEFGHIJKLMNOPQRSTUVWXYZ}` | $\mathrm{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$ |
| `\mathrm{abcdefghijklmnopqrstuvwxyz}` | $\mathrm{abcdefghijklmnopqrstuvwxyz}$ |
| `\mathrm{0123456789}`      | $\mathrm{0123456789}$      |



### 26. 手写体/花体
| LaTeX语法                  | 符号效果                  |
|----------------------------|---------------------------|
| `\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZ}` | $\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$ |


### 27. Fraktur体
| LaTeX语法                  | 符号效果                  |
|----------------------------|---------------------------|
| `\mathfrak{ABCDEFGHIJKLMNOPQRSTUVWXYZ}` | $\mathfrak{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$ |
| `\mathfrak{abcdefghijklmnopqrstuvwxyz}` | $\mathfrak{abcdefghijklmnopqrstuvwxyz}$ |
| `\mathfrak{0123456789}`    | $\mathfrak{0123456789}$    |



### 28. 小型手写体
| LaTeX语法                  | 符号效果                  |
|----------------------------|---------------------------|
| `\scriptstyle\text{abcdefghijklm}` | $\scriptstyle\text{abcdefghijklm}$ |

### 29. 括号

| 名称               | LaTeX语法                          | 符号效果                  |
|--------------------|------------------------------------|---------------------------|
| 短括号             | `( \frac{1}{2} )`                  | $\left(\frac{1}{2}\right)$ |
| 长括号（自适应）| `\left( \frac{1}{2} \right)`        | $\left(\frac{1}{2}\right)$ |
| 圆括号（小括号）| `\left( \frac{a}{b} \right)`        | $\left(\frac{a}{b}\right)$ |
| 方括号（中括号）| `\left[ \frac{a}{b} \right]`        | $\left[\frac{a}{b}\right]$ |
| 花括号（大括号）| `\left\{ \frac{a}{b} \right\}`      | $\left\{\frac{a}{b}\right\}$ |
| 角括号             | `\left \langle \frac{a}{b} \right \rangle` | $\left\langle\frac{a}{b}\right\rangle$ |
| 单竖线（绝对值）| `\left| \frac{a}{b} \right|`        | $\left|\frac{a}{b}\right|$ |
| 双竖线（范数）| `\left \| \frac{a}{b} \right \|`    | $\left\|\frac{a}{b}\right\|$ |
| 高斯符号           | `\left \lbrack \frac{a}{b} \right \rbrack` | $\left\lbrack\frac{a}{b}\right\rbrack$ |
| 取底符号           | `\left \lfloor \frac{a}{b} \right \rfloor` | $\left\lfloor\frac{a}{b}\right\rfloor$ |
| 取顶符号           | `\left \lceil \frac{c}{d} \right \rceil` | $\left\lceil\frac{c}{d}\right\rceil$ |
| 上下箭头           | `\left \uparrow \frac{a}{b} \right \downarrow`, `\left \Uparrow \frac{a}{b} \right \Downarrow`, `\left \updownarrow \frac{a}{b} \right \Updownarrow` | $\left\uparrow\frac{a}{b}\right\downarrow$, $\left\Uparrow\frac{a}{b}\right\Downarrow$, $\left\updownarrow\frac{a}{b}\right\Updownarrow$ |
| 混合括号           | `\left [ 0,1 \right ), \left \langle \psi \right |` | $\left [ 0,1 \right ),\left \langle \psi \right |$ |
| 单左括号           | `\left \{ \frac{a}{b} \right .`     | $\left\{\frac{a}{b}\right.$ |
| 单右括号           | `\left . \frac{a}{b} \right \}`     | $\left.\frac{a}{b}\right\}$ |
| 左右括号           | `\lparen \rparen`                  | $\lparen\rparen$           |
| 左右大括号         | `\lbrace \rbrace`                  | $\lbrace\rbrace$          |
| 左右竖大括号       | `\lmoustache \rmoustache`          | $\lmoustache\rmoustache$  |
| 左右群括号         | `\lgroup \rgroup`                  | $\lgroup\rgroup$          |
| 双左（右）中括号   | `\llbracket \rrbracket`            | $\llbracket\rrbracket$    |






