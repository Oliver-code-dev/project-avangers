# Projeto Vingadores

Projeto desenvolvido para praticar **HTML** e **CSS**, criando uma página temática dos Vingadores com cabeçalho, galeria de imagens, seção de história e rodapé.

## Tecnologias utilizadas

- HTML5
- CSS3

## O que pratiquei em HTML

- `<!DOCTYPE html>`: informa ao navegador que o documento usa HTML5.
- `<html lang="pt-br">`: define que a página está em português do Brasil.
- `<head>`: contém configurações da página, como título, charset e link do CSS.
- `<meta charset="UTF-8">`: permite o uso correto de caracteres especiais, como acentos.
- `<meta name="viewport">`: ajuda a página a se adaptar a telas menores, como celulares.
- `<link>`: conecta o arquivo HTML ao arquivo CSS.
- `<header>`: representa o cabeçalho da página, onde estão a logo e o menu.
- `<nav>`: representa a área de navegação.
- `<ul>` e `<li>`: criam uma lista para organizar os links do menu.
- `<a>`: cria links para navegar pela própria página e para sites externos.
- `<main>`: agrupa o conteúdo principal da página.
- `<section>`: separa o site em partes, como Galeria e História.
- `<h1>` e `<h2>`: criam títulos e subtítulos.
- `<div>`: organiza conteúdos em blocos.
- `<img>`: exibe imagens.
- `alt`: adiciona uma descrição alternativa para imagens, contribuindo com acessibilidade.
- `<figure>`: agrupa uma imagem com sua legenda.
- `<figcaption>`: cria a legenda da imagem.
- `<p>`: cria parágrafos de texto.
- `<footer>`: representa o rodapé da página.

Também pratiquei atributos como:

- `class`: permite aplicar estilos CSS em elementos específicos.
- `id`: cria identificadores para navegar até seções da página.
- `href`: define o destino de um link.
- `src`: informa o caminho de uma imagem.
- `target="_blank"`: abre links externos em uma nova aba.

## O que pratiquei em CSS

- Seletor universal `*`: remove margens e preenchimentos padrões dos elementos.
- `box-sizing: border-box`: facilita o cálculo do tamanho dos elementos.
- `scroll-behavior: smooth`: cria uma rolagem suave ao clicar nos links do menu.
- `font-family`: define a fonte usada no site.
- `margin` e `padding`: criam espaços externos e internos nos elementos.
- `color` e `background-color`: definem cores de texto e fundo.
- `max-width` e `margin: 0 auto`: centralizam o conteúdo da página.
- Classes reutilizáveis, como `.dark` e `.text-center`.
- `display: flex`: organiza os elementos com Flexbox.
- `justify-content` e `align-items`: alinham elementos horizontal e verticalmente.
- `flex-wrap`: permite que os itens da galeria quebrem linha em telas menores.
- `gap`: cria espaçamento entre itens.
- `flex: 1 1 250px`: define como as imagens da galeria crescem, diminuem e se organizam.
- `background-image`, `background-size` e `background-position`: criam e posicionam a imagem de fundo da seção principal.
- `border-radius`: arredonda os cantos das imagens.
- `transition`: deixa a mudança de cor dos links mais suave.
- `:hover` e `:focus`: alteram a aparência dos links quando o mouse passa sobre eles ou quando recebem foco.
- Seletores como `header ul li + li` e `.history p + p`, usados para aplicar estilo a elementos específicos próximos uns dos outros.

## Estrutura do projeto

```text
project-avangers/
├── images/
├── projeto-vingadores-header copy.html
├── projeto-vingadores-header.css
└── README.md
