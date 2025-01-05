# Exercício 5 - Menu para dispositivos móveis
Crie um menu responsivo que se adapta a dispositivos móveis de acordo com as imagens de referência abaixo.

Dicas:

- Utilize o HTML fornecido abaixo como base;

- Utilize o breakpoint (ponto de quebra da interface) de 768px;

- Não se limite apenas às media queries, lembre-se que elas devem ser usadas em conjunto com tudo o que aprendemos até agora (sinta-se livre para usar o flex e o grid como achar necessário)

- Repare que existem outras partes da página que também são responsivas, tente implementar todas as adaptações na interface como um desafio extra!

**HTML Base**
```html
<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu Responsivo</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <header>
    <nav class="navbar">
      <div class="logo">LOGO</div>
      <ul class="menu">
        <li><a href="#">Início</a></li>
        <li><a href="#">Sobre</a></li>
        <li><a href="#">Serviços</a></li>
        <li><a href="#">Contato</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h1>Treinando Responsividade com Media Queries</h1>
      <p>
        O objeitvo deste exercício é criar um menu com comportamento adaptável para dispositivos
        móveis usando apenas HTML e CSS.
      </p>
    </section>
  </main>
</body>

</html>
```

**Imagens de referência**
(em telas de largura até 768px)

<img src="https://assets-v2.circle.so/44bgg6va39ay8s2ki6c60ni7ubor">
<img src="https://assets-v2.circle.so/gmgpoig2fkflhhf4c6t0slym5svp">

(em telas de largura maior que 768px)
<img src="https://assets-v2.circle.so/4vsukpbksre16hqvbji90lxtf2p1">
<img src="https://assets-v2.circle.so/ay609elqrn6x6siqgtz0zqp1y28q">