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







