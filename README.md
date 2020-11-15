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

Tabela de conteúdos
====================
<!--ts-->
   * [Colocando Imagem Inicial no README](#colocando-imagem-inicial-no-readme)
<!--te-->


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
## Alinhamento e Dimensionamento de Imagem
#### Em Markdown
Para inserir uma imagem em markdown, basta fazer `![](caminho-da-imagem)`.
#### Em Html
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

Nâo consegui escrever diretamente no README usando o <a href="https://www.codecogs.com/eqnedit.php?latex=\LaTeX" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\LaTeX" title="\LaTeX" /></a>.
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

# Criando Ávore de Diretórios para o GitHub
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
