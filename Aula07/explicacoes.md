CSS
Cascading Style Sheets ou Folhas de Estilo em Cascata

#Comentários

* Não afetará o código
* Ajudará a lembrar os blocos de códigos 
* Auxilia outras pessoas a compreender 


/*  
 comentário em css 

*/

/* Comentário em CSS  */
<!-- Comentário em HTML -->
Atalho do teclado: Ctrl + ;

------

#Anatomia 

<h2>subtítulo</h2>


h2 {
    color: blue;
    background-color: yellow;
}


* Seletor 
* Declaração 
* Propriedades 
* Valor das propriedades

------

#Adicionando CSS 

## inline : atributo 'style'

## <style> : tag html 

## link: arquivo css externo 
 
 * inline > style > link 

------

#Ordem crescente de especificação

(menor)
* Seletores Universais 
    * {}
* Tipo de Seletores
     h1 {} 
* Classes seletoras
    <h1 class="titulo"> Titulo </h1>

    .titulo {

    }

* Atributos Seletores

Ex:
a[href*="example"] {
  background-color: silver;
}

* Pseudo-classes

* Seletores ID

<h1 id="titulo"> Titulo </h1>

    #titulo {

    }

(maior)


------

# Agrupar

h1, h2 {
    color: red;
    font-size: 12px;
}

------

## Regra !important

* Não é considerado uma boa prática
* sobrescreve todas as demais regras

h2 {
    color: red !important;
    font-size: 12px;
}


------

#Dev Tools

------

Fontes

font-family: Arial, sans-serif;
font-size: 23px;
font-style: normal;
font-weight: 500; /*bold, lighter, normal*/
text-align: justify; /*line-through, underline, overline e none*/
line-height: 20px; /* altura da linha - está relacionado ao font-size */


Cores 

h2 { color: purple }
h2 { color: #3459ff }
p { color: rgb(12, 34, 32) }





