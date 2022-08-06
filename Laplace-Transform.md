## Laplace Transform

- [Wiki](https://en.wikipedia.org/wiki/Laplace_transform#Formal_definition) | [YT Gajendra Purohit](https://youtu.be/EDVJotmT584)

**Definition**
- Let $F(t)$ be a function of $t$ defined for { $0 \leqslant t < \infty$} then laplace transform of $f(t)$ denoted by $L[f(t)]$ or $F(s)$ is defined by 
- $$L[f(t)] = F(s) = \int_0^\infty e^{-st} f(t) dt $$
- $s \geqslant 0$ otherwise undefined integration.  

**Formulae**
|Laplace|Inverse Laplace
|--|--
|$$L(1) = \frac{1}{s}$$|$$L^{-1}(\frac{1}{s}) = 1$$
|$$L(t^n) = \frac{\Gamma {n+1}}{s^{n+1}}$$|$$L^{-1}(\frac{1}{s^{n+1}}) = \frac{t^n}{\Gamma {n+1}}$$
|$$L(e^{at}) = \frac{1}{s-a}$$ | $$L^{-1}(\frac{1}{s-a}) = e^{at}$$
|$$L(Sin(at)) = \frac{a}{s^2+a^2}$$ |$$L^{-1}(\frac{1}{s^2+a^2}) = \frac{Sin(at)}{a}$$
|$$L(Sin(hat)) = \frac{a}{s^2-a^2}$$ |$$L^{-1}(\frac{1}{s^2-a^2}) = \frac{Sin(hat)}{a}$$
|$$L(Cos(at)) = \frac{s}{s^2+a^2}$$ |$$L^{-1}(\frac{s}{s^2+a^2}) = Cos(at)$$
|$$L(Cos(hat)) = \frac{s}{s^2-a^2}$$ |$$L^{-1}(\frac{s}{s^2-a^2}) = Cos(hat)$$


**First Shifting Theorem** for laplace  
if $L(f(t)) = f(s)$  
then $L(e^{at}f(t)) = f(s-a)$
- First find the laplace of $f(t)$ then replace  "$s$" with " $s-a$"

[**First Shifting Theorem** for `Inverse` laplace](https://piped.kavin.rocks/watch?v=f7IQqZ9zBiY&t=300)

$$L^{-1}(f(s)) = f(t)$$
$$L^{-1}(f(s-a)) = e^{at}f(t)$$
$$L^{-1}(f(s-a)) = e^{at} L^{-1}(f(s))$$

**Second Shifting Theorem** for laplace
<!-- # A collapsible section with markdown -->
<details>
  <summary> Prerequisite - Unit Step Function</summary>
  
  $$H(t-a) =  \left\{
\begin{array}{ll}
      1 & t\geqslant a \\
    
      0 & t < a \\
\end{array} 
\right.  $$
</details>

$$L(f(t)) = f(s)$$
$$L(f(t-a)H(t-a)) = e^{as} f(s)$$

- Find the Laplace of $f(t)$ then replace the value of $a$ in $e^{as}$

**Second Shifting Theorem** for Inverse laplace
$$L^{-1}(f(s)) = f(t)$$
$$L^{-1}(e^{as}f(s)) = f(t-a) H(t-a)$$









