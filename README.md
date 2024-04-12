# Pagina de Filmes
Desenvolvi uma página de filmes usando React. Este projeto foi construído para explorar e demonstrar minha habilidade em consumir APIs externas. Para isso, utilizei a API do The Movie Database (TMDB), que fornece uma vasta quantidade de informações sobre filmes, que eu queria apresentar de forma elegante e acessível.

# Estrutura do Projeto e Navegação
Comecei configurando o ambiente de navegação do projeto usando o BrowserRouter do react-router-dom, que permite a criação de uma aplicação de página única (SPA). Defini três rotas principais:

# /(Home): Aqui, os usuários podem ver uma lista dos filmes mais bem avaliados. Para isso, faço uma chamada à API para buscar esses filmes.

# /movie/:id (Movie): Nesta rota, mostro detalhes específicos de um filme selecionado, como o orçamento, a receita, a duração e uma descrição geral.

# /search (Search): Permite que os usuários façam buscas por filmes usando palavras-chave.

# Componentes e Funcionalidades
O componente App serve como o layout principal, incluindo o Navbar para a navegação e um Outlet que renderiza os componentes das rotas ativas. Em Home, uso a API para obter e exibir filmes altamente avaliados. Em Movie, detalho mais informações sobre um filme escolhido, utilizando ícones para uma melhor visualização das informações.

No componente Search, implementei uma funcionalidade de busca dinâmica, onde os resultados da pesquisa são exibidos em tempo real à medida que o usuário digita sua consulta. Isso foi alcançado usando useState e useEffect para gerenciar o estado e os efeitos colaterais da busca, respectivamente.

# Interação com a API
Para interagir com a API do TMDB, configurei variáveis de ambiente para armazenar a chave da API e os endpoints necessários. Isso facilita a manutenção do código e melhora a segurança. As chamadas à API são feitas com fetch, e os dados recebidos são processados e armazenados no estado local dos componentes usando o hook useState.

# Estilo e UX
Para a estilização, foquei em criar uma interface limpa e responsiva. Utilizei CSS para personalizar o layout, garantindo que a aplicação seja agradável e fácil de usar em diferentes dispositivos. O Navbar inclui um formulário de busca que melhora a navegabilidade do site, permitindo que os usuários encontrem facilmente o conteúdo desejado.

# Conclusão
Este projeto não só reforçou minha compreensão dos fundamentos do React, como componentes, estado, e roteamento, mas também me deu a oportunidade de trabalhar com APIs externas e aprimorar a experiência do usuário em aplicações web. Estou muito satisfeito com o resultado e animado para aplicar esses conhecimentos em projetos futuros.







# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
