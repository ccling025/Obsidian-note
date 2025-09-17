https://hackmd.io/@CynthiaChuang/Basic-LaTeX-Commands
---

## 二元運算號

| 預覽        | 指令        | .   | 預覽          | 指令          | .   | 預覽               | 指令               | .   | 預覽              | 指令              |
| --------- | --------- | --- | ----------- | ----------- | --- | ---------------- | ---------------- | --- | --------------- | --------------- |
| $+$       | `+`       |     | $-$         | `-`         |     | $\pm$            | `\pm`            |     | $\mp$           | `\mp`           |
| $\times$  | `\times`  |     | $\ast$      | `\ast`      |     | $\star$          | `\star`          |     | $\cdot$         | `\cdot`         |
| $\div$    | `\div`    |     | $\setminus$ | `\setminus` |     | $\oplus$         | `\oplus`         |     | $\ominus$       | `\ominus`       |
| $\otimes$ | `\otimes` |     | $\odot$     | `\odot`     |     | $\oslash$        | `\oslash`        |     | $\bigcirc$      | `\bigcirc`      |
| $\vee$    | `\vee`    |     | $\wedge$    | `\wedge`    |     | $\uplus$         | `\uplus`         |     | $\circ$         | `\circ`         |
| $\bullet$ | `\bullet` |     | $\diamond$  | `\diamond`  |     | $\triangleright$ | `\triangleright` |     | $\triangleleft$ | `\triangleleft` |

---

## 二元關係符號

| 預覽            | 指令            | .   | 預覽            | 指令            | .   | 預覽        | 指令        |
| ------------- | ------------- | --- | ------------- | ------------- | --- | --------- | --------- |
| $<$           | `<`           |     | `$>$`         | `>`           |     | `$=$`     | `=`       |
| $\le$         | `\le`         |     | `$\ge$`       | `\ge`         |     | `\equiv`  | `\equiv`  |
| $\ll$         | `\ll`         |     | `\gg`         | `\gg`         |     | `\doteq`  | `\doteq`  |
| $\prec$       | `\prec`       |     | `\succ`       | `\succ`       |     | `\sim`    | `\sim`    |
| `\preceq`     | `\preceq`     |     | `\succeq`     | `\succeq`     |     | `\simeq`  | `\simeq`  |
| `\subset`     | `\subset`     |     | `\supset`     | `\supset`     |     | `\approx` | `\approx` |
| `\subseteq`   | `\subseteq`   |     | `\supseteq`   | `\supseteq`   |     | `\cong`   | `\cong`   |
| `\sqsubset`   | `\sqsubset`   |     | `\sqsupset`   | `\sqsupset`   |     | `\Join`   | `\bowtie` |
| `\sqsubseteq` | `\sqsubseteq` |     | `\sqsupseteq` | `\sqsupseteq` |     | `\mid`    | `\mid`    |
| `\in`         | `\in`         |     | `\ni`         | `\ni`         |     | `\propto` | `\propto` |
| `\vdash`      | `\vdash`      |     | `\dashv`      | `\dashv`      |     | `\models` | `\models` |
| `\perp`       | `\perp`       |     | `\parallel`   | `\parallel`   |     | `\smile`  | `\smile`  |
| `\frown`      | `\frown`      |     | `\asymp`      | `\asymp`      |     |           |           |

**可在前面加上 `\not` 得到否定形式，ex：** ``\not <`` 得到 $\not <$  

---

## 邏輯符號

| 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 |
|---|---|---|---|---|---|---|---|
| `\forall` | `\forall` |  | `\exists` | `\exists` |  | `\nexists` | `\nexists` |
| `\therefore` | `\therefore` |  | `\because` | `\because` |  | `\And` | `\And` |
| `\lor` | `\lor` |  | `\vee` | `\vee` |  | `\curlyvee` | `\curlyvee` |
| `\bigvee` | `\bigvee` |  | `\land` | `\land` |  | `\wedge` | `\wedge` |
| `\curlywedge` | `\curlywedge` |  | `\bigwedge` | `\bigwedge` |  | `\neg` | `\neg` |

---

## 上標、下標及 Head

| 預覽                            | 指令                            | .   | 預覽                             | 指令                             | .   | 預覽                | 指令                |
| ----------------------------- | ----------------------------- | --- | ------------------------------ | ------------------------------ | --- | ----------------- | ----------------- |
| $$a^b$$                       | `a^b`                         |     | `a_t`                          | `a_t`                          |     | `a^b_t`           | `a^b_t`           |
| `a^{b+1}_{t+1}`               | `a^{b+1}_{t+1}`               |     | `\overline{m+n}`               | `\overline{m+n}`               |     | `\underline{m+n}` | `\underline{m+n}` |
| `\overbrace{m+\cdots+n}^{26}` | `\overbrace{m+\cdots+n}^{26}` |     | `\underbrace{m+\cdots+n}_{26}` | `\underbrace{m+\cdots+n}_{26}` |     | `\bar{a}`         | `\bar{a}`         |
| `\vec{a}`                     | `\vec{a}`                     |     | `\hat{a}`                      | `\hat{a}`                      |     | `\dot{a}`         | `\dot{a}`         |
| `\overrightarrow{ab}`         | `\overrightarrow{ab}`         |     | `\overleftarrow{ab}`           | `\overleftarrow{ab}`           |     | `\widehat{abc}`   | `\widehat{abc}`   |
| `\overset{\frown}{ab}`        | `\overset{\frown}{ab}`        |     |                                |                                |     |                   |                   |

---

## 大尺寸運算符號

| 預覽           | 指令           | .   | 預覽          | 指令          | .   | 預覽          | 指令          | .   | 預覽          | 指令          |
| ------------ | ------------ | --- | ----------- | ----------- | --- | ----------- | ----------- | --- | ----------- | ----------- |
| `\sum`       | `\sum`       |     | `\bigcap`   | `\bigcap`   |     | `\bigcup`   | `\bigcup`   |     | `\biguplus` | `\biguplus` |
| `\bigsqcup`  | `\bigsqcup`  |     | `\prod`     | `\prod`     |     | `\coprod`   | `\coprod`   |     | `\bigodot`  | `\bigodot`  |
| `\bigotimes` | `\bigotimes` |     | `\bigoplus` | `\bigoplus` |     | `\bigwedge` | `\bigwedge` |     | `\bigvee`   | `\bigvee`   |
| `\int`       | `\int`       |     | `\oint`     | `\oint`     |     |             |             |     |             |             |

---

## 標準函式符號

| 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 |
|---|---|---|---|---|---|---|---|
| `\sin` | `\sin` |  | `\cos` | `\cos` |  | `\tan` | `\tan` |
| `\sec` | `\sec` |  | `\csc` | `\csc` |  | `\cot` | `\cot` |
| `\arcsin` | `\arcsin` |  | `\arccos` | `\arccos` |  | `\arctan` | `\arctan` |
| `\sinh` | `\sinh` |  | `\cosh` | `\cosh` |  | `\tanh` | `\tanh` |
| `\exp` | `\exp` |  | `\log` | `\log` |  | `\ln` | `\ln` |
| `\lim` | `\lim` |  | `\liminf` | `\liminf` |  | `\limsup` | `\limsup` |
| `\inf` | `\inf` |  | `\max` | `\max` |  | `\min` | `\min` |
| `\deg` | `\deg` |  | `\arg` | `\arg` |  | `\gcd` | `\gcd` |

---

## 根號與分數

| 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 |
|---|---|---|---|---|---|---|---|---|---|---|
| `\surd` | `\surd` |  | `\sqrt{2}` | `\sqrt{2}` |  | `\sqrt[n]{}` | `\sqrt[n]{}` |  | `\sqrt[3]{2}` | `\sqrt[3]{2}` |
| `\frac{2}{4}` | `\frac{2}{4}` |  | `\tfrac{2}{4}` | `\tfrac{2}{4}` |  | `\cfrac{2}{4}` | `\cfrac{2}{4}` |  |  |  |

---

## 微積分符號

| 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 |
|---|---|---|---|---|---|---|---|
| `\nabla x` | `\nabla{x}` |  | `\partial x` | `\partial{x}` |  | `x^{\prime}` | `x^{\prime}` |
| `\int_{-N}^{N} e^x\, dx` | `\int_{-N}^{N} e^x\, dx` |  | `\infty` | `\infty` |  |  |  |

---

## 二項式係數

| 預覽 | 指令 | . | 預覽 | 指令 |
|---|---|---|---|---|
| `\dbinom{n}{r}` | `\dbinom{n}{r}` |  | `\binom{n}{n-r}` | `\binom{n}{n-r}` |

---

## 箭號

| 預覽 | 指令 | . | 預覽 | 指令 |
|---|---|---|---|---|
| `\leftarrow` | `\leftarrow` |  | `\rightarrow` | `\rightarrow` |
| `\longleftarrow` | `\longleftarrow` |  | `\longrightarrow` | `\longrightarrow` |
| `\Leftarrow` | `\Leftarrow` |  | `\Rightarrow` | `\Rightarrow` |
| `\Longleftarrow` | `\Longleftarrow` |  | `\Longrightarrow` | `\Longrightarrow` |
| `\leftharpoonup` | `\leftharpoonup` |  | `\rightharpoonup` | `\rightharpoonup` |
| `\leftharpoondown` | `\leftharpoondown` |  | `\rightharpoondown` | `\rightharpoondown` |
| `\hookleftarrow` | `\hookleftarrow` |  | `\hookrightarrow` | `\hookrightarrow` |
| `\mapsto` | `\mapsto` |  | `\longmapsto` | `\longmapsto` |
| `\leftrightarrow` | `\leftrightarrow` |  | `\longleftrightarrow` | `\longleftrightarrow` |
| `\Leftrightarrow` | `\Leftrightarrow` |  | `\Longleftrightarrow` | `\Longleftrightarrow` |
| `\rightleftharpoons` | `\rightleftharpoons` |  | `\uparrow` | `\uparrow` |
| `\downarrow` | `\downarrow` |  | `\Uparrow` | `\Uparrow` |
| `\Downarrow` | `\Downarrow` |  | `\updownarrow` | `\updownarrow` |
| `\Updownarrow` | `\Updownarrow` |  | `\nearrow` | `\nearrow` |
| `\searrow` | `\searrow` |  | `\swarrow` | `\swarrow` |
| `\nwarrow` | `\nwarrow` |  |  |  |  

---

## 分隔符號

| 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 |
|---|---|---|---|---|---|---|---|---|---|---|
| `(` | `(` |  | `)` | `)` |  | `[` | `[` |  | `]` | `]` |
| `\{` | `\{` |  | `\}` | `\}` |  | `\langle` | `\langle` |  | `\rangle` | `\rangle` |
| `\lfloor` | `\lfloor` |  | `\rfloor` | `\rfloor` |  | `\lceil` | `\lceil` |  | `\rceil` | `\rceil` |
| `\vert` | `\vert` |  | `\Vert` | `\Vert` |  | `/` | `/` |  | `\backslash` | `\backslash` |

---

## 希臘字母

**大寫字母**

| 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 |
|---|---|---|---|---|---|---|---|---|---|---|
| `\Gamma` | `\Gamma` |  | `\Delta` | `\Delta` |  | `\Lambda` | `\Lambda` |  | `\Xi` | `\Xi` |
| `\Pi` | `\Pi` |  | `\Sigma` | `\Sigma` |  | `\Upsilon` | `\Upsilon` |  | `\Phi` | `\Phi` |
| `\Psi` | `\Psi` |  | `\Omega` | `\Omega` |  |  |  |  |  |  |

**小寫字母**

| 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 | . | 預覽 | 指令 |
|---|---|---|---|---|---|---|---|---|---|---|
| `\alpha` | `\alpha` |  | `\beta` | `\beta` |  | `\gamma` | `\gamma` |  | `\delta` | `\delta` |
| `\epsilon` | `\epsilon` |  | `\varepsilon` | `\varepsilon` |  | `\zeta` | `\zeta` |  | `\eta` | `\eta` |
| `\theta` | `\theta` |  | `\vartheta` | `\vartheta` |  | `\iota` | `\iota` |  | `\kappa` | `\kappa` |
| `\lambda` | `\lambda` |  | `\mu` | `\mu` |  | `\nu` | `\nu` |  | `\xi` | `\xi` |
| `o` | `o` |  | `\pi` | `\pi` |  | `\varpi` | `\varpi` |  | `\rho` | `\rho` |
| `\varrho` | `\varrho` |  | `\sigma` | `\sigma` |  | `\varsigma` | `\varsigma` |  | `\tau` | `\tau` |
| `\upsilon` | `\upsilon` |  | `\phi` | `\phi` |  | `\varphi` | `\varphi` |  | `\chi` | `\chi` |
| `\psi` | `\psi` |  | `\omega` | `\omega` |  |  |  |  |  |  |

---


