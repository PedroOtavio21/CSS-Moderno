# Aula 3 - Principais propriedades do flex
Nesta aula, somos apresentados na prática as principais propriedades do flex, desde sua "ativação" de display no elemento pai (container), até a manipulação da posição dos itens na página com **justify-content**, **align-items** e **gap**.

### display: flex
Propriedade que ativa a estilização em display, dado um container qualquer. Quando utilizada, organiza os elementos de um container na horizontal (direção padrão)

### flex-direction
Propriedade responsável por alterar a direção padrão, na qual os elementos estão dispersos dentro de um container com a propriedade flex aplicada

### justify-content
Primeira das principais propriedades mais utilizadas do flex. Ela alinha os elementos ao longo do eixo principal aplicado no flex, seja o horizontal ou vertical

Possui como principais valores:
- start
- center
- end
- space-between
- space-around
- space-evenly

### align-items
Segunda das principais propriedades mais utilizadas do flex. Diferente de justify-content, ela alinha os elementos ao longo do eixo perpendicular ao eixo principal aplicado no flex.

Tem como principais valores:
- start
- center
- end

### gap
Espécie de espaçamento entre os items, onde substitui na maioria das vezes o uso dele do que o próprio margin entre os elementos. 

Exemplo de código visto em aula:
```css
/* A manipulação vista nessa aula precisa ser usada no elemento pai! */
.flex-container{
    display: flex; /* Ativa a propriedade Flex no CSS*/
    flex-direction: row; /* Altera a direção e disposição dos itens*/
    justify-content: center; /*Alinha os itens ao longo do eixo principal*/
    align-items: center; /*Alinha os items ao longo do eixo perpendicular*/
    gap: 1rem; /*Espaçamento entre os itens no container*/
}
```