---
noteID: d7c084b8-a071-43e2-a640-46b216f6e5d1
---
# Operators
## 1. Binary Operator
| LaTeX grammer |    Symbol     |          Explanation           |
| :-----------: | :-----------: | :----------------------------: |
|    `\cdot`    |    $\cdot$    |         inner product          |
|   `\times`    |   $\times$    |         cross product          |
|     `\pm`     |     $\pm$     |           plus minus           |
|    `\circ`    |    $\circ$    |             circle             |
| `\circledast` | $\circledast$ |          convolution           |
|    `\odot`    |    $\odot$    |                                |
|   `\oplus`    |   $\oplus$    |           direct sum           |
|   `\otimes`   |   $\otimes$   | tensor, product measure spaces |

## 2. Calculus
| LaTeX grammer |       Symbol        |    Explanation     |
| :-----------: | :-----------------: | :----------------: |
|  `\partial`   |     $\partial$      | partial derivative |
|   `\nabla`    |      $\nabla$       |       nabla        |
|   `\Delta`    |      $\Delta$       |   capital delta    |
|    `\int`     | $\displaystyle\int$ |      integral      |

# Relation Symbols
| LaTeX grammer |  Symbol   |       Explanation        |
| :-----------: | :-------: | :----------------------: |
|    `\neq`     |  $\neq$   |        not equal         |
|    `\geq`     |  $\geq$   | greater than or equal to |
|    `\leq`     |  $\leq$   |  less than or equal to   |
|    `\sim`     |  $\sim$   |         similiar         |
|   `\simeq`    | $\simeq$  |        asymptotic        |
|   `\approx`   | $\approx$ |       approximate        |
|   `\propto`   | $\propto$ |       proportional       |
# Arrows
|   LaTeX grammer   |      Symbol       |         Explanation         |
| :---------------: | :---------------: | :-------------------------: |
|   `\rightarrow`   |   $\rightarrow$   |        right arrow        |
|   `\leftarrow`    |   $\leftarrow$    |        left arrow         |
|    `\uparrow`     |    $\uparrow$     |         up arrow          |
|   `\downarrow`    |   $\downarrow$    |        down arrow         |
| `\leftrightarrow` | $\leftrightarrow$ |    bidirectional arrow    |
| `\Leftrightarrow` | $\Leftrightarrow$ | bidirectional thick arrow |
# Set Operations
| LaTeX grammer |   Symbol    |  Explanation   |
| :-----------: | :---------: | :------------: |
|    `\cup`     |   $\cup$    |    union     |
|    `\cap`     |   $\cap$    | intersection |
|     `\in`     |    $\in$    |   element    |
|   `\notin`    |  $\notin$   | not element  |
|     `\ni`     |    $\ni$    |   element    |
|   `\subset`   |  $\subset$  |    subset    |
|  `\subseteq`  | $\subseteq$ |    subset    |
|   `\supset`   |  $\supset$  |    subset    |
|  `\supseteq`  | $\supseteq$ |    subset    |
# Complements
| LaTeX grammer |     Symbol     |              Explanation              |
| :-----------: | :------------: | :-----------------------------------: |
| `\dfrac{}{}`  | $\dfrac{a}{b}$ | always shows fraction in display mode |
| `\tfrac{}{}`  | $\tfrac{a}{b}$ |  always shows fraction in type mode   |
|  `\emptyset`  |  $\emptyset$   |               empty set               |
# Spacing
```
$local minimum$ (no spacing)
$local\, minimum$ (one spacing)
$local\; minimum$ (two spacing)
$local\quad minimum$ (four spacing)
```
$local minimum$ (no spacing)
$local\, minimum$ (one spacing)
$local\; minimum$ (two spacing)
$local\quad minimum$ (four spacing)
# Fractions
## `\over`
Things at the left of `\over` will be the numerator, and right will be the denominator.
`$s^2+2s+s\over s+\sqrt s+1$`
$\displaystyle{s^2+2s+s\over s+\sqrt s+1}$
## `\frac`
Things at the first braket will be the numerator, and second will be the denominator.
`$\frac{1+s}{s(s+2)}$`
$\displaystyle{\frac{1+s}{s(s+2)}}$

# Matrices
We use `matrix` symbol, using `&` for columns and `\\` for rows.
```
$$
\begin{gather}
\begin{matrix}1&2\\3&4\\ \end{matrix}\\
\begin{pmatrix}1&2\\3&4\\ \end{pmatrix}\\
\begin{bmatrix}1&2\\3&4\\ \end{bmatrix}\\
\begin{Bmatrix}1&2\\3&4\\ \end{Bmatrix}\\
\begin{vmatrix}1&2\\3&4\\ \end{vmatrix}\\
\begin{Vmatrix}1&2\\3&4\\ \end{Vmatrix}
\end{gather}
$$
```
$$
\begin{gather}
\begin{matrix}1&2\\3&4\\ \end{matrix}\\
\begin{pmatrix}1&2\\3&4\\ \end{pmatrix}\\
\begin{bmatrix}1&2\\3&4\\ \end{bmatrix}\\
\begin{Bmatrix}1&2\\3&4\\ \end{Bmatrix}\\
\begin{vmatrix}1&2\\3&4\\ \end{vmatrix}\\
\begin{Vmatrix}1&2\\3&4\\ \end{Vmatrix}
\end{gather}
$$

# Norms
We use `\vert` and `\left\lvert`, `\right\rvert` for norm characters.
```
$$\vert x \vert$$
$$\left\lvert \frac{s^2+1}{s^3+2s^2+3s+1} \right\rvert$$
```
$$\vert x \vert$$
$$\left\lvert \frac{s^2+1}{s^3+2s^2+3s+1} \right\rvert$$
# Cases (piecewise functions)
We use `cases` symbol.
```
$$\vert x\vert=
\begin{cases}
-x,\;if\;x<0\\
+x,\;if\;x\geq0
\end{cases}$$
```
$$\vert x\vert=
\begin{cases}
-x,\;if\;x<0\\
+x,\;if\;x\geq0
\end{cases}$$
# Font Type
`$\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$`
$\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$
`$\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$`
$\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$

# How to align about certain character
We use `aligned` symbol for it. Things will be aligned about `&character`.
```
$$
\begin{aligned}
f(x)&=ax^2 + bx + c\\
g(x)&=ax^4
\end{aligned}
$$
```
$$
\begin{aligned}
f(x)&=ax^2 + bx + c\\
g(x)&=ax^4
\end{aligned}
$$

# How to use Roman font
We use `\textrm{}`. We can use `{\rm}`, too.
```
$$\displaystyle\int f\, d\mu =\sup\{\mathcal L(f, P) : P\textrm{ is an }\mathcal S \textrm{-partition of X}\}.$$
```
$$\displaystyle\int f\, d\mu =\sup\{\mathcal L(f, P) : P\textrm{ is an }\mathcal S \textrm{-partition of X}\}.$$
```
$$
\dfrac{{\rm d}y}{{\rm d}x}
$$
```
$$
\dfrac{{\rm d}y}{{\rm d}x}
$$
