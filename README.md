
Setting up
* https://ranous.files.wordpress.com/2020/05/rtl-sdr4linux_quickstartguidev20.pdf

PySDR
* SDR: radiou that uses software to perform signal-processing tasks that were traditionally performed by hardware
* dsp: digital processing of signals, in this case RF
* Recommended SDR textbook: https://www.analog.com/en/education/education-library/software-defined-radio-for-engineers.html
* https://ubuntu.com/blog/introduction-to-open-source-private-lte-and-5g-networks

## Frequency Domain

* Think in the frequency domain
* Audio equalizer
* Frequency domain: any signal can be represented by sine waves summed together
* amplitude, phase, frequency
* impulse
* Fourier properties: linearity, frequency shift, scaling in time, convolution in time, convolution in frequency
* fftshift (center frequencies around 0)
* windowing: Fourier expects periodic signal; windowing ensures beginning and start of signal connect (Hmaming, Hanning, Blackman, Kaiser, rectangular window: multiplying by array of ones / do nothing)