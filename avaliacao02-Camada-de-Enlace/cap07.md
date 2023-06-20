# Capitulo 7

## Recapitulação

O modelo OSI divide as funções de uma rede em camadas:

* A camada de aplicação fornece a interface para o usuário
* A camada de transporte é responsável pela divisão e gerenciamento das comunicações entre os processos que são executados entre os hosts
* Os protocolos da camada de rede organizam os dados da comunicação para que eles possam viajar através da conexão entre host de origem e destino.

Para que os pacotes da camada de rede cheguem ao destino a informação pode trafegar por diferentes meios físicos.

Podemos dizer que a camada de enlace do modelo OSI prepara os pacotes da camada de rede para que eles possam ser transmitidos pelo meio fisico.

A PDU (Unidade de dado de protocolo) da camada de enlace é o quadro.

Vamos imaginar a seguinte situação, dois computadores desejam se comunicar, um de Paris e outro do Japão.

Por mais que os dois se comuniquem usando o mesmo protocolo de rede (IP por exemplo), serão necessários inúmeros protocolos da camada de enlace para que a informação chegue ao destino, tendo em vista a quantidade de meios fisicos e dispositivos intermediários de rede diferentes, pelos quais a informações terá que trafegar para chegar ao destino.