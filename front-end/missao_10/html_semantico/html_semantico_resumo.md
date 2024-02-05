## 10ª Missão - Aprenda a construir um web site responsivo

### Artigo- HTML Semântico: Conheça os elementos semânticos da HTML5

Atualmente o papel da HTML não é apenas estruturar documentos para a web, mas também descrever o significado do conteúdo presente nesses documentos por meio de tags semânticas. O HTML semântico tem como objetivo descrever o significado do conteúdo presente em documentos HTML, tornando-o mais claro tanto para programadores quanto para browsers e outras engines que processam essa informação.

- Principais tags:

```html
<header>
<section>
<article>
<nav>
<aside>
<main>
<figure>
<footer>
<a>
<em>
<strong>
<cite>
<q>
<time>
```

- #### header

O `<header>` é utilizado para representar o cabeçalho de um documento ou seção declarado no HTML. Nele podemos inserir elementos de `<h1>` a `<h6>`, até elementos para representar imagens, parágrafos ou mesmo listas de navegação.

```html
<header>
     <h1>Título da página</h1>
     <h2>Subtítulo da página</h2>
</header>
```



- #### section

O elemento `<section>` representa uma seção dentro de um documento e geralmente contém um título, o qual é definido por meio de um dos elementos entre `<h1>` e `<h6>`. Podemos utilizar o `<section>`, por exemplo, para descrever as seções/tópicos de um documento.

```html
<section>
    <h3>Seção 1</h3>

    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>
</section>
```



- #### article

Utilizamos o elemento `<article>` quando precisamos declarar um conteúdo que não precisa de outro para fazer sentido em um documento HTML, por exemplo, um artigo em um blog. É recomendado identificar cada `<article>` com um título.

```html
<article>
    <h3>Título do artigo 1</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>
</article>
<article>
    <h3>Título do artigo 2</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>
</article>
```



- #### nav

O elemento `<nav>` é utilizado quando precisamos representar um agrupamento de links de navegação, que, por sua vez, são criados com os elementos `<ul>`, `<li>` e `<a>`.

```html
<nav>
     <ul>
         <li><a href=”#”>pagina 1</a></li>
         <li><a href=”#”>pagina 2</a></li>
         <li><a href=”#”>pagina 3</a></li>
         <li><a href=”#”>pagina 4</a></li>
     </ul>
</nav>
```



- #### aside

O elemento `<aside>` é utilizado quando precisamos criar um conteúdo de apoio/adicional ao conteúdo principal. Por exemplo, ao falar de HTML semântico, podemos indicar ao leitor outros conteúdos sobre a linguagem HTML como sugestão de leitura complementar.

```html
<aside>
  <nav>
    <ul>
        <li>Link 1</li>
        <li>Link 2</li>
        <li>Link 3</li>
        <li>Link 4</li>
     </ul>
  </nav>
</aside>
```



- #### main

O elemento `<main>` especifica o conteúdo principal e, consequentemente, de maior relevância dentro da página. Para ser considerada bem construída, uma página deve apresentar apenas um conteúdo principal.

```html
<main>
  <h2>Titulo</h2>

  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>

  <article>
     <h3>Subtítulo</h3>
        <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum...</p>
   </article>
</main>
```



- #### figure

O elemento `<figure>`  é uma marcação de uso específico para a inserção de uma figura. Para incluir a descrição dessa figura, podemos utilizar o elemento `<figcaption>`.

```html
<figure>
  <img src=”http://meusite.com.br/assets/imagem.jpg” alt=”Imagem”>
</figure>
```

```html
<figure>
   <img src=”http://meusite.com.br/assets/imagem.jpg” alt=”Imagem”>

   <figcaption>Figura 1. Imagem</figcaption>
</figure>
```



- #### footer

O elemento `<footer>` representa um rodapé de um documento, como a área presente no final de uma página web. Normalmente é utilizado para descrever informações de autoria, como nome e contato do autor, e data de criação do conteúdo.

```html
<footer>
     <p>Escrito por Estevão Dias</p>
     <p>Publicado em 25/03/2017 </p>
</footer>
```



### Semântica no nível do texto

Além da semântica estrutural, o HTML nos permite descrever o significado de um conteúdo em nível de texto utilizando um conjunto de elementos semânticos. Assim, é possível, por exemplo, destacar os trechos de texto que devem receber algum tipo de destaque.

- #### a

A principal função do elemento `<a>` é descrever um link, conectando os diversos documentos de um site e permitindo a navegação por esse conteúdo. Normalmente esses documentos estão relacionados por compartilharem um assunto em comum.

```html
<a href=”//www.devmedia.com.br” alt=”DevMedia”>DevMedia</a>
```



- #### em

O elemento `<em>` é utilizado quando desejamos enfatizar um trecho ou palavra no texto, indicando que ela contribui de forma mais relevante para o sentido/compreensão do conteúdo.

```html
<p>Você <em>tem certeza</em> que essa definição está correta?</p>
```



- #### strong

O elemento `<strong>` também é utilizado para destacar uma parte do texto. Sua principal diferença em relação ao elemento `<em>` é que `<em>` pode alterar o propósito de uma frase, como vimos anteriormente.

```html
<p>Compreender esses elementos HTML é importante porque
<strong>possibilita o desenvolvimento de soluções web modernas</strong>.</p>
```



- #### cite e q

O elemento `<cite>`  é utilizado para declarar que naquele trecho há uma citação, isto é, um trecho de texto que não foi escrito pelo autor do conteúdo. Normalmente utiliza-se o `<cite>` em conjunto com o elemento `<q>`, responsável por apresentar o conteúdo retirado de outra fonte.

```html
<p>
	<q>Lorem ipsum dolor sit amet, consectetur </q> - <cite>http://br.lipsum.com/</cite>.
</p>
```



- #### time

O elemento `<time>` é utilizado para representar datas. Assim, caso seja necessário informar a data em que um conteúdo foi escrito, podemos declarar a tag `<time>` e acrescentar a ela o atributo datetime para escrever a data de forma padronizada.

```html
<time datetime=”2017-04-07”>4/7</time>
```

