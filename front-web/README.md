# Projeto Frontend

Este é o código do frontend do sistema de encomendas e entrega de pedidos. 

Tecnologias utilizadas:

- ReactJS;

## Criando o projeto do zero com `create-react-app`:

```bash
npx create-react-app front-web --template typescript --use-npm
```

# Pré-requisitos

# Instalação de dependências (com npm)

```bash 
npm install
```

# Execução (com npm)

Pré-requisito: arquivo .env na raíz do projeto com as seguintes variáveis de ambiente:

- REACT_APP_ACCESS_TOKEN_MAP_BOX: token para acesso à api do Map Box, para o mapa da aplicação;

- REACT_APP_API_URL: url do backend deste serviço;

- REACT_APP_API_PRODUCTS_URL: path da api de obtenção da lista de produtos;

- REACT_APP_API_ORDERS_URL: path api de geração de pedidos de produtos;

```bash 
npm start
```

# Deploy no Netlify

O deploy do frontend é automático, a cada push feito no github.

[Tutorial passo a passo do deploy no Netlify](https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/).

Live link: https://sds2-luciano-brum.netlify.app/