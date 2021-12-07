## Banco de Filtros (Mel)

O ouvido humano pussuí uma percepção bem mais apurada para as baixas frequências, não conseguindo identificar pequenas variações nas altas frequências tão bem. Para adaptar o sinal a esta característica é utilizada a escala Mel, que consiste em uma escala logarítmica de frequências definidas pelas seguintes equações:

$m = 2595 \log_{10} (1 + \frac{f}{700})$

$f = 700 (10^{m/2595} - 1)$

Onde $f$ é a frequência em Hz e $m$ é a frequência mel

Para o processamento do sinal de áudio em questão são implementados uma série de filtros triângulares espaçados equidistantemente na escala Mel. Normalmente utiliza-se 40 filtros.

Na escala em Hz os filtros ficarão muito mais próximos uns dos outros nas baixas frequencias do que nas altas, conforme é mostrado no gráfico abaixo:

Saiba mais sobre a [Escala Mel](https://en.wikipedia.org/wiki/Mel_scale).