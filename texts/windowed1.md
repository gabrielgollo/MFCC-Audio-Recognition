# Janelamento
After slicing the signal into frames, we apply a window function such as the Hamming window to each frame. A Hamming window has the following form:

$ w[n]=0.54−0.46cos(2πnN−1) $

where, $ 0≤n≤N−1 $, N is the window length. Plotting the previous equation yields the following plot:

There are several reasons why we need to apply a window function to the frames, notably to counteract the assumption made by the FFT that the data is infinite and to reduce spectral leakage.