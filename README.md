# Read-me

Blog criado em Quarto usando RStudio. Usei o vídeo [Blogging with Quarto: a 10 minute getting started tutorial](https://www.youtube.com/watch?v=YoKjBcuUP0s) como referência.

## 1. Acesso ao Blog

[Prof. Robson](https://robsonfvilela.github.io/profrobson/)

## 2. Editar `_quarto.yml`

É preciso adicionar o comando `output-dir: docs` ao arquvio `_quarto.yml` para que o RStudio gere os posts no diretório `docs`. Assim o GitHub pode transformá-los em um site.

``` r
project:
  type: website
  output-dir: docs

website:
  title: "profrobson"
  navbar:
    right:
      - about.qmd
      - icon: github
        href: https://github.com/robsonfvilela
      - icon: twitter
        href: https://twitter.com/robsonfvilela
format:
  html:
    theme: solar
    css: styles.css
```
