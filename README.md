<p align="center">
  <img
     width="200px"
     align="center"
     src="https://github.com/icaro-freire/mementos_GitHub/blob/master/figs/fig-github.png"
         alt="Mementos GitHub" 
  />
  <h2 align="center">
      Mementos do GitHub
         <p align="center">
             (porque recordar é viver :sweat_smile:)
         </p>
  </h2>
</p>

<p align="center">
  <a href="https://github.com/icaro-freire/mementos_GitHub/issues"><img align="center" alt="GitHub issues" src="https://img.shields.io/github/issues/icaro-freire/mementos_GitHub"></a>
  <a href="https://github.com/icaro-freire/mementos_GitHub/network"><img align="center" alt="GitHub forks" src="https://img.shields.io/github/forks/icaro-freire/mementos_GitHub"></a>
  <a href="https://github.com/icaro-freire/mementos_GitHub/stargazers"><img align="center" alt="GitHub stars" src="https://img.shields.io/github/stars/icaro-freire/mementos_GitHub"></a>
  <a href="https://t.me/IcaroFreire"><img align="center" alt="@IcaroFreire" src="https://img.shields.io/badge/contact-Telegram-blue"></a>
</p>

> `Mementos` significa "lembranças", "recordações". Esse repositório é para arquivamento de comandos do GitHub que vou usando durante o aprendizado. A ideia é organizar num único local onde eu possa acessá-los com facilidade.

Sumário
-------------------
<!--ts-->
   * [Colocando Imagem Inicial no README](#colocando-imagem-inicial-no-readme)
   * [Botões Estilizados (Badges)](#botões-estilizados-badges)
   * [Alinhamento e Dimensionamento de Imagem](#alinhamento-e-dimensionamento-de-imagem)
       - [Em Markdown](#em-markdown)
       - [Em Html](#em-html)
   * [Escrevendo em LaTeX](#escrevendo-em-latex)
   * [Criando Árvore de Diretórios para o GitHub](#criando-árvore-de-diretórios-para-o-github)
<!--te-->
---

# Colocando Imagem Inicial no README

Para colocar a imagem na página inicial de cada reposotório, no README.md, usa-se _html_:

```html
<p align="center">
  <img
     width="200px"
     align="center"
     src="https://github.com/icaro-freire/mementos_GitHub/blob/master/figs/fig-github.png"
         alt="Mementos GitHub" 
  />
  <h2 align="center">
      Mementos GitHub
  </h2>
  <p align="center">
      (Recordar é viver :sweat_smile:)
  </p>
</p>
```
# Botões Estilizados (Badges)
- Para colocar os vários botões estilizados, pode ser usado o _site_ [shields.io <i class="fa fa-external-link" aria-hidden="true"></i>
](https://shields.io/);
- Tal site pode sugerir os _badges_ ou podemos criar um;
     + Caso criemos um, uma imagem é gerada sem um link. Então, precisamos colocar `![url-da-imagem-gerada](link-desejado)`;
- Tenho percebido que o _Html_ facilita na hora da centralização dos objetos. 
Um repositório que contém muitas informações sobre customização de _badges_ é esse [daqui <i class="fa fa-external-link" aria-hidden="true"></i>
](https://github.com/alexandresanlim/Badges4-README.md-Profile).

# Alinhamento e Dimensionamento de Imagem
### Em Markdown
Para inserir uma imagem em markdown, basta fazer `![](caminho-da-imagem)`.
### Em Html
Para inserir e dimensionar, usamos:
```html
<img align="center" src="caminho-da-imagem" alt="nome-alternativo" width="n"/>
```
Pra deixar centralizada no texto:alinhar e dimensionar imagens usamos os comandos em _html_:
```html
<p align="center">
  <img align="center" src="caminho-da-imagem" alt="nome-alternativo" width="n"/>
</p>
```

# Escrevendo em LaTeX

Não consegui escrever diretamente no README usando o <a href="https://www.codecogs.com/eqnedit.php?latex=\LaTeX" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\LaTeX" title="\LaTeX" /></a>.
Para fazer isso, é preciso gerar um `html` num editor _online_ de <a href="https://www.codecogs.com/eqnedit.php?latex=\LaTeX" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\LaTeX" title="\LaTeX" /></a>.\n
Uso o [codecogs][CD].

Por exemplo, se quero gerar a equação:

<p align="center">
  <img 
      src="https://latex.codecogs.com/gif.latex?f(z_0)&space;=&space;\frac{1}{2\pi&space;i}\oint_\Gamma&space;\frac{f(z)}{z&space;-&space;z_0}\,\textrm{d}z"
      title="f(z_0) = \frac{1}{2\pi i}\oint_\Gamma \frac{f(z)}{z - z_0}\,\textrm{d}z"
  />
</p>

Usamos os comandos

```html
<p align="center">
  <img 
      src="https://latex.codecogs.com/gif.latex?f(z_0)&space;=&space;\frac{1}{2\pi&space;i}\oint_\Gamma&space;\frac{f(z)}{z&space;-&space;z_0}\,\textrm{d}z"
      title="f(z_0) = \frac{1}{2\pi i}\oint_\Gamma \frac{f(z)}{z - z_0}\,\textrm{d}z"
  />
</p>
```
Mas, para gerar esses comandos, precisamos:
1. digitar a equação no _site_ [codecogs][CD];
2. verificar o tamanho adequado;
3. copiar o _link_ htlm gerado.

Como mostra a figura a seguir:

<p align="center">
  <img align="center" src="https://github.com/icaro-freire/mementos_GitHub/blob/master/figs/codecogs.png" alt="figura" width="700"/>
</p>

# Criando Árvore de Diretórios para o GitHub
- Uso o _site_ [tree](https://tree.nathanfriend.io/) para digitar meus diretórios de maneira bem simples.
- Depois copio o texto gerado pelo site
- Por fim, colo aqui no README do GitHub
Por exemplo, a árvore de diretórios desse repositório aqui mesmo, é dada por:

```bash
mementos_GitHub/
  .
  ├── figs/
  │   ├── codecogs.png
  │   └── fig-github.png
  └── README.md
```


