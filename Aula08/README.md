Conteúdos vistos em aula:

## BACKGROUNDS

- background-color:
- background-image: url('../img/bici.jpg')
- background-repeat: repeat-x (repeat, no repeat, repeat-x, repeat-y, round e space)
- background-position: right top
- background-attachment: fixed (fixed, scroll, inherit e initial)

exemplo background-attachment: [link](https://www.w3schools.com/cssref/pr_background-attachment.asp)

- background-size: 130px (auto, cover, contain)

Exemplo cover: [link](https://www.w3schools.com/cssref/tryit.asp?filename=trycss3_background-size3)
Exemplo contain: [link](https://www.w3schools.com/cssref/tryit.asp?filename=trycss3_background-size4)
[Exemplos](https://www.w3schools.com/cssref/playdemo.asp?filename=playcss_background-size&preval=contain)

---

## FONTES

@import url('link da fonte')

@font-face {
font-family: "Roboto";
src: url("../fonts/Roboto/Roboto-Regular.ttf");
}

---

### Ícones

Google Fonts - ícones

<link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">

---

## METODOLOGIA BEM

- Padrão de nomenclatura para manter o projeto simples e organizado
- Block Element Modifier
- Bloco Elemento Modificador

EX:

.container {

}

.container\_\_titulo {
color: red;
font-size:30px;
}

.container\_\_titulo--destaque{
color: blue;
}

```
<ul class="lista">
  <li class="lista__item lista__item--destacado">
    <h2 class="lista__titulo">Publicações do autor Fulano</h2>
    <p class="lista__autor">Nome do autor</p>
    <p class="lista__texto">texto texto</p>
  </li>
</ul>


<div class="container">
   <button class="container__botao1">botao 1</button>
   <button class="container__botao2 container__botao2--hover">botao 2</button>
</div>
```

📌 [Material extra](https://medium.com/trainingcenter/bem-em-5min-f5c80fd23439)
