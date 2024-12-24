# Aula 7 - Propriedades dos filhos de um container flex
Além de estilizar um container com base em seu display flex, o flex possibilita também estilizar os próprios itens dentro de um container, individualmente

## Principais propriedades
Cada item possui 3 propriedades de estilização, responsáveis pelo seu crescimento ou encolhimento (proporcionais ao epaço disponível e ao seu tamanho original), além de seu tamanho base, onde as duas propriedades anteriores se aplicam

### flex-grow
Reponsável pelo crescrimento de um determinado elemento

Possui como valor padrão o 0, onde não irá crescer e utilizará seu tamanho normal.

Já o valor 1 ou maiores, fará o elemento crescer o máximo possível ocupando todo o tamanho disponível de forma proporcional.

O cálculo do valor consiste em subtrair o valor de crescimento excedente pelo valor base do elemento escolhido, de forma proporcional

### flex-shrink
Responsável pelo encolhimento de um determinado elemento

Possui como valor padrão de encolhimento sendo 1, sendo a taxa de encolhimento do elemento

Já utilizando o valor 0, fará com oque o elemento deixe de encolher, mesmo com a diminuição da altura ou largura da página

**Nota**: Fique atento a taxa de redução do tamanho dos elementos na página, pois pode acabar quebrando a estilização dos elementos!

### flex-basis
Tamanho padrão de um elemento dentro do container flex

Possui como valor padrão o 1 ou até mesmo não citar um valor padrão na propriedade `flex-basis`

## Abreviando as propriedades
As três propriedades citadas acima podem serem usadas em uma única linha, com a propriedade `flex`.

Possui como ordem no short-cut: `grow`, `shrink` e `basis`.

**Nota**: Além de todo o conteúdo citado, tal propriedade funciona no eixo principal!