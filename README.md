# Sistema de Catálogo e Cálculo de Livros

## Descrição

Este projeto simula uma livraria online, onde os usuários podem navegar por diferentes seções, como o Catálogo de Livros, Mais Vendidos, Recomendações, Sobre Nós, e Contato. O sistema foi desenvolvido utilizando HTML, CSS e JavaScript e inclui interatividade, como gráficos dinâmicos com **Chart.js**, cálculos de compras via parâmetros na URL, e redirecionamento de páginas.

A aplicação permite que os usuários visualizem livros disponíveis para compra, adicionem itens ao carrinho e finalizem a compra. O design é baseado em um layout simples e intuitivo, utilizando CSS para a estilização.

## Estrutura de Diretórios

A estrutura de diretórios do projeto é organizada da seguinte forma:

│   .gitattributes
│   package.json
│   package-lock.json
│   README.md
│   
├───css
│       login.css
│       redirecionar.css
│       index.css
│       contato.css
│       sobrenos.css
│       carrinho.css
│       confirmacao.css
│       catalogo.css
│       maisvendido.css
│       recomendacoes.css
│
├───imagens
│       1984.jpg
│       domcasmurro.jpg
│       duna.jpg
│       expresso.jpg
│       garota.jpg
│       habito.jpg
│       iluminado.jpg
│       orgulho.jpg
│       passaro.jpg
│       sapiens.jpg
│       senhordosaneis.jpg
│       sofia.jpg
│       livrariaAtual.jpg
│       livrariaAntiga1.png
│       livrariaAntiga2.avif
│       livrariaAntiga3.jpg
│       favicon_redirecionar.png
│       favicon_index.png
│       favicon_sobre.png
│       favicon_contato.png
│       favicon_login.png
│       favicon_carrinho.png
│       favicon_catalogo.png
│       favicon_confirmacao.png
│       favicon_maisvendidos.png
│
├───paginas
│       catalogo.html
│       carrinho.html
│       confirmacao.html
│       contato.html
│       index.html
│       login.html
│       redirecionar.html
│       sobrenos.html
│       maisvendidos.html
│       recomendacoes.html
│
├───.vscode
│       settings.json
│
└───node_modules
    ├───@kurkle
    │   └───color
    │       └───dist
    └───chart.js
        ├───auto
        ├───dist
        │   ├───chunks
        │   ├───controllers
        │   ├───core
        │   ├───elements
        │   ├───helpers
        │   ├───platform
        │   ├───plugins
        │   │   └───plugin.filler
        │   ├───scales
        │   └───types


## Funcionalidades

- **Página de Catálogo**: Exibe uma lista de livros, com informações como título, autor e preço. 
- **Página de Mais Vendidos**: Apresenta gráficos interativos, como o gráfico de barras dos livros mais vendidos utilizando **Chart.js**.
- **Página de Recomendações**: Sugere livros baseados nas preferências literárias dos usuários.
- **Página de Sobre Nós**: Detalha informações sobre a livraria, sua missão e história.
- **Página de Contato**: Exibe um formulário de contato para interagir com os usuários.

## Bibliotecas Utilizadas

- **Chart.js**: Biblioteca utilizada para criar gráficos interativos, como o gráfico de barras com os livros mais vendidos e outro tipo de gráfico com os gêneros mais populares.
  
## Contribuição

Sinta-se à vontade para fazer um fork deste projeto, enviar pull requests e contribuir para o seu desenvolvimento. Se você deseja melhorar o projeto ou adicionar novas funcionalidades, por exemplo, o sistema de login, ou um filtro avançado de livros, ficaremos felizes em revisar sua contribuição.
# SistemaLivra
