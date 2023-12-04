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

- justify-content + flex-wrap

```css
.container-wrap-flex-end {
   …
   display: flex;
   flex-wrap: wrap;
   justify-content: flex-end;
   gap: 30px;
}
.container-wrap-center {
   …
   display: flex;
   flex-wrap: wrap;
   justify-content: center;
   gap: 30px;
}
.container-wrap-space-between {
   …
   display: flex;
   flex-wrap: wrap;
   justify-content: space-between;
   gap: 30px;
}
.container-wrap-space-around {
   …
   display: flex;
   flex-wrap: wrap;
   justify-content: space-around;
   gap: 30px;
}
.container-wrap-space-evenly {
   …
   display: flex;
   flex-wrap: wrap;
   justify-content: space-evenly;
   gap: 30px;
}
```





