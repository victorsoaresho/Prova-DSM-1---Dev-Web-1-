# StarTec - Seu portal de notícias

Projeto de um site de notícias para a prova de Desenvolvimento Web 1 do curso de Desenvolvimento de Software Multiplataforma, na Fatec - Franca.

Link do site: https://victorsoaresho.github.io/Prova-DSM-1---Dev-Web-1-/StarTec/index.html

## 🚀 Começando

O projeto foi construído em HTML e CSS puro, sendo assim para execulta-lo, basta baixar os arquivos ou acessar o link do site. 

### 📋 Pré-requisitos para acessar

Computador e acesso a internet

### Glossário de tags HTML>

**!DOCTYPE html>**: Este é um comando HTML que define o tipo de documento sendo usado, neste caso, HTML5.

**html lang="pt-br">**: Abre a tag HTML e define o idioma padrão do documento como português do Brasil.

**head>**: Abre a seção do cabeçalho do documento, onde as configurações e metadados são definidos.

**meta charset="UTF-8">**: Define a codificação de caracteres como UTF-8, que é um padrão amplamente usado para suportar caracteres especiais e internacionais.

**meta name="viewport" content="width=device-width, initial-scale=1.0">**: Define a configuração da viewport, controlando como a página é dimensionada em dispositivos móveis. Isso permite que o site seja responsivo.

**title>**: Define o título da página exibido na barra de título do navegador.

**link rel="stylesheet" href="style.css">**: Conecta o arquivo CSS externo "style.css" ao documento HTML, permitindo que o estilo da página seja controlado separadamente.

**link rel="shortcut icon" href="Imagens/StarTec.png" type="image/x-icon">**: Define o ícone da página exibido na guia do navegador, que é um atalho para o site.

**body>**: Abre a seção principal do corpo da página, onde todo o conteúdo visível é colocado.

**div class="Logo">**: Cria uma divisão (um bloco) com a classe "Logo" que pode ser estilizada usando CSS.

**h1>**: Cria um cabeçalho de primeiro nível, geralmente usado para títulos importantes.

**nav class="Menu">**: Define uma barra de navegação que contém links para outras páginas ou seções do site.

**a href="index.html">**: Cria um link para outra página ou recurso com o URL especificado dentro do atributo "href".

**article class="Corpo">**: Define uma seção de conteúdo principal, como um artigo, que pode ser estilizada usando CSS.

**p>**: Cria um parágrafo de texto.

**br>**: Insere uma quebra de linha para separar elementos ou parágrafos.

**img>**: Exibe uma imagem na página com o atributo "src" especificando o caminho da imagem e "alt" contendo um texto alternativo para acessibilidade.

**i>**: Define o texto como itálico.

**a href="URL" target="_blank">**: Cria um link para outra página da web com a URL especificada e abre essa URL em uma nova janela ou aba do navegador.

**iframe>**: Permite incorporar um vídeo do YouTube na página.

**footer>**: Define o rodapé da página, geralmente contendo informações de contato ou direitos autorais.

**script>**: Abre uma seção para incorporar scripts JavaScript na página.

As pseudoclasses HTML são usadas para aplicar estilos a elementos HTML com base em estados ou características específicas que não podem ser selecionadas apenas com seletores de elementos ou classes. Elas permitem que você selecione elementos com base em interações do usuário, como passar o mouse sobre um elemento, clicar nele ou o estado atual do elemento, como se está focado, segue as pseudoclasses usadas:
Logo, Menu, Corpo, Título, Subinfo, Concerto, informação, Autor

Este código HTML é uma estrutura básica para criar uma página da web e exibir conteúdo, estilização e interatividade.


## ⚙️ Glossário de tags CSS>

**@charset "UTF-8";**: Define a codificação de caracteres do arquivo CSS como UTF-8, que suporta caracteres especiais e internacionais.

**@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');**: Importa uma fonte chamada "Roboto" do Google Fonts para ser usada no estilo da página.

**:root**: Define as variáveis globais CSS que podem ser reutilizadas em todo o documento.

**--fonte1**: Define uma variável de fonte que é usada para definir a família de fontes "Roboto" para todo o documento.

**--color1** e **--color2**: Definem variáveis de cores que podem ser usadas em todo o documento para manter um esquema de cores consistente.

**\***: Seleciona todos os elementos HTML na página.

**padding: 0px; margin: 0px;**: Remove preenchimento e margens padrão de todos os elementos, garantindo um layout consistente.

**font-family: var(--fonte1);**: Define a família de fontes para todos os elementos como a variável --fonte1, ou seja, "Roboto".

**.Logo**: Seleciona elementos com a classe "Logo" para aplicar estilos específicos.

**text-align: center; padding: 35px; margin: auto;**: Centraliza o texto e define preenchimento e margens específicos para elementos com a classe "Logo".

**background-image**: Define um fundo gradiente para a classe "Logo".

**.Menu**: Seleciona elementos com a classe "Menu" para aplicar estilos específicos.

**background-color**: Define a cor de fundo da classe "Menu".

**box-shadow**: Adiciona uma sombra ao elemento "Menu".

**border-bottom-left-radius** e **border-bottom-right-radius**: Arredonda as bordas inferiores do elemento "Menu".

**.Menu > a**: Seleciona elementos âncora dentro da classe "Menu" para aplicar estilos específicos.

**text-decoration**: Remove a decoração de link padrão.

**:hover**: Aplica estilos quando o cursor do mouse está sobre o link.

**.Corpo**: Seleciona elementos com a classe "Corpo" para aplicar estilos específicos.

**background-color**: Define a cor de fundo da classe "Corpo".

**min-width** e **max-width**: Define a largura mínima e máxima para o elemento "Corpo".

**margin**: Define margens para centralizar o elemento "Corpo".

**box-shadow**: Adiciona uma sombra ao elemento "Corpo".

**border-bottom-left-radius** e **border-bottom-right-radius**: Arredonda as bordas inferiores do elemento "Corpo".

**.Corpo p**: Seleciona parágrafos dentro da classe "Corpo" para aplicar estilos específicos.

**text-align**: Define o alinhamento do texto.

**text-indent**: Define o recuo da primeira linha do texto.

**font-size** e **line-height**: Controlam o tamanho da fonte e o espaçamento entre linhas.

**.Corpo a**: Seleciona links dentro da classe "Corpo" para aplicar estilos específicos.

**.Corpo img**: Seleciona imagens dentro da classe "Corpo" para aplicar estilos específicos.

**.video**: Seleciona elementos com a classe "video" para aplicar estilos específicos.

**position**: Define a posição dos elementos de vídeo.

**.video > iframe**: Seleciona iframes dentro da classe "video" para aplicar estilos específicos.

**.Subinfo**: Seleciona elementos com a classe "Subinfo" para aplicar estilos específicos.

**.Título h1**: Seleciona elementos h1 dentro da classe "Título" para aplicar estilos específicos.

**.Share**: Seleciona elementos com a classe "Share" para aplicar estilos específicos.

**.Share > a**: Seleciona âncoras dentro da classe "Share" para aplicar estilos específicos.

**.Subinfo#Concerto**: Seleciona elementos com a classe "Subinfo" que também têm o ID "Concerto" para aplicar estilos específicos.

**footer**: Seleciona o elemento footer para aplicar estilos específicos.

Esses estilos CSS são usados para formatar e estilizar a página da web, garantindo consistência visual em toda a página. As variáveis CSS são usadas para manter o código mais organizado e facilitar a manutenção do estilo da página.

## 🛠️ Construído com

Ferramentas que foram utilizadas na criação do projeto: 

* [Visual Studio Code](https://code.visualstudio.com/) - Editor de código fonte

## ✒️ Autores

Criado por Victor Hugo Ferreira Soares

## 📄 Licença

Este é um código público e livre, fique a vontade para baixa-lo e edita-lo da maneira que preferir.


## 🎁 Expressões de gratidão

* Conte a outras pessoas sobre este projeto 📢;
* Convide alguém da equipe para uma cerveja 🍺;
* Um agradecimento especial ao Gustavo Guanabara por me ajudar a construir este site;


---
⌨️ com ❤️ por [Victor](https://github.com/victorsoaresho) 😊
