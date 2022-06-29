# Anotações das aulas

### 28/06/2022

- Git: Sistema de versionamento de projetos que é mais utilizado no ramo de desenvolvimento de softwares.
- Github: GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git.

### Introdução ao HTML 5

- O HTML foi criado em 1.991.
- Elemento: é a base do HTML (todos os processos em HTML são elementos).
- Os elementos são compostos por:
  - Abertura da tag;
  - Atributo;
  - Conteúdo;
  - fechamento da tag;

### Estrutura básica do HTML

A estrutura básica do HTML é composta por:
- **`<!DOCTYPE html>`** - não faz parte da estrutura, apenas informa ao navegador o que está sendo escrito.
- **`<html>`** - tag do elemento HTML propriamente dito. Tudo o que pertence a este documento estará dentro deste elemento;
  - **`<head>`** - onde serão alocados os metadados (informações gerais sobre o documento) incluindo seu título e links para scripts e folhas de estilos;
  - `<meta>` - comando utilizado para inserir os metadados;
  - `<title></title>` - Onde será inserido o título do documento no navegador;
  - **`</head>`** - Fechamento do elemento head;
  - **`<body>`** - Abertura do elemento body (onde estará o conteúdo da página);
  - **`</body>`** - Fechamento do elemento body;
- **`</html>`** - Fechamento do elemento html, finalizando a edição do documento.

### Semântica

Durante muitos anos o elemento padrão no HTML era a div, construíamos nosso conteúdo todo baseado nela, e assim nascia a sopa de divs.
Mas em 2014 saiu a quinta versão do HTML, e com ela vieram vários mudanças importantes, como performance e acessibilidade, mas nesse curso introdutório vamos focar na semântica.

A semântica nos permite descrever mais precisamente o nosso conteúdo, agora um bloco de texto não é apenas uma div, agora é um article e tem mais significado assim.

### Elementos que ressignificaram as divs

**`<section>`**
Representa uma seção genérica de conteúdo quando não houver um elemento mais específico para isso.

**`<header>`**
É o cabeçalho da página ou de uma seção da página e normalmente contém logotipos, menus, campos de busca.

**`<article>`**
Representa um conteúdo independente e de maior relevância dentro de uma página, como um post de blog, uma notícia em uma barra lateral ou um bloco de comentários. Um article pode conter outros elementos, como header, cabeçalhos, parágrafos e imagens.

**`<aside>`**
É uma seção que engloba conteúdos relacionados ao conteúdo principal, como artigos relacionados, biografia do autor e publicidade. Normalmente são representadas como barras laterais.

**`<footer>`**
Esse elemento representa o rodapé do conteúdo ou de parte dele, pois ele é aceito dentro de vários elementos, como article e section e até do body. Exemplos de conteúdo de um <footer> são informações de autor e links relacionados.

**`<h1>-<h6>`**
Eles não foram criados na versão 5 do HTML e nem são específicos para semântica, mas servem para esse propósito. São utilizados para marcar a importância dos títulos, sendo **`<h1>`** o mais importante e **`<h6>`** o menos. Uma dica: use apenas um **`<h1>`** por página, pois ele representa o objetivo da sua página.
