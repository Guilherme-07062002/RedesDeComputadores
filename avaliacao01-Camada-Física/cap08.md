# Capitulo 8 - Camada Física do Modelo OSI

## Introdução

A camada fisica controla como os dados serão colocados no meio físico da comunicação, ou seja a função dela é codificar os digitos binários em sinais, para poder transmiti-los, seja por um fio de cobre, cabo de fibra óptica ou ondas de rádio.

Ou seja seguindo a ordem das camadas do modelo OSI, a esse ponto os dados já terão sido segmentados pela camada de transporte, colocados em pacotes pela camada de rede e depois encapsulados como quadros pela camada de enlace de dados, **o objetivo da camada física é criar o sinal elétrico, óptico ou frequencial (no caso do wireless) que representem os bits de cada unidade de informação.

E também de forma inversa a camada física também recupera os dados e restaura a informação no destino.

Sendo assim, podemos dizer que de forma semelhante a um "código morse", a camada fisica pega a informação, transmite ela por meio de sinais, dependendo do meio utilizado para que o destino possa receber e decodificar, dessa forma acontece a comunicação.

Dessa forma, exemplificando, em um fio de cobre, os pulsos eletricos representam o 1 e a "pausa" entre eles representa o 0, dessa forma a informação é enviada e transformada novamente em bits no destino, e vice versa.


## Capacidade de transportar dados

Diferentes meios de transmissão suposrtam diferentes velocidades de transferência da informação.

### Largura de banda

Consiste na capacidade de um meio de transportar dados, ou seja a largura de banda mede a quantidade de informações que podem fluir de um lugar para outro durante um determinado tempo.

Exemplo:

- 'Quantos mega(megabytes) tem sua internet?'

- '5 mega (O que quer dizer que sua largura de banda é de 5Mbps ou seja, a transferência é de 5 megabytes de informação por segundo)'

## Cabo de cobre

É o meio fisico mais utilizado, além do cabo de cobre tradicional ou como também é chamado, cabo de pares trançados (muito utilizado em residências), também existe o cabo coaxial: que é um cabo 'blindado' geralmente utilizado em ambientes externos, como por exemplo para realizar a conexão em antenas que fiquem fora de casa, pois eles possuem uma blindagem que os protege contra fatores como chuva ou ventos fortes.

É importante tomar os devidos cuidados pois os cabos não blindados também podem sofrer interferência de campos eletromagneticos, isso costuma acontecer quando se aproxima um ima ou um fio elétrico que passe proximo a ele, pois a eletricidade pode gerar campos eletromagneticos, e estes causam interferência no sinal, chamamos isso de **diafonia** (quando fios se cruzam e causam alguma interferência um no outro).

## Meio fisico de fibra

Geralmente utiliza de vidro ou fibra de plástico para transmitir os bits codificados em pulsos de luz da origem para o destino, ele também suporta taxas de largura de banda maiores.

Uma vantagem da fibra é que ela não sofre interferência de campos eletromagnéticos já que transmite a informação por meio de pulsos de luz.

No entanto ela é mais cara do que o fio de cobre e exige mais cuidados na instalação.

## Meio fisico sem fio

Transmite a informação por meio de ondas eletromagneticas nas frequências de rádio e microondas.

Funciona muito bem em ambientes abertos, no entanto alguns materiais de construção utilizados em prédios e estruturas podem barrar uma parte do sinal causando interferência, isso também pode acontecer por meio de outros dispositivos sem fio que se comuniquem paralelamente na mesma frequência.

Ela também exige que exista mais medidas de segurança já que por não depender de um cabo ou outro meio fisico, na teoria qualquer um pode se conectar, para isso que usuários precisam de senha ou outros artificios para utiliza-la.

Um tipo de conexão wireless (sem fio) é o bluetooth, mas ele foi criado na intenção de ser utilizado na passagem de informação em curtas distâncias.
