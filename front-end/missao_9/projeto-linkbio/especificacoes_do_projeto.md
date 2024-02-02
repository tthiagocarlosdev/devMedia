

passo_3_especificacoes_do_layout, passo_4_orientacoes_basicas, passo_5_arquivos_do_projeto e passo_6_dicas_de_implementacao

# Projeto passo a passo: LinkBio do Neymar Jr.

## 2º passo: Especificações do Projeto

- O site será uma página simples com duas seções:

- [x] Seção Banner;

- [x] Seção Estatísticas.

![Estrutura da página](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig1.png)



- Na Seção Banner, teremos os seguintes elementos:

  - [ ] Um vídeo como plano de fundo;

  - [x] Uma imagem (logo);

  - [x] Um título;

  - [x] Cinco links;

![Seção Banner](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig2.png)



- Já a Seção Estatísticas terá como parte da estrutura os seguintes elementos:
  - [ ] Uma imagem como plano de fundo;
  - [ ] Um subtítulo;
  - [ ] Uma tabela informativa com as estatísticas do Neymar.

![Seção Estatísticas](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig3.png)

## Conhecendo as especificações do projeto

- [ ] ##### 1- O site deve ter um vídeo que será aplicado como plano de fundo da Seção Banner
  
  - [ ] O vídeo deve ser executado automaticamente, em looping e não deve reproduzir áudio.




- [ ] ##### 2- A imagem que será usada como logo da Seção Banner deve ter um formato circular e ter uma borda com uma cor gradiente

![Imagem (logo) da Seção Banner](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig4.png)

- [ ] ##### 3- O título do site deve ter uma "tarja" com cor gradiente, posicionada abaixo das letras "Ne" e uma imagem de "perfil verificado" posicionada à direita do título

![Título da Seção Banner](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig5.png)

- [ ] ##### 4- Os links externos do site devem direcionar o usuário para as redes sociais do Neymar Jr.

![Especificações do Projeto](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig6.png)

![Especificações do Projeto](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig7.png)

- [ ] ##### 5- A cor de fundo de um link deve ser modificada sempre que um usuário passar o cursor do mouse sobre o link

![Link sofrendo alteração](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig8.png)

- [ ] ##### 6- Na Seção Estatísticas, uma imagem deve ser aplicada como plano de fundo e também possuir o efeito Parallax

![Especificações do Projeto](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/31.png)



- [ ] ##### 7- O título da Seção Banner e o subtítulo da Seção Estatísticas devem ter um efeito de sombreamento

![Título com efeito sombreado](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig9.png)

![Subtítulo com efeito sombreado](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig10.png)



- [ ] ##### 8- A tabela da Seção Estatísticas terá as informações sobre o Neymar Jr.

![Tabela informativa](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig11.png)



- [ ] ##### 9 - As linhas da tabela devem ter um efeito "zebrado"

![Especificações do Projeto](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/35.png)

![Especificações do Projeto](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/36.png)



- [ ] ##### 10- O projeto deve utilizar as imagens fornecidas

No desenvolvimento do projeto serão utilizados treze imagens:

- [x] Uma imagem utilizada como logo da página;
- [ ] Uma imagem utilizada como "perfil verificado" no título da Seção Banner;
- [x] Cinco imagens utilizadas como ícones dos links;
- [x] Uma imagem utilizada como plano de fundo na Seção Estatísticas;
- [x] Cinco imagens utilizadas como ícones na primeira coluna da tabela.

![Imagens utilizadas no projeto](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig12.png)



- [ ] ##### 11 - Especificações do layout

O projeto será desenvolvido conforme o layout:

![Layout da página Home](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo2/fig13.png)



## 3º passo: Especificações do layout

O objetivo deste passo é disponibilizar as especificações do layout do projeto.

A ideia é dar a você informações sobre as dimensões (*altura, largura e espaçamento*) dos elementos HTML da página.

O projeto será desenvolvido conforme o layout:

![Estrutura da página](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig1.png)

- [x] ##### Fontes do Projeto

O projeto deve utilizar como padrão as fontes __Ysabeau Infant__ e __Montserrat__ para os textos do site.

![Utilização das fontes no projeto (parte 1)](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig3.png)

![Utilização das fontes no projeto (parte 2)](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig4.png)

- html

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Ysabeau+Infant&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
```

- css

 ```css
 font-family: 'Montserrat', sans-serif;
 font-family: 'Ysabeau Infant', sans-serif;
 ```



- [x] ##### Paleta de cores

```css
#fff
#ffffffcc
#000000
#000000cc
#0200006e
#ffdf00
#009c3b
```

![Especificações do Layout](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/47.png)

![Especificações do Layout](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/48.png)

![Especificações do Layout](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/49.png)



- [ ] ##### Conhecendo as dimensões do layout

  - [x] 1 - A Seção Banner deve ocupar a largura total da tela e ter uma altura de 100vh, garantindo que o vídeo ocupe todo o espaço disponível na seção.

  ![Especificações do Layout](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/51.png)

  

  - [ ] 2 - A imagem de perfil da Seção Banner terá largura e altura de 200px e ficará espaçada a 20px (gap) do título.

  ![Dimensões da imagem de perfil](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig5.png)

  

  - [x] 3 - O container dos links terá uma largura de 768px e ficará espaçado a 40px do container de informações

  ![Dimensões do container dos links](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig6.png)

  

  - [x] 4 - Os links ocuparão toda a largura do container, terão um espaçamento interno de 10px e ficarão espaçados a 20px (gap) entre si.

  ![Dimensões dos links](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig7.png)

  

  - [x] 5 - A Seção Estatística deve ocupar a largura total da tela e ter uma altura de 100vh, garantindo que a imagem de fundo ocupe todo o espaço disponível na seção

  ![Dimensões da Seção Estatística](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig8.png)

  

  - [x] 6- Haverá um espaço de 40px (gap) entre o subtítulo e a tabela da Seção Estatística

  ![Espaçamento entre os elementos da Seção Estatística](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig9.png)

  

  - [x] 7- Todas as células da tabela terão um espaçamento interno de 20px

  ![Espaçamento interno das células da tabela](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig10.png)

  

  - [ ] 8- As células da primeira coluna terão seus elementos alinhados lado a lado na horizontal, com cada imagem tendo uma largura de 30px e um espaçamento de 10px (gap) entre elas e os textos

  ![Alinhamento e espaçamento das células da primeira coluna](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig11.png)

  

  - [ ] 9- Os elementos da página devem estar centralizados

  ![Layout centralizado](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo3/fig12.png)



## 4º passo: Orientações básicas

## 5º passo: Arquivos do projeto

- ##### TEXTO DA SEÇÃO BANNER

<titulo> Neymar Jr

<link> Siga meu canal no YouTube
<link> Me siga no Instagram
<link> Me siga no Twitter
<link> Me siga no Facebook
<link> Me siga na Twitch

- ##### TEXTO DA SEÇÃO ESTATÍSTICAS

<subtitulo> Estatísiticas

<tabela>
Times -> Brasil / Santos / Barcelona / PSG / Al-Hilal
Temporadas -> 13 / 5 / 4 / 6 / 1
Jogos -> 124 / 230 / 186 / 173 / 0
Gols -> 77 / 138 / 105 / 118 / 0 
Assistências -> 77 / 77 / 77 / 77 / 77
Títulos -> 2 / 6 / 8 / 13 / 0

## 6º passo: Dicas de Implementação

- [ ] ### 1 - Como definir um vídeo de plano de fundo

Para que o vídeo do projeto seja aplicado como plano de fundo da Seção Banner, você pode realizar os seguintes passos:

1. Utilizar a ***tag <video>\*** para aplicar o vídeo;
2. Utilizar ***propriedades CSS\*** para fazer com que o vídeo ocupe todo o espaço da Seção Banner e seja exibido por trás dos outros elementos desta seção.

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/90.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/91.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/92.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/93.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/94.png)

__A tag HTML `<video>` permite definir as dimensões (largura e altura) de um vídeo através dos atributos width e height.__

- HTML

```html
<video
     autoplay loop muted
     src="./video/videoneymar.mp4"
     type="video/mp4">
</video>
```

- css

```css
.secao-banner video {
  position: absolute;
  z-index: -1;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```



- [ ] ### 2 - Como criar uma borda cor gradiente

Você pode criar o efeito de uma borda com cor gradiente na imagem de perfil da Seção Banner utilizando o pseudo-elemento CSS ::before

![Efeito de borda com cor gradiente](http://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/fig1.png)

Um gradiente é um efeito que cria uma mistura de cores, geralmente indo de uma cor para outra de forma suave e gradual.

Um gradiente pode ser linear ou circular e pode ser personalizado conforme a preferência do programador/designer.

![Exemplos de gradientes](http://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/fig2.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/98.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/99.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/100.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/101.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/102.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/103.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/104.png)

- css

```css
.container {
  width: 200px;
  height: 200px;
  background-color: black;
  border-radius: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.container::before {
  content: "";
  width: 215px;
  height: 215px;
  position: absolute;
  background: linear-gradient(90deg, #ffdf00, #009c3b);
  border-radius: 100%;
  z-index: -1;
}
```



- [ ] ### 3 - Como criar uma "tarja" gradiente

Você pode criar o efeito de uma "tarja" com cor gradiente abaixo das letras "Ne" do título "Neymar Jr." utilizando o pseudo-elemento CSS ::before,

![Efeito de tarja com cor gradiente](http://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/fig3.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/108.png)

![Dicas de Implementação](https://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/109.png)

- css

```css
.logo-titulo h1::before {
  content: "";
  position: absolute;
  bottom: 2px;
  left: 5px;
  width: 55px;
  height: 5px;
  border-radius: 4px;
  background: linear-gradient(90deg, #ffdf00, #009c3b);
}
```



- [ ] ### 4 - Como criar efeito de sombra no título e subtítulo

Você pode criar um efeito de sombra no título e no subtítulo da página utilizando a propriedade CSS text-shadow, 

![Dica de como criar o sombreado do título e subtítulo](http://www.devmedia.com.br/arquivos/projeto_guiado/front-end/linkbio/passo6/fig4.png)

- css

```css
div h2 {
  font-size: 74px;
  color: #fff;
  text-shadow: 3px 6px 1px #000000;
}
```

- [ ] Certifique-se de definir o vídeo como plano de fundo da Seção Banner.
- [ ] Certifique-se de criar o efeito de borda gradiente na imagem de perfil da Seção Banner.
- [ ] Certifique-se de criar o efeito de "tarja" gradiente abaixo das letras "Ne" do título da página.
- [ ] Certifique-se de criar o efeito de sombra para o título da página utilizando a propriedade text-shadow.

- [ ] 
