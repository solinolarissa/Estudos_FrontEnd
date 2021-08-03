# Shorthand 

* junção de propriedades 
* resumido
* legível 

```css
{
/*background Properties*/

background-color: #000;
background-image: url(images/bg.gif);
background-repeat: no-repeat;
background-position: left top;

/*background Shorthand*/
background: #000 url(images/bg.gif) no-repeat left top;


/*background Properties*/

font-style: italic;
font-weigth: bold;
font-size: .8em;
line-heigth: 1.2;
font-family: Arial, sans-serif;
/*background Shorthand*/
font: italic bold .8em 1.2 Arial, sans-serif;

}

```

# Detalhes 

* não irá considerar propriedades anteriores 
* valores não especificados irão assumir o valor padrão
* geralmente a ordem descrita não importa, mas, se houver muitas propriedades 
com valores semelhantes, poderemos encontrar problemas.