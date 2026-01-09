# Latex常用方程式



## 上标、下标及积分等

| 效果 | 语法 |
|------|------|
| $a^2$ | `a^2` |
| $a_2$ | `a_2` |
| $a^{2+3}$ | `a^{2+3}` |
| $a_{(i,j)}$ | `a_{(i,j)}` |
| $a^{b^c}$ | `a^{b^c}` |
| $a_{b_c}$ | `a_{b_c}` |
| $3^4$ | `3^4` |
| $\overset{\text{downset}}{(AB)}$ | `\\overset{\\text{downset}}{(AB)}` |
| $\underset{\text{upset}}{(AB)}$ | `\\underset{\\text{upset}}{(AB)}` |
| $\overline{klm}$ | `\\overline{klm}` |
| $\underline{klm}$ | `\\underline{klm}` |
| $\overbrace{1+2+\cdots+100}$ | `\\overbrace{1+2+\\cdots+100}` |
| $\underbrace{1+2+\cdots+100}$ | `\\underbrace{1+2+\\cdots+100}` |
| $\int_a^b f(x)dx$ | `\\int_a^b f(x)dx` |
| $\iint_a^b f(x,y)dxdy$ | `\\iint_a^b f(x,y)dxdy` |
| $\iiint_a^b f(x,y,z)dxdydz$ | `\\iiint_a^b f(x,y,z)dxdydz` |
| $\oint_a^b f(x)dx$ | `\\oint_a^b f(x)dx` |
| $\sum_{i=1}^n i$ | `\\sum_{i=1}^n i` |
| $\prod_{i=1}^n i$ | `\\prod_{i=1}^n i` |
| $\lim_{x \to \infty} f(x)$ | `\\lim_{x \to \\infty} f(x)` |
| $\lim_{x \to 0^+} f(x)$ | `\\lim_{x \to 0^+} f(x)` |

## 括号和分隔符

| 效果 | 语法 |
|------|------|
| $(a + b)$ | `(a + b)` |
| $[a + b]$ | `[a + b]` |
| ${a + b}$ | `{a + b}` |
| $\langle a + b \rangle$ | `\\langle a + b \\rangle` |
| $\lceil a + b \rceil$ | `\\lceil a + b \\rceil` |
| $\lfloor a + b \rfloor$ | `\\lfloor a + b \\rfloor` |
| $\lVert a + b \rVert$ | `\\lVert a + b \\rVert` |
| $\left(\frac{a}{b}\right)$ | `\\left(\\frac{a}{b}\\right)` |
| $\left[\frac{a}{b}\right]$ | `\\left[\\frac{a}{b}\\right]` |
| $\left\{\frac{a}{b}\right\}$ | `\\left\\{\\frac{a}{b}\\right\\}` |
| $\left\langle\frac{a}{b}\right\rangle$ | `\\left\\langle\\frac{a}{b}\\right\\rangle` |
| $\left\lceil\frac{a}{b}\right\rceil$ | `\\left\\lceil\\frac{a}{b}\\right\\rceil` |
| $\left\lfloor\frac{a}{b}\right\rfloor$ | `\\left\\lfloor\\frac{a}{b}\\right\\rfloor` |
| $\left\lVert\frac{a}{b}\right\rVert$ | `\\left\\lVert\\frac{a}{b}\\right\\rVert` |
| $\left( a, b \right]$ | `\\left( a, b \\right]` |
| $\left[ a, b \right)$ | `\\left[ a, b \\right)` |

## 根号

| 效果 | 语法 |
|------|------|
| $\sqrt{a}$ | `\\sqrt{a}` |
| $\sqrt[n]{a}$ | `\\sqrt[n]{a}` |
| $\sqrt{a + b}$ | `\\sqrt{a + b}` |
| $\sqrt[n]{a + b}$ | `\\sqrt[n]{a + b}` |
| $\sqrt{a^2 + b^2}$ | `\\sqrt{a^2 + b^2}` |

## 函数

| 效果 | 语法 |
|------|------|
| $\sin a$ | `\\sin a` |
| $\cos a$ | `\\cos a` |
| $\tan a$ | `\\tan a` |
| $\cot a$ | `\\cot a` |
| $\sec a$ | `\\sec a` |
| $\csc a$ | `\\csc a` |
| $\arcsin a$ | `\\arcsin a` |
| $\arccos a$ | `\\arccos a` |
| $\arctan a$ | `\\arctan a` |
| $\cot^{-1} a$ | `\\cot^{-1} a` |
| $\sinh a$ | `\\sinh a` |
| $\cosh a$ | `\\cosh a` |
| $\tanh a$ | `\\tanh a` |
| $\coth a$ | `\\coth a` |
| $\ln a$ | `\\ln a` |
| $\log a$ | `\\log a` |
| $\log_{10} a$ | `\\log_{10} a` |
| $\exp a$ | `\\exp a` |
| $\max(a, b)$ | `\\max(a, b)` |
| $\min(a, b)$ | `\\min(a, b)` |
| $\gcd(a, b)$ | `\\gcd(a, b)` |
| $\text{sign}(a)$ | `\\text{sign}(a)` |
| $\text{mod}(a, b)$ | `\\text{mod}(a, b)` |

## 微分及导数

| 效果 | 语法 |
|------|------|
| $\frac{df}{dx}$ | `\\frac{df}{dx}` |
| $\frac{d^2f}{dx^2}$ | `\\frac{d^2f}{dx^2}` |
| $\frac{\partial f}{\partial x}$ | `\\frac{\\partial f}{\\partial x}` |
| $\frac{\partial^2 f}{\partial x^2}$ | `\\frac{\\partial^2 f}{\\partial x^2}` |
| $\nabla f$ | `\\nabla f` |
| $f'(x)$ | `f'(x)` |
| $f''(x)$ | `f''(x)` |
| $f^{(n)}(x)$ | `f^{(n)}(x)` |
| $\dot{f}(t)$ | `\\dot{f}(t)` |
| $\ddot{f}(t)$ | `\\ddot{f}(t)` |
| $\int f(x)dx$ | `\\int f(x)dx` |
| $\int_a^b f(x)dx$ | `\\int_a^b f(x)dx` |
| $\iint f(x,y)dxdy$ | `\\iint f(x,y)dxdy` |
| $\iiint f(x,y,z)dxdydz$ | `\\iiint f(x,y,z)dxdydz` |
| $\oint f(x)dx$ | `\\oint f(x)dx` |

## 关系运算符

| 效果 | 语法 |
|------|------|
| $=$ | `=` |
| $\neq$ | `\\neq` |
| $\approx$ | `\\approx` |
| $\equiv$ | `\\equiv` |
| $\sim$ | `\\sim` |
| $\cong$ | `\\cong` |
| $\propto$ | `\\propto` |
| $<$ | `<` |
| $>$ | `>` |
| $\leq$ | `\\leq` |
| $\geq$ | `\\geq` |
| $\ll$ | `\\ll` |
| $\gg$ | `\\gg` |
| $\subset$ | `\\subset` |
| $\supset$ | `\\supset` |
| $\subseteq$ | `\\subseteq` |
| $\supseteq$ | `\\supseteq` |
| $\in$ | `\\in` |
| $\notin$ | `\\notin` |
| $\forall$ | `\\forall` |
| $\exists$ | `\\exists` |
| $\nexists$ | `\\nexists` |
| $\Rightarrow$ | `\\Rightarrow` |
| $\Leftarrow$ | `\\Leftarrow` |
| $\Leftrightarrow$ | `\\Leftrightarrow` |
| $\rightarrow$ | `\\rightarrow` |
| $\leftarrow$ | `\\leftarrow` |
| $\leftrightarrow$ | `\\leftrightarrow` |

## 集合与逻辑符号

| 效果 | 语法 |
|------|------|
| $\varnothing$ | `\\varnothing` |
| $\emptyset$ | `\\emptyset` |
| $\cup$ | `\\cup` |
| $\cap$ | `\\cap` |
| $\setminus$ | `\\setminus` |
| $\subseteq$ | `\\subseteq` |
| $\supseteq$ | `\\supseteq` |
| $\subset$ | `\\subset` |
| $\supset$ | `\\supset` |
| $\in$ | `\\in` |
| $\notin$ | `\\notin` |
| $\ni$ | `\\ni` |
| $\exists$ | `\\exists` |
| $\forall$ | `\\forall` |
| $\nexists$ | `\\nexists` |
| $\land$ | `\\land` |
| $\lor$ | `\\lor` |
| $\lnot$ | `\\lnot` |
| $\Rightarrow$ | `\\Rightarrow` |
| $\Leftarrow$ | `\\Leftarrow` |
| $\Leftrightarrow$ | `\\Leftrightarrow` |
| $\rightarrow$ | `\\rightarrow` |
| $\leftarrow$ | `\\leftarrow` |
| $\leftrightarrow$ | `\\leftrightarrow` |

## 几何符号

| 效果 | 语法 |
|------|------|
| $\triangle$ | `\\triangle` |
| $\square$ | `\\square` |
| $\circ$ | `\\circ` |
| $\angle$ | `\\angle` |
| $\measuredangle$ | `\\measuredangle` |
| $\parallel$ | `\\parallel` |
| $\perp$ | `\\perp` |
| $\sim$ | `\\sim` |
| $\cong$ | `\\cong` |
| $\equiv$ | `\\equiv` |
| $\otimes$ | `\\otimes` |
| $\oplus$ | `\\oplus` |
| $\ominus$ | `\\ominus` |
| $\odot$ | `\\odot` |

## 戴帽符号

| 效果 | 语法 |
|------|------|
| $\hat{a}$ | `\\hat{a}` |
| $\check{a}$ | `\\check{a}` |
| $\acute{a}$ | `\\acute{a}` |
| $\grave{a}$ | `\\grave{a}` |
| $\dot{a}$ | `\\dot{a}` |
| $\ddot{a}$ | `\\ddot{a}` |
| $\breve{a}$ | `\\breve{a}` |
| $\bar{a}$ | `\\bar{a}` |
| $\vec{a}$ | `\\vec{a}` |
| $\overrightarrow{AB}$ | `\\overrightarrow{AB}` |
| $\overleftarrow{AB}$ | `\\overleftarrow{AB}` |
| $\widehat{AB}$ | `\\widehat{AB}` |
| $\widetilde{AB}$ | `\\widetilde{AB}` |

## 箭头符号

| 效果 | 语法 |
|------|------|
| $\leftarrow$ | `\\leftarrow` |
| $\rightarrow$ | `\\rightarrow` |
| $\leftrightarrow$ | `\\leftrightarrow` |
| $\Leftarrow$ | `\\Leftarrow` |
| $\Rightarrow$ | `\\Rightarrow` |
| $\Leftrightarrow$ | `\\Leftrightarrow` |
| $\longleftarrow$ | `\\longleftarrow` |
| $\longrightarrow$ | `\\longrightarrow` |
| $\longleftrightarrow$ | `\\longleftrightarrow` |
| $\Longleftarrow$ | `\\Longleftarrow` |
| $\Longrightarrow$ | `\\Longrightarrow` |
| $\Longleftrightarrow$ | `\\Longleftrightarrow` |
| $\uparrow$ | `\\uparrow` |
| $\downarrow$ | `\\downarrow` |
| $\updownarrow$ | `\\updownarrow` |
| $\Uparrow$ | `\\Uparrow` |
| $\Downarrow$ | `\\Downarrow` |
| $\Updownarrow$ | `\\Updownarrow` |
| $\nearrow$ | `\\nearrow` |
| $\searrow$ | `\\searrow` |
| $\nwarrow$ | `\\nwarrow` |
| $\swarrow$ | `\\swarrow` |
| $\mapsto$ | `\\mapsto` |
| $\longmapsto$ | `\\longmapsto` |

## 特殊符号

| 效果 | 语法 |
|------|------|
| $\cdots$ | `\\cdots` |
| $\vdots$ | `\\vdots` |
| $\ddots$ | `\\ddots` |
| $\aleph$ | `\\aleph` |
| $\beth$ | `\\beth` |
| $\gimel$ | `\\gimel` |
| $\daleth$ | `\\daleth` |
| $\nabla$ | `\\nabla` |
| $\Delta$ | `\\Delta` |
| $\Lambda$ | `\\Lambda` |
| $\Omega$ | `\\Omega` |
| $\Phi$ | `\\Phi` |
| $\Psi$ | `\\Psi` |
| $\Sigma$ | `\\Sigma` |
| $\Theta$ | `\\Theta` |
| $\Upsilon$ | `\\Upsilon` |
| $\Xi$ | `\\Xi` |
| $\pi$ | `\\pi` |
| $e$ | `e` |
| $\imath$ | `\\imath` |
| $\jmath$ | `\\jmath` |
| $\ell$ | `\\ell` |
| $\Re$ | `\\Re` |
| $\Im$ | `\\Im` |
| $\top$ | `\\top` |
| $\bot$ | `\\bot` |
| $\ast$ | `\\ast` |
| $\star$ | `\\star` |
| $\circ$ | `\\circ` |
| $\bullet$ | `\\bullet` |
| $\dagger$ | `\\dagger` |
| $\ddagger$ | `\\ddagger` |
| $\S$ | `\\S` |
| $\P$ | `\\P` |
| $\copyright$ | `\\copyright` |
| $^{TM}$ | `^{TM}` |
| $^{\text{®}}$ | `^{\\text{®}}` |

## 分数、矩阵和多行列式

| 效果 | 语法 |
|------|------|
| $\frac{2}{4}=0.5$ | `\\frac{2}{4}=0.5` |
| ${a+b \over a-b}$ | `${a+b \\over a-b}` |
| $\tfrac{2}{4} = 0.5$ | `\\tfrac{2}{4} = 0.5` |
| $\cfrac{2}{c + \cfrac{2}{d + \cfrac{2}{4}}} = a$ | `\\cfrac{2}{c + \\cfrac{2}{d + \\cfrac{2}{4}}} = a` |
| $\dfrac{2}{4} = 0.5$ | `\\dfrac{2}{4} = 0.5` |
| $\dbinom{n}{r}=\binom{n}{n-r}=\mathrm{C}_n^r=\mathrm{C}_n^{n-r}$ | `\\dbinom{n}{r}=\\binom{n}{n-r}=\\mathrm{C}_n^r=\\mathrm{C}_n^{n-r}` |
| $n \choose n-r$ | `n \\choose n-r` |
| $\tbinom{n}{r}=\tbinom{n}{n-r}=\mathrm{C}_n^r=\mathrm{C}_n^{n-r}$ | `\\tbinom{n}{r}=\\tbinom{n}{n-r}=\\mathrm{C}_n^r=\\mathrm{C}_n^{n-r}` |
| $\binom{n}{r}=\dbinom{n}{n-r}=\mathrm{C}_n^r=\mathrm{C}_n^{n-r}$ | `\\binom{n}{r}=\\dbinom{n}{n-r}=\\mathrm{C}_n^r=\\mathrm{C}_n^{n-r}` |
| $\begin{matrix} x & y \\ z & v \end{matrix}$ | `\\begin{matrix} x & y \\\\ z & v \\\\end{matrix}` |
| $\begin{vmatrix} x & y \\ z & v \end{vmatrix}$ | `\\begin{vmatrix} x & y \\\\ z & v \\\\end{vmatrix}` |
| $\begin{Vmatrix} x & y \\ z & v \end{Vmatrix}$ | `\\begin{Vmatrix} x & y \\\\ z & v \\\\end{Vmatrix}` |
| $\begin{bmatrix} 0 & \cdots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \cdots & 0 \end{bmatrix}$ | `\\begin{bmatrix} 0 & \\cdots & 0 \\\\ \\vdots & \\ddots & \\vdots \\\\ 0 & \\cdots & 0 \\\\end{bmatrix}` |
| $\begin{Bmatrix} x & y \\ z & v \end{Bmatrix}$ | `\\begin{Bmatrix} x & y \\\\ z & v \\\\end{Bmatrix}` |
| $\begin{pmatrix} x & y \\ z & v \end{pmatrix}$ | `\\begin{pmatrix} x & y \\\\ z & v \\\\end{pmatrix}` |
| $\bigl( \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \bigr)$ | `\\bigl( \\begin{smallmatrix} a & b \\\\ c & d \\\\end{smallmatrix} \\bigr)` |
| $f(n) = \begin{cases} n/2, & \text{if } n \text{ is even} \\ 3n+1, & \text{if } n \text{ is odd} \end{cases}$ | `f(n) = \\begin{cases} n/2, & \\text{if } n \\text{ is even} \\\\ 3n+1, & \\text{if } n \\text{ is odd} \\\\end{cases}` |
| $\begin{align} f(x) & = (m+n)^2 \\ & = m^2+2mn+n^2 \end{align}$ | `\\begin{align} f(x) & = (m+n)^2 \\\\ & = m^2+2mn+n^2 \\\\end{align}` |
| $\begin{array}{lcl} z & = & a \\ f(x,y,z) & = & x + y + z \end{array}$ | `\\begin{array}{lcl} z & = & a \\\\ f(x,y,z) & = & x + y + z \\\\end{array}` |
| $\begin{array}{lcr} z & = & a \\ f(x,y,z) & = & x + y + z \end{array}$ | `\\begin{array}{lcr} z & = & a \\\\ f(x,y,z) & = & x + y + z \\\\end{array}` |
| $\begin{cases} 3x + 5y + z \\ 7x - 2y + 4z \\ -6x + 3y + 2z \end{cases}$ | `\\begin{cases} 3x + 5y + z \\\\ 7x - 2y + 4z \\\\ -6x + 3y + 2z \\\\end{cases}` |
| $\begin{array}{|c|c||c|} a & b & S \\ 0 & 0 & 1 \\ 0 & 1 & 1 \\ 1 & 0 & 1 \\ 1 & 1 & 0 \end{array}$ | `\\begin{array}{|c|c||c|} a & b & S \\\\ 0 & 0 & 1 \\\\ 0 & 1 & 1 \\\\ 1 & 0 & 1 \\\\ 1 & 1 & 0 \\\\end{array}` |
| $\begin{array}{cc} a & b \\ c & d \end{array}$ | `\\begin{array}{cc} a & b \\\\ c & d \\\\end{array}` |
| $\def\arraystretch{1.5} \begin{array}{c:c:c} a & b & c \\ d & e & f \\ g & h & i \end{array}$ | `\\def\\\\arraystretch{1.5} \\begin{array}{c:c:c} a & b & c \\\\ d & e & f \\\\ g & h & i \\\\end{array}` |
| $\begin{rcases} a & \text{if } b \\ c & \text{if } d \end{rcases} \Rightarrow \dots$ | `\\begin{rcases} a & \\text{if } b \\\\ c & \\text{if } d \\\\end{rcases} \\Rightarrow \\dots` |

### 希腊字母
| 符号 | Latex代码 | 符号 | Latex代码 | 符号 | Latex代码 |
|------|-----------|------|-----------|------|-----------|
| α | `\\alpha` | β | `\\beta` | γ | `\\gamma` |
| δ | `\\delta` | ε | `\\epsilon` | ζ | `\\zeta` |
| η | `\\eta` | θ | `\\theta` | ι | `\\iota` |
| κ | `\\kappa` | λ | `\\lambda` | μ | `\\mu` |
| ν | `\\nu` | ξ | `\\xi` | π | `\\pi` |
| ρ | `\\rho` | σ | `\\sigma` | τ | `\\tau` |
| υ | `\\upsilon` | φ | `\\phi` | χ | `\\chi` |
| ψ | `\\psi` | ω | `\\omega` | | |
| Γ | `\\Gamma` | Δ | `\\Delta` | Θ | `\\Theta` |
| Λ | `\\Lambda` | Ξ | `\\Xi` | Π | `\\Pi` |
| Σ | `\\Sigma` | Υ | `\\Upsilon` | Φ | `\\Phi` |
| Ψ | `\\Psi` | Ω | `\\Omega` | | |

### 数学运算符
| 运算 | Latex代码 | 运算 | Latex代码 | 运算 | Latex代码 |
|------|-----------|------|-----------|------|-----------|
| + | `+` | - | `-` | × | `\\times` |
| ÷ | `\\div` | ± | `\\pm` | ∓ | `\\mp` |
| = | `=` | ≠ | `\\neq` | ≈ | `\\approx` |
| ≤ | `\\leq` | ≥ | `\\geq` | ∈ | `\\in` |
| ∉ | `\\notin` | ⊂ | `\\subset` | ⊃ | `\\supset` |
| ∩ | `\\cap` | ∪ | `\\cup` | ∅ | `\\emptyset` |
| ∀ | `\\forall` | ∃ | `\\exists` | ¬ | `\\lnot` |
| ∧ | `\\land` | ∨ | `\\lor` | → | `\\rightarrow` |
| ← | `\\leftarrow` | ↔ | `\\leftrightarrow` | ⇒ | `\\Rightarrow` |
| ⇐ | `\\Leftarrow` | ⇔ | `\\Leftrightarrow` | | |

## 参考资料

- [ProcessOn LaTeX 符号参考](https://www.processon.com/latex-symbol)
- [Markdown语法](https://www.processon.com/markdown_format)
- [mermaid语法](https://www.processon.com/mermaid/flowchart)
