# Resumo Pseudo-classes e Pseudo-elementos	

## Pseudo-classes

Definir o estilo dos estados de um elemento até alterá-lo de uma posição específica na estrutura.

### De estado

- Quando o mouse passar por cima do elemento:

```css
p:hover {
    border-left: 3px solid blue;
}
```

- Quando o link for acessado. Exclusivo apenas para links:

```css
a:visited {
    color: red;
}
```

### Estrutural

Estiliza o elemento baseado na sua posição.

- Estilo aplicado ao __primeiro__ elemento do tipo:

```css
first-of-type {
    color: green;
}
```

- Estilo aplicado ao __úlitimo__ elemento do tipo:

```css
p:last-of-type {
    color: black;
}
```

- Estio aplicado ao elemento definido no seletor na posição indicada:

```css
p: nth-of-type(2) {
 	color: blue;   
}
```

- Aplica o estilo em todos os elementos __ímpares__:

```css
div:nth-of-type(odd) {
    color: white;
}
```

- Aplica o estilo em todos os elementos __pares__:

```css
div:nth-of-type(even) {
	color: pink;   
}
```

#### Estrutural child

Os tipos child devem ser utilizados quando queremos estilizar elementos caso eles estejam em posições específicas com base em seus elementos pai, por exemplo: estilizar um elemento somente se ele for o 2º parágrafo dentro de um elemento pai, ou a primeira imagem dentro de um elemento pai.

- Estiliza um elemento caso ele seja o __primeiro filho__ do elemento pai:

```css
p:first-child{
    color: peru;
}
```

- Estiliza um elemento caso ele seja o __último filho__ do elemento pai:

```css
p:last-child{
    color: peru;
}
```

- Estiliza um elemento caso ele esteja na __posição definida no parâmetro__:

```css
p:nth-child(2){
    color: royalblue;
}
```

- Aplica o estilo em todos os elementos que estiverem nas posições __ímpares__:

```css
p:nth-child(odd){
    color: purple;
}
```

- Aplica o estilo em todos os elementos que estiverem nas posições __pares__:

```css
p:nth-child(even){
    color: lightseagreen;
}
```



## Pseudo-elementos

Alterar partes específicas de um elemento, tais como a primeira letra ou primeira linha de um parágrafo.

- __Primeira letra__ do parágrafo:

```css
p::first-letter {
    font-size: 32px;
    font-weight: bold;
}
```

- __Primeira linha__ do parágrafo:

```css
p::first-line {
    background-color: yellow;
}
```

Adicionando conteúdos a um elemento:

- Adiciona um conteúdo __antes__ de um elemento:

```css
a::before {
    content: "";
    width: 20px;
    height: 20px;
    background-image: url("img/link.png");
    background-size: 20px 20px;
}
```

- Adiciona um conteúdo __depois__ de um elemento:

```css
a::after {
    content: "";
    width: 20px;
    height: 20px;
    background-image: url("img/link.png");
    background-size: 20px 20px;
}
```

Os pseudo-elementos `before` e `after` __não__ podem ser utilizados com o seletor `img`. Para contornar isso adicione a tag `img` dentro do elemento semântico `figure` e aplique o pseudo-elemento desejado neste.

Os pseudo-elementos before e after tem o display:inline definido como padrão, portanto, será necessário alterar esse display caso queira exibir imagens através desses pseudo-elementos.