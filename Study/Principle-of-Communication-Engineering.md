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



### Single Sideband Modulation
[Yt](https://www.youtube.com/watch?v=0PyLguMXRfc)

**Generation of SSB Signal**  
[**Phase Shifter Method**](https://www.youtube.com/watch?v=D6IBERQFP3s)  
**Detection of SSB Signal With a Carrier**
- $$\phi_{SSB+C} = A_c Cos(2 \pi f_ct) + [m(t)Cos(2 \pi f_ct)+m_h(t)Sin(2 \pi f_ct)]$$
- If the carrier signal can be extracted by narrow-band-filtering of $\phi_{SSB+C}$ then $m(t)$ can be recovered by `Coherrent detection` .
- Alternatively if the carrier amplitude is large envlope then also $m(t)$ can be recovered using `envelop detection` .
- $$\phi_{SSB+C} = [A_c + m(t)] Cos(2 \pi f_ct)+m_h(t)Sin(2 \pi f_c t)$$
$$=E(t) Cos(e \pi f_c t + \theta)$$
- Where $$E(t) = [[A_c + m(t)]^2 + m_h^2(t)]^\frac{1}{2}$$




























