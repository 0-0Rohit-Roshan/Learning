## Fourier TRansform
is a mathematical transform that decomposes functions depending on space or time into functions depending on `spatial frequency` or `temporal frequency`.  
[YT Gajendra Purohit](https://www.youtube.com/playlist?list=PLU6SqdYcYsfKwY6IPDCshf1kKlk1CCd7d)


**Fourier Transform can exist for -**
- Energy signal (Absolutly intigrable)
- Power signal (Not Absolutly intigrable)
- Impulse signal related signal (But donot exist for Neither energy nor power signal).It is an exception of NENP because it is an absolutely intigratable signal.

**Representation**  
$x(t) \longleftrightarrow X(j \omega) or X(F)$  
$\therefore$ where $X(j \omega) = |X(j \omega)| \angle X(j \omega)$

**Formulae**
- $X(t) \rightarrow X(j \omega)$
- $X(j \omega ) = \int_{-\infty}^\infty$
- Fourier Transform $$f(s) = \frac{1}{\sqrt{2 \pi}} \int_{-\infty}^{\infty} e^{i \eta x} f(x) dx$$
- Inverse Fourier Transform $$f(x) = \frac{1}{\sqrt{2 \pi}} \int_{-\infty}^{\infty} e^{i \eta x} f(s) ds$$
- Fourier $Sine$ Transform $$f_s (s) =  \sqrt{\frac{2}{\pi}} \int_{0}^{\infty} f(x) Sine(sx) dx$$ Inverse Fourier $Sine$ Transform $$f_s (x) = \sqrt{\frac{2}{\pi}} \int_{0}^{\infty} f(s) Sine(sx) ds$$
- Fourier $Cosine$ Transform $$f_c (s) = \sqrt{\frac{2}{\pi}} \int_{0}^{\infty} f(x) Cos(sx) dx$$ Inverse Fourier $Cosine$ Transform $$f_c(x) = \sqrt{\frac{2}{\pi}} \int_{0}^{\infty} f(s) Cos (sx) ds$$
- Appliation of Fourier Transform to `Boundary Value Problem` (_solving partial deferential equation with the help of fourier transform_)

### Fourier transform of test signals
- ramp
- unit impulse
- unit step
- rectangular impulse

 [Fourier transforms and delta functions](https://www.youtube.com/watch?v=8abBLKEZLaI)

### Properties of Fourier Transform
- Linearity
- Time Scaling
- Duality
- Time Shift
- 

### Other Properties

### Fourier transform of Periodic Signal 
[Neso](https://www.youtube.com/watch?v=9I4z5JPbvgg)
- $X(t) = $ Periodic signal $\leftrightarrow X(\omega) = ?$
- `Complex Fourier series expansion` of $X(t)$ is $\sum_{n=- \infty}^{\infty} C_n e^{jn \omega_0t}$
- $A_0 \leftrightarrow 2\pi A_0 \delta (\omega)$
- $A_0 = 1 \leftrightarrow 2\pi \delta (\omega)$
- $C_n \leftrightarrow 2\pi C_n \delta (\omega)$ --- $ \therefore$ fourier transform follows the `principle of homoginity`.
- $C_n e^{jn \omega_0t} \leftrightarrow 2\pi C_n \delta (\omega - n\omega_o)$
- $X(\omega) = \sum_{n=- \infty}^{\infty} 2\pi C_n \delta (\omega - n\omega_o)$ --- $ \therefore$ fourier transform follows the `Law of Additivity`.  
- Steps 
    - Find the equation of periodic signal $C_n$
    - Apply for `e` exponential $$X(\omega) = \sum_{n=- \infty}^{\infty} 2\pi C_n \delta (\omega - n\omega_o)$$
    - For trgnometric function $$Cos (2\pi f_t) \leftrightarrow \frac{1}{2}[\delta(f-f_c) + \delta(f+f_c)]$$  $$Sin (2\pi f_t) \leftrightarrow \frac{1}{2}[\delta(f-f_c) - \delta(f+f_c)]$$
    - Signum function
- Example `Rectangular pulse train`
    - $C_n = \frac{A_o \tau}{T_o} Sa{\frac{n \omega_o \tau}{\tau}}$
    - $X \omega_o = X(\omega) = \sum_{n=- \infty}^{\infty} 2\pi [\frac{A_o \tau}{T_o} Sa{\frac{n \omega_o \tau}{\tau}}] \delta (\omega - n\omega_o) $















