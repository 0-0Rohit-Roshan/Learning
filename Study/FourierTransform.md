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





















