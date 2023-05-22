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
  