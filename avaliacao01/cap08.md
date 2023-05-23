# Capitulo 8 - Camada Física do Modelo OSI

## Introdução

A camada fisica controla como os dados serão colocados no meio físico da comunicação, ou seja a função dela é codificar os digitos binários em sinais, para poder transmiti-los, seja por um fio de cobre, cabo de fibra óptica ou ondas de rádio.

Ou seja seguindo a ordem das camadas do modelo OSI, a esse ponto os dados já terão sido segmentados pela camada de transporte, colocados em pacotes pela camada de rede e depois encapsulados como quadros pela camada de enlace de dados, **o objetivo da camada física é criar o sinal elétrico, óptico ou frequencial (no caso do wireless) que representem os bits de cada unidade de informação.

E também de forma inversa a camada física também recupera os dados e restaura a informação no destino.

Sendo assim, podemos dizer que de forma semelhante a um "código morse", a camada fisica pega a informação, transmite ela por meio de sinais, dependendo do meio utilizado para que o destino possa receber e decodificar, dessa forma acontece a comunicação.

Dessa forma, exemplificando, em um fio de cobre, os pulsos eletricos representam o 1 e a "pausa" entre eles representa o 0, dessa forma a informação é enviada e transformada novamente em bits no destino, e vice versa.
