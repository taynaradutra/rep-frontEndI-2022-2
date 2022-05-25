# Flexbox

- Flex Container
    - Flex itens
- Nesting: um elemento contém outros elementos 


## Eixos  (Axis)

- Main axis 
- Cross axis


## Propriedades do Flex container

### Direção dos itens

- Flex é de única dimensão (row ou column)
- propriedade: flex-direction (row | row-reverse | column | column-reverse)

### Flex-wrap

- Multi linhas
- Cada nova lihnha torna-se um novo flex-container
- Propriedade: flex-wrap: (wrap | nowrap | wrap-reverse)



### justify-content

- Alinhamento dos elementos dentro do container
- Main axis
- justify-content: (flex-start | flex-end | center | space-around | space-between )


### align-itens 

- Alinhamento dos elementos no eixo cruzado
- align-items: (stretch | flex-start | flex-end | center)


### gap 

- Espaços entre os elementos
- ex => gap: 10px;

## Propriedades do flex items 

### flex-basis

- Definir largura/altura do elemento conforme main axis

### flex-grow

- O crescimento do item dentro do container em relação aos espaços vazios. 
- flex:grow: 1 /* 1 irá ocupar todo o espaço disponível */;

### order 

- Controlar a ordem de cada item

### align-content 

-  Contêiners multilinhas


