# Anotações 1° Avaliação

## Capitulo 2 - Comunicando-se pela rede

### Elementos da comunicação

A comunicação se inicia com uma informação ou mensagem que deve ser enviada de um individuo (ou dispositivo) para outro. As pessoas trocam ideias usando vários metodos de comunicação diferentes e todos esses métodos possuem três elementos em comum.

* O primeiro desses elementos é a origem da mensagem, ou remetente, que precisam enviar uma mensagem a outros individuos ou dispositivos.

* O segundo elemento é o destino, ou receptor, que recebe a mensagem e a interpreta.

* O terceiro elemento, chamaremos de canal, consiste no meio que fornece o caminho sobre o qual a mensagem poderá transitar da origem para o destino.

### Comunicando as mensagens

Em teoria uma única informação poderia ser enviada como um único fluxo massivo e continuo de bits, no entanto se as mensagens fossem realmente transmitidas dessa maneira, nenhum outro dispositivo poderia utilizar a mesma rede enquanto os dados circulassem, e isso resultaria em atrasos consideráveis.

Uma melhor abordagem encontrada foi dividir a mensagem em pedaços menores, essa divisão é chamada de **segmentação**. Segmentar gera dois grandes benefícios:

* Ao enviar pedaços menores, vários dispositivos podem conversar ao mesmo tempo de forma intercalada na mesma rede, processo de intercalar os pedaços em diferentes caminhos é denominado **multiplexação**.

* A segmentação aumenta a confiabilidade das comunicações, tendo em vista que cada mensagem não irá precisar necessariamente percorrer o mesmo caminho, dessa forma não há perigo de congestionamento. E caso alguma parte da mensagem falhe, apenas aquilo que foi perdido precisará ser reenviado.

No entanto o aspecto negativo de se utilizar a **multiplexação** e a **segmentação** é o nível de complexidade envolvida. Imagine se você tivesse de enviar 100 páginas mas cada envelope envolve apenas uma, o processo demandaria muito tempo.

Em comunicações de rede cada mensagem passa por um processo similar ao de o empacotamento de uma carta, para garantir que se chegue ao seu destino.

### Componentes da rede

O caminho que uma mensagem vai utilizar para chegar ao seu destino pode ser tão simples como um único cabo, ou tão complexo quanto uma rede que atravessa todo o planeta.

Dentre esses meios, existem o meio físico (mídia) que se constituem de componentes vísiveis como: Switch, cabos, um computador ou laptop, etc... No entanto o meio físico também pode ser invisível como no caso o ar, com a utilização de frequência de rádio e ondas eletromagneticas.

Além disso existem os serviços de rede, que são serviços que fornecem uma informação de resposta a alguma requisição ou solicitação.
Serviços incluem muitas das aplicações que utilizamos durante o dia-a-dia, como um serviço de hospedagem de e-mails ou serviços de hospedagem na nuvem.

### Dispositivos finais e seu papel na rede

Os dispositivos finais são aqueles que utilizamos e fornecem a interface entre a rede e nós humanos.
Alguns exemplos de dispositivos finais:

* Computadores
* Impressoras
* Camêras de segurança
* Celulares

No contexto de rede chamamos dispositivos finais de hosts, existem hosts de origem e de destino, podemos destinguir um do outro apartir do seu endereço, quando um host inicia a comunicação ele usa o endereço do outro host (de destino), para especificar aonde a mensagem deverá chegar.

Um host pode agir como um cliente ou servidor, ou ambos, o software instalado determina o seu papel.

* Servidores são hosts cujo o software instalado costuma ser especializado em **fornecer** informações ou serviços, como e-mail, ou páginas web a outros hosts.
* Clientes são hosts cujo software instalado é focado em solicitar e exibir as informações obtidas no servidor.
  
### Dispositivos intermediários e seu papel na rede

Fornecem conectividade e operam por trás do cenário de rede para garantir que as mensagems possam trafegar. Esses dispositivos conectam os hosts entre si.
Exemplos:

* Dispositivos de acesso a rede (Hubs, switchs e pontos de acesso sem fio)
* Roteadores
* Modems
* Firewalls

Além disso, eles também realizam o gerenciamento de dados enquanto eles fluem. Eles utilizam o endereço de destino além de um conjunto de informações para determinar qual o melhor caminho pelo qual a mensagem deve trafegar por meio de processos que são executados nestes dispositivos que executam as seguintes funções:

* Regenerar e retransmitir sinais
* Manter informação sobre quais caminhos existem pela rede
* Notificar outros dispositivos acerca de erros e falhas de comunicação
* Direcionar mensagens por caminhos alternativos quando necessário.
* Classificar e direcionar mensagems de acordo com prioridades (QoS)
* Permitir ou negar fluxo de dados

#### Tipos de meio físico

* Cabos de fios metalicos
* Fibra óptica
* Transmissão sem fio (wireless)

A codificação de sinal que ocorre em cada meio fisico é diferente, em fios metálicos os dados são enviados por meio de impulsos elétricos, já em fibra optica são passados por meio de feixes de luz, e em transmissões sem fio a comunicação acontece por meio de ondas eletromagnéticas que representam os valores de bit.

Diferentes meios físicos possuem diferentes características e individualidades, alguns são mais eficientes a grandes distâncias, outros são mais resistentes em ambientes externos, enquanto alguns são melhores quando há a necessidade de trafegar uma grande quantidade de dados, além disso cada um possui um custo especifico para o uso e instalação.

### Redes de área local

Uma Rede Local (ou **LAN**) geralmente se espalha por uma única área, fornecendo serviços para um determinada região, como por exemplo a rede de um campus, e costuma ser administrada por uma única organização.

### Redes de longa distância

Chamamos de **WAN** redes de longas distâncias que interconectam LANs, ou seja, quando uma empresa possui filiais que são separadas por grandes distâncias, pode ser necessário usar um provedor de telecomunicações para realizar a interconexão entre essas redes locais, e é ai que WAN entra.

### Intranet

Termo usado para se referir a conexões privadas, que pertencem a alguma organização específica que e só pode ser acessado por funcionários ou membros desta.

### Internet - Uma rede de redes

A internet pode ser definida como uma grande interconexão entre redes LAN e WAN, ou seja é um grande conglomerado de redes interconectadas que se comunicam entre si, permitindo o fluxo e passagem de informação a milhões de usuários ao redor do mundo.
