# Media queries para preferência de esquemas de cores
Nesta aula, veremos uma forma diferente de trabalhar com as media queries em estilização de sites.

## prefers-color-scheme
Diferente da aula anterior, utilizaremos a media querie para trabalhar com a preferência de cores do usuário, podendo ser clara ou escura

Exemplo:
```css
@media screen and (prefers-color-scheme: dark){
    body {
        background-color: #1c1a1d;
        color: #fff;
    }

    .products {
        background-color: #2c2c2c;
        color: #fff;
    }
}
```

Existem três valores principais para a propriedade prefers-color-scheme:
1. light: Indica que o usuário prefere um esquema de cores **claro**.

2. dark: Indica que o usuário prefere um esquema de cores **escuro**.

3. no-preference: Indica que o usuário **não tem preferência** específica.