# Repositório de apoio à formação de redes, modelo OSI
## Por [Duarte Pedro Pinto](https://dpnpinto.github.io)
O objetivo desta formação é oferecer uma compreensão teórica e prática do funcionamento de cada camada do modelo OSI, através de uma análise detalhada de seus componentes.
Aqui serão colocados exemplos utilizados nesta formação, de forma a que os formandos possam, de uma forma prática, testar os conhecimentos adquiridos.
## O que é o modelo OSI ?
O Modelo OSI (Open Systems Interconnection) é um modelo desenvolvido pela ISO (Internation Standart Organization) que tem um conjunto de regras que explica como diferentes sistemas comunicam através de uma rede. O Modelo OSI consiste em 7 camadas, cada uma com funções e responsabilidades específicas.

Esta abordagem em camadas facilita a interoperabilidade entre diferentes dispositivos e tecnologias. O Modelo OSI fornece uma estrutura clara para a transmissão de dados e gestão de problemas de rede. O Modelo OSI é amplamente utilizado como referência para compreender o funcionamento dos sistemas de rede.

Vamos discutir o Modelo OSI e vamos abordar cada uma das camadas do Modelo OSI em detalhe. Vamos também discutir o fluxo de dados no Modelo OSI e como o Modelo OSI é diferente do Modelo TCP/IP.

## Camadas (layers) do modelo OSI
Como referido existem sete (7) camadas no modelo OSI, cada uma das quais tem uma tarefa especifica de tratamento da informação. São as indicadas infra:

- Fisica (Layer 1)
- Ligação (Layer 2)
- Rede (Layer 3)
- Transporte (Layer 4)
- Sessão (Layer 5)
- Apresentação (Layer 6)
- Aplicação (Layer 7)

## Camada 1 – Camada Física

A camada mais ao nivel dos componentes de ligação fisica do modelo de referência OSI é a Camada **Física**. É responsável pela conexão física, real, entre os dispositivos. A camada física contém informação na forma de bits. A Camada Física é responsável por transmitir bit'ss individuais de um nó da ligação para o próximo. Ao receber dados, esta camada recebe o sinal e converte-o em binário, 0s e 1s, e envia-os para a Camada de Ligação de Dados, que irá recompor a trama. Dispositivos comuns da camada física são Hub's, Repetidores, Modem's e Cabos.

### Funções da Camada Física

- Sincronização de Bits: A camada física fornece a sincronização dos bits. Recorrendo a um relógio que controla tanto o emissor como o receptor, proporcionando assim sincronização ao nível do bit.
- Controlo da Taxa de Bits: A Camada Física também define a taxa de transmissão, ou seja, o número de bits enviados por segundo.
- Topologias Físicas: A camada física especifica como os diferentes dispositivos/nós estão organizados numa rede, ou seja, por topologia de barramento, topologia em estrela, em canal.
- Modo de Transmissão: A camada física também define como os dados fluem entre os dois dispositivos conectados. Os vários modos de transmissão possíveis são Simplex, Half-duplex e Full-duplex.
