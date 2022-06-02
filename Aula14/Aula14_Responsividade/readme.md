# Aula 14 - Design Adaptativo

## Media queries

max-width - tudo que estiver abaixo.
min-width - tudo que for maior.

#### Breakpoints

- 0 a 480px -> pequenos smartphones
- 481 a 768px -> tablets e grandes smartphones
- 769 a 1279px -> notebooks, grandes tablets e pequenos desktops
- > = 1280px grandes desktops e monitores

- Mobile first

@media (min-width: 460px){
/_ Tablets _/
}
@media (min-width: 768px){
/_ Laptop _/
}

- Mobile last

@media (max-width: 768px){
/_ Tablets _/
}
@media (max-width: 460px){
/_ Smartphones _/
}
