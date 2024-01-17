<center>
  <p align="center">
    <img src="https://camo.githubusercontent.com/f21f1fa29dfe5e1d0772b0efe2f43eca2f6dc14f2fede8d9cbef4a3a8210c91d/68747470733a2f2f6173736574732e76657263656c2e636f6d2f696d6167652f75706c6f61642f76313636323133303535392f6e6578746a732f49636f6e5f6c696768745f6261636b67726f756e642e706e67" alt="Nest Logo" width="150" />
  </p>  
</center>
<br />

## Como usar

Para clonar e executar este aplicativo, você precisará do [Git](https://git-scm.com) e do [Node.js](https://nodejs.org/en/download/) (que vem com o [npm](http://npmjs.com)) instalados no seu computador. Na sua linha de comando:

```bash
# Clone this repository
$ git clone https://github.com/herlanderbento/next-store.git

# Go into the repository
$ cd next-store

# Install dependencies
$ npm install

# Run the db 
$ npm run db:server

# Run the app
$ npm run dev
```

> **Note

## Tecnologia

- Next >= 13 [x]
- App Router [x]
- Tailwind [x]
- Next Auth (Para Autenticação, Utilizar Google) [ ]
- Shadcn UI [x]
- Deploy Vercel [ ]


## Características principais

- Criar Páginas
    - Login [x]
    - Cadastro de Produtos [x]
    - Lista de Produtos [x]
- Na página de "Cadastro de Produtos"
    - Nome do Produto [x]
    - Preço [x]
    - Descrição [x]
- Na página de "Lista de Produtos"
    - Produto [x]
    - Botão de Adicionar no Carrinho [x]
    - Grid com 3 Colunas [x]
    - Adicionar Campo de Busca utilizando searchParams
- Criar Drawer para "Carrinho" listando produtos adicionados [x]