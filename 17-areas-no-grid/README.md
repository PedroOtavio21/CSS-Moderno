# Aula 17 - Áreas no grid e propriedade grid-area
A partir desta aula, será dada uma maneira nova de se trabalhar com a disposição dos elementos dentro de um grid-container, diferente de aulas passadas onde foram trabalhadas propriedades básicas como `grid-column` e `grid-row`, além do `grid-template` como um todo

## grid-template-areas
Um pouco similar a propriedade template antes vista, onde você organiza e manipula uma espécie de template para os elementos se organizarem dentro do grid container

Porém, o `grid-template-areas` é uma espécie de template onde você nomeia e organiza os elementos dentro de um container, facilitando tanto a linha de código para leitores, quanto para a visualização de elementos dentro do grid container!

Os nomes dados anteriormente no template podem ser usados para serem atribuidos aos itens individualmente, pela propriedade `grid-area`

### Como se utilizar
1. Defina primeiramente o escopo / esboço de como será o seu grid container
   - Defina os nomes de cada elemento dentro do `grid-template-areas`

2. Adicione o nome de cada elemento definido anteriormente no `grid-template-areas` em cada item desejado do container na propriedade `grid-area`

Ex.:
```css
.grid-container {
    display: grid;
    gap: 1rem;
    /* Passo 1 */
    grid-template-areas:
      "cabecalho cabecalho cabecalho cabecalho"
      "sidebar   conteudo  conteudo  conteudo"
      "sidebar   conteudo  conteudo  conteudo"
      "sidebar    rodape    rodape    rodape";
}

.item {
    border-radius: .25rem;
    padding: 1rem;
}

.sidebar{
    /* Passo 2 */
    grid-area: sidebar;
    background-color: #4a66c3;
}
```