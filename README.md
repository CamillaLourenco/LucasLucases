# Algoritmo de Huffman em C
Este repositório contém uma implementação do algoritmo de Huffman em C para compactação de dados.

## Funcionamento
O algoritmo de Huffman funciona através da criação de uma árvore binária com base nas frequências de ocorrência dos símbolos da mensagem a ser compactada. Cada símbolo é representado por um nó na árvore, e os caminhos até cada símbolo são utilizados como códigos de compressão. Os símbolos com maior frequência de ocorrência ficam mais próximos da raiz da árvore, enquanto os símbolos com menor frequência ficam mais distantes. Dessa forma, os códigos dos símbolos mais frequentes tendem a ser mais curtos, o que resulta em uma compressão mais eficiente.

## Benefícios
Aumento da eficiência de armazenamento de dados: a compactação de dados permite que mais informações sejam armazenadas em menos espaço, o que é especialmente útil para aplicações que lidam com grandes volumes de dados.

Redução de tempo de transmissão de dados: ao enviar dados compactados, menos tempo é gasto na transmissão, o que é benéfico para aplicações que lidam com dados em tempo real ou em larga escala.
Segurança de dados: a compactação de dados também pode ser usada como uma técnica de criptografia para proteger informações confidenciais.

## Utilização
Este algoritmo de Huffman pode ser utilizado em várias aplicações, tais como:

Compactação de arquivos: para reduzir o tamanho de arquivos de imagem, vídeo, música, entre outros.
Transmissão de dados: para aumentar a velocidade de transmissão de dados em redes.
Armazenamento de dados: para aumentar a eficiência do armazenamento em dispositivos de armazenamento.
Espero que essa informação adicional ajude a esclarecer o propósito e aplicações do projeto de algoritmo de Huffman em C. Se você tiver alguma outra dúvida, estou sempre aqui para ajudar.

## Instalação

1. Clone este repositório para sua máquina:

git clone  https://github.com/iLucasPires/minishell.git 

2. Entre na pasta 42Labs:

cd 42Labs/

3. Compile o código com o comando:

make


## Como usar

Para usar o programa de compactação, use o seguinte comando:


./encoder_program -help

Isso irá exibir as opções de uso disponíveis.

## Sobre o projeto
Este projeto foi construído em sete etapas:
1. **Fase 1 - Estudo:** //Neste passo, é realizada uma pesquisa para compreender o objetivo do projeto, os desafios enfrentados e as habilidades necessárias para completar a tarefa. //Neste passo, é realizada uma pesquisa para compreender o objetivo do projeto, os desafios enfrentados e as habilidades necessárias para completar a tarefa. Nesta fase, é importante estudar sobre o algoritmo de Huffman, sua funcionalidade e aplicações para entender como implementá-lo corretamente.

2. **Fase 2 - Construção das principais estruturas de dados:** //Nesta etapa, são criadas as estruturas fundamentais para o algoritmo, como a árvore Huffman e o mapa de símbolos. // Nesta etapa, são criadas as estruturas fundamentais para o algoritmo, como a árvore Huffman e o mapa de símbolos. A árvore Huffman é construída a partir da análise da mensagem a ser compactada, registrando o número de ocorrências de cada símbolo e criando nós para cada símbolo. O mapa é criado para armazenar os códigos dos símbolos.

3. **Fase 3 - Entendendo Encode / Decode:** // Nesta fase, as funções para codificar e decodificar os dados são implementadas. // Nesta fase, as funções para codificar e decodificar os dados são implementadas. A codificação é feita através da utilização dos caminhos na árvore Huffman para representar cada símbolo, enquanto a decodificação consiste em percorrer a árvore para descobrir qual símbolo representa cada caminho.

4. **Fase 4 - Compactando / Descompactando:** // Neste passo, os dados são efetivamente compactados e descompactados. //  Neste passo, os dados são efetivamente compactados e descompactados. A compactação é feita através da substituição dos símbolos da mensagem original pelos códigos correspondentes na árvore Huffman, enquanto a descompactação é feita através da utilização do mapa de símbolos para recuperar os símbolos originais a partir dos códigos.

5. **Fase 5 - Compartilhando memória:** // Nesta etapa, o algoritmo é otimizado para compartilhar memória entre as diferentes estruturas de dados. // Nesta etapa, o algoritmo é otimizado para compartilhar memória entre as diferentes estruturas de dados, a fim de reduzir o consumo de memória e tornar o algoritmo mais eficiente.

6. **Fase 6 - Aplicando Fase 3 e 4 no novo programa:** // Neste passo, as funções de codificação e decodificação são aplicadas em um novo programa. // Neste passo, as funções de codificação e decodificação são aplicadas em um novo programa que irá utilizar o algoritmo de Huffman para compactar e descompactar dados.

7. **Fase 7 - MVP:** // O projeto é considerado concluído quando atinge o MVP (produto mínimo viável). // O projeto é considerado concluído quando atinge o MVP (produto mínimo viável), isto é, quando o algoritmo consegue realizar a compactação e descompactação de dados com eficiência e qualidade satisfatória.

------- Exemplos de aplicação:

- Uma aplicação de compactação de arquivos de imagem, onde o algoritmo de Huffman é utilizado para reduzir o tamanho dos arquivos antes de serem salvo ou transmitido
- Um sistema de transmissão de dados em redes, onde o algoritmo é utilizado para compressão dos dados antes de serem enviados, tornando a transmissão mais rápida e eficiente.
- Um sistema de armazenamento de dados, onde o algoritmo é utilizado para compactar os dados antes de serem salvos, aumentando a capacidade de armazenamento.
