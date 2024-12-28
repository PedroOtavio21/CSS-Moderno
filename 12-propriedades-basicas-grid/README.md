# Aula 12 - Propriedades básicas do grid
Nesta aula, será passado por cima pelas principais propriedades básicas do grid e como ele se comporta nos dois eixos (principal e vertical)

## display: grid
Assim como oque ocorre no flex-box, o valor `grid` ativa a estilização com `grid container` e `grid items`. 

Outra curiosidade, é que diferente do `flex`, a direção padrão continua sendo a coluna, além de fazer com oque os itens ocupem todo o espaço disponível no `grid container`.

Outra coisa que o `grid` tem em comum com o `flex`, são o uso das estilizações como `justify-content`, `align-items` e `gap`.

## Estilização em itens individuais
O grid tem um fator essencial em sua estilização de elementos dentro de um documento html: estilização individual em cada item dentro de um grid container, como seu tamanho e posicionamento!

**Nota:** Abaixo, você poderá utilizar uma sintaxe de início e termino de posicionamento de elementos no grid, além de utilizar apenas um valor qualquer que definirá a linha ou coluna onde o elemento se encontrará. Ex.:

```css
.item1 {
    grid-column: 1 / 3;
    gridn
}
```

**Nota:** Fique atento à sobreposição de itens no css, pois os que vierem sempre afrente do item anterior, terão sempre prioridade

### grid-column
Define o número de colunas a serem utilizadas no grid, além de definir onde este elemento deverá ser posicionado na coluna

Um fator interessante a se destacar, é que se você definir esta estilização para apenas um item, o restante "tentará" se organizar em colunas de acordo com o item que você estilizou, mesmo que você não tenha definido explicitamente!

### grid-row
Similar ao `grid-column`, o `grid-row` define o posicionamento do item por meio de linhas no `grid-container`. 

Como citado antes no `grid-column`, caso você não tenha especificado o posicionamento dos demais itens, eles irão se organizar de forna "automática" no container.