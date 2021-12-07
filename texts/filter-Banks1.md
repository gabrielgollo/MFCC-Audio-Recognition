## Banco de Filtros (Mel)

O ouvido humano pussuí uma percepção bem mais apurada para as baixas frequências, não conseguindo identificar pequenas variações nas altas frequências tão bem. Para adaptar o sinal a esta característica é utilizada a escala Mel, que consiste em uma escala logarítmica de frequências definidas pelas seguintes equações:

$m = 2595 \log_{10} (1 + \frac{f}{700})$

$f = 700 (10^{m/2595} - 1)$

Onde $f$ é a frequência em Hz e $m$ é a frequência mel

The final step to computing filter banks is applying triangular filters, typically 40 filters, nfilt = 40 on a Mel-scale to the power spectrum to extract frequency bands. The Mel-scale aims to mimic the non-linear human ear perception of sound, by being more discriminative at lower frequencies and less discriminative at higher frequencies. We can convert between Hertz (f) and Mel (m) using the following equations:

Each filter in the filter bank is triangular having a response of 1 at the center frequency and decrease linearly towards 0 till it reaches the center frequencies of the two adjacent filters where the response is 0, as shown in this figure:


Saiba mais sobre a [Escala Mel](https://en.wikipedia.org/wiki/Mel_scale).