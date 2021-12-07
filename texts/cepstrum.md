## Cepstrum

A representação em Cepstrum é a ultima etapa para obtenção dos MFCCs. A origem do termo Cepstrum vem do inglês da palavra espectro. Mudando a ordem das primeiras letras de conceitos comuns no domínio da frequência obtêm-se os seus equivaventes no Cepstrum do sinal.

- **Spec**trum  ⟷ **Ceps**trum
- **Frequ**ency ⟷ **Quefr**ency
- **Fil**tering ⟷ **Lif**tering

O cálculo do Cepstrum é definido pela seguinte equação matemática:

$Cepstrum=FFT^{-1}(log_{10}|FFT(x)|)$

Na construção de MFCCs este cálculo é um pouco diferente. Substituí-se a FFT inversa por uma transformada de cosseno (que é semelhante a uma transformada de Fourier) aplicando essa operação sobre o sinal que passou pelo banco de filtros Mel.

Desta forma obtem-se os coeficientes (MFCC) do sinal que estão exemplificados no gráfico abaixo:

Saiba mais sobre [Cepstrum](https://en.wikipedia.org/wiki/Cepstrum) e sobre a [Transformada discreta de cosseno](https://pt.wikipedia.org/wiki/Transformada_discreta_de_cosseno).