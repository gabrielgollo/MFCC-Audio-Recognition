## Janelamento

Após fragmentar o sinal é necessário aplicar sobre cada frame uma função de janela. Normalmente utiliza-se a janela Hamming pois ela geralmente apresenta melhores resultados para processamento de voz, porém pode-se escolher qualquer outro tipo de janela que cumpra a mesma função.

A janela Hamming é definida pela seguinte equação:

$ w[n] = 0.54 − 0.46 cos ( \frac{2πn}{N − 1} )\ $

onde, $ 0≤n≤N−1 $, $N$ é a largura da janela em amostras. 

Plotando a equação obtem-se o seguinte gráfico: