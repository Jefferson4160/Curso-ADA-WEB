📄 README: Portfolio Pessoal (HTML/CSS Flexbox)
Este é um projeto simples de portfólio pessoal criado utilizando HTML e CSS, com foco no uso do Flexbox para o layout e responsividade da navegação e da seção inicial de banner.

✨ Tecnologias Utilizadas
HTML5: Estrutura básica da página.

CSS3: Estilização e layout, incluindo:

Flexbox: Utilizado para criar o layout da barra de navegação (<header>) e da seção de banner (<main>).

Google Fonts (Heebo): Fonte customizada para o design.

🖼️ Estrutura do Arquivo
O projeto é organizado da seguinte forma:

nome-do-projeto/
├── index.html # Estrutura principal da página
└── css/
└── style.css # Todos os estilos CSS do projeto
🎨 Principais Características de Estilo
Navbar (header #navbar)
A navegação foi construída usando Flexbox para garantir que o logo (.nav-brand) e a lista de links (.nav-list) fiquem alinhados horizontalmente com o máximo de espaço entre eles, utilizando a propriedade justify-content: space-between.

Seção de Banner (main #banner)
Utiliza display: flex para colocar o conteúdo de texto/botão (.banner-content) e a imagem de perfil (.banner-image) lado a lado.

Usa max-width: 1200px e margin: 0 auto para centralizar o conteúdo principal na tela.

O espaçamento entre o conteúdo e a imagem é gerenciado pela distribuição de espaço do Flexbox (usando justify-content: space-between) para criar o afastamento visual.

Projeto ainda em andamento. Próximas implementações:

- Novas Sections
- Responsividade

👤 Desenvolvedor
Este projeto foi desenvolvido por Jefferson Silva (conforme o código HTML) como parte de um estudo sobre desenvolvimento web e Flexbox.
