# Resumo - 2ª Missão - Aprenda a construir seu primeiro documento HTML

- Título da página - `<title></title>`

O título de uma página web permite que o usuário identifique o tipo de conteúdo que ele pode esperar dentro daquela página. Esse título pode ser definido por meio da tag title.

```html
<title>Tags básicas do HTML - Tag Title</title>
```

- Título do conteúdo - `<h1></h1>`

```html
<h1>Título de nível 1</h1>
<h2>Título de nível 2</h2>
<h3>Título de nível 3</h3>
<h4>Título de nível 4</h4>
<h5>Título de nível 5</h5>
<h6>Título de nível 6</h6>
```

- Textos ou conteúdos através de parágrafos - `<p></p>`

```html
<p>Título de nível 1</p>
```

- Criar links em uma página web - <a>

```html
<!-- Abrir uma página do próprio site -->

  <a href="pagina2.html">
    Abrir página 2
  </a>

  <!-- Link para um número de telefone -->
  <a href="tel:+5521995566889">
    +55 21 99556 - 6889
  </a>

  <!-- Link para um email -->
  <a href="mailto:suporte@exemplo.com">
    Enviar email
  </a>

  <!-- Âncora para um elemento da própria página -->
  <a href="#contato">
    Contato
  </a>

  <!-- Link para um site externo que abrirá em uma nova guia -->
  <a href="https://www.mercadolivre.com.br/" target="_blank">
    Site do mercado livre
  </a>
```

- Para exibir uma imagem na página - `<img>`

```html
<!-- Imagem do mesmo diretório que o projeto e na mesma pasta que o arquivo que a exibe -->
<img src="computador.jpg" alt="Notebook Lenovo Ideapad S145" title="Notebook Lenovo">

<!-- Imagem do mesmo diretório que o projeto porém em uma subpasta -->
<img src="assets/computador.jpg" alt="Notebook Lenovo Ideapad S145" title="Notebook Lenovo">

<!-- Imagem de uma url externa -->
<img src="https://http2.mlstatic.com/D_NQ_NP_785711-MLA40805775472_022020-O.webp" alt="Notebook Lenovo Ideapad S145" title="Notebook Lenovo">
```

- Tag usada para agrupar elementos - `<div></div>`

```html
<div>
  <img src="computador.jpg" alt="Notebook Lenovo Ideapad S145"
       title="Notebook Lenovo">
  <a href="pagina2.html">
    Abrir descrição do produto
  </a>
</div>
```

- Para destacar algumas palavras - `<span></span>`

```html
<span>Notebook Lenovo Ideapad</span>
```

```html
<div>
    <h3>
        <span>Notebook Lenovo Ideapad</span> S145 8ª Intel Core I5 8GB 1TB HD 15,6" W10 Prata
    </h3>

    <p>
        Com o Notebook da Lenovo você terá um notebook de <span>última geração</span>, prático e <span>veloz</span>, com excelente capacidade de <span>armazenamento</span>, design inovador e exclusivo, além de você estar sempre conectado com estilo. Sua tela de 15.6" oferece.
    </p>
</div>
```





