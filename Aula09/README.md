## METODOLOGIA BEM

- Padrão de nomenclatura para manter o projeto simples e organizado
- Block Element Modifier
- Bloco Elemento Modificador

EX:

.container {

}

.container__titulo {
color: red;
font-size:30px;
}

.container__paragrafo{

}

.container___titulo--destaque{
color: blue;
}


.nav{

}

.nav__item{

}

.menu__item--active{}
```
<ul class="lista">
  <li class="lista__item lista__item--destacado">
    <h2 class="lista__titulo">Publicações do autor Fulano</h2>
    <p class="lista__autor">Nome do autor</p>
    <p class="lista__texto">texto texto</p>
  </li>
</ul>


<div class="container">
   <button class="container__botao">botao 1</button>
   <button class="container__botao active">botao 2</button>
</div>
```




📌 [Material extra](https://medium.com/trainingcenter/bem-em-5min-f5c80fd23439)
