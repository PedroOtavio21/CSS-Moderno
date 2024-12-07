# Aula 3 - Principais propriedades do flex
Nesta aula, somos apresentados na prática as principais propriedades do flex, desde sua "ativação" de display no elemento pai (container), até a manipulação da posição dos itens na página com **justify-content**, **align-items** e **gap**.

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