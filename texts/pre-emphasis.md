# Pré-Ênfase
O primeiro passo é aplicar uma pré-Ênfase. A pré-Ênfase é um processo de redução da amplitude do sinal,
The first step is to apply a pre-emphasis filter on the signal to amplify the high frequencies. A pre-emphasis filter is useful in several ways: 

1. balance the frequency spectrum since high frequencies usually have smaller magnitudes compared to lower frequencies, 
1. avoid numerical problems during the Fourier transform operation and 
1. may also improve the Signal-to-Noise Ratio (SNR).

The pre-emphasis filter can be applied to a signal x using the first order filter in the following equation: