- TDM FDM
- Concept of Spectrum
- [Frequency spectrum](https://www.youtube.com/watch?v=r18Gi8lSkfM) 
- Amplitude Spectrum - Variation of frequency for frequency.
- Phase Spectrum - variation of phase for frequency.
- Real valued signal ?
- Fourier transform of rectangular pulse.
- Decaying Exponantial vs Rising Exponantial.
- Properties of Fourier Transform.
- Euler's Condition
- Amplitude Spectrum of Fourier Transform
- frequency shift in Fourier Transform
- cos / Sin shifting in fourier transform.
- Gaussian Pulse
- Gaussian Distribution
- Gaussian Curve
- Pulse shifting
- Q. Why transmit gausian pulse instead of rectangular pulse ?
- Energy spectral Density
- Q. Energy of Sinc pulse ?  
**Dirac Delta Function**
- a generalized function or distribution over the real numbers, whose value is zero everywhere except at zero, and whose integral over the entire real line is equal to one.
- Q. Fourier Transform of Delta Function ?
    * Delta function can be considerd as a limiting form of Gaussian pulse.
    * Application of Delta function ?
- Fourier transform of Delta function
- [Fourier transform of Periodic Signal](FourierTransform.md)
- Continous wave modulation.  




### Continuos Wave Modulation
- The Objective of modulation is to shift the base band to the frequency range suitable for Transmission .
-  Shifting a range of frequency is achived by modulation.
- `Modulation` -  The process by which carachteristic of a carrier signal is changed in acordance to message signal.
- `Demodulation` - Resotring the passband signal to baseband signal .
- The Modulatron is the core of the transmitter and the Demodulation is the core of the reciver.
- `Q.` [Why only sinusuidal signal as carrier in modulation ?](https://www.quora.com/Why-are-sinusoidal-signals-used-as-carriers-in-modulation-technique)  
`A.`  To avoid aliasing and bandwidth congestion we use sinusoidal waves for modulation techniques.

## Amplitude Modulation
- Carrier Signal $C(t) = A_c Cos(2 \pi f_c t)$  
$A_c$ Carrier Amplitude | $f_c$ Carrier Frequency  
- Message Signal $m(t)$
- Amplitude of the Carrier is varied  about a mean value , linearly with $m(t)$. 
- 

**Linear Modulation Technique**
- $S(t) = A_c (1+K_a m(t)) Cos(2 \pi f_c t)$  
$K_a$ = Amplitude Sensitivity $[Volt^{-1}]$ 

$K_a m(t) > 1$|$K_a m(t) < 1$
--|--
Overmodulated|
Phase Revarsal|
Envlop Distortion|Modulation % </br> $K_a m(t) x 100 < 100$ </br> avoid Envlope distortion.
- For satisfactory envlop detection $f_c >> \omega_{message}$

**Spectrum of AM Signal**
- Spectrum of AM signal $S(t)$ is $S(f)$
- $$S(f) = \frac{A_c}{2} [\delta(f-f_c) + \delta(f+f_c)] + \frac{K_a A_c}{2} [m(f-f_c)+m(f+f_c)]$$
- AM Spectrum 
    - Two Delta function at $\pm f_c$
    - Two .... baseband at $\pm f_c$

```
Note
```
- $f_c < \omega$ lower & upper side band at $-f_c$ and $+f_c$ will overlap and reasult in message distortion.
- Baseband bandwidth $\omega$  
Passband `Transmissionband` bandwidth $2 \omega$

**Singleton Modulation**
- $m(t) = A_m Cos(2 \pi f_m t)$  
$S(t) = A_c[1 +  \mu Cos(2 \pi f_m t)]Cos(2 \pi f_c t) $  
$\mu = K_a A_m$
- $S(t) = A_c Cos(2 \pi f_c t) + \frac{1}{2} \mu A_c Cos(2 \pi (f_c+f_m) t) + \frac{1}{2} \mu A_c Cos(2 \pi (f_c-f_m) t)$  
$S(f) = \frac{A_c}{2} [\delta(f-f_c) + \delta(f+f_c)] + \mu\frac{A_c}{4} [\delta(f-f_c-f_m) + \delta(f+f_c+f_m)] + \mu\frac{A_c}{4} [\delta(f-f_c+f_m) + \delta(f+f_c-f_m)]$
```
Note
```
- Carrier Power - $\frac{1}{2} A_c^2$
- Upper Side frequency power - $\frac{1}{8} \mu^2 A_c^2$
- Lower Side frequency power - $\frac{1}{8} \mu^2 A_c^2$
- Total Power in Modulated wave - $[\frac{1}{2}+\frac{1}{4}\mu^2]A_c^2$
- Total power in side band (message part) = $\frac{1}{4} \mu^2 A_c^2$  
- Power efficiency = $\frac{Total ~power ~in ~Side Band}{Total ~Power ~in ~Modulated ~Wave}$ =  $\frac{\mu^2}{2+\mu^2}$  
For $\mu = 1$ power efficiency is 33% .

### Generation of AM Signal
[**Switching Modulator**](https://www.youtube.com/watch?v=tp0GaNKqaaY)
- Asumption
    - $A_c$ is large enough to switch across diode characteristics
    - Diode is an ideal switch .
- $$V_1(t) = A_c Cos(2 \pi f_c t) + m(t)$$
- Assuming $|mt| << A_c$ then, $$V_2(t) \sim  $$
- Thus diode isacting like a switch which is active only for the positive cycle of the Sine wave (carrier).
- $V_2(t) = [A_c Cos(2 \pi f_c t) + m(t)] gt_0$
- Representing $gt_0$ by Fourier series...
- 


**Demodulation of AM Signal**
- **Envlop Detector**
-
- Design Requirments
    - Charging time constant must be shorter than carrier period,$$(r_s + R_f)C<<\frac{1}{f_c}$$
    - Discharging time constant must be larger compared to period of carrier wave , $$R_RC>> \frac{1}{f_c}$$
    - Discharging time constant must be smaller than period of modulating message signal, $$R_RC << \frac{1}{\omega}$$

```
Note
```
- AM modulation is the oldest & cheapest method of modulation.
- Generation
    - Switching Modulator
    - Square law Modulator
- Recovery 
    - Envlop Detector
    - Square law Detector
- AM modulation wastes power in carrier transmission. One band, either lower or upper band can be used
- wasting bandwidth by useing both upper side band & lower side band.
- Above disadvantages can be overcomed by
    - Double sideband supressed carrier
    - Single sideband carrier
    - Vastigial sideband

### Double Sideband Supressed Carrier Modulation

**Generation of DSB-SC**

**Demodulation of DSB-SC**
- **Coherent Detection**
-
- **Coherent DEtection with Phase Shift in Local oscilator**
- 

**Costas Reciever**  
**Quadrature Carrier Multiplexing**  
**Quadrature carrier DEmodulation**





### Single Sideband Modulation
[Yt](https://www.youtube.com/watch?v=0PyLguMXRfc)

**Hilbert Transform**
- Shift the characteristics of a signal by $\pm90\degree$, $$X_h(t) = H[X(t)] = \frac{1}{\pi} \int_{-\infty}^{\infty} \frac{X(k)}{t-k} dk$$
$$= X(t) * \frac{1}{\pi t}$$
- Taking FT both side, $$jX_h(f) = X(f) j Sgn(f)$$

**Generation of SSB Signal**  
[**Phase Shifter Method**](https://www.youtube.com/watch?v=D6IBERQFP3s)  

- [Donald Duck](https://www.youtube.com/watch?v=fQYEQig6O64)  

**Detection of SSB Signal With a Carrier**
- $$\phi_{SSB+C} = A_c Cos(2 \pi f_ct) + [m(t)Cos(2 \pi f_ct)+m_h(t)Sin(2 \pi f_ct)]$$
- If the carrier signal can be extracted by narrow-band-filtering of $\phi_{SSB+C}$ then $m(t)$ can be recovered by `Coherrent detection` .
- Alternatively if the carrier amplitude is large envlope then also $m(t)$ can be recovered using `envelop detection` .
- $$\phi_{SSB+C} = [A_c + m(t)] Cos(2 \pi f_ct)+m_h(t)Sin(2 \pi f_c t)$$
$$=E(t) Cos(e \pi f_c t + \theta)$$
- Where $$E(t) = [[A_c + m(t)]^2 + m_h^2(t)]^\frac{1}{2}$$




























