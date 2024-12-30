# Aula 16 - Alinhando elementos no grid
No contexto do display: grid, as propriedades align e justify são usadas para controlar o alinhamento dos elementos dentro do grid. Elas atuam em dois níveis: no conteúdo dos itens ou no próprio grid.

## align
A palavra-chave align está relacionada ao **eixo vertical** (bloqueado pelo sentido de escrita), ou seja, o alinhamento no **eixo y**.

### Propriedades relacionadas ao align:

- **align-items**: Alinha o conteúdo dos itens dentro de cada célula.
- **align-content**: Alinha o grid inteiro dentro de seu contêiner, se houver espaço extra vertical.
- **align-self**: Alinha um item individual (sobrescreve align-items).

### Variações do align:

- **start**: Alinha ao início do eixo vertical.
- **end**: Alinha ao final do eixo vertical.
- **center**: Centraliza no eixo vertical.
- **stretch**: Estica para preencher o espaço disponível (comportamento padrão).

## justify
A palavra-chave justify está relacionada ao **eixo horizontal** (inline pelo sentido de escrita), ou seja, o alinhamento no **eixo x**.

### Propriedades relacionadas ao justify:

- **justify-items**: Alinha o conteúdo dos itens dentro de cada célula no eixo horizontal.
- **justify-content**: Alinha o grid inteiro dentro de seu contêiner, se houver espaço extra horizontal.
- **justify-self**: Alinha um item individual (sobrescreve justify-items).

### Variações do justify:

- **start**: Alinha ao início do eixo horizontal.
**end**: Alinha ao final do eixo horizontal.
**center**: Centraliza no eixo horizontal.
**stretch**: Estica para preencher o espaço disponível (comportamento padrão).

## place
A propriedade place é uma **abreviação combinada** que une as funcionalidades de **alinhamento dos itens** (align) e posicionamento no **eixo horizontal** (justify). Ela pode ser usada para simplificar o código e torna a escrita mais concisa.

### place-items
Define simultaneamente o alinhamento para todos os itens do grid (conteúdo dentro de cada célula) nos eixos vertical e horizontal.

Sintaxe:

```css
place-items: <align-value> <justify-value>;
```
Exemplo:

```css
place-items: center stretch;
```

O conteúdo será centralizado verticalmente (center).
E será esticado horizontalmente (stretch).
Se apenas um valor for fornecido, ele será aplicado a ambos os eixos.

### place-content
Define o alinhamento de todo o grid dentro de seu contêiner (similar a align-content e justify-content).

Sintaxe:

```css
place-content: <align-value> <justify-value>;
```

Exemplo:

```css
place-content: start center;
```
O grid será alinhado ao início do eixo vertical (start).
E centralizado no eixo horizontal (center).

### place-self
Define o alinhamento para um único item dentro do grid, unificando align-self e justify-self.

Sintaxe:

```css
place-self: <align-value> <justify-value>;
```

Exemplo:

```css
place-self: center start;
```

O item será centralizado verticalmente (center).
E alinhado ao início do eixo horizontal (start).
