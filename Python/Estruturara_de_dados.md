


## Estrutura de dados

São a forma como os dados sao agregados e organizados.
Depende de como queremos transformar com nosso algoritmo. Qual nosso objetivo?a estrutura de dados depende do nosso objetivo
- Ajuda a limpar e organizar dados
- Traz eficiencia em buscas, complexidade, relacionamentos entre dados, diversas formas de organização.
Em Python existem dois tipos de estruturas de dados:

 - SEQUENCIAS = são objetos ordenados e finitos (strings, listas e tuplas)  
  - DICIONÁRIOS =  são conjuntos de elementos de mapeamento    indexados por chaves.

## Pilha
 política “último a entrar, primeiro a sair”)
   
## Fila
FIFO (First In First Out), ou seja, o primeiro que entrar será o primeiro a sair. primeiro da fila

## Tupla

 - (tupla) != [lista]  
 - depois de criada nao altera as infos dentro, são
   valores fixos. 
   listas --> sequências  homogêneas,
   tuplas -->são estruturas de dados  heterogêneas.
#### Tuplas x Listas

As tuplas possuem algumas vantagens com relação às listas, que são:

-   Como as tuplas são imutáveis, a iteração sobre elas é mais rápida e, consequentemente, possuem um ganho de desempenho com relação às listas;
-   Tuplas podem ser utilizadas como chave para um dicionário, já que seus elementos são imutáveis. Já com a lista, isso não é possível;
-   Se for necessário armazenar dados que não serão alterados, utilize uma tupla. Isso garantirá que esses sejam protegidos de alterações posteriores.
https://www.treinaweb.com.br/blog/principais-estruturas-de-dados-no-python


## Sets

 - coleção de itens desordenada 
 - parcialmente imutável 
 - não contem    duplicados

Por ser parcialmente imutável, os sets possuem permissão de adição e remoção de elementos.

 - são utilizados, normalmente, com operações matemáticas de união, interseção e diferença simétrica
 
 - ## Dicionários
 - são conjuntos de elementos de mapeamento  indexados por chaves únicas
 - coleções de itens desordenados atrelados a um identificados único(chave)
 -  muito utilizado quando queremos armazenar dados de forma organizada e que possuem identificação única (como acontece em bancos de dados).
 `dict = {chave: valor}`
 `nome_do_dicionario = {1: ‘João’, 2: ‘José’}
nome_do_dicionario = {‘nome’: ‘João’, ‘sobrenome’: ‘Silva’}`












