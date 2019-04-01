# DB2

## Estrutura de armazenamento DB2

#### Database
    Objeto ultilizado para agrupar outros objetos.

##### Storage Group
    Conjunto de discos que armazenam os dados fisicamente das *Tabelas* e *Index*.

##### Tables
    No DB2, todos os dados são representados em *table* que são organizados em linhas e colunas.

##### Index
    É criado para agilizar pesquisas acessando diretamente o banco de dados.
    Conjunto ordenado de ponteiros.

##### Table Space
    Espaço reservado em disco que armazena os dados reais da *Table* e *Index*.
    É uma boa prática colocar somente um objeto em cada *Table* *Space*.

### Sistema de Objetos
    DB2 ultiliza alguns objetos para gerenciar e garantir a arquitetura dos dados, chamados de DB2 System objects.
##### DB2 Catalog
    O catalogo é o conjuto de *Tables* que contêm informações sobre todos os objetos definidos no DB2,tais como *INDEX* , *VIEW* , *STORAGE GROUP* , *TABLE*.


