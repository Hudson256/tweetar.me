# Tweetar.me

## Overview

**Tweetar.me** é uma plataforma de microblogging inspirada no Twitter, desenvolvida para oferecer uma experiência de usuário fluida e moderna. Com uma interface minimalista e responsiva, este projeto permite aos usuários postar "tweets", visualizar perfis, salvar favoritos e muito mais.

## Funcionalidades Principais

- **Autenticação de Usuários**: Cadastro e login de usuários com proteção de rotas para conteúdo privado.
- **Postagem de Tweets**: Usuários podem postar, editar e visualizar tweets.
- **Favoritos**: Salve tweets como favoritos para acesso rápido posteriormente.
- **Perfis de Usuários**: Cada usuário possui um perfil onde seus tweets são exibidos.
- **Interface Responsiva**: Totalmente responsivo, garantindo uma ótima experiência em dispositivos móveis e desktops.

## Tecnologias Utilizadas

- **Frontend**:
  - React
  - Vite
  - Tailwind CSS
- **Autenticação**:
  - Custom hooks para gerenciamento de autenticação
- **Infraestrutura**:
  - Vercel para deploy contínuo

## Estrutura do Projeto

```bash
tweetar.me/
├── src/
│   ├── assets/                # Imagens e outros assets
│   ├── components/            # Componentes React reutilizáveis
│   ├── constants/             # Constantes usadas no projeto
│   ├── hooks/                 # Hooks personalizados
│   ├── pages/                 # Páginas da aplicação
│   ├── main.css               # Estilos principais
│   └── main.jsx               # Arquivo de entrada principal
├── .env.example               # Exemplo de arquivo de variáveis de ambiente
├── package.json               # Dependências e scripts do projeto
├── postcss.config.js          # Configuração do PostCSS
├── tailwind.config.js         # Configuração do Tailwind CSS
├── vite.config.js             # Configuração do Vite
└── vercel.json                # Configuração do deploy na Vercel
```
## Como Rodar o Projeto
## Requisitos

- Node.js
- Docker
- Yarn ou NPM

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/Hudson256/tweetar.me.git
   cd tweetar.me```
2. Instale as dependências:

```bash
yarn install
# ou
npm install
```
3. Configure as variáveis de ambiente no arquivo .env, utilizando o exemplo fornecido em .env.example.

4.Inicie o servidor de desenvolvimento:
```bash
yarn dev
# ou
npm run dev
```
## Testes
O projeto inclui uma suíte de testes para garantir a estabilidade e a qualidade do código. Para rodar os testes, utilize o comando:
```bash
yarn test
# ou
npm run test
```
## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests. Este projeto segue o padrão de código estabelecido por ESLint e Prettier, então certifique-se de rodar o linter antes de submeter suas alterações.

## Licença
Este projeto é licenciado sob a licença MIT.

## Contato
Se você tiver alguma dúvida ou sugestão, entre em contato pelo e-mail: hudsono256@gmail.com.
