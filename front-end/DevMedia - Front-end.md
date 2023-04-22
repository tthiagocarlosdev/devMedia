# DevMedia - Front-end

## Módulo 1 - HTML e CSS

### 1ª Missão - Conhecendo a carreira Front-End

#### 1. Conhecendo as carreiras da programação

O programador Full Stack domina tanto a carreira front-end quanto a carreira back-end

#### 2. Introdução ao Front-end

Front-end é a parte visual e interativa de um software

O front-end web, ou apenas front-end, é um site onde o usuário consegue ver botões, imagens, informações da página e interagir com ela, clicando em um botão, abrindo um link e navegando pelo site

#### 3. Back-end

O usuário não tem acesso ao back-end

Back-end é a camada responsável por manipular e armazenar as informações do site

Back-end é a camada responsável por manipular e armazenar as informações do site. Nele o usuário não tem acesso, quem consegue interagir com o back-end é a camada front-end

#### 4. Tipos de sites

Site estático não precisa que seu conteúdo seja sempre atualizado.

Site dinâmico precisa de um back-end para guardar as informações e exibir em tempo real, ou seja, é um site onde as suas informações estão sempre mudando, por exemplo um site de vendas que precisa exibir produtos disponíveis em tempo real.

No começo criamos sites estáticos, ou seja, sites que não precisam de atualizações dinâmicas, com o tempo, prática e aprendizado criamos sites dinâmicos, ou seja, que o seu conteúdo muda em tempo real.

#### 5. Programação front-end

O front-end faz a conexão visual entre o usuário e a empresa através de um site.

Um programador front-end:

- Cria a parte visual de um site.
- Insere botões, textos e imagens na tela.
- Cria a navegação do site.

É através do front-end que o usuário consegue ter uma visão da empresa. No front-end o usuário consegue conhecer e interagir com a empresa, visualizar informações e comprar um produto.

#### 6. Exemplos práticos de front-end

Vamos analisar um exemplo real de site estático - neste exemplo, o site [webstorm](https://www.webstorm.com.br/loja-virtual/) 

Vamos analisar um exemplo real de site dinâmico, site [Amazon](https://www.amazon.com.br/)

Seja em sites estáticos ou dinâmicos, o front-end vai sempre se preocupar com a aparência das informações que serão exibidas para o usuário, dessa forma o usuário vai conseguir identificar do que se trata cada uma delas.

#### 7. Conclusão

É no front-end que o usuário consegue ver os botões, imagens e textos, além de conseguir clicar nos ícones

As responsabilidades do front-end estão sempre ligadas à interação do usuário, por exemplo, é responsabilidade do front-end exibir e coletar informações. Já o back-end tem a responsabilidade de armazenar e fornecer informações para o front-end.

### 2ª Missão - Aprenda a construir seu primeiro documento HTML

#### 1. Introdução à HTML

A HTML é utilizada para estruturar todo o conteúdo da página, definindo elementos como parágrafos, títulos, imagens, etc. Sendo assim, essa linguagem é utilizada na construção de qualquer página web e, portanto, deve ser conhecida por todo programador que trabalha com esse tipo de aplicação.

#### 2. Criando a primeira página HTML

Toda página HTML, para ser corretamente interpretada pelo browser, deve conter pelo menos a seguinte estrutura básica:

```html
01 <!DOCTYPE html>
02 <html>
03     <head>
04         <meta charset="utf-8">
05         <title>Título da página</title>
06     </head>
07     <body>
08
09     </body>
10 </html>
```

Linha 1: A tag DOCTYPE define o tipo de documento e a versão da linguagem de marcação utilizada. Nesse caso estamos usando a HTML em sua versão mais recente (5).

Linhas 2 e 10: As tags html delimitam o documento, ou seja, todo conteúdo da página deve ficar dentro dessas tags.

Linhas 3 e 6: As tags head definem o cabeçalho da página, no qual adicionamos informações como título (linha 5 - tag title), codificação (linha 4 - charset) e inserimos referências a folhas de estilo CSS.

Linhas 7 e 9: As tags body delimitam o corpo do documento, logo, todo conteúdo visível da página deverá estar dentre dessas tags.

#### HTML: Fundamentos do HTML

#### 1. Mostre suas ideias para o mundo

### Por que aprender HTML?

HTML é a linguagem que traduz para o navegador o que ele deve exibir como um texto, um link, uma imagem, etc. Conhecer essa linguagem é fundamental, porque sem ela é impossível ser um programador web 😨

### O que vamos aprender?

Aqui temos alguns destaques:

- Como criar uma primeira página web
- Elementos, tags e atributos

### Pré-requisitos

- Esse curso não tem nenhum pré-requisito 🙌

HTML é a linguagem que diz para o navegador o que é o que em uma página web.

#### 2. Criando e abrindo uma página web no seu PC

Provavelmente esse curso será o seu primeiro contato com código! Então, antes da gente começar, vamos ter certeza de que você tem tudo o que precisa no seu computador para começar 💪

### Baixe e instale um editor

Para escrever o código você vai precisar de um editor de texto, mas não um como o bloco de notas. Existem opções melhores, feitas para programadores.

Uma delas, é o Visual Studio Code, que você pode baixar no endereço abaixo.

https://code.visualstudio.com/Download

### Como abrir uma página web no navegador?

Conforme você for avançando na programação verá outras formas de fazer isso.

Por enquanto, vamos nos concentrar em como podemos ver as nossas páginas no navegador pra conferir o que fizemos.

Passo #1, localize o local onde o arquivo HTML foi salvo

Geralmente, a página principal de um site se chama index.html, por isso salvamos o código HTML visto anteriormente com esse nome.

Passo #2, abra o arquivo HTML em um navegador

Clique com o botão direito do mouse sobre o arquivo e escolha um navegador para abri-lo, por enquanto pode ser qualquer um, mas eu usei o Google Chrome.

Passo #3, confira a página no navegador

Como o navegador consegue ler e interpretar o HTML, ele vai abrir e processar o arquivo, mostrando um resultado.

Ver o arquivo no navegador não significa que ele esteja na internet, ele não está. Esse passo deixaremos para uma outra matéria.

Escrevemos o HTML em um editor de texto feito para programadores.

#### 3. O que é o HTML?

HTML (Hyper Text Markup Language) é a linguagem que usamos para estruturar as páginas web de um site.

Escrevemos código HTML utilizando tags, como <h1></h1> ou <p></p>, e dentro delas adicionamos o conteúdo que desejamos que o navegador exiba para quem estiver acessando a página web.

O papel das tags é estruturar a informação contida em uma página web, descrevendo para o navegador o que é um texto, um título, um botão, etc.

O texto entre os símbolos menor que < e maior que > é chamado elemento e grande parte deles será composto por duas tags: uma de abertura e uma de fechamento. As tags de fechamento possuem uma barra após o símbolo menor que.

O navegador não mostra as tags de um elemento, mas sim a informação contida entre as suas tags de abertura e fechamento.

HTML utiliza elementos para descrever a estrutura de uma página.

#### 4. Uma linguagem de tags e atributos

HTML é inteiro sobre como estruturar um documento utilizando tags e atributos.

**Tags são como contêineres para informação**

As tags descrevem para o navegador algo sobre o que elas contém.

Algumas vezes você lerá tag e elemento como se eles fossem a mesma coisa, mas tecnicamente um elemento é composto pelas suas tags de abertura e fechamento, bem como pelo conteúdo que está entre elas.

**Atributos dão mais informação sobre o conteúdo de um elemento**

Algumas vezes um elemento contém algo que necessita de mais detalhes e quando for esse o caso, o HTML nos dará atributos para suprir essa necessidade.

Existem diversos atributos com diferentes nomes e valores. Certos atributos podem estar disponíveis apenas para alguns elementos.

Uma página web é um documento de texto escrito com a linguagem HTML.

#### 5. Cabeça e, então, o corpo

Escrevemos o HTML em um arquivo com a extensão .html, comumente chamado documento HTML. Esse documento, quando corretamente lido pelo navegador dá origem uma página web, com a qual o usuário pode interagir.

**Por dentro da estrutura do HTML**

Uma vez que o documento será lido e interpretado pelo navegador, devemos escrevê-los observando certas regras.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Chapeuzinho Vermelho - Conto dos irmãos Grimm</title>
    </head>
    <body>
        <h1>Chapeuzinho Vermelho</h1>

        <p>Houve, uma vez uma graciosa menina; quem a via ficava logo gostando dela, 
        assim como ela gostava de todos; particularmente, amava a avozinha, 
        que não sabia o que dar e o que fazer pela netinha. 
        Certa vez, presenteou-a com um chapeuzinho de veludo vermelho e, 
        porque lhe ficava muito bem, a menina não mais quis usar outro e acabou 
        ficando com o apelido de Chapeuzinho Vermelho. Um dia, a mãe chamou-a e disse-lhe:</p>

        <blockquote>- Vem cá, Chapeuzinho Vermelho; aqui tens um pedaço de bolo e 
        uma garrafa de vinho; leva tudo para a vovó; ela está doente e fraca e 
        com isso se restabelecerá. Põe-te a caminho antes que o sol esquente muito e, 
        quando fores, comporta-te direito; não saias do caminho, 
        senão cais e quebras a garrafa e a vovó ficará sem nada. 
        Quando entrares em seu quarto, não esqueças de dizer "bom-dia, vovó," 
        ao invés de mexericar pelos cantos.</blockquote>
    </body>
</html>
```

**Explorando esse documento**

- **DOCTYPE**

DOCTYPE é uma instrução sobre qual a versão do HTML que vai ser renderizada, nesse caso <!DOCTYPE html> representa o HTML versão 5. Essa declaração deve ser a primeira linha do arquivo HTML.

- **html**

É dentro dessa tag que todas as demais serão escritas. A única coisa que pode ficar fora dessa tag é a declaração DOCTYPE.

Um documento HTML deve ser escrito e estruturado em duas grandes seções: head e body.

- **head**

É aqui que adicionamos tags com informações importantes sobre o documento, tais como o seu título, descrição, codificação de caracteres, entre outras.

Nesse exemplo, utilizamos as tags meta e title.

- **meta**

Meta informa para o navegador qual codificação de caracteres utilizamos quando o documento foi escrito, algo importante para que um "�" não apareça no lugar de outros caracteres, como letras acentuadas, por exemplo.

A codificação de caracteres você encontra no rodapé do seu editor de códigos, mas ela também depende do servidor onde a página web será hospedada, que geralmente vai usar UTF-8.

- **title**

Também adicionamos em head o título da página web, utilizando title.

- **body**

É o corpo da página web, onde todo o conteúdo que será apresentado para o usuário estará.

Essa, com certeza, é a maior parte do documento.

Aqui usamos três elementos para estruturar o conteúdo da página web: h1, p, blockquote.

- **h1**

A maioria das páginas web terá um H1, que representa um título, geralmente escrito em letra maior. Existem seis formas de criar um título no HTML, começando com H1 até H6, o tamanho da letra vai ficando cada vez menor.

- **p**

Um p é um parágrafo de um texto.

- **blockquote**

É uma citação no texto.

Esse é apenas um exemplo de documento.

Na próxima aula conheceremos o nesting e saberemos o porquê de meta não ter tag de fechamento 🤔

head contém informações importantes sobre o documento e body o conteúdo que será apresentado para o usuário.

#### 6. Tags de abertura, fechamento e nesting

Vimos anteriormente que um elemento é um nome entre os sinais maior que > e menor que <.

Por exemplo, o elemento body se escreve <body> e o elemento p se escreve <p>.

**Elementos escritos com pares de tags**

Alguns elementos se escrevem com pares de tags, sendo uma de abertura e a outra de fechamento.

Esse é o tipo mais comum de tag utilizado.

Ao escrever essas tags é necessário abrí-las e fechá-las, dessa forma:

```html
<body>
    <h1>Chapeuzinho Vermelho</h1>
    ...
</body>
```

A primeira tag do par, <body>, se chama tag de abertura e a outra, </body>, se chama tag de fechamento.

É o par, <body> e </body>, que juntas formam o elemento body.

É a barra que informa ao navegador onde a tag body termina.

Os elementos escritos com pares de tags podem conter outros elementos. Isso se chama nesting, aninhamento em tradução livre:

```html
<body>
    <p>
        DevMedia - Plataforma para programadores
    </p>
</body>
```

Perceba que o elemento body contém outro elemento, p, como se body fosse um ninho para outros elementos, daí o nome nesting. Enxergar isso é fundamental porque um documento HTML é um conjunto de elementos aninhados.

É importante lembrar de fechar uma tag aberta para que o navegador possa ler corretamente o HTML que escrevemos.

Um documento HTML é um conjunto de elementos aninhados.

#### 7. Elementos sem tag de fechamento

Uma vez que estudamos os elementos que se escrevem com um par de tags, você deve estar pensando: “algum elemento se escreve com uma única tag”? Sim!

Esses elementos não possuem nesting e obtém seus conteúdos de uma outra forma.

**Elementos que se escrevem com uma única tag**

Um exemplo é img.

Escrever <img></img> é errado, o correto é escrever <img>.

Geralmente, esses elementos se baseiam mais em atributos para dar informações sobre o seu conteúdo. Como vimos, um atributo possui nome e valor.

Por exemplo, img possui o atributo src, que aponta para o local de onde o seu conteúdo será obtido.

```html
<img src="https://www.devmedia.com.br/arquivos/cursos/logo.png" alt="Objeto real">
```

Aqui, img obtém seu conteúdo do endereço “https://www.devmedia.com.br/arquivos/cursos/logo.png”, onde o logo da DevMedia está.

**Outros exemplos**

Um outro elemento que não possui tag de fechamento e que usaremos muito se chama input.

Ora um input é aquela caixinha na qual digitamos texto, ora ele é uma elaborada forma de selecionar uma cor.

Elementos que não precisam de tag de fechamento não permitem o nesting e nunca possuirão outras tags aninhadas dentro delas.

Existem poucos elementos que possuem apenas tag de abertura, a maioria possui tag de abertura e fechamento.

**Como saber qual elemento tem par e qual não tem?**

vem com a experiência, mas uma boa documentação ajuda a acelerar esse conhecimento.

Elementos sem tag de fechamento tendem a depender mais de atributos.

#### HTML: Tags básicas

#### 1. Introdução

Neste curso vamos aprender a utilizar as tags básicas do HTML e para isso vamos criar a página que pode ser vista abaixo.

![projeto01](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/projeto01/imagens/projeto01.png)

Aprender as tags básicas é essencial para se criar uma página web.

#### 2. Entendendo o exemplo

Agora que conhecemos o nosso exemplo ficará mais fácil aprendermos cada tag básica.

#### 3. Relembrando o conceito de Tags HTML

No curso anterior aprendemos o que são tags e elementos HTML, porém por serem conceitos importantes vamos relembrar no **Flow** abaixo.

É através das tags HTML que o navegador vai saber como exibir um conteúdo para o usuário.

#### 4. Tag title

O título de uma página web permite que o usuário identifique o tipo de conteúdo que ele pode esperar dentro daquela página. Esse título pode ser definido por meio da tag title.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Tags básicas do HTML - Tag Title</title>
    </head>
    <body>
        <h1>Tag Title</h1>
        <p>A tag title é responsável por definir o título de uma página web.</p>
        <p>O conteúdo do título de uma página é muito importante para a otimização do 		mecanismo de pesquisa (SEO)! O título da página é usado pelos algoritmos do mecanismo de pesquisa para decidir a ordem ao listar as páginas nos resultados da pesquisa.</p>
    </body>
</html>
```

Caso a tag title não seja definida no arquivo html, o título que aparecerá na aba da página será o **nome do arquivo**.

A tag title é muito importante para o documento HTML. Além dela indicar qual o conteúdo que será abordado na página, ela é importante para os mecanismos de busca como o Google por exemplo.

#### 5. Tags h1, h2, h3, h4, h5 e h6

Toda página web possui títulos para que o usuário possa entender do que se trata o conteúdo apresentado.

Veja abaixo onde posicionar e como utilizar as tags h1, h2, h3, h4, h5 e h6:

```html
<h1>Título de nível 1</h1>
<h2>Título de nível 2</h2>
<h3>Título de nível 3</h3>
<h4>Título de nível 4</h4>
<h5>Título de nível 5</h5>
<h6>Título de nível 6</h6>
```

Assim como as tags h1 à h6, as tags p, a, img, div, span e iframe que veremos nas próximas aulas, devem ser inseridas entre as tags de abertura e fechamento do elemento body.

Através dos títulos conseguimos identificar do que se trata um conteúdo.

#### 6. Tag p

Na nossa página web é comum separarmos textos ou conteúdos através de parágrafos.

```html
<p>Título de nível 1</p>
```

Ao separar o conteúdo da página em parágrafos garantimos a acessibilidade à dispositivos de leitura.

#### 7. Tag a

Criar links em uma página web significa utilizar a tag **<a>**. 

Além de abrir um link externo como por exemplo uma nova página, um número de telefone ou um endereço de e-mail, um link pode enviar o usuário para uma parte específica do próprio site.

Exemplos de links:

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

A tag <a> é utilizada para enviar o usuário para outra página, ligar para um telefone, enviar um email ou enviar para outra parte da sua página web.

#### 8. Tag img

Para exibir uma imagem na página é muito simples basta utilizar a tag **<img>** .

Para exibir uma imagem local é necessário que ela esteja no mesmo diretório do seu projeto.

É possível exibir uma imagem que não esteja na mesma pasta do arquivo que a exibe, desde que ela esteja dentro do diretório do projeto.

Exemplos do uso da tag img:

```html
<!-- Imagem do mesmo diretório que o projeto e na mesma pasta que o arquivo que a exibe -->
<img src="computador.jpg" alt="Notebook Lenovo Ideapad S145" title="Notebook Lenovo">

<!-- Imagem do mesmo diretório que o projeto porém em uma subpasta -->
<img src="assets/computador.jpg" alt="Notebook Lenovo Ideapad S145" title="Notebook Lenovo">

<!-- Imagem de uma url externa -->
<img src="https://http2.mlstatic.com/D_NQ_NP_785711-MLA40805775472_022020-O.webp" alt="Notebook Lenovo Ideapad S145" title="Notebook Lenovo">
```

A tag <img> exibe uma imagem na página.

#### 9. Tag div

Uma das tags mais utilizadas no HTML é a tag **<div>.** Ela é usada para agrupar elementos.

Exemplo do uso da tag **div**:

```html
<div>
  <img src="computador.jpg" alt="Notebook Lenovo Ideapad S145"
       title="Notebook Lenovo">
  <a href="pagina2.html">
    Abrir descrição do produto
  </a>
</div>
```

Utilizamos a tag div para organizar melhor nosso documento HTML.

#### 10. Tag span

Em uma frase às vezes é necessário que algumas palavras recebam algum tipo de destaque. Nesse caso utilizamos a tag span para definir quais são essas palavras. 

Exemplo do uso da tag span:

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

Como vimos <span> não possui aparência visual, porém mais a frente quando você estudar CSS ela poderá ser estilizada. 

Utilizamos a tag span para marcar textos e com isso organizar melhor nosso documento HTML, além de inserir estilos CSS a elas.

#### 11. Tag iframe

A tag iframe é usada para incorporar, ou seja, trazer o conteúdo de uma página web externa para o nosso site.

Exemplo de uso da tag iframe:

```html
<div>
    <h3>Previsão do tempo</h3>

    <p>Veja o como está o clima hoje.</p>

    <iframe
      src="https://www.accuweather.com/"
      width="600" height="450"
    > </iframe>

</div>
```

Existem alguns sites que não permitem que você copie a sua URL e a utilize no iframe dentro do seu site. Ao fazer isso o iframe no seu site não será carregado.

O Google Maps, assim como outros sites, possui uma URL específica para iframe.

Veja a codificação usada para incorporar corretamente o Google Maps no seu site:

```html
<div>
    <h3>Contato</h3>

    <p>Endereço: Av. Ayrton Senna, 3000 - Barra da Tijuca, Rio de Janeiro - RJ</p>

    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3673.1178584692666!2d-43.36403258535193!3d-22.982693146361264!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9bda2ec9620a2d%3A0x5c8412e8969fa343!2sDevMedia!5e0!3m2!1spt-BR!2sbr!4v1614278713361!5m2!1spt-BR!2sbr"
      width="600" height="450"
    ></iframe>

  </div>
```

A tag iframe incorpora o conteúdo de uma página externa no nosso site.

#### 12. Arquitetura do projeto

A página que vamos criar:

![projeto01](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/projeto01/imagens/projeto01.png)

Nosso projeto é uma loja virtual que exibe dois produtos em promoção

#### 13. Criando a estrutura do projeto

Antes de começarmos a digitar nosso documento HTML crie uma pasta para o projeto e baixe as imagens dos produtos (**Figura 1**) que estão disponíveis no botão **Baixar Código Fonte**.

Feito isso crie um arquivo chamado index.html e insira o código abaixo:

```html
<!DOCTYPE html>
  <html lang="pt-br">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Loja virtual</title>
  </head>
  <body>
      Produtos em promoção

      Informática

      Notebook Lenovo Ideapad S145 8ª Intel Core I5 8GB 1TB HD 15,6" W10 Prata
      R$ 3 500,00
      imagem computador.jpg
      Com o Notebook da Lenovo você terá um notebook de última geração,
      prático e veloz, com excelente capacidade de armazenamento, design
      inovador e exclusivo, além de você estar sempre conectado com estilo.
      Sua tela de 15.6" oferece...
      Comprar

      Computador Desktop Completo
      R$ 2 500,00
      imagem desktop.jpg
      Já vem com Monitor LED HDMI Intel Core i5 8GB HD 500GB com caixas
      de som mouse e teclado EasyPC Standard Plus.
      Comprar

  </body>
  </html>
```

Ao salvar as alterações perceba que nosso site é apenas um conjunto de textos.

![projeto01semtag](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/projeto01/imagens/projeto01semtag.png)

Sem utilizar as tags HTML nosso site é apenas um conjunto de texto que não dá para entender do que se trata.

#### 14. Inserindo as tags no projeto

O próximo passo é inserir as tags que aprendemos neste curso. Para isso abra o arquivo index.html e insira o código abaixo:

```html
<!DOCTYPE html>
  <html lang="pt-br">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Loja virtual</title>
  </head>
  <body>
      <h1>Produtos em promoção</h1>
      <h2>Informática</h2>

      <div>
          <h3>
              Notebook Lenovo Ideapad S145 8ª Intel Core I5 8GB 1TB HD 15,6"
              W10 Prata
          </h3>
          <p> R$ 3 500,00 </p>

          <img src="computador.jpg" alt="Notebook Lenovo Ideapad S145"
             title="Notebook Lenovo">

          <p> Com o Notebook da Lenovo você terá um notebook de última
           geração, prático e veloz, com excelente capacidade de armazenamento,
           design inovador e exclusivo, além de você estar sempre conectado
           com estilo. Sua tela de 15.6" oferece...</p>

          <a href="https://lista.mercadolivre.com.br"
           target="_blank" > Comprar </a>
      </div>

      <div>
          <h3>Computador Desktop Completo</h3>
          <p>R$ 2 500,00</p>

          <img src="desktop.jpg" alt="Computador Desktop Completo"
            title="Computador desktop">
          <p> Já vem com Monitor LED HDMI Intel Core i5 8GB HD 500GB
             com caixas de som mouse e teclado EasyPC Standard Plus. </p>
          <a href="https://lista.mercadolivre.com.br"
            target="_blank"> Comprar </a>
      </div>
  </body>
  </html>
```

Ao salvar as alterações nossa página terá a aparência da imagem abaixo:

![projeto01](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/projeto01/imagens/projeto01.png)

Parabéns! Você criou uma página web e aprendeu a utilizar as seguintes tags:

- h1 ... h6 - criar títulos
- p - criar um parágrafo
- a - criar um link
- img - exibir uma imagem
- div - agrupar elemento



### 3ª Missão - Aprenda a construir sua primeira página web estilizada

#### HTML: Meta Tags

#### 1. Introdução

Quando começamos a criar uma página HTML a primeira coisa que fazemos é definir o conteúdo de cabeçalho, como título e meta tags.

Neste curso você aprenderá a trabalhar com as seguintes tags:

- title
- meta (description, charset, viewport, robots)
- link
- style

O uso das tags de cabeçalho é muito importante para a construção de páginas HTML com as características e propriedades do documento customizadas.

#### 2. Title

Para definir o título de uma página precisamos definir a tag <title> dentro do cabeçalho HTML:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <title>Minha Página</title>
</head>
<body>

</body>
</html>
```

![tagtitle01](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/projeto01/imagens/tagtitle01.png)

A tag title é muito útil para identificar onde o usuário está na página:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Curso de HTML</title>
</head>
<body>
    <h1>Introdução</h1>
    <div>
        <p>
            Bem-vindo ao curso de HTML, aqui você vai aprender tudo sobre HTML, do básico ao avançado.
        </p>
    </div>
</body>
</html>
```

![tagtitle02](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/projeto01/imagens/tagtitle02.png)

Como vimos, o uso da tag title é importante, pois serve como identificação da página para o usuário.

#### 3. Meta tag description

Para definir a descrição de uma página precisamos utilizar a tag <meta name="description"> dentro do cabeçalho HTML :

```html
<!DOCTYPE html>
<html>
<head>
    <title>Curso de HTML</title>
    <meta name="description" content="Este é o curso de HTML onde você vai aprender tudo do básico ao avançado">
</head>
<body>

</body>
</html>
```

As meta tags podem ou não utilizar '/' para o seu fechamento. O uso mais comum é sem a '/':

```html
<meta name="description" content="Descrição">
```

Porém também é aceito o uso de '/':

```html
<meta name="description" content="Descrição"/>
```

A meta tag description é utilizada por buscadores na hora de exibir o resultado da busca.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>DevMedia | Plataforma para Programadores</title>
        <meta name="description" content="São milhares de Cursos, DevCasts, Códigos e Artigos sobre Java, JavaScript, PHP, Delphi, Banco de dados, HTML, CSS, C#, C++, Python e .NET. Acesse agora!" />
    </head>
    <body>

    </body>
</html>
```

Apesar de não ser vista pelo usuário, a tag <meta name="description"> é muito importante para buscadores e por isso devemos saber utilizá-la corretamente.

#### 4. Meta tag charset

Para definir o charset da página precisamos utilizar a tag <meta charset=”código do charset”> dentro do cabeçalho HTML.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Página do curso de HTML</title>
    </head>
    <body>
        <h1>Introdução</h1>
        <p>Este é o curso de HTML</p>
    </body>
</html>
```

Em alguns casos essa codificação é implícita no arquivo, com isso os caracteres da página não vão quebrar mesmo que a meta charset não for utilizada. Porém é recomendado que você sempre utilize essa meta tag.

A tag charset é utilizada para definir o conjunto de caracteres de uma página, e por vezes resolve problemas como a exibição incorreta de caracteres.

A tag meta charset é muito útil para definir o conjunto de caracteres da página, evitando problemas de acentuação.

#### 5. Meta tag Robots

Para definir se uma página deve ou não ser exibida em um buscador, precisamos utilizar a tag <meta name="robots"> dentro do cabeçalho HTML.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Comentários em aberto - DevMedia</title>
         <meta name="robots" content="noindex" />
    </head>
    <body>
        <h1>Relatórios de comentários em aberto</h1>
        <p>Aqui entra o conteúdo do relatório</p>
    </body>
</html>
```

Além do noindex, existe também um outro tipo de uso para a tag robots, o nofollow.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Área de comentários</title>
        <meta name="robots" content="nofollow" />
    </head>
    <body>
        <h1>Área de comentários</h1>
        <p>Aqui são exibidos todos os comentários</p>
    </body>
</html>
```

Quando temos uma página administrativa, como um relatório de comentários, ou relatório financeiro, não queremos que essas páginas apareçam em resultados de busca, e por isso utilizamos a meta tag robots.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta name="description" content="Relatório financeiro" />
        <meta charset="UTF-8">
        <meta name="robots" content="noindex, nofollow"/>
        <title>Relatório financeiro</title>
    </head>
    <body>
        <h1>Relatório financeiro</h1>
        <div>
            <p>
            Dados financeiros do segundo trimestre fiscal de 2021
            </p>
            <p>
                As planilhas podem ser acessadas pelo <a href="https://www.office.com">office online</a>
            </p>
            <p>
                Acesse outros dados do relatório no <a href="https://www.meusite.com/relatorimportante/">nosso sistema interno</a>
            </p>
        </div>
    </body>
</html>
```

A meta tag robots é importante para indicar aos buscadores como queremos que os dados da nossa página sejam tratados.

- **noindex** não aparece nos buscadores;
- **nofollow** não associa links adicionados as nossas páginas nos buscadores.

#### 6. Viewport

Para configurar a exibição correta da página em múltiplos tamanhos de tela, precisamos utilizar a tag <meta name="viewport"> dentro do cabeçalho HTML .

```html
<!DOCTYPE html>
<html>
    <head>
        <meta name="description" content="Comentários" />
        <meta charset="UTF-8">
        <meta name="robots" content="noindex, nofollow">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Comentários</title>
    </head>
    <body>
        <h1>Comentários</h1>
        <div>
            <p>
                Venha conhecer meu site. É bem legal. <a href="https://www.meusite.com.br">https://www.meusite.com.br</a>
            </p>
        </div>
    </body>
</html>
```

Através da meta tag viewport podemos garantir que a exibição da nossa página será a melhor possível independentemente do tamanho da tela em que ela está sendo exibida.

#### 7. Adicionando estilos CSS

CSS é uma linguagem que permite a estilização de elementos em uma página HTML.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Tech News - Notí­cias do dia</title>
</head>
<body>
    <h1>Tech News</h1>

    <h3>Notí­cias do dia</h3>

    <div>
        <p>Visual Studio recebe uma atualização</p>
        <p>Unity 2020 beta. Confira as novidades!</p>
        <p>Unreal Engine 5 sai esse ano e promete gráficos incrí­veis.</p>
    </div>
</body>
</html>
```

```css
h1 {
    color: #0000ff;
}

h3 {
    color: #ff0000;
}
```

Agora sabemos o que é o CSS e como ele interage com os elementos HTML, chegou a hora de associar o arquivo CSS ao nosso documento HTML através da tag <link>.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="Fórum" />
        <meta name="robots" content="noindex, nofollow">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="estilo.css">
        <title>Fórum</title>
    </head>
    <body>
        <h1>Fórum</h1>

        <h3>If/else vs Switch/Case</h3>

        <div>
            <b>Marcos: </b><p>Depende de cada caso, eu uso os dois</p>
        </div>
        <div>
            <b>Augusto: </b><p>Não sei, o Switch / case parece mais organizado pra mim.</p>
        </div>
        <div>
            <b>Camila: </b><p>Eu prefiro if/else, é mais simples e serve na maioria das situações</p>
        </div>
    </body>
</html>
```

A tag **b** é utilizada para destacar uma palavra fazendo com que ela fique em negrito.

Agora que vimos como adicionar um arquivo CSS externo a página HTML, vamos ver como adicionar um código CSS diretamente ao documento.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="Fórum" />
        <meta name="robots" content="noindex, nofollow">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style>
            div{
                background: #b8b8b8;
            }
        </style>
        <title>Fórum</title>
    </head>
    <body>
        <h1>Fórum</h1>

        <h3>If/else vs Switch/Case</h3>

        <div>
            <b>Marcos: </b><p>Depende de cada caso, eu uso os dois</p>
        </div>
        <div>
            <b>Augusto: </b><p>Não sei, o Switch / case parece mais organizado pra mim.</p>
        </div>
        <div>
            <b>Camila: </b><p>Eu prefiro if/else, é mais simples e serve na maioria das situações</p>
        </div>
    </body>
</html>
```

Agora que vimos as duas formas de uso, confira um exemplo prático de uma página estilizada com CSS através do uso da tag <style>:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="Lançamento de Jogos" />
        <meta name="robots" content="noindex, nofollow">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style>
            h1 {
                color:#02af3b;
            }
            h3 {
                color: #ff7300;
            }
            div {
                background: #6694eb;
            }
        </style>
        <title>Lançamentos</title>
    </head>
    <body>
        <h1>Jogos</h1>

        <h3>Lançamentos de jogos 2021</h3>

        <div>
            <p>The Medium</p>
            <p>Yakuza 3</p>
            <p>Yakuza 4</p>
            <p>Yakuza 5</p>
            <p>MLB The Show 21</p>
        </div>
    </body>
</html>
```

![tagstyle](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/projeto01/imagens/tagstyle.png)

Através do uso das tags <link> e <style> podemos adicionar estilos CSS ao conteúdo de nossa página HTML.

#### 8. Praticando

Agora que já sabemos como utilizar as tags de cabeçalho, vamos construir um exemplo. Nele vamos exibir uma página HTML que mostra o nome dos alunos aprovados e reprovados.

Todas as tags de cabeçalho vistas neste curso foram utilizadas, com exceção da tag link, já que utilizamos a tag style para o CSS. 

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Resultados dos alunos</title>
        <meta name="description" content="Lista de aprovação" />
        <meta charset="UTF-8">
        <meta name="robots" content="noindex">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style>
            b { color:#02af3b; }
            p { color: #ce0909; }
        </style>
    </head>
    <body>
        <h1>Resultados dos alunos</h1>

        <h3>Aprovados</h3>
        <div>
            <p><b>Marcus</b></p>
            <p><b>Camila</b></p>
            <p><b>Fred</b></p>
            <p><b>Julia</b></p>
        </div>
        <h3>Reprovados</h3>
        <div>
            <p>Tamires</p>
            <p>Paulo</p>
            <p>César</p>
            <p>Gabriela</p>
        </div>
    </body>
</html>
```

![resultadoalunos](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/projeto01/imagens/resultadoalunos.png)

**Entendendo o código do exemplo**

Para que a página que criamos tenha as características que desejamos, precisamos utilizar as seguintes tags de cabeçalho:

- Title
- Meta tag Description
- Meta tag Charset
- Meta tag Noindex
- Meta tag Viewport
- Style

#### CSS: Introdução

#### 1. Introdução





