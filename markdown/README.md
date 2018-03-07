# This is a describtion of how to use Markdown
## Math equations
### Math equation alignment
1. by `align`

try to use this code:
```latex
$$
\begin{align}
h(x) =& \frac{1}{\int_xt(x)\mathrm{d}x} \tag{1}\\
f(x) =& \frac{1}{\int_x\eta(x)\mathrm{d}x}g(x)\tag{2}
\end{align}
$$
``` 
and it will look like this below:
$$
\begin{align}
h(x) =& \frac{1}{\int_xt(x)\mathrm{d}x} \tag{1}\\
f(x) =& \frac{1}{\int_x\eta(x)\mathrm{d}x}g(x)\tag{2}
\end{align}
$$

or like this code
```latex
$$
\begin{align}
a &= b + c \tag{3}\\
  &= d + e + f\tag{4}
\end{align}
$$
```

and we will get equations below:
$$
\begin{align}
a &= b + c \tag{3}\\
  &= d + e + f\tag{4}
\end{align}
$$

2. by `eqnarray`
try this code:
```latex
$$
\begin{eqnarray}
a & = & b + c \\
& = & d + e + f + g + h + i
+ j + k + l\\
&& +\: m + n + o \\
& = & p + q + r + s
\end{eqnarray}
$$
```
and we will get things like this:
\begin{eqnarray}
a & = & b + c \\
& = & d + e + f + g + h + i
+ j + k + l\\
&& +\: m + n + o \\
& = & p + q + r + s
\end{eqnarray}

## Some other things