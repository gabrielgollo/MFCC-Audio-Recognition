## Framing/Fragmentação

Esta etapa consiste em fragmentar o sinal, anteriomente longo, em vários sinais curtos. Isto é feito com o objetivo de analisar separadamente as informações do domínio da frequência, tendo em vista que as conponentes frequênciais mudam ao longo do sinal. Analisar uma transforma de Fourier do sinal completo não faz sentido neste caso pois as informações iriam se misturar dificultando a compreeensão.

Na próxima etapa será realizada uma transformação que resultará na atunuação das extremidades de todos os frames. Para que isto não cause perdas de informação, os frames são cortados de maneira a deixar uma interseção entre um fragmento e seu sucessor.

Configurações comuns utilizam um quadro que abranja 25 ms sendo os primeiros 10 ms uma repetição do final do quadro anterior.