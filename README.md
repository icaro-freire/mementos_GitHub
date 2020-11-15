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

Para colocar a imagem na página inicial de cada reposotório, no README.md, usa-se `html`:

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



# Criando Ávore de Diretórios para o GitHub

# ALternativas para Links
<a href="https://www.codecogs.com/eqnedit.php?latex=\tau\varepsilon\chi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\tau\varepsilon\chi" title="\tau\varepsilon\chi" /></a> é tecnologia, em Grego.

Uma equação que gosto muito é essa:

<p align="center">
<img src="https://latex.codecogs.com/gif.latex?f(z_0)&space;=&space;\frac{1}{2\pi&space;i}\oint_\Gamma&space;\frac{f(z)}{z&space;-&space;z_0}\,\textrm{d}z" title="f(z_0) = \frac{1}{2\pi i}\oint_\Gamma \frac{f(z)}{z - z_0}\,\textrm{d}z" /></p>

Essas equações foram feita em LaTeX no [Editor Online Codecogs][CD], o qual gera um html.

[CD]: https://www.codecogs.com/latex/eqneditor.php

Texto qualquer só para dizer que o comando `<p align="center"> <img ...> </p>` deixa a equação centralizada.
Também posso redimensionar dessa forma: `<img width="600" height="200" src="https://www.python.org/python-.png">`, como:

<p align="center">
<img width="200" height="200" src="https://latex.codecogs.com/gif.latex?f(z_0)&space;=&space;\frac{1}{2\pi&space;i}\oint_\Gamma&space;\frac{f(z)}{z&space;-&space;z_0}\,\textrm{d}z" title="f(z_0) = \frac{1}{2\pi i}\oint_\Gamma \frac{f(z)}{z - z_0}\,\textrm{d}z" />
</p>

Mas, fica muito ruim!

Agora um teste para gerar uma árvore de diretórios

#### Deste de árvore de diretório para esse repositório

```
teste_TeX_projeto
  .
  ├── figs/
  │   ├── bateria.png
  │   └── readme.md
  ├── main.txt
  └── README.md
```

#### Forma resumida
```
ativmatUFRB
 │
 ├── guia_ativmatUFRB
 └── classe_ativmatUFRB
 ```
#### Forma não resumida
```
ativmatUFRB
 ■
 │
 ├── guia_ativmatUFRB
 │     ·
 │     ├── aux-files
 │     │    ├── ...
 │     │    └── ...
 │     ├── tex
 │     │    ├── 00_resumo-sumario.tex 
 │     │    ├── 01_antes-de-comecar.tex
 │     │    ├── 02_como-instalar.tex
 │     │    ├── 03_explicando-a-classe.tex
 │     │    └── 04_lista-de-pacotes.tex
 │     ├── guia_ativmatUFRB.cls
 │     ├── guia-ativmatUFRB_v1.61.pdf
 │     ├── guia-ativmatUFRB_v1.61.synctex
 │     ├── guia-ativmatUFRB_v1.61
 │     └── README.md
 │
 ├── classe_ativmatUFRB
 │     ·
 │     ├── aux-files
 │     │     ├── ...
 │     │     └── ...
 │     ├── figs
 │     │     ├── espiral.pdf
 │     │     └── ufrb.jpeg
 │     ├── fonts
 │     │     └── intimacy
 │     │           ├── intimacy.ttf
 │     │           └── intimcy2.ttf
 │     ├── ativmatUFRB.cls
 │     ├── modelo_ativmatUFRB_v1.61.pdf
 │     ├── modelo_ativmatUFRB_v1.61.synctex
 │     ├── modelo_ativmatUFRB_v1.61.tex
 │     └── README.md
 └── README.md
```

