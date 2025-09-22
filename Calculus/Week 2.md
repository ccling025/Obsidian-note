### Thm.
$$
\begin{aligned}
&\text{Suppose } f,g \text{ are continuous at } x=c \\ 
\\
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
\\
&\text{Given } \varepsilon>0, \text{ suppose } \delta = \sqrt{c}\varepsilon\\
\\
&\text{Then } 0<|x-c|<\delta\\
\\
&\implies \frac{|x-c|}{\sqrt{x}+\sqrt{c}} < \frac{1}{\sqrt{c}}|x-c| < \frac{\delta}{\sqrt{c}}\\
\\
&\frac{|x-c|}{\sqrt{x}+\sqrt{c}} < \frac{\delta}{\sqrt{c}}, \quad |\sqrt{x}-\sqrt{c}| < \varepsilon\#
\end{aligned}
$$
### 合成函數的連續性
$$
\begin{align}
&\text{pf. } \lim_{x\to c} (g \circ f)(x) = (g \circ f)(c)\\
\\
&\forall \ \varepsilon > 0, \exists \ \delta_1 > 0, \text{ s.t.}\\
\\
&|y-f(c)| < \delta_1 \implies |g(y)-g(f(c))| < \varepsilon\\
\\
&\exists \ \delta_2 > 0, \text{ s.t.}\\
\\
&|x-c| < \delta_2 \implies |f(x)-f(c)| < \delta_1\\
\\
&\implies |g(f(x))-g(f(c))| < \varepsilon\\
\\
&\implies \lim_{x\to c} g(f(x)) = g(f(c)) \#
\end{align}
$$
*** 
### $\text{pf. } \lim_{x \to 0}x\sin{x} = 0$
$$
\begin{align}
&-1 \le \sin{x} \le 1\\
&-x \le x\sin{x} \le x \\
&\lim_{x \to 0}-x \le \lim_{x \to 0}x\sin{x} \le \lim_{x \to 0}x \\
\\
&\text{by squeeze rule: } \lim_{x \to 0}x\sin{x} = 0 \#
\end{align}
$$
### $\text{pf. } \lim_{x\to 0} \frac{\sin x}{x}=1$
$$
\begin{align}
&\text{Small }\triangle=\frac{1}{2}\sin x \quad \text{Sector}=\frac{1}{2}x \quad \text{Big }\triangle = \frac{1}{2}x \\
\\
&\frac{1}{2}x > \frac{1}{2}\sin x, \quad \frac{\sin x}{x}<1\\
\\
&\frac{1}{2}\tan x > \frac{1}{2}x, \quad \frac{\sin x}{\cos x} > x\\
\\
&\cos x < \frac{\sin x}{x} < 1\\
\\
&\lim_{x\to 0} \cos x < \lim_{x\to 0} \frac{\sin x}{x} < \lim_{x\to 0} 1\\
\\
&1 < \lim_{x\to 0} \frac{\sin x}{x} < 1\\
\\
&\Rightarrow \text{by squeeze rule } \lim_{x\to 0} \frac{\sin x}{x}=1\#
\end{align}
$$
![[IMG_6587.jpeg]]
![[IMG_6600.jpeg]]
![[IMG_6602.jpeg]]
![[IMG_6604.jpeg]]
![[IMG_6605.jpeg]]
![[IMG_6606.jpeg]]
![[IMG_6607.jpeg]]
![[IMG_6608.jpeg]]


