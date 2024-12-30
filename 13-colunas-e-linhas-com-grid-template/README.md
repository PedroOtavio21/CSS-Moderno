# Aula 13 - Colunas e linhas com grid-template
Nesta aula, veremos uma forma mais simplificada e bastante útil de se estilizar os elementos dentro de um container com `grid-template`!

## grid-template
Propriedade que sempre deverá ser utilizado no elemento pai, ou seja, no `grid-container`

**Nota:** Utilize em conjunto com as propriedades `grid-row` e `grid-column` para melhor eficácia no posicionamento dos itens no grid container!

**Nota:** Na aula, foi visto um estra em relação aos valores nas propriedades `grid row` e `grid column`. Caso você queria que um elemento prencha todo o espaço de uma determinada área dentro do container, utilize o valor `span` seguido da coluna ou linha a ser ocupada!

Basicamente, funciona como uma espécie de esquema de colunas ou linhas a serem pré-definidas em seus valores. Ele basicamente é dividido em duas opções:

### grid-template-columns
Define o esquema a ser utilizado pelas colunas do grid!

Diferente do `grid-column`, onde você inseria a quantidade de colunas que seriam dispostas no `grid container`, no `grid-template-column` você deverá inserir "n" valores, com unidades de medidas a sua escolha (procure valores responsivos) que representarão as "n" colunas do seu `grid container` 

### grid-template-row
Mesmo esquema de estilização que ocorre com a propriedade acima, porém voltado para a estilização das colunas no `grid container`!

## Unidades de medida em valores no template
Há diversas formas de se definir valores do `grid-template` no css. Dentre elas:
- N valores (visto acima, onde você escolhe valores quaisqueres n vezes, porém acaba por ficar um pouco trabalhoso)
- Com frações, ou "frames", porém acaba ficando repetindo como acima
- Utilizando o método `repeat()`, onde você indica a quantidade seguida do valor a ser repetido
- Utilizando o método `minmax()`, você definirá um valor **mínimo** e **máximo** do tamanho de uma **linha** ou **coluna**, ou seja, responsividade aplicada!