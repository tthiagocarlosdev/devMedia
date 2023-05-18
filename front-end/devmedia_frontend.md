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

Para mudar a aparência de uma página web é necessário utilizar uma linguagem de estilo chamada CSS (Cascading Style Sheets - Folha de Estilo em Cascata). Com ela podemos mudar o visual dos elementos que compõem um documento HTML.

É fundamental para um desenvolvedor web ter conhecimentos de CSS.

É muito importante destacar as responsabilidades de cada linguagem na construção de uma página web. Enquanto o HTML lida com a estrutura, o CSS lida com a aparência.

CSS é uma linguagem fundamental para o desenvolvimento de páginas web. Alterar a aparência de uma aplicação é responsabilidade do CSS, que é usado para estilizar os elementos HTML de uma página

```html
<div>
    <a href="#">Contato</a>
</div>
```

```css
a {
    text-decoration: none;
    color: white;
    background-color: black;
    padding: 10px 15px;
}
```

![cssintr](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/imagens/cssintr.png)

#### 2. Sintaxe do CSS

Como vimos na aula passada, o CSS tem como tarefa alterar a aparência de uma página web. Veremos a seguir como é a sintaxe do CSS e como podemos usá-lo em uma página web:

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estrutura CSS</title>
    <style>
        h1 {
            font-size: 28px;
            color: blue;
        }
    </style>
</head>
    <body>
        <h1>Introdução ao CSS</h1>
        <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O CSS é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
    </body>
</html>
```

![estruturacss](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/imagens/estruturacss.png)

Cada estilo aplicado no CSS altera uma característica do elemento.

É fundamental utilizar a sintaxe do CSS de forma correta para que os estilos sejam aplicados na página. Todos os estilos devem estar dentro de uma chave de abertura e uma chave de fechamento. Além disso, cada estilo é representado por uma propriedade e seu valor. Essa regra vale para qualquer elemento que terá a aparência mudada no código CSS.

#### 3. Meu primeiro código CSS

Agora que vimos como é a sintaxe de um código CSS e como é importante implementá-la corretamente, veremos como o código CSS é usado em uma página HTML:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estrutura CSS</title>
    <style>
        h1 {
            font-size: 48px;
            color: blue;
        }

        p {
            font-size: 20px;
        }
    </style>
</head>
<body>
    <h1>Introdução ao CSS</h1>
    <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O CSS é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado.</p>
</body>
</html>
```

![primeirocodigocss](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/imagens/primeirocodigocss.png)

Cada propriedade no CSS nos permite alterar uma característica de um elemento no HTML.

Um código CSS deve estar com a sintaxe correta e também ficar dentro da tag **style** para que os estilos sejam aplicados de forma correta.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estrutura CSS</title>
    <style>
        h1 {
            font-size: 48px;
            color: blue;
        }
        
        p {
            font-size: 20px;
        }

        a {
            font-size: 20px;
            color: white;
            background-color: blue;
        }
    </style>
</head>
<body>
    <h1>Introdução ao CSS</h1>
    <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O CSS é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado.</p>
    <a href="https://www.devmedia.com.br/css">Guia de CSS</a>
</body>
</html>
```

![primeirocodigocss2](/home/thiago/Downloads/PROGRAMACAO/devMedia/front-end/imagens/primeirocodigocss2.png)

As propriedades font-size e color normalmente são aplicadas em textos como foram vistos os exemplos das tags h1 (título) e p (parágrafo). Quando essas propriedades são usadas em outros elementos, seus estilos são aplicados nos textos que estiverem dentro desses elementos.

#### 4. Padrões de cor

Padrões de cores é um assunto muito relevante para um programador front-end. Isso porque as cores são constantemente usadas em todo tipo de projeto. Sendo assim, é um conhecimento fundamental para sua carreira como desenvolvedor front-end.

É muito importante que você conheça os principais padrões de cor que são usados no CSS.

O padrão **nominal** utiliza o nome das cores em inglês.

O padrão **RGB** (red, green, blue) utiliza valores de 0 a 255 para indicar o quanto de cada cor se quer ao estilizar um elemento.

Tanto a cor RGB quanto a Hexadecimal utilizam as cores vermelha, verde e azul para criar outras cores. Essas cores são utilizadas principalmente nas propriedades color e background-color.

- __Utilizando um seletor de cores__

Como vimos, não precisamos decorar cores RGB ou Hexadecimal, podemos utilizar uma ferramenta para selecionar a cor que queremos. Seguem duas ferramentas seletoras de cores:

1. Site do Mozilla [[Seletor de cores - CSS | MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Colors/Color_picker_tool)]
2. Site Pick Color From Image [[Color Picker online | HEX Color Picker | HTML Color Picker](https://imagecolorpicker.com/)]

#### 5. CSS em arquivo externo

Vimos nas aulas anteriores que adicionamos CSS por meio da tag <style>. No entanto, o mais indicado é aplicar o código de estilo por meio de um arquivo CSS externo.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estrutura CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
    <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O CSS é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado.</p>
</body>
</html>
```

```css
h1 {
      font-size: 48px;
      color: blue;
}

p {
      font-size: 20px;
}
```

Quando usamos a tag <style> dentro do arquivo HTML estamos usando **CSS incorporado** (ou interno). Já quando colocamos os estilos em um arquivo CSS separado estamos usando **CSS externo**.

### Vinculando arquivo CSS externo de outra pasta

Já sabemos que para adicionar estilos em uma página é necessário vincular um arquivo CSS externo ao HTML do projeto.

```html
<!DOCTYPE html>
…
    <link rel="stylesheet" href="estilo.css">
…
</html>
```

No entanto, para casos em que o arquivo.css esteja salvo em outra pasta precisaremos utilizar uma sintaxe levemente diferente.

Dividir o seu projeto em pastas é uma ótima prática, pois deixará os arquivos mais organizados. Isso facilita a alteração/evolução do código.

```css
/* Link HTML */
<link rel="stylesheet" href="css/estilos.css">
}
```

Utilizar um arquivo CSS externo deixa a manutenção de um projeto mais fácil. Além de termos arquivos mais fáceis de manter, não temos todo o código (estrutura e estilo) misturado em um mesmo arquivo. É uma boa prática separar os códigos HTML e CSS em arquivos distintos, deixando cada arquivo com uma única responsabilidade

#### 6. Propriedades de fonte

É muito importante para o programador front-end conhecer as propriedades CSS a fim de ter diversas opções de estilos para usar em suas páginas web. No flow a seguir veremos mais algumas propriedades CSS, que são bastantes utilizadas:

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estrutura CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
     <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O CSS é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
</body>
</html>
```

```css
h1 {
    font-size: 48px;
    font-family: 'Verdana';
}
```

Existem muitas famílias de fontes no CSS. Algumas delas são fontes padrão, ou seja, já vem nativamente no navegador. Já outras são externas onde se torna necessário instalar essas fontes ou usar um link externo para usá-las

No artigo [Lista de fontes padrão do CSS](https://www.devmedia.com.br/lista-de-fontes-padrao-no-css/43215) você vai conferir a lista das fontes padrão mais utilizadas na linguagem.

**Propriedade font-weight**

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estrutura CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
    <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O CSS é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
</body>
</html>
```

```css
h1 {
       font-size: 48px;
       font-family: 'Verdana';
 }

p {
       font-size: 28px;
       font-weight: bold
}
```

**Propriedade font-style**

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estrutura CSS</title>
<link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
    <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O CSS é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
</body>
</html>
```

```css
h1 {
      font-size: 48px;
      font-family: 'Verdana';
}

p {
      font-size: 28px;
      font-weight: bold;
      font-style: italic;
}
```

**Propriedade text-decoration**

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
     <p>Aprenda o que é o <span>CSS</span> e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O <span>CSS</span> é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
<a href="https://www.devmedia.com.br/css">Guia de CSS</a>
</body>
</html>
```

- underline

  ```css
  h1 {
      font-size: 48px;
      font-family: Verdana;
      text-decoration: underline;
  }
  
  p {
      font-size: 24px;
      font-style: italic;
      font-weight: bold;
  }
  
  span {
     font-weight: bold;
  }
  ```

  

- overline

  ```css
  h1 {
      font-size: 48px;
      font-family: Verdana;
      text-decoration: overline;
  }
  
  p {
      font-size: 24px;
      font-style: italic;
      font-weight: bold;
  }
  
  span {
     font-weight: bold;
  }
  
  a {
      font-size: 24px;
      text-decoration: overline;
  }
  ```

  

- line-trrough

  ```css
  h1 {
      font-size: 48px;
      font-family: Verdana;
      text-decoration: line-through;
  }
  
  p {
      font-size: 24px;
      font-style: italic;
      font-weight: bold;
      text-decoration: line-through;
  }
  
  span {
      font-weight: bold;
  }
  
  a {
      font-size: 24px;
      text-decoration: line-through;
  }
  ```

  

- none

  ```css
  h1 {
      font-size: 48px;
      font-family: Verdana;
      text-decoration: underline;
  }
  
  p {
      font-size: 24px;
      font-style: italic;
      font-weight: bold;
  }
  
  span {
     font-weight: bold;
  }
  
  a {
      font-size: 24px;
      text-decoration: none;
  }
  ```

  

Existem outras propriedades que são muito importantes na estilização de textos.

**Propriedade text-align**

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estrutura CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
    <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O CSS é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
    <a href="https://www.devmedia.com.br/css">Guia de CSS</a>
</body>
</html>
```

- left

  ```css
  h1 {
      font-size: 48px;
      font-family: 'Verdana';
      text-decoration: underline;
      text-align: left;
  }
  
  p {
      font-size: 28px;
      font-weight: bold;
      font-style: italic;
  }
  
  a {
     font-size: 28px;
     text-decoration: none;
  }
  ```

  

- center

  ```css
  h1 {
          font-size: 48px;
          font-family: 'Verdana';
          text-decoration: underline;
          text-align: center;
    }
  
   p {
          font-size: 28px;
          font-weight: bold;
          font-style: italic;
  }
  
  a {
         font-size: 28px;
         text-decoration: none;
  }
  ```

  

- right

  ```css
  h1 {
      font-size: 48px;
      font-family: 'Verdana';
      text-decoration: underline;
      text-align: right;
  }
  
  p {
      font-size: 28px;
      font-weight: bold;
      font-style: italic;
  }
  
  a {
     font-size: 28px;
     text-decoration: none;
  }
  ```

  

**Propriedade line-height**

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estrutura CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
    <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O CSS é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
    <a href="https://www.devmedia.com.br/css">Guia de CSS</a>
</body>
</html>
```

```css
h1 {
        font-size: 48px;
        font-family: 'Verdana';
        text-decoration: underline;
        text-align: center;
  }

 p {
        font-size: 28px;
        font-weight: bold;
        font-style: italic;
        line-height: 48px;
}

a {
      font-size: 28px;
      text-decoration: none;
}
```

A seguir veremos como elementos de textos recebem estilos através de um container:

**Estilizando textos dentro de uma div**

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estrutura CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <div>
        <h1>Estilos para textos</h1>
        <h2>Estilizando textos dentro de um container.</h2>
        <p>Podemos estilizar os elementos de texto dentro de uma div definindo os estilos diretamente na div.</p>
    </div>
</body>
</html>
```

```css
div {
    color: #ff2200;
}

h1 {
    font-size: 28px;
    color: #0022ff
}

h2 {
    font-size: 24px;
}

p {
    font-size: 20px;
}
```

### Exemplo Prático

Agora veremos um exemplo de uma página de artigo que contém apenas elementos de texto. Nessa página teremos elementos que recebem os estilos que vimos no decorrer dessa aula.

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>CSS - Linguagem de estilos</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>O que é CSS?</h1>
    <h2>Nesse artigo vamos aprender o que é CSS e como usá-lo</h2>
    <p>CSS é chamado de linguagem de estilos <span>(Cascading Style Sheet)</span> e é usado para estilizar elementos escritos em uma linguagem de marcação como HTML. O CSS separa o conteúdo da representação visual do site. Pense  na decoração da sua página. Utilizando o CSS é possível alterar a cor do texto e do fundo, fonte e espaçamento entre parágrafos.</p>
    <p>O CSS foi desenvolvido pelo W3C <span>(World Wide Web Consortium)</span> em 1996, por uma razão bem simples. O HTML não foi projetado para ter tags que ajudariam a formatar a página. Você deveria apenas escrever a marcação para o site.</p>
</body>
</html>
```

```css
h1 {
    font-size: 32px;
    font-family: 'Verdana';
    text-decoration: underline;
    text-align: center;
}

h2 {
    font-size: 24px;
    font-family: 'Verdana';
    font-weight: normal;
    color: #3f4df3;
}

p {
    font-size: 18px;
    font-family: 'Verdana';
}

span {
    font-weight: bold;
}
```



As fontes representam uma parte muito importante nas páginas web, visto que basicamente todos os sites possuem texto em suas páginas. Aprender a usar propriedades para estilizar fontes é fundamental para o desenvolvedor web deixar os textos com um visual mais apresentável

#### 7. Exemplo prático

Até aqui vimos diversas propriedades que mudam a aparência de elementos de texto na tela.

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Receita: Bolo de Chocolate</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <div>
        <h1>Receita para bolo de chocolate</h1>
        <h2>Receita simples e prática do bolo mais querido dos brasileiros</h2>
        <img src="bolo-chocolate.jpg" alt="Bolo de Chocolate">
    </div>
    <div>
        <h3>Ingredientes</h3>
        <p> Massa, 4 colheres (sopa) de chocolate em pó, 2 colheres (sopa) de manteiga, 3 xícaras (chá) de farinha de trigo,4 ovos, Massa, 2 colheres (sopa) de fermento, 1 xícara (chá) de leite e 3 colheres (sopa) de açúcar</p>
    </div>
    <div>
        <h3>Modo de fazer</h3>
        <p>1 - Bata por 5 minutos em um liquidificador os ovos, o chocolate em pó, a manteiga, a farinha de trigo, o açúcar e o leite</p>
        <p>2 - Adicione o fermento e misture com uma espátula delicadamente.</p>
        <p>3 - Em uma forma untada, despeje a massa e asse em forno médio (180 ºC) preaquecido por cerca de 40 minutos. Não se esqueça de usar uma forma alta para essa receita: como leva duas colheres de fermento, ela cresce bastante</p>
    </div>
</body>
</html>
```

```css
div {
    font-family: Verdana;
}

h1 {
    font-size: 22px;
    text-align: center;
}

h2 {
    font-size: 18px;
    color: #88100f;
    font-weight: normal;
    text-align: center;
}

h3 {
    font-size: 16px;
    text-decoration: underline;
    color: #88100f;
}

p {
    font-size: 14px;
    line-height: 28px;
}
```

Ao definir estilos de texto para uma div, todos os elementos de texto que estão dentro dela terão a aparência mudada por esses estilos

Ao decorrer desse curso vimos diversas propriedades úteis no CSS. Elas serão muito utilizadas daqui para frente nos seus projetos e estudos.

Com o que vimos até aqui, já é possível melhorar os estilos de suas páginas, principalmente dos textos. Conhecendo os estilos aprendidos nas aulas, você dá mais um passo na sua carreira para programador front-end.

As propriedades de texto são muito importantes na estilização de páginas web. Isso porque praticamente todo tipo de projeto front-end terá elementos de texto nas suas páginas. Aprender a usar essas propriedades é fundamental para o desenvolvedor front-end deixar os textos com um visual mais apresentável.

#### 8. Faça você mesmo

Nesta aula o objetivo é você mesmo criar o exemplo.

### Construindo o projeto

No flow a seguir vemos como um projeto web deve ser construído:

### Camadas para criar um projeto

1a Camada - Criar a estrutura de pastas e o arquivo HTML

![Faça voce](https://www.devmedia.com.br/arquivos/cursos/css_intro_2426/aula8/27.png)

2a Camada - Criar o código HTML da página

![Faça voce](https://www.devmedia.com.br/arquivos/cursos/css_intro_2426/aula8/36.png)

3a Camada - Criar o código CSS da página

![Faça voce](https://www.devmedia.com.br/arquivos/cursos/css_intro_2426/aula8/55.png)

Parabéns! Você agora conhece os fundamentos do CSS! Durante o curso você aprendeu:

- O que é CSS
- A sintaxe do código CSS
- Propriedades de texto e de cor
- Criar e estilizar uma página web

#### CSS: Propriedades

##### Introdução: 1. Conceito de propriedades

As propriedades representam características dos elementos das páginas web. Quando há uma propriedade com um valor definido, temos um estilo do elemento sendo configurado, o que altera sua aparência na página

![img](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula1/fig1.png)

##### Propriedades: 2. Cor

Uma coisa muito importante na hora de estilizar uma página web é saber alterar as cores de um elemento. Para isso, temos duas propriedades muito conhecidas no CSS que abordamos no curso anterior: color e background-color.

Agora vamos abordar as propriedades, começando pela propriedade `color`:

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades de cor</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Propriedades de cor</h1>
    <p>Temos duas propriedades muito utilizadas no CSS para manipular cores: color e background-color.</p>
</body>
</html>
```

```css
h1 {
    color: blue;
}

p {
    color: red;
}
```

Na **Figura 1** vemos que a propriedade color é responsável por alterar a cor dos elementos de texto. Basta utilizar a propriedade color e o valor da cor que se deseja definir no texto.

![Alterando a cor dos textos](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula2/fig1.png)

Agora veremos a propriedade `background-color`:

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades de cor</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Guia de CSS</h1>
    <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. Vem aprender CSS com a DevMedia. No link abaixo você confere mais sobre essa linguagem de estilo.</p>
    <a href="https://www.devmedia.com.br/css/">Guia de CSS</a>
</body>
</html>
```

```css
h1 {
    font-size: 24px;
}

p {
    font-size: 18px;
}

a {
    font-size: 18px;
    color: white;
    background-color: green;
}
```

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Tecnologias Front-End</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Tecnologias front-end</h1>
    <h2>HTML, CSS e JavaScript estão em alta no mercado</h2>
    <div>
        <p>Para se tornar um desenvolvedor front-end você precisará conhecer as seguintes tecnologias: HTML, CSS e JavaScript. Com elas é possível construir aplicações web e atender a demanda que o mercado pede.</p>
        <p>Abaixo você tem um plano de estudo com essas tecnologias, clique no link e conheça cada uma delas de maneira mais aprofundada.</p>
        <a href="https://www.devmedia.com.br/programacao/front-end">Plano de estudo Front-End</a>
    </div>
</body>
</html>
```

```css
h1 {
    font-size: 32px;
}

h2 {
    font-size: 24px;
}

div {
    background-color: #0000ff;
}

p {
    font-size: 18px;
    color: #ffffff;
}

a {
    font-size: 18px;
    color: #ffffff;
}
```

A seguir veremos como mudar a cor de fundo da tag `body`, que é a tag que contém todos os elementos que são visíveis na tela:

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedade CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Background-color</h1>
    <p>Utilizamos essa propriedade para alterar a cor do plano de fundo, seja de um elemento ou do documento como um todo. Para isso, basta atribuir a cor desejada à propriedade background-color, declarada dentro do seletor no qual ela deve ser aplicada.</p>
</body>
</html>
```

```css
body {
    background-color: #1053ac;
}

h1 {
    font-size: 32px;
    color: #ffffff;
}

p {
    font-size: 18px;
    color: #ffffff;
}
```

Trabalhar com cores é essencial para o desenvolvedor front-end. Vimos que no CSS temos duas formas para manipular cores de elementos. Uma delas é com a propriedade color, onde alteramos a cor dos textos e a outra forma é com a propriedade background-color, que nos permite mudar a cor de fundo dos elementos.

##### Propriedades: 3. Fonte

É muito importante para o programador front-end conhecer as propriedades CSS a fim de ter diversas opções de estilos para usar em suas páginas web. A seguir veremos mais algumas propriedades CSS, que são bastantes utilizadas na estilização de elementos HTML:

![Aula Fonte](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula3/7.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
     <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O CSS é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
</body>
</html>
```

```css
h1 {
    font-size: 48px;
    font-family: 'Verdana';
}
```

Existem muitas famílias de fontes no CSS. Algumas delas são fontes padrão, ou seja, já vem nativamente no navegador. Já outras são externas onde se torna necessário instalar essas fontes ou usar um link externo para usá-las.

No artigo [Lista de fontes padrão do CSS](https://www.devmedia.com.br/lista-de-fontes-padrao-no-css/43215) você vai conferir a lista das fontes padrão mais utilizadas na linguagem.

- Propriedade `font-weight`:

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
     <p>Aprenda o que é o CSS e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O <span>CSS</span> é uma linguagem fundamental para quem quer trabalhar com <span>desenvolvimento web</span>. Abaixo você tem o ponto de partida para o seu aprendizado</p>
</body>
</html>
```

```css
h1 {
    font-size: 48px;
    font-family: Verdana;
}

p {
    font-size: 24px;
    font-family: Verdana;
    font-weight: bold;
}
```

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
     <p>Aprenda o que é o <span>CSS</span> e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O <span>CSS</span> é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
</body>
</html>
```

```css
h1 {
    font-size: 48px;
    font-family: Verdana;
}

p {
    font-size: 24px;
    font-family: Verdana;
}

span {
    font-weight: bold;
}
```

![Aplicando negrito em partes do texto](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula3/fig1.png)

- Propriedade `text-decoration`:

![Propriedades de fonte](https://www.devmedia.com.br/arquivos/cursos/css_intro_2426/aula6/28.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
     <p>Aprenda o que é o <span>CSS</span> e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O <span>CSS</span> é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
<a href="https://www.devmedia.com.br/css">Guia de CSS</a>
</body>
</html>
```

```css
h1 {
    font-size: 48px;
    font-family: Verdana;
    text-decoration: underline;
}

p {
    font-size: 24px;
    font-style: italic;
    font-weight: bold;
}

span {
   font-weight: bold;
}
```

- Propriedade `text-align`:

Existem outras propriedades que são muito importantes na estilização de textos. A seguir veremos a propriedade que é responsável pelo alinhamento de textos:

![Aula Fonte](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula3/41.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
    <p>Aprenda o que é o <span>CSS</span> e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O <span>CSS</span> é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
    <a href="https://www.devmedia.com.br/css">Guia de CSS</a>
</body>
</html>
```

```css
h1 {
    font-size: 48px;
    font-family: Verdana;
    text-decoration: underline;
    text-align: center;
}

p {
    font-size: 24px;
    font-family: Verdana;
}

span {
    font-weight: bold;
}

a {
    font-size: 24px;
    text-decoration: none;
}
```

- Propriedade `line-height`:

Propriedade no CSS que é responsável por definir a altura das linhas de textos:

![Aula Fonte](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula3/46.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Introdução ao CSS</h1>
    <h2>Linguagem de estilos</h2>
    <p>Aprenda o que é o <span>CSS</span> e como ele funciona. Comece a criar os seus primeiros estilos formatando elementos de texto. O <span>CSS</span> é uma linguagem fundamental para quem quer trabalhar com desenvolvimento web. Abaixo você tem o ponto de partida para o seu aprendizado</p>
    <a href="https://www.devmedia.com.br/css">Guia de CSS</a>
</body>
</html>
```

```css
h1 {
    font-size: 48px;
    font-family: Verdana;
    text-decoration: underline;
    text-align: left;
}

h2 {
    font-size: 28px;
    font-family: Verdana;
    color: gray;
}

p {
    font-size: 24px;
    font-family: Verdana;
    line-height: 48px;
}

span {
    font-weight: bold;
}

a {
    text-decoration: none;
}
```

- Elemento `div`:

A seguir veremos como elementos de textos recebem estilos através de um `container`:

![Aula Fonte](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula3/59.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>Estilos de fonte</h1>

    <div>
        <p>No CSS temos diversas propriedades que servem para estilizar textos nas páginas web. Algumas delas são font-size, font-family, color etc. Para conhecer mais dessas fontes, clique no link abaixo.</p>
        <a href="https://www.devmedia.com.br/estilizando-fontes-com-css/24226">Estilizando fontes no CSS</a>
    </div>

</body>
</html>
```

```css
h1 {
    font-size: 36px;
    font-family: Arial;
    text-decoration: underline;
    text-align: center;
}

div {
    font-size: 24px;
    font-family: Arial;
}
```

Ao utilizar as propriedades **font-size** e **line-height** inserimos um número seguido por **px**. Pixel (px) é uma unidade de medida. Existem outras como, por exemplo, cm (centímetros), mm (milímetros), in (polegadas), entre outras, porém, pixel (px) é a mais utilizada nos códigos CSS.

As fontes representam uma parte muito importante nas páginas web, visto que basicamente todos os sites possuem texto em suas páginas. Aprender a usar propriedades para fontes como font-size e font-family é fundamental para o desenvolvedor web deixar os textos com uma aparência mais apresentável.

##### Propriedades 4. Altura e largura:

No CSS temos duas propriedades que definem a área que um elemento ocupa na tela: `height` (altura) e `width` (largura).

![Aula Tamanho](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula4/3.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Propriedades de Tamanho</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <div>
        <h1>Propriedades de Tamanho</h1>
    </div>
</body>
</html>
```

```css
div {
    height: 100px;
    width: 400px;
    background-color: #00FF00;
}
```

As propriedades `height` e `width` podem ser usadas em qualquer elemento do HTML.

![Aula Tamanho](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula4/12.png)

![Aula Tamanho](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula4/15.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Resultado da pesquisa</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <div>
        <img src="homem-aranha.jpg"/>
        <h1>Homem-Aranha é o herói mais querido dos fãs</h1>
        <p>Pesquisa feita com mais de 3 mil entrevistados revelaram que o herói da Marvel é o preferido do mundo dos super-heróis com 48% da preferência do público. Logo atrás vem a dupla da DC, Super-Homem e Batman, com 23% e 12% do percentual dos votos respectivamente.</p>
    </div>
</body>
</html>
```

```css
h1 {
    font-size: 32px;
    font-family: 'Arial';
}

p {
    font-size: 18px;
    line-height: 28px;
    font-family: 'Arial';
}

img {
    height: 375px;
    width: 500px;
}
```

Ao utilizar `height` e `width` em uma imagem é importante ter atenção com as dimensões (altura e largura) originais da imagem. 

Também é possível definir apenas a largura ou a altura de uma imagem no CSS. Essa é uma forma de deixar uma imagem proporcional, pois o outro valor não definido será ajustado automaticamente.

As propriedades height e width são importantes pois com elas definimos o espaço que um elemento ocupa na tela. Isso nos permite fazer ajustes na tela, como por exemplo diminuir o tamanho de uma imagem que ocupa mais espaço do que deveria. Height e width são umas das propriedades mais usadas no CSS.

##### Propriedades 5. Margem

Nessa aula veremos propriedades que são usadas para criar margens entre elementos. Essas propriedades são muito úteis na estilização da página, pois evitam que os elementos fiquem “colados” uns nos outros.

![Aula Margem](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula5/2.png)

![Aula Margem](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula5/6.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Tecnologias Front-End</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <h1>PS5: Sony realizará PlayStation Showcase em 9 de setembro</h1>
    <p>A Sony divulgou nesta quinta-feira (2) um novo PlayStation Showcase 2021, evento que contará com os futuros lançamentos da empresa para PlayStation 5. A transmissão ao vivo ocorrerá no dia 9 de setembro (quinta-feira), nos canais oficiais da marca no YouTube e Twitch.</p>
</body>
</html>
```

```css
h1 {
    font-size: 20px;
    font-family: Verdana;
    text-align: center;
    margin: 60px;
}

p {
    font-size: 18px;
    font-family: Verdana;
    text-align: justify;
    margin: 60px;
}
```

Agora veremos propriedades mais específicas que também aplicam margem em elementos. No flow a seguir vamos conhecer as propriedades `margin-top`, `margin-bottom`, `margin-right` e `margin-left`:

![Aula Margem](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula5/13.png)

![Aula Margem](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula5/22.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Tecnologias Front-End</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <div>
        <h1>5 mitos sobre alergias e intolerâncias a alimentos</h1>
        <h2>Nem sempre ter sintomas após comer um alimento é sinal de alergia</h2>
    </div>
    <div>
        <img src="alimentos.jpg">
        <img src="alimentos2.jpg">
        <p>De acordo com pesquisas recentes, até 35% das pessoas se diagnosticam erroneamente (ou a seus filhos) com uma intolerância alimentar ou alergia e, em seguida, tentam lidar com isso sozinhas, em vez de procurar aconselhamento médico adequado.</p>
    </div>
</body>
</html>
```

```css
div {
    width: 600px;
    margin-top: 50px;
    margin-bottom: 50px;
    margin-left: 50px;
    margin-right: 50px;
}

h1 {
    font-size: 24px;
    font-family: Verdana;
}

h2 {
    font-size: 14px;
    font-family: Verdana;
    color: #313131;
}

img {
    width: 280px;
}

p {
    font-size: 18px;
    font-family: Verdana;
    text-align: justify;
}
```

Agora veremos formas mais resumidas de utilizar a propriedade `margin`. É importante conhecer essas formas porque são bastante usadas na estilização de páginas web:

![Aula Margem](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula5/28.png)

No flow a seguir veremos uma forma que é muito útil para centralizar elementos em uma página web:

![Aula Margem](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula5/33.png)

![Aula Margem](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula5/38.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Tecnologias Front-End</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <div>
        <h1>Tecnologias no desenvolvimento front-end</h1>
        <h2>As tecnologias front-end são essenciais para a construção de páginas web. A utilização delas em conjunto nos permite criar diversos tipos de páginas web.</h2>
        <h3>HTML5</h3>
        <p>HTML5 é uma linguagem de marcação para a World Wide Web e é uma tecnologia chave da Internet, originalmente proposto por Opera Software. É a quinta versão da linguagem HTML.</p>
        <h3>CSS3</h3>
        <p>CSS3 é a terceira mais nova versão das famosas Cascading Style Sheets, pela qual se define estilos para um projeto web. Com efeitos de transição, imagem, imagem de fundo/background e outros, pode-se criar estilos únicos para seus projetos web.</p>
        <h3>JavaScript</h3>
        <p>JavaScript é uma linguagem de programação interpretada estruturada, de script em alto nível com tipagem dinâmica fraca e multiparadigma. Juntamente com HTML e CSS, o JavaScript é uma das três principais tecnologias da World Wide Web.</p>
    </div>
</body>
</html>
```

```css
div {
    margin: 0 auto;
}

h1 {
    font-size: 24px;
    font-family: Verdana;
}

h2 {
    font-size: 16px;
    font-family: Verdana;
    color: #777777;
}

h3 {
    font-size: 18px;
    font-family: Verdana;
    color: #ff4400;
}

p {
    font-size: 16px;
    font-family: Verdana;
    text-align: justify;
}
```

Sempre que precisar definir todas as margens de um elemento utilize a propriedade **margin** ao invés de especificar cada uma das margens. Veja o exemplo abaixo:
_margin: 20px 45px 50px 60px;_
Dessa forma o código fica mais legível e fácil de manter

No flow a seguir veremos sobre a remoção de margens, quando utilizamos o valor 0:

![Aula Margem](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula5/41.png)

![Aula Margem](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula5/44.png)

As propriedades de margem são muito úteis quando precisamos distanciar elementos. Com elas podemos deixar o layout de uma página mais agradável, evitando que os elementos fiquem "colados" entre si.

##### Propriedades 6. Borda

Nessa aula veremos propriedades que são usadas para criar bordas nos elementos. Essas propriedades são muito usadas na estilização de elementos, pois com elas criamos linhas que ficam ao redor do elemento.

![Aula Borda](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula6/2.png)

![Aula Borda](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula6/3.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Tecnologias Front-End</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <div>
        <h1>Evento debate acesso a testes genéticos e medicina de precisão</h1>
        <p>Estima-se que 6% a 8% da população mundial de 7,8 bilhões de pessoas são afetadas por alguma doença genética, sendo que ao menos 4 entre 10 pacientes recebem um diagnóstico errado ao menos uma vez, complicando seus quadros clínicos. Por meio da Medicina Genética, dispõe-se de conhecimento para oferecer agilidade, personalização e precisão no diagnóstico e tratamento dos pacientes diagnosticados com estas doenças. Este contexto também se aplica para as chamadas síndromes hereditárias de câncer. Por sua vez, é um conhecimento que ainda não chegou a uma grande parcela dos profissionais de saúde e não é realidade para os pacientes no SUS.</p>
    </div>
</body>
</html>
```

```css
div {
    width: 600px;
    border-width: 2px;
    border-style: solid;
    border-color: #454545;
}

p{
    font-size: 24px;
    text-align: center;
}
```

Agora veremos a sintaxe das propriedades de borda. Vamos abordar como elas são aplicadas nos elementos:

![Aula Borda](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula6/10.png)

![Aula Borda](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula6/12.png)

![Aula Borda](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula6/15.png)

Agora veremos como definir bordas utilizando uma propriedade que aplica as características de borda uma vez só:

![Aula Borda](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula6/23.png)

![Aula Borda](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula6/29.png)

A ordem dos valores não altera a aparência da borda do elemento. Porém, para seguir questões de boas práticas, é indicado usar a forma padrão de declaração dos valores da borda.

Propriedades específicas que aplicam bordas em cada um dos lados de um elemento:

![Aula Borda](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula6/33.png)

![Aula Borda](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula6/39.png)

Utilize a propriedade **border** quando todas as bordas tiverem os mesmos valores. Isso oferece as seguintes vantagens:

- código menor e mais fácil de manter
- conter todos os valores de borda em uma propriedade só

As propriedades de borda são muito utilizadas quando precisamos definir o contorno de elementos. Com elas podemos deixar a estilização mais agradável, definindo as características da borda (largura, estilo e cor) de um elemento.

##### Propriedades 7. Espaçamento interno

Nessa aula veremos a propriedade `padding` que é usada para criar espaçamento interno nos elementos. Essa propriedade é muito utilizada, pois com ela podemos criar espaços ao redor do conteúdo de um elemento.

![Aula Espaçamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula7/3.png)

![Aula Espaçamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula7/6.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Front-End</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <a href="https://www.devmedia.com.br/css">Guia de CSS</a>
</body>
</html>
```

```css
a {
    font-family: Verdana;
    font-size: 24px;
    text-decoration: none;
    background-color: #3198c2;
    color: #ffffff;
    border: 2px solid black;
    padding: 20px;
}
```

Uma comparação entre as propriedades `margin` e `padding`, mostrando no que são diferentes.

![Aula Espaçamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula7/11.png)

![Aula Espaçamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula7/15.png)

Resumo das diferenças entre as propriedades `margin` e `padding`:

- Padding:
  - Espaço dentro do elemento
  - Fica dentro da borda
- Margin:
  - Espaço fora do elemento
  - Fica fora da borda

Agora veremos propriedades mais específicas que também aplicam espaçamento interno em elementos. Vamos conhecer as propriedades `padding-top`, `padding-bottom`, `padding-right` e `padding-left`:

![Aula Espaçamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula7/20.png)

Agora veremos formas mais resumidas de utilizar a propriedade `padding`. É importante conhecer essas formas porque são bastante usadas na estilização de páginas web:

![Aula Espaçamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula7/30.png)

![Aula Espaçamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula7/32.png)

A forma compacta da propriedade padding é muito utilizada, pois deixa o código mais legível e fácil de manter.

As propriedades de espaçamento interno são muito utilizadas para estilizar páginas web, pois com elas podemos criar espaços ao redor do conteúdo de um elemento. Isso faz com que as bordas do elemento não fiquem grudadas no seu conteúdo.

##### Propriedades 8. Arredondamento de bordas

Nessa aula veremos a propriedade `border-radius` que serve para arredondar os cantos das bordas de um elemento.

![Aula Arredondamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula8/4.png)

![Aula Arredondamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula8/7.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Bordas No CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>

    <div id="teste">
        <p>Elemento <span>div</span></p>
    </div>
</body>
</html>
```

```css
div {
    width: 200px;
    padding: 5px;
    border: 8px solid #000;
    border-radius: 15px;
}

p {
    font-size: 24px;
    text-align: center;
}
```

Quando a propriedade border-radius tem um único valor, ele é usado para arredondar todos os quatro cantos do elemento.

Agora veremos como usar a propriedade `border-radius` para aplicar valores diferentes para cada canto do elemento.

![Aula Arredondamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula8/10.png)

![Aula Arredondamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula8/11.png)

![Aula Arredondamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula8/13.png)

![Aula Arredondamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula8/14.png)

![Aula Arredondamento](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula8/15.png)

Um estilo muito usado com a propriedade `border-radius` é o arredondamento das bordas de apenas um lado do elemento. Essa estilização é utilizada em diversos elementos, especialmente títulos e subtítulos, o que pode melhorar a aparência do elemento na página.

##### Propriedades 9. União de estilos

Vamos aprender sobre a união de estilos no CSS. 

![Aula União](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula9/2.png)

![Aula União](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula9/4.png)

```html
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="UTF-8">
    <title>Front-End</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <span>Tecnologias Front-End</span>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>
    <a href="https://www.devmedia.com.br/programacao/front-end">Guia Front-End</a>
</body>
</html>
```

```css
span, li, a {
    font-size: 24px;
    font-family: Verdana;
    color: #2255ee;
}
```

A união de estilos nos oferece a vantagem de não replicar código CSS para os elementos que tenham os mesmos estilos.

A união de estilos no CSS é muito útil pois nos permite aplicar estilos em diversos elementos de uma vez só. Além disso, usar a união de estilos deixa o código mais legível e fácil de manter.

##### Propriedades 10. Exemplo prático

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Barbearia Stylus</title>
        <link rel="stylesheet" href="estilo.css">
    </head>
    <body>
        <div>
            <img src="img/logotipo.jpg">
            <h1>O lugar que faz seu estilo</h1>
            <h2>Venha conhecer nossos serviços e ver todas as vantagens de assinar o nosso plano.</h2>
        </div>
        <div>
            <h3>NOSSOS SERVIÇOS</h3>
            <p>Somos especializados em cortes masculinos oferecendo um serviço moderno e de qualidade. Temos uma grande variedade de tipos de corte especiais para nossos clientes. Também temos um plano que oferece muitas vantagens para nossa clientela.</p>
        </div>
        <div>
            <h3>CONTATO</h3>
            <p>Você pode entrar em contato conosco através do email <span>contato@barbeariastylus.com.br</span> ou através do telefone <span>(21) 99999-9999</span> (WhatsApp)</p>
            <a href="https://api.whatsapp.com/send?phone=999999999&text=Send20%a20%quote">Fale conosco no WhatsApp</a>
        </div>
    </body>
</html>
```

```css
body {
    background-color: #f1f1f1;
}

img {
    width: 190px;
}

div {
    width: 600px;
    margin: 0 auto;
    text-align: center;
}

h1 {
    font-size: 24px;
    font-family: Verdana;
    color: #606062;
    padding: 10px;
    border: 5px solid #606062;
}

h2 {
    font-size: 20px;
    font-family: Verdana;
    color: #7a797b;
    margin: 35px 20px;
}

h3 {
    font-size: 18px;
    font-family: Verdana;
    font-weight: normal;
    color: #606062;
    padding: 10px 0;
    margin-top: 30px;
    border-top: 2px solid #606062;
    border-bottom: 2px solid #606062;
}

p {
    font-size: 18px;
    font-family: Verdana;
    text-align: justify;
    line-height: 32px;
    color: #616163;
    margin-bottom: 35px;
}

span {
    font-weight: bold;
}

a {
    font-size: 16px;
    font-family: 'Verdana';
    font-weight: bold;
    text-decoration: none;
    padding: 10px 15px;
    margin-top: 15px;
    color: #ffffff;
    background-color: #25D366;
    border-radius: 25px;
}
```

![img](https://www.devmedia.com.br/arquivos/cursos/CSS_propriedades/aula11/layout_completo.png)

Com as propriedades vistas nesse curso, você terá mais recursos na hora de estilizar uma página web. Conhecendo e praticando os estilos aprendidos nas aulas, você avança na sua carreira como programador front-end.

As propriedades de texto são usadas em quase todos os elementos de uma página web. Vimos no exemplo da aula diversos estilos de texto sendo aplicados nos elementos. As propriedades `font-size` e `font-family` geralmente são usadas em todos os textos para que eles fiquem de acordo com o design da página.

##### Propriedades 11. Faça você mesmo





















