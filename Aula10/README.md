# Aula 10 - Modelo de caixa e Posicionamento
  

## Modelo de Caixa

- Width e Heigth
- Padding 
- Border (solid, dotted, dashed ou double)
    - Border radius
- Margin 
- Box-sizing 
    - content-box: conteúdo + padding + margin + border
    - border-box: altura e largura abrange o padding + margin + border


CSS Resetting Margin and Padding

```  
    * {        
        box-sizing: border-box;        
        margin: 0;        
        padding: 0;        
    } 
```

## Posicionamento  

Propriedades: top, right, botton, left  

### Relative

Altera o posicionamento do elemento que contém esse posicionamento, não impactando nos demais.  

Preserva o 'espaço' do fluxo normal.
  

### Absolute  

Elemento passa a pertencer a uma nova 'camada'. Assim, é removido o espaço do fluxo comum. Há um novo fluxo.  

O elemento é absoluto é em relação a página toda (obs: se não houver um elemento pai).

Se houver, um elemento pai relativo, então este elemento tem a sua posição absoluta em relação ao elemento pai.  
  

### Fixed 

Há um novo fluxo para esse elemento.
 

### Sticky