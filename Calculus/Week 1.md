*** 
## Definition of Limit
### Limit Exists
$$\begin{aligned} 
{\displaystyle \lim_{x \to c}} \ &f(x) =L \ \Rightarrow \ \forall\ \varepsilon > 0, \exists\ \sigma > 0
\text{, such that: } \\ &0<|x - c|<\sigma \ \Rightarrow \ |f(x) - L|<\varepsilon
\end{aligned}$$
### Limit does not exist
$$\begin{aligned}
&{\displaystyle \lim_{x \to c}} \ f(x) \not= L \ \Rightarrow \ \exists \ \varepsilon > 0, \forall \ \sigma>0, \ \text{such that:} \\ \ &\exists \ x \ \text{satisfying} \ 0<|x-c|<\sigma \ \text{but} \ |f(x)-L| \ge \varepsilon
\end{aligned}$$

e.g.
$$f(x) = \begin{cases}
	2x-1 \ &\text{if} \ x \not = 3 \\
	6 \ &\text{if} \ x = 3
\end{cases}$$
Note that: $$\lim_{x \to 3}f(x) = 5$$
	We want to know how close x is to 3 that the gap between f(x) and 5 can be smaller than 0.1.
	Hence, the problem becomes:
	$$\text{When} \ |x-3|<\varepsilon, \text{but} \ x \not=3, \ \text{satisfies} \ |f(x) - 5|<0.1$$
	Notice that when $\varepsilon = 0.05, \ |f(x) - 5| = 0.1$,
	so $\varepsilon = 0.05$ is exactly what we want.

## 加法性質的證明

**定理**  
若  
$$
\lim_{x \to a} f(x) = L, \quad \lim_{x \to a} g(x) = M,
$$  
則  
$$
\lim_{x \to a} (f(x) + g(x)) = L + M.
$$

---

**證明**  

由極限定義：  
- 對任意 $\varepsilon > 0$，存在 $\delta_1 > 0$，使得  
  $$
  0 < |x-a| < \delta_1 \implies |f(x) - L| < \tfrac{\varepsilon}{2}.
  $$

- 同時，存在 $\delta_2 > 0$，使得  
  $$
  0 < |x-a| < \delta_2 \implies |g(x) - M| < \tfrac{\varepsilon}{2}.
  $$

取  
$$
\delta = \min(\delta_1, \delta_2),
$$  
則當 $0 < |x-a| < \delta$ 時，有  
$$
|(f(x)+g(x)) - (L+M)| \le |f(x)-L| + |g(x)-M|
< \tfrac{\varepsilon}{2} + \tfrac{\varepsilon}{2} = \varepsilon.
$$

因此  
$$
\lim_{x \to a} (f(x)+g(x)) = L+M.
$$

