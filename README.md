# B.Log - PersonalBlog-v1

Bem-vindo ao **B.Log**, um blog pessoal para compartilhar ideias, conhecimento e explorar o mundo da tecnologia.

## Funcionalidades
- Visualização de artigos publicados
- Listagem dinâmica de artigos, ordenados por data
- Tema escuro/claro com alternância
- Menu de navegação por ano dos artigos
- Layout responsivo e moderno
- Integração com Firebase Firestore para armazenamento dos artigos

## Estrutura de arquivos
- `index.html`: Página principal do blog, exibe lista de artigos.
- `view.html`: Página de visualização de artigo individual, com menu de navegação.
- `style.css`: Estilos modernos e responsivos para todo o site, incluindo animações e temas.
- `config.js`: Configuração do Firebase utilizada para conectar ao Firestore.
- `favicon.png`: Ícone do site.

## Tecnologias utilizadas
- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **Firebase Firestore**

## Como funciona
- Os artigos são buscados do Firestore e exibidos dinamicamente.
- O tema do site pode ser alternado e é salvo no `localStorage`.
- O menu de navegação permite filtrar artigos por ano.
- O layout é adaptado para dispositivos móveis.

