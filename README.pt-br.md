![ArtGarage](/images/ArtGarage.png)

# ArtGarage

Aplicativo Frontend construído com HTML, CSS e JavaScript puro. Foram utilizados Flexbox e media queries para o design responsivo, visando atender a múltiplos tipos de dispositivos, tanto desktop quanto mobile, com diferentes resoluções. A webApp pode ser acessada [aqui](https://nothingnothings.github.io/ArtGarage/).

A versão com Webpack deste aplicação web pode ser encontrada [aqui](https://github.com/nothingnothings/ArtGarageWebpackVersion).

![CodeFactor Grade](https://img.shields.io/codefactor/grade/github/nothingnothings/ArtGarage/master?style=flat-square)
[![en](https://img.shields.io/badge/lang-en-red.svg?style=flat-square)](https://github.com/nothingnothings/ArtGarage)
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg?style=flat-square)](https://github.com/nothingnothings/ArtGarage/blob/master/README.pt-br.md)

## Tecnologias

Algumas das linguagens e bibliotecas utilizadas:

- HTML5
- CSS3 (animações, principalmente Flexbox e estilos comuns, com media queries para ajustes)
- JavaScript puro (sem frameworks JavaScript; uso de `var`, funções normais e eventListeners comuns)

## Estrutura de Diretórios do Projeto

```
.\
│
├── images\
│   ├── ArtGarage.png
│   ├── about1.jpg
│   ├── about2.jpg
│   ├── favicon.ico
│   ├── products1.jpg
│   ├── products2.jpg
│   └── products3.jpg
│
├── scripts\
│   └── index.js
│
├── README.md
├── index.html
└── style.css

```

## Configuração

Para usar este projeto, clone-o usando o Git:

1. Execute `git clone` para clonar o projeto em seu repositório local Git.
2. Sirva os arquivos com a ajuda de um provedor de hospedagem (apenas frontend).

## Recursos

- Aplicativo web inspirado em SPA (Single-Page Application)
- Design responsivo (mobile e desktop) criado com Flexbox e media queries
- Adição/remoção de classes CSS (animação "slide-in"), implementada com JavaScript
- Uso de GitHub Actions para, ao executar o comando git push, transferir o conteúdo do branch master para o branch gh-pages, que então realiza o deploy em https://nothingnothings.github.io/ArtGarage/.
- Favicon personalizado, compatível com múltiplos dispositivos 

## Inspiração

Este aplicativo foi baseado no curso "CSS Flexbox" oferecido pela Origamid.


