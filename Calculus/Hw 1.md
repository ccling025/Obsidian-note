## 1.2
### 39
![[Pasted image 20250916095802.png]]
### 45
Prove that $\lim_{x \to c} f(x) = 0$ if and only if $\lim_{x \to c} |f(x)| = 0$.
This can be expressed as:
$$ \lim_{x \to c} f(x) = 0 \iff \lim_{x \to c} |f(x)| = 0 $$

The proof requires two parts: proving the forward direction ($\implies$) and the reverse direction ($\impliedby$).

{Part 1: Forward Direction ($\implies$)}
We assume that $\lim_{x \to c} f(x) = 0$ and we will prove that $\lim_{x \to c} |f(x)| = 0$.

By the definition of a limit, since $\lim_{x \to c} f(x) = 0$, for any given $\varepsilon > 0$, there exists a $\delta > 0$ such that if $0 < |x - c| < \delta$, then $|f(x) - 0| < \varepsilon$, which simplifies to $|f(x)| < \varepsilon$.

Now, let's consider the limit of $|f(x)|$. We need to show that for any given $\varepsilon > 0$, there exists a $\delta > 0$ such that if $0 < |x - c| < \delta$, then $||f(x)| - 0| < \varepsilon$.
The expression $||f(x)| - 0|$ is simply $||f(x)||$. Since $|f(x)| \ge 0$, we have $||f(x)|| = |f(x)|$.
Thus, we need to show that $|f(x)| < \varepsilon$.

From our initial assumption, we already have that for any $\varepsilon > 0$, there exists a $\delta > 0$ such that $|f(x)| < \varepsilon$ whenever $0 < |x - c| < \delta$. We can use this same $\delta$.
Therefore, by the definition of a limit, $\lim_{x \to c} |f(x)| = 0$.

{Part 2: Reverse Direction ($\impliedby$)}
We assume that $\lim_{x \to c} |f(x)| = 0$ and we will prove that $\lim_{x \to c} f(x) = 0$.

By the definition of a limit, since $\lim_{x \to c} |f(x)| = 0$, for any given $\varepsilon > 0$, there exists a $\delta > 0$ such that if $0 < |x - c| < \delta$, then $||f(x)| - 0| < \varepsilon$, which simplifies to $|f(x)| < \varepsilon$.

Now, let's consider the limit of $f(x)$. We need to show that for any given $\varepsilon > 0$, there exists a $\delta > 0$ such that if $0 < |x - c| < \delta$, then $|f(x) - 0| < \varepsilon$.
The expression $|f(x) - 0|$ is simply $|f(x)|$.
Thus, we need to show that $|f(x)| < \varepsilon$.

From our initial assumption, we already have that for any $\varepsilon > 0$, there exists a $\delta > 0$ such that $|f(x)| < \varepsilon$ whenever $0 < |x - c| < \delta$. We can use this same $\delta$.
Therefore, by the definition of a limit, $\lim_{x \to c} f(x) = 0$.

Since both directions of the proof hold true, we have successfully shown that $\lim_{x \to c} f(x) = 0$ if and only if $\lim_{x \to c} |f(x)| = 0$.

### 51
{3. Prove $\lim_{x \to -2} \frac{1}{x+1} = -1$}

$\forall \varepsilon > 0, \exists \delta > 0, \text{ s.t. } 0 < |x - (-2)| < \delta \implies \left|\frac{1}{x+1} - (-1)\right| < \varepsilon$

$\text{Check}$ $\left|\frac{1}{x+1} + 1\right| = \left|\frac{1 + (x+1)}{x+1}\right| = \left|\frac{x+2}{x+1}\right| = \frac{|x+2|}{|x+1|} < \varepsilon$

$\text{assume}$ $\delta \le \frac{1}{2}, \quad |x+2| < \frac{1}{2} \implies -\frac{1}{2} < x+2 < \frac{1}{2}$

$\implies -\frac{3}{2} < x+1 < -\frac{1}{2}$

$\implies |x+1| \ge \frac{1}{2}, \quad \frac{1}{|x+1|} \le 2$

$\text{Guess}$ $\delta = \min\left\{\frac{1}{2}, \frac{\varepsilon}{2}\right\}$

$|x+2| < \delta, \quad \frac{|x+2|}{|x+1|} < \frac{2\delta}{|x+1|}$

$\frac{|x+2|}{|x+1|} < 2\delta, \quad \left|\frac{1}{x+1} + 1\right| < \varepsilon \quad \text{Q.E.D.}$


*39
![[Pasted image 20250916095225.png]]
*55
![[Pasted image 20250916095544.png]]
*56
![[Pasted image 20250916095725.png]]
*59
![[Pasted image 20250916095942.png]]