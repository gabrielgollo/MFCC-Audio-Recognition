## Pré-Ênfase

O primeiro passo é aplicar um filtro de pré-ênfase. A pré-ênfase é um processo de normalização da amplitude do sinal e balanceamento do espectro. Este procedimento possuí várias vantagens, como por exemplo: 

1. Balancear a as frequências do sinal, já que altas frequências custumar ter amplitudes menores ; 
1. Evitar erros numéricos durante o cálculo da FFT ;
1. Melhora a [relação sinal-ruído](https://pt.wikipedia.org/wiki/Relação_sinal-ruído).

Obtém a pré-ênfase do sinal aplicando-se a seguinte equação no sinal (x) de áudio bruto:

$y(t)=x(t)-\alpha x(t-1)$