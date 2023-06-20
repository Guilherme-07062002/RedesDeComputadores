# Exercícios capitulo 2

## 1 - Liste 5 dispositivos finais, 6 dispositivos intermediários e 3 formas de meio fisico a rede

* Dispositivos finais: computador desktop, laptop, servidor, PDA, telefone celular, impressora, câmera de segurança, telefone IP, ponrot eletrônico de dispositivo de venda, caixa automático.
* Dispositivo intermediario: repetidor, hub, ponto de acesso sem fio, switch, roteador, modem e firewall.
* Meios fisicos de rede: cabo de cobre, cabo de fibra e ondas de rádio (sem fio)

## 2- Compare e contraste os termos a seguir: rede LAN, WAN, rede interconectada e a internet

* Rede – um grupo de dispositivos interconectados capaz de carregar muitos tipos diferentes de comunicações.
* LAN – uma rede local, ou grupo de redes locais interconectadas que estão sob o mesmo controle administrativo.
* WAN - Prestadores de Serviços de Telecomunicações (TSP) que operam grandes redes regionais abrangendo grandes distâncias. Ou redes que conectam LANs em localizações separadas geograficamente.
* Rede interconectada - Malha de redes LAN e WAN que se comunicam entre si.
* Internet - A rede interconectada de acesso público mais conhecidade e amplamente utilizada. Uma grande interconexão de várias redes ao redor do mundo.
  
## 3- Compare e contraste as camadas do modelo OSI com a pilha de protocolo TCP/IP

Há dois tipos básicos de modelos de rede: modelo de protocolo e modelo de referência.

Um modelo de protocolo segue de forma bem intrinseca um conjunto de aplicações de um determinado protocolo. Ou seja o modelo de protocolo representa as funcionalidades utilizadas para se conectar o humano com a rede de dados. Ou seja o modelo TCP/IP é um modelo de protocolo porque ele descreve as funções de cada camada.

Já o modelo de referência não tem esse proposito, ele tem como principal intuito facilitar a compreensão acerca das camadas do protocolo.

Portanto podemos destacar o quanto os dois se divergem, observando as diferentes formas que os dois modelos representam as camadas de aplicação e redes. O modelo TCP/IP não especifica necessáriamente os protocolos utilizados, ele se foca mais em dizer qual a função utilizada naquela camada, enquanto que o modelo OSI divide a camada especificando quais os protocolos são utilizados detalhadamente, para facilitar a compreensão.

## 4- Explique porque modelos de rede são usados

Apesar dos modelos mais conhecidos serem o OSI e o TCP/IP, programadores de protocolos de rede podem criar os seus próprios protocolos, dessa forma os modelos auxiliam no projeto e desenvolvimento de um novo protocolo.

Além disso eles estimulam a padronização, e dessa forma diferentes fornecedores podem trabalhar juntos,previne mudanças tecnologicas em uma camada que possa afetar a outra, e fornece e uma linguagem comum para descrever as funções e recursos da rede.

## 5- Trabalhe sobre os termos a seguir: protocolo, PDUs e encapsulamento

**Protocolo** é um conjunto pré-determinado de regras que determinam a comunicação entre hosts. Uma comunicação pode exigir vários protocolos trabalhando em conjunto, chamamos isso de um conjunto de aplicações de protocolo. Esses protocolos são implementados nos hosts de destino e origem.

**Encapsulamento**: Quando os dados são passados através da pilha de protocolos, enquanto isso são adicionados informações a ele em cada nivel, isso é conhecido como o processo de encapsulamento.

A forma que um dado assume em cada camada é chamado de **PDU (Unidade de dados de protocolo)**, em cada fase do processo a PDU recebe um nome diferente.

Abaixo estão listadas as PDUs dentro do conjunto de aplicações do protocolo TCP/IP:

* Dados - Camada de aplicação
* Segmento - Camada de transporte
* Pacote - Camada de rede
* Quadro - Camada de acesso a rede

## 6- Explique o encapsulamento comparando com o processo de envio de uma carta

Páginas individuais são escritas enumeradas e envelopadas, em seguida cada envelope é separado e enviado para o destinatario.

Para isso eles são guardados em malas postais e transportados por meio de vans.

Ao longo do caminho pode ser necessário transferir as malas para outras vans, ou diferentes meio de transporte, e também pode ser preciso tomar rotas diferentes.

Por fim o pacote é recebido pelo destino, e desempacotado, dessa forma é possivel visualizar a carta.

## 7- Quais são os únicos papeis dos endereços das camadas 2, 3 e 4?

* Camada 4 (portas) - identificam os aplicativos individuais enviando ou recebendo dados.
* Camada 3 (lógicos) - Identificam dispositivos e suas redes;
* Camada 2 (fisicos) - Identificam dispositivos em uma rede local
