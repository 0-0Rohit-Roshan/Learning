




#### Classes of System
![img](..\Resources\Clssses-of-System.jpg)

#### Required Formulae
- `s` in laplace = $\sigma+j\omega$ 
- $$\int_{-\infty}^{\infty} |f(t)| e^{\sigma t}dt < \infty$$
- Inverse $$f(t) = \frac{1}{2\pi j} \int_{?}^{?} |f(s)| e^{s t}ds = f(t)a(t)$$

Function|Laplace Transform
--|--
$\delta (t)$|$$1$$
$a(t)$|$$\frac{1}{s}$$
$t .a(t)$|$$\frac{1}{s^2}$$
$t^na(t)$|$$\frac{n!}{s^{n+1}}$$
$e^{-at}a(t)$|$$\frac{1}{s+a}$$
$Sin \omega t(at)$|$$\frac{\omega}{s^2+ \omega^2}$$

- Linearity $$k f(t) \Longleftrightarrow KF(s)$$ $$LT[f_1(t)+f_2(t)] \Longleftrightarrow F_1(s)+F_2 (s)$$

- Frequency Shift $$e^{-at} f(t)\Longleftrightarrow F(s+a)$$

- Final Value Theorem

- Infinite Value Theorem

![img](..\Resources\Model-combined.jpg)

Component|Capacitor|Inductor|Resistor
--|--|--|--
V-I|$$V(t)=\frac{1}{C} \int_{0}^{T} i(t)dt$$|$$V = L \frac{di}{dt}$$|$$V = Ri(t)$$
I-V|$$I(t)= C \frac{dv}{dt}$$|$$I = \frac{1}{L} \int_{0}^{t} V(t)d(t)$$ | $$I = \frac{V(t)}{R}$$
V-Q | $$V(t) = \frac{1}{C} q(t)$$ | $$V(t) = L \frac{d_a^2}{dt^2} $$ | $$V(t) = R \frac{q(t)}{d(t)}$$
Z(s)|$$\frac{1}{CS}$$ | $$LS$$ | $$R$$
Y(s)| $$CS$$ | $$ LS $$ | $$ \frac{1}{R} $$


Transfer function:
- begin by writing a general nth-order, linear, time-invariant differential
equation,Take laplace transform, Then the ratio of the input & output side after laplace transform.

`Zero initial conditions` mean that the system is rest and no energy is stored in any components of the circuit. Generally, zero indicates linear system i.e. if there is no input then there should be zero output.













Q. Differential vs Difference eqn ?  
Q. Single Input Single Output (SISO) vs Multi input Multi Output (MIMO) System?
Q. RLC Tank Circuit?
- Open Loop System Applications
    - Washing Machine.
    - Electric Bulb.
    - Electric Hand Drier.
    - Time based Bread Toaster.
    - Automatic Water Faucet.
    - TV Remote Control.
    - Electric Clothes Drier.
    - Shades or Blinds on a window.
- The main difference between an open-loop system and a closed-loop system is that the closed-loop system has the ability to self-correct while the open-loop system doesn't.











