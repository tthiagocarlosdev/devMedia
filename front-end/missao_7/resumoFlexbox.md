# Flexbox

- Display Flex

```css
.elemento{
    display: flex;
}
```

- Direção

  - Elementos alinhados em linha:

  ```css
  .elemento{
      display: flex;
  	flex-direction: row;
  }
  ```

  ```css
  .elemento{
      display: flex;
   	flex-direction: row-reverse;
  } 
  ```

  - Elementos alinhados em coluna:

  ```css
  .elemento{
      display: flex;
  	flex-direction: column;
  }
  ```

  ```css
  .elemento{
      display: flex;
  	flex-direction: column-reverse;
  }
  ```

- Quebra de linha:

  - Padrão, não quebra a linha:

  ```css
  .elemento{
      display: flex;
      flex-wrap: nowrap;
  }
  ```

  - Quebra linha:

  ```css
  .container-quebra-de-linha {
      display: flex;
      flex-wrap: wrap;
  }
  ```

  ```css
  .container-quebra-de-linha-reversa{
      display: flex;
      flex-wrap: wrap-reverse;
  }
  ```

- flex-flow:

```css
.container-em-linha-sem-quebra-de-linha {
   display: flex;
   flex-flow: row nowrap;
}
```

```css
.container-em-linha-com-quebra-de-linha {
   display: flex;
   flex-flow: row wrap;
}
```

- justify-content

```css
.container-flex-end {
   …
   display: flex;
   justify-content: flex-end;
}
.container-center {
   …
   display: flex;
   justify-content: center;
}
.container-space-between {
   …
   display: flex;
   justify-content: space-between;
}
.container-space-around {
   …
   display: flex;
   justify-content: space-around;
}
.container-space-evenly {
   …
   display: flex;
   justify-content: space-evenly;
}
```

- justify-content, flex-direction column:

```css
.container-column-flex-end {
   …
   height: 90vh;
   display: flex;
   flex-direction: column;
   justify-content: flex-end;
}
.container-column-center {
   …
   height: 90vh;
   display: flex;
   flex-direction: column;
   justify-content: center;
}
.container-column-space-between {
   …
   height: 90vh;
   display: flex;
   flex-direction: column;
   justify-content: space-between;
}
.container-column-space-around {
   …
   height: 90vh;
   display: flex;
   flex-direction: column;
   justify-content: space-around;
}
.container-column-space-evenly {
   …
   height: 90vh;
   display: flex;
   flex-direction: column;
   justify-content: space-evenly;
}
```

- align-items

```css
.container-flex-start {
   …
   display: flex;
   align-items: flex-start;
}
.container-center {
   …
   display: flex;
   align-items: center;
}
.container-flex-end {
   …
   display: flex;
   align-items: flex-end;
}

.container-flex-end {
   …
   display: flex;
   align-items: stretch;
}
```

```css
.container-column-flex-start {
   …
   display: flex;
   flex-direction: column;
   align-items: flex-start;
}

.container-column-center {
   …
   display: flex;
   flex-direction: column;
   align-items: center;
}

.container-column-flex-end {
   …
   display: flex;
   flex-direction: column;
   align-items: flex-end;
}
```

```css
.container-stretch-center {
   …
   display: flex;
   align-items: stretch;
   justify-content: center;
}
.container-center-center {
   …
   display: flex;
   align-items: center;
   justify-content: center;
}
.container-center-space-between {
   …
   display: flex;
   align-items: center;
   justify-content: space-between;
}
.container-center-space-around {
   …
   display: flex;
   align-items: center;
   justify-content: space-around;
}
.container-center-space-evenly {
   …
   display: flex;
   align-items: center;
   justify-content: space-evenly;
}
```

- flex-grow - elemento filho ocupará o espaço disponível, conforme a largura do elemento pai:

```css
.elementoPai{
    display: flex;
}
.elementoFilho{
    flex-grow: 1;
}
```

- flex-grow não aplicado

```css
.elementoPai{
    display: flex;
}
.elementoFilho{
    flex-grow: 0;
}
```

- flex-shrink - indica como um elemento filho terá seu tamanho reduzido para continuar a caber em um elemento pai:

```css
.elementoPai{
    display: flex;
}
.elementoFilho{
    flex-shrink: 1;
}
```

- flex-basis - indica uma largura ou uma altura inicial para um elemento filho, conforme o alinhamento do elemento pai:

  - define a largura inicial:

  ```css
  .elementoPai{
      display: flex;
      flex-direction: row;
  }
  .elementoFilho{
      flex-basis: 1;
  }
  ```

  - define a altura inicial:

  ```css
  .elementoPai{
      display: flex;
      flex-direction: column;
  }
  .elementoFilho{
      flex-basis: 1;
  }
  ```

- Flex - abreviação das propriedades: `flex-grow`, `flex-shrink` e `flex-basis`:

```css
.elementoPai{
    display: flex;
}
.elementoFilho{
    flex: 1 1 auto;
}
```





