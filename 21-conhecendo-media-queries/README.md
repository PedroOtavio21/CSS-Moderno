# Aula 21 - Conhecendo media queries

## Oque são media queries?
Uma funcionalidade do CSS que permite aplicar **estilos diferentes** dependendo das características do dispositivo em que a página está sendo visualizada

As regras para decidir se um grupo de estilos será aplicado podem ser diversas, como **largura de tela**, **orientação**, **resolução**, entre outras

Seu **objetivo** é tornar o design **responsivo**, ou seja, adaptável a **diferentes tamanhos de tela** (desktop, tablet, smartphone) ou mesmo a diferentes preferências do dispositivo do usuário (como esquema de cores)

## Conceitos básciso
Viewport:
- **Área visível** de uma página em um dispositivo, media queries ajudam a definir estilos com base no tamanho do viewport

Responsividade:
- Capacidade de uma página web **se ajustar** a diferentes tamanhos de tela, proporcionando uma **boa experiência de usuário** independentemente do dispositivo utilizado

Unidades relativas:
- Unidades de medida como: %, em, rem, vw (viewport width) e vh (viewport height) são importantes para trabalhar com Media Queries, pois ajudam a **criar layouts fluidos**

**Nota**: Importante sempre que possível utilizar em conjunto unidades de media relativas com técnincas de responsivas como displays flex e grid vistos nas aulas anteriores!!

## Sintaxe básica das media queries
Sintaxe:
```css
@media (condição) {
    /* Estilos aplicados quando a condição for verdadeira */
}
```

Exemplo:
```css
@media (max-width: 600px) {
    body {
        background-color: #4c6daf;
    }
}
```
O código acima aplica um fundo azul em telas com largura até 600px (normalmente são os dispositivos móveis)

## Tipos de media queries mais comuns
1. max-width e min-width:
- **max-width:** Aplica o estilo se a largura do viweport for **menor ou igual** ao valor especificado

- **min-width:** Aplica o estilo se a largura do viewport for **maior ou igual** ao valor especificado

2. orientation:
Controla a **orientação da tela** (paisagem ou retrato)

3. screen:
Aplica os estilos **apenas** quando a página for visualizada em uma **tela**

## Exemplos de uso prático

### Layout responsivo com media queries
Media Queries permitem que elementos da página ajustem seu layout e estilo conforme o **tamanho da tela muda**

### Media Queries para acessibilidade
Estilos podem ser ajustados para garantir que o conteúdo seja **acessível** em diferentes condições, como alto contraste para usuários com deficiência visual

## Melhores práticas

### *Moblide First*
Desenvolva o **layout** para dispositivos móveis **primeiro** e depois adicione Media Queries para telas maiores, isso facilita a **adaptação** e **otimização** do código

### Uso consciente de breakpoints
Escolha breakpoints (largura de tela) que **façam sentido** para o conteúdo, como 480px para smarthphones, 768px para tablets e 1024px para desktops, **evite criar muitos breakpoints** desnecessários

### Não exagerar nas media queries
Mantenha as Media Queries **simples** e **claras**. Evite sobrecarregar o CSS com múltiplas condições desnecessárias, o que pode **dificultar** a **manutenção do código**