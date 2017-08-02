# Especificação do Projeto

-> CONTEÚDOS ABORDADOS: 

Gerenciamento de Memória : políticas de substituição de páginas

Composição do projeto para avaliação:

Código Fonte

Arquivo de saída

Apresentação

# Informações gerais

Composição dos Grupos: 3 pessoas

Peso do projeto na média da 2ªVA: 20% da média

Data de Entrega: 22/08

Data de Apresentação: 22/08


# Descrição do Projeto

O projeto consistirá na Implementação de 2 (dois) algoritmos de substituição de páginas.

 

# Entradas

O programa desenvolvido deverá ler dois arquivos, um de configuração de memória e outro com as requisições de alocação de página.

O arquivo de configuração da memória será dado por uma linha com definição de tamanho da memória e tamanho das páginas, ambos em Kb. Com base nesses dados, o programa deverá gerar a memória com as informações passadas, calculando a quantidade de páginas disponíveis. As demais linhas da entrada será com a alocação desta memória, informando número da página, nome do processo,instante de tempo em que foi armazenada, instante de tempo de última referência e os bits de referenciado e modificado.

O arquivo com as requisições será composto por um conjunto de linhas onde cada linha representará uma requisição, informando o nome do processo por um caracter e tamanho da requisição (para cálculo de quantidade de páginas a serem alocadas) em Kb.

# Exemplo de entrada:

-> Arquivo de configuração da memória

256;8

0 A 95 130 0 0 

1 B 110 135 1 0

3 C 235 340 0 1

4 A 300 300 1 1 

-> Arquivo de requisições

A 8

C 30

D 14

E 6


# Saídas

A saída do projeto é um arquivo composto por uma tabela com as páginas da memória, onde cada página deverá ter as seguintes informações: Alocada ("Vazio" para não alocada ou Nome do processo, quando alocada) ; Tempo de Chegada; Tempo da Última Referência; R (referenciada); M (modificada).

# Apresentação

A apresentação será composta por uma explanação dos algoritmos e implementação dos mesmos seguido de uma demonstração com um arquivo de entrada disponibilizado no dia da apresentação.

Tempo máximo de apresentação: 20min.

Tempo mínimo de apresentação: 15min.

 

Grupos x Temas

Grupo 1: 

FIFO
RELÓGIO

Grupo 2: 

SEGUNDA CHANCE
NRU

Grupo 3:

FIFO
LRU

Grupo 4: 

SEGUNDA CHANCE
RELÓGIO
