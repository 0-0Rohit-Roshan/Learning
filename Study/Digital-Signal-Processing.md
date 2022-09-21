<details>
<summary>Signal</summary> 

- [CLASSIFICATION of SIGNALS](https://www.youtube.com/watch?v=L19p9Qa_Wlg)
- Uniform Sampler & Non Uniform Sampler
- Quantisation
- Periodic & Aperiodic Signal
- Even & Odd Signal `Significance`
- Discrete & Continuous Signal (System) `Significance`
- `Del(n)` `U(n)` `h(n)`
- Discrete Signal Transformation.
- Convolution Formula
</details>
<details>
<summary>System</summary>

- LInear , NonLinear System
- Superposition Principe in system
- Unit Response output of system
- Time Variant Time Invariant System
- Causal  , Non Causal System
- Causality in terms of impulse response
- Stable system , Unstable system
- Recursive , Non Recursive System.
- Feedback , Feedforward System Comparision
- Spectrum of Signal
- nfs frequency
- Filtering in Spectrum domain 
- Continuos signal frequency period
- Spectrum of discrete time signal
- relation between continuous time frequency and discrit time frequency.
- Damping Factor
- H transform
- Implimentation of discrite time sysytem
    - Stability function
- Properties of convolution
- convoltion clock

</details>
<details>
<summary>Correlation</summary>

**Correlation**
- Types

Cross-correlation|Auto-Correlation|Circular-correlation
--|--|--
Two different Signals `X` & `Y` , Cross-correlation $r_{xy}$|
- Corelation Coefficient
</details>


<details>
<summary>### Z-Transform</summary>

- S-Transform - Continuous System
- Z-Transform - Discrete System
- [Pole zero plot, Transfer function, Difference equation, Stability, Impulse & Step Response](https://www.youtube.com/watch?v=CE_h0gqgGV4)
- [Region of Convergence (ROC) - z transformtion |finite and infinite signals|](https://www.youtube.com/watch?v=0oYrhk8vWF4)

<details>
<summary>Properties</summary>


1. Linearity  
2. Time Shifting  
3. Folding  
4. Scaling  
5. Differentiation in Z-Domain  
6. Convolution  
7. Correlation 

</details>
<details>
<summary>How Pole Location affects the response</summary>

- Poles should be inside the unit circle for the system to be stable.

</details>

<details>
<summary>Difference Equation</summary>

### Difference Equation 
- [Yt](https://www.youtube.com/watch?v=LdeOHgcoxT4)
- General formula $$Y(n) = Y_h(n) + Y_p(n)$$
</details>
</details>











## MCQ
<details>
<summary>MCQ</summary>

1. What is the solution called when the input of the system is assumed to be zero? 

A. Complete solution
B.General solution
C. Homogeneous solution
D. Particular solution 

Answer: C

2. How is the complete solution of any difference equation given?

A. yp(n) – yh(n)
B. yp(n) * yh(n)
C. yp(n) + yh(n)
D. yh(n) – yp(n)

Answer: C

3. Let x(n) be the input signal, y(n) be the response, and h(n) be the unit sample response of the system. What is the relation given by

A. Convolution difference
B. Convolution sum
C. Convolution product
D. Convolution division

Answer: B

4. What is the correct sequence of procedures to perform on h(n) to convolute x(n) and y(n)?

Folding shifting multiplication with x(n)summation
Multiplication with x(n)summation folding shifting
Summation folding shifting multiplication with x(n)
Shifting summation folding multiplication with x(n)

Answer: 1

5. What is the necessary condition for an LTI system to be causal in nature?

A. For negative value of n, impulse response should be non-zero
B. For positive value of n, impulse response should zero
C.For negative value of n, impulse response should be zero
D. For positive value of n, impulse response should be non-zero

Answer: C

6. What is the value of discrete-time signal x(n) for the value of n being non-integer?

A. Positive
B. Negative
C. Undefined
D. Zero

Answer: C

7. How is the unit ramp signal defined in discrete-time function?

A. u(n)=n for n≥0;u(n)=0 for n<0   
B. u(n)=n for n≤0;u(n)=0 for n>0   
C. u(n)=n for n>0;u(n)=0 for n≤0   
D. None of these

Answer: A

8. What is the condition for a real-valued signal to be antisymmetric in nature?

A. x(n)=-x(n)
B. x(n)=x(-n)
C. x(n)=-x(-n)
D. None of these

Answer: C

9. What is another term used for time scaling operation in digital signal processing?

A. Upsampling
B. Downsampling
C. Convolution
D. Quantisation

Answer: B

 Which of the following functions represents impulse function?

A. x(n)=n for n≥0;x(n)=0 for n<0
B. x(n)=1 for n=0;x(n)=0 for n≠0 
C. x(n)=0 for n=0;x(n)=1 for n≠0
D. x(n)=n for n≤0;x(n)=0 for n>0

Answer: B

The autocorrelation of a discrete signal x(n) is represented by which of the given equations?

A. rxy(l)=x(l)-x(-l)
B. rxy(l)=x(l)+x(-l)
C. rxy(l)=x(l)x(-l)
D. rxy(l)=x(l)x(l)

Answer: C

 Which of the following is the type of discrete system?

A. Non-causal systems
B. Recursive systems
C. Dynamic systems
D. All of the above

Answer: D

What is another term used for two-sided Z transform?

A. Bilateral Z-transform
B. Unilateral Z-transform
C. Trilateral Z-transform
D. None of these

Answer: A

What is zero padding technique?

A. Zeroes are added at the end of the sequence to make the number of samples equal to a power of two. 
B. Zeroes are added at the start of the sequence to make the number of samples equal to a power of two. 
C. Zeroes are added anywhere in between the sequence to make the number of samples equal to a power of two. 
D. None of the mentioned. 

Answer: A

How many complex additions are needed for 16 direct computations in discrete Fourier transform?

A. 56
B. 240
C. 756
D. 32

Answer: B
Solution- number of total complex additions = N(N – 1)
N = 16
Complex additions = 16(16 – 1) = 240

Which of the following statements is invalid about linear convolution?

A. It needs zero padding.
B. The sequence length of input and output is the same.
C. The input and output sequence is aperiodic.
D. All the above statements are valid.

Answer: B

17. In the divide and conquer approach, the equation to calculate total complex additions is ________

A. N (M + L + 2)
B. N (M + L – 3)
C. N (M + L – 2)
D. N (M – L + 1)

Answer: C

Which of the following properties is correct for FIR (Finite Impulse Response) filters?

A. FIR filters are generally canonical
B. FIR filters are not always stable
C. FIR filters require less memory than IIR filters
D. FIR filter’s linear phase realisation structure can not be designed easily

Answer: A

19. Which technique is used to obtain a discrete-time signal from a continuous-time signal?

A. Differentiating
B. Convolution
C. Integrating
D. Sampling

Answer: D

20. What is the method of joining steps in the digital to analogue conversion known as?

A. Quadratic interpolation
B. Staircase approximation
C. Linear interpolation
D. None of the above

Answer: B

21. What should be the minimum frequency of sampling to avoid aliasing?

A. F/2  ( here, F is the analogue signal frequency)
B. F
C. 2F
D. 4F

Answer: C

22. Which of the following factors provides the quality of output from the A/D converter?

A. Quantisation to signal noise ratio
B. Signal to quantisation noise ratio
C.Quantisation error
D. None of the above

Answer: B

23. In RADAR signal application, which of the following elements is unnecessary?

A. Digital signal processor
B. A/D converter
C. D/A converter
D. All of the above

Answer: C

24. Which of the following correctly represents the Z-transform X(z) of a discrete-time signal x(n)?


Answer- A

25. For a sequence of finite duration with anti-causal property, the Z-transform ROC is ________

Entire z-plane, except at z = ∞
Z = 0
Entire z-plane, except at z = 0
Z = ∞

Answer- A

26. In which condition of ROC is a linear time-invariant system called BIBO stable? 

The ROC of the system is a unit circle
The ROC of the system includes unit circle
The ROC of the system excludes unit circle
D. None of the above

Answer- B

27. Which of the following equations represents a periodic signal x(t)’s average power?


Answer: A

28. Which of the following system functions represents an all pass filter?

A. H(z)=zk
B. H(z)=z-k
C. H(z)=z1/k
D. H(z)=z2k

Answer: B

29. In an invertible system, _____

A. The input and output signals have many to one correspondence
B. The input and output signals have many to many correspondences
C. The input and output signals have one to many correspondences
D. The input and output signals have one to one correspondence

Answer: D

30. In which of the following applications digital signal processing is used?

A. Space applications
B. Biomedical applications
C. Video processing
D. All of the above

Answer: D

31. Which of the following is/are common applications of IIR filters?

A. Audio equalisation
B. IoT/IIoT smart sensors
C. High-speed RF applications
D. All of the above

Answer: D

32. In the Overlap add method to compute N point DFT, M-1 zeroes are added _________.

A. At the first of each data block
B. At the last of each data block
C. In between the data block
D. No zeroes are added

Answer: B

33. In a single complex-valued multiplication, the number of quantisation errors is ______.

A. Three
B. Four
C. Seven
D. Two 

Answer: B

34. In a logarithmic scale, the Signal-to-Quantisation Noise ratio is expressed as _______.


Answer:D

35. What is the nature of truncation error in the case of representation of a number in two’s complement?

A. Zero
B. Always positive
C. Always negative
D. Can’t say

Answer: C

36. In which of the following transformations, the poles of the transformation and the poles of matched z-transform are identical?

A. Impulse transformation
B. Approximation of derivatives
C. Bilinear transformation
D. None of the above

Answer: A

37. Which of the following is/are the frequent applications of Hilbert transform?

A. Bandpass signals representation
B. SSB signals generation
C. Minimum phase type filter designing
D. All of the above

Answer: D

</details>





















