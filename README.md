# Inventory Management API

## Descrição

Este projeto é uma API de gerenciamento de inventário, destinada a ser utilizada por empresas de mercado e logística para gerenciar produtos, categorias, estoques e autenticação de usuários.

## Estrutura do Projeto

inventory-management-api/
├── config/
│ └── db.js
├── controllers/
│ ├── authController.js
│ └── productController.js
├── models/
│ ├── User.js
├── .env
├── .gitignore
├── app.js
├── package.json
└── README.md


## Funcionalidades Implementadas

- Configuração do servidor Express (`app.js`)
- Configuração da conexão com o banco de dados MongoDB (`config/db.js`)
- Implementação dos controladores de autenticação e produtos (`controllers/`)
- Modelos de usuário e produto (`models/`)

## Instalação

1. Clone o repositório:
   ```bash
   git clone <URL_DO_SEU_REPOSITORIO>
   cd inventory-management-api

 ## Instale as dependências:
 npm install


## Configure as variáveis de ambiente:
MONGO_URI=<sua_uri_do_mongodb>
JWT_SECRET=<seu_segredo_jwt>
PORT=5000


## Inicie o servidor:
npm run dev


## Endpoints
Autenticação

    POST /api/auth/register - Registra um novo usuário
    POST /api/auth/login - Faz login de um usuário existente

Produtos

    GET /api/products - Obtém todos os produtos
    POST /api/products - Cria um novo produto

## Em Desenvolvimento

# Este projeto está em desenvolvimento ativo. Futuras funcionalidades incluirão:

    Gerenciamento de categorias
    Controle de estoque
    Relatórios e análises
    Integração com outras APIs
    Testes unitários e de integração

# Contribuição

Sinta-se à vontade para contribuir com este projeto enviando pull requests. Antes de começar, por favor, abra uma issue para discutir o que você gostaria de mudar.
Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.