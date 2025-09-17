### Thm.
$$
\begin{aligned}
&\text{Suppose } f,g \text{ are continuous at } x=c \\ 
&f , g \text{ 的四則運算、合成皆為連續}
\end{aligned}
$$
*** 
### e.g.
$$
\begin{aligned}
&\text{pf: } \lim_{x \to c} f(x)g(x) = f(c)g(c)\\
\\
&\lim_{x \to c} f(x) \times \lim_{x \to c} g(x) = f(c) \cdot g(c)\#\\
\end{aligned}
$$
*** 
### e.g.
$$
\begin{aligned}
&\text{pf: }f(x) = \sqrt{x}, c>0, \text{ then } \lim_{x \to c} f(x) = f(c)\\
\\
&\text{Check } |\sqrt{x}-\sqrt{c}| = \frac{|x-c|}{\sqrt{x}+\sqrt{c}} < \frac{1}{\sqrt{c}}|x-c| < \varepsilon\\
&\text{Given } \varepsilon>0, \text{ suppose } \delta = \sqrt{c}\varepsilon\\
&\text{Then } 0<|x-c|<\delta\\
&\implies \frac{|x-c|}{\sqrt{x}+\sqrt{c}} < \frac{1}{\sqrt{c}}|x-c| < \frac{\delta}{\sqrt{c}}\\
&\frac{|x-c|}{\sqrt{x}+\sqrt{c}} < \frac{\delta}{\sqrt{c}}, \quad |\sqrt{x}-\sqrt{c}| < \varepsilon\#
\end{aligned}
$$
### 合成函數的連續性
$$
\begin{align}
&\text{pf. } \lim_{x\to c} (g \circ f)(x) = (g \circ f)(c)\\
&\forall \ \varepsilon > 0, \exists \ \delta_1 > 0, \text{ s.t.}\\
&|y-f(c)| < \delta_1 \implies |g(y)-g(f(c))| < \varepsilon\\
\\
&\exists \ \delta_2 > 0, \text{ s.t.}\\
&|x-c| < \delta_2 \implies |f(x)-f(c)| < \delta_1\\
&\implies |g(f(x))-g(f(c))| < \varepsilon\\
&\implies \lim_{x\to c} g(f(x)) = g(f(c)) \#
\end{align}
$$