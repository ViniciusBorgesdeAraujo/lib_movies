# MoviesLib

MoviesLib é uma aplicação web construída com Vite e React que permite aos usuários pesquisar e visualizar informações detalhadas sobre filmes. Esta biblioteca consome a API do The Movie Database (TMDb) para fornecer dados atualizados sobre os filmes.

## Visão Geral

- **Framework:** React com Vite
- **Roteamento:** React Router
- **Ícones:** React Icons
- **Estilização:** CSS
- **Hospedagem:** Netlify

## Funcionalidades

- **Página Inicial:** Exibe os filmes mais bem avaliados.
- **Pesquisa:** Permite buscar por filmes.
- **Detalhes do Filme:** Exibe detalhes específicos sobre um filme selecionado.

## Demonstração

Você pode ver a aplicação em funcionamento [aqui](https://lib-movies.netlify.app/).

## Estrutura do Projeto

```plaintext
movieslib/
├── public/
├── src/
│   ├── components/
│   │   ├── MovieCard.jsx
│   │   └── Navbar.jsx
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Movie.jsx
│   │   └── Search.jsx
│   ├── App.jsx
│   ├── index.css
│   ├── App.css
│   └── main.jsx
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
```

## Instalação

Siga os passos abaixo para clonar e rodar o projeto localmente.

### Pré-requisitos

- Node.js instalado
- NPM ou Yarn instalado

### Passos para instalação

1. **Clone o repositório:**

```bash
git clone https://github.com/ViniciusBorgesdeAraujo/lib_movies.git
```

2. **Navegue até o diretório do projeto:**

```bash
cd lib_movies
```

3. **Instale as dependências:**

```bash
npm install
# ou
yarn install
```

4. **Crie um arquivo `.env` na raiz do projeto e adicione suas chaves da API:**

```env
VITE_API=https://api.themoviedb.org/3/movie/
VITE_API_KEY=sua_chave_api_aqui
VITE_SEARCH=https://api.themoviedb.org/3/search/movie
VITE_IMG=https://image.tmdb.org/t/p/w500/
```

5. **Execute o projeto:**

```bash
npm run dev
# ou
yarn dev
```

6. **Abra o navegador e acesse:**

```plaintext
http://localhost:3000
```

## Contribuição

Sinta-se à vontade para fazer um fork do projeto e enviar pull requests. Todas as contribuições são bem-vindas!

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Vinicius Borges de Araujo - [GitHub](https://github.com/ViniciusBorgesdeAraujo)

---

Feito com ♥ por Vinicius Borges de Araujo.
