# Aula 3 - Principais propriedades do flex
Nesta aula, somos apresentados na prática as principais propriedades do flex, desde sua "ativação" de display no elemento pai no html (container), até a manipulação do posicionamento de itens na página com `justify-content`, `align-items` e `gap`.

### display: flex
Valor que ativa a estilização pela propriedade display, dado um container qualquer dentro do código html. Quando utilizada, organiza os elementos de um container na direção horizontal, sendo o padrão do flex

### flex-direction
Valor responsável por alterar a **direção do eixo principal** dos elementos presentes dentro do container flex, podendo ser de valores verticais e horizontais, além de valores com ordem inversa para os elementos dispersos na verticial e horizontal.

Exemplos dos valores citados acima:
- `row`
- `row-reverse`
- `column`
- `column-reverse`

### justify-content
Primeira das principais propriedades mais utilizadas do flex. Ela alinha os elementos ao longo do **eixo principal** aplicado no flex, seja o horizontal ou vertical

**Nota**: Fique atento ao eixo principal predefinido inicialmente, pois o resultado será diferente de acordo com seu valor escolhido na propriedade `justify-content`

Possui como principais valores:
- `start`
- `center`
- `end`
- `space-between`
- `space-around`
- `space-evenly`

### align-items
Segunda das principais propriedades mais utilizadas do flex. Diferente de justify-content, ela alinha os elementos ao longo do eixo perpendicular ao eixo principal aplicado no flex.

**Nota**: Fique atento ao eixo principal predefinido inicialmente, pois o resultado será diferente de acordo com seu valor escolhido na propriedade `align-items`

Tem como principais valores:
- `start`
- `center`
- `end`

### gap
Espécie de espaçamento entre os items, a partir do flex-container

Algumas vezes, pode ser até utilizado para substituir o espaçamento entre os items com o `margin`, visto que possuem comportamentos semelhantes

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