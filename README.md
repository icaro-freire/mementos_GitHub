<p align="center">
  <img
      width = "200px"
      align = "center"
      src   = "https://github.com/icaro-freire/mementos_GitHub/blob/master/figs/fig-github.png"
      alt   = "Mementos GitHub" 
  >
  <h2 align = "center">
      Mementos do GitHub 
          <p align = "center">
             (porque recordar é viver :sweat_smile:)
          </p>
  </h2>
</p>

<p align="center">
  <img
       align = "center" 
       alt   = "GitHub last commit" 
       src   = "https://img.shields.io/github/last-commit/icaro-freire/mementos_GitHub"
  >
  <a href="https://github.com/icaro-freire/mementos_GitHub/network">
      <img 
          align = "center" 
          alt   = "GitHub forks" 
          src   = "https://img.shields.io/github/forks/icaro-freire/mementos_GitHub"
      >
  </a>
  <a href = "https://github.com/icaro-freire/mementos_GitHub/stargazers">
      <img 
          align = "center" 
          alt   = "GitHub stars" 
          src   = "https://img.shields.io/github/stars/icaro-freire/mementos_GitHub"
      >
  </a>
  <a href = "https://github.com/icaro-freire/mementos_GitHub/issues">
      <img 
          align = "center" 
          alt   = "GitHub issues" 
          src   = "https://img.shields.io/github/issues/icaro-freire/mementos_GitHub"
      >
  </a>
</p>
<p align = "center">
  <a href = "https://t.me/IcaroFreire">
      <img 
          align = "center" 
          alt   = "GitHub issues" 
          src   = "https://img.shields.io/badge/contact-Telegram-2CA5E0?logo=Telegram&style=for-the-badge"
      >
  </a>
</p>

> `Mementos` significa "lembranças", "recordações". 
Esse repositório é para arquivamento de comandos do GitHub que vou usando durante o aprendizado. 
A ideia é organizar num único local para que eu possa acessá-los com facilidade.

Sumário
-------------------
<!--ts-->
   * [Colocando Imagem Inicial no README](#colocando-imagem-inicial-no-readme)
   * [Botões Estilizados (Badges)](#botões-estilizados-badges)
   * [Alinhamento e Dimensionamento de Imagem](#alinhamento-e-dimensionamento-de-imagem)
       - [Em Markdown](#em-markdown)
       - [Em Html](#em-html)
       - [Imagens por caminhos absolutos](#imagens-por-caminhos-absolutos)
   * [Escrevendo em LaTeX](#escrevendo-em-latex)
   * [Criando Árvore de Diretórios para o GitHub](#criando-árvore-de-diretórios-para-o-github)
   * [Usando o .gitignore](#usando-o-gitignore)
   * [Linha horizontal em Html](#linha-horizontal-em-html)
   * [Visualizando pdf](#visualizando-pdf)
       - [Com nbviewer](#com-nbviewer)
       - [Com GitHub Pages](#com-github-pages)
   * [Comentários em códigos](#comentarios-em-codigos)
       - [Um simples comentário](#um-simples-comentario)
       - [Comentar várias linhas](#comentar-varias-linhas)
   * [Texlo colapsado](#texto-colapsado)

<!--te-->
---

# Colocando Imagem Inicial no README

Para colocar a imagem na página inicial de cada reposotório, no README.md, usa-se _html_:

```html
<p align = "center">
   <img 
        width = "200px"
        align = "center"
        src   = "https://github.com/icaro-freire/mementos_GitHub/blob/master/figs/fig-github.png"
        alt   = "Mementos GitHub" 
  >
  <h2 align = "center">
      Mementos GitHub
  </h2>
  <p align="center">
      (Recordar é viver :sweat_smile:)
  </p>
</p>
```
# Botões Estilizados (Badges)
  - Para colocar os vários botões estilizados, pode ser usado o _site_ [shields.io](https://shields.io/);
  - Tal site pode sugerir os _badges_ ou podemos criar um;
     + Caso criemos um, uma imagem é gerada sem um link. Então, precisamos colocar `![url-da-imagem-gerada](link-desejado)`;  
  - Tenho percebido que o _Html_ facilita na hora da centralização dos objetos. 
Um repositório que contém muitas informações sobre customização de _badges_ é esse [daqui](https://github.com/alexandresanlim/Badges4-README.md-Profile).

# Alinhamento e Dimensionamento de Imagem
### Em Markdown
Para inserir uma imagem em markdown, basta fazer `![](caminho-da-imagem)`.
### Em Html
Para inserir e dimensionar, usamos:

```html
<img 
     align = "center" 
     src   = "caminho-da-imagem" 
     alt   = "nome-alternativo" 
     width = "n"
>
```
Obsservações
- `align` centraliza a imagem _inline_;
- `src` é o local onde inserimos a *url* onde está hospedada a imagem (numa pasta do repositório, por exemplo);
- `alt` é um nome que irá substituir (nome alternativo) a imagem, caso esta não seja carregada por algum motivo;
- `width` é a largura da imagem e *n* é um número inteiro.
- Além disso, todos esses comandos podem ser digitados na mesma linha, ou seja, caso ideal quanda a imagem (ou equação) estiver *inline*.

Pra deixar centralizada em relação à largura da margem do texto, usamos os comandos em _html_:

```html
<p align="center">
  <img 
       align = "center" 
       src   = "caminho-da-imagem" 
       alt   = "nome-alternativo" 
       width = "n"
  >
</p>
```
### Imagens por caminhos absolutos
- É possível colocar as imagens, usando os diretórios do próprio GitHub.
    + isso evita quebra de _link_ quando pegamos de alguma `url`.
Para o `gif` a segui, o código foi:
```bash
![gato-felix](/figs/gato-felix.gif)
```
![gato-felix](/figs/gato-felix.gif)

Caso precise centralizar, é melhor usar _html_:
```html
<p align="center">
   <img 
        align = "center" 
        src   = "/figs/gato-felix.gif
   >
</p>
```
<p align="center">
   <img 
      align = "center" 
      src   = "/figs/gato-felix.gif"
   >
</p>

# Escrevendo em LaTeX

Não consegui escrever diretamente no README usando o <a href="https://www.codecogs.com/eqnedit.php?latex=\LaTeX" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\LaTeX" title="\LaTeX" /></a>
Para fazer isso, é preciso gerar um `html` num editor _online_ de LaTeX.
Particularmente, uso o [codecogs][CD].

[CD]: https://www.codecogs.com/latex/eqneditor.php?lang=pt-br

Por exemplo, se quero gerar a equação:

<p align="center">
  <img 
      src   = "https://latex.codecogs.com/gif.latex?f(z_0)&space;=&space;\frac{1}{2\pi&space;i}\oint_\Gamma&space;\frac{f(z)}{z&space;-&space;z_0}\,\textrm{d}z"
      title = "f(z_0) = \frac{1}{2\pi i}\oint_\Gamma \frac{f(z)}{z - z_0}\,\textrm{d}z"
  >
</p>

Usamos os comandos

```html
<p align="center">
  <img 
      src   = "https://latex.codecogs.com/gif.latex?f(z_0)&space;=&space;\frac{1}{2\pi&space;i}\oint_\Gamma&space;\frac{f(z)}{z&space;-&space;z_0}\,\textrm{d}z"
      title = "f(z_0) = \frac{1}{2\pi i}\oint_\Gamma \frac{f(z)}{z - z_0}\,\textrm{d}z"
  >
</p>
```
Mas, para gerar esses comandos, precisamos:
1. digitar a equação no _site_ [codecogs][CD];
2. verificar o tamanho adequado;
3. copiar o _link_ htlm gerado.

Como mostra a figura a seguir:

<p align="center">
  <img 
       align = "center" 
       src   = "https://github.com/icaro-freire/mementos_GitHub/blob/master/figs/codecogs.png" alt="figura" width="700"
  >
</p>

# Criando Árvore de Diretórios para o GitHub
- Uso o _site_ [tree](https://tree.nathanfriend.io/) para digitar meus diretórios de maneira bem simples.
- Depois copio o texto gerado pelo site;
- Por fim, colo aqui no README do GitHub.

Por exemplo, a árvore de diretórios desse repositório aqui mesmo, é dada por:

```bash
mementos_GitHub/
  .
  ├── figs/
  │   ├── codecogs.png
  │   └── fig-github.png
  └── README.md
```
Uma outra opção é usar o uma extensão para o editor [Vs Code](https://code.visualstudio.com/), denominada [file-tree-generator
][tree-file].
Com ela, a mesma árvore acima é dada por:
<pre>
📦mementos_GitHub 
 ┣ 📂figs 
 ┃ ┣ 📜codecogs.png 
 ┃ ┣ 📜fig-github.png 
 ┗ 📜README.md 
</pre> 
 
 **Obs.:** o resultado deve estar dentro da _tag_ `<pre> ... </pre>`, para que seja mantido o alinhamento vertical.

[tree-file]: https://marketplace.visualstudio.com/items?itemName=Shinotatwu-DS.file-tree-generator

# Usando o .gitignore

- Para ignorar uma pasta, basta digitar no arquivo _.gitignore_: `nome-da-pasta/` 
- para ignorar arquivos: `*.extensao-do-arquivo` 

# Linha horizontal em Html
Para fazer uma linha horizontal, em _html_ usamos: `<hr width="X%">` ou `<hr width="X">` ou `<hr width="X px">`.

# Visualizando pdf
### Com nbviewer
- Abrir o *site* [https://nbviewer.jupyter.org/](https://nbviewer.jupyter.org/);
- Digitar o `url` (que está no GitHub) do pdf.
### Com GitHub Pages
Para usar a visualização direta do `.pdf` no próprio GitHub, precisamos ativar a *GitHub Pages*.
- Ir em `Settings`;
- Rolar até `GitHub Pages`;
  - Em *Source*, escolher o *Branch* adequado;
  - Escolher uma pasta adequada: pode ser a raiz (*root*) ou criar uma (geralmente *docs*);
  - Salvar;
  - Atualizar algumas vezes a página do seu projeto;
  - O *link* para o `.pdf` é: `https://seu-usuario.github.io/nome-do-projeto/nome-do-arquivo.pdf`

# Comentários em códigos

## Um simples comentário
Para um simples comentário, usamos a sintax:

```
"aqui deve conter uma linhas vazia"
[comentário]: # (escreva aqui seu comentário)
```
- Perceba que há um espaço entre `#` 
- Seu comentário deve estar entre parênteses;
- Deve conter uma linha vazia antes do comentário.
- Entre o colchete, pode vir qualquer texto (geralmente com o nome "comentário", para o identidicar)
## Comentar várias linhas
Para comentar várias linhas, usamos a sintax:

```html
<!--
Escreva aqui
seu
Comentário
-->
```

# Texto colapsado

A *tag* `<details> ... </details>` colapsa um texto longo dentro de um tópico destacado (fazemos esse destaque no tópico com a *tag* `<summary> ... </summary>`).

<details>
  <summary>
    Tópico 01
  </summary>
    Texto longo sobre o tótico 01 ...
</details>
<details>
  <summary>
    Tópico 02
  </summary>
    Texto longo sobre o tótico 02 ...
    <details>
      <summary>
        * Subtópico 2.1
      </summary>
        - Pode fazer subtópicos também!
    </details>
</details>

A ideia acima foi gerada com:

```html
<details>
  <summary>
    Tópico 01
  </summary>
    Texto longo sobre o tótico 01 ...
</details>
<details>
  <summary>
    Tópico 02
  </summary>
    Texto longo sobre o tótico 02 ...
    <details>
      <summary>
        Subtópico 2.1
      </summary>
        Pode fazer subtópicos também!
    </details>
</details>
```
