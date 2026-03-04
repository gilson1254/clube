# Netflix Clube

Este projeto é uma aplicação web que simula uma interface de clube/plataforma de streaming, inspirada na Netflix. Ele foi desenvolvido utilizando tecnologias modernas para oferecer uma experiência de usuário rica e responsiva.

## Tecnologias Utilizadas

### Frontend
*   **React**: Biblioteca JavaScript para construção de interfaces de usuário.
*   **Vite**: Ferramenta de build rápida para desenvolvimento frontend.
*   **TypeScript**: Superset de JavaScript que adiciona tipagem estática.
*   **Tailwind CSS**: Framework CSS utilitário para estilização rápida e responsiva.
*   **Radix UI**: Componentes de UI acessíveis e personalizáveis.
*   **Wouter**: Uma pequena e rápida biblioteca de roteamento para React.

### Backend
*   **Node.js**: Ambiente de execução JavaScript no lado do servidor.
*   **Express**: Framework web para Node.js, utilizado para construir a API.
*   **TypeScript**: Para desenvolvimento do backend com tipagem estática.

## Como Rodar o Projeto

Siga os passos abaixo para configurar e executar o projeto em sua máquina local.

### Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas:
*   [Node.js](https://nodejs.org/en/) (versão 18 ou superior)
*   [pnpm](https://pnpm.io/installation/) (gerenciador de pacotes)

### Instalação

1.  Clone este repositório:
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd netflix-clube
    ```
2.  Instale as dependências do projeto usando pnpm:
    ```bash
    pnpm install
    ```

### Executando em Modo de Desenvolvimento

Para iniciar o servidor de desenvolvimento do frontend e backend:

```bash
pnpm dev
```

Isso iniciará o aplicativo cliente (Vite) e o servidor (Express) simultaneamente. O frontend estará disponível em `http://localhost:5173` (ou outra porta disponível) e o backend em `http://localhost:3000` (ou outra porta, conforme configurado no `server/index.ts`).

### Construindo para Produção

Para construir o projeto para implantação em produção:

```bash
pnpm build
```

Este comando irá compilar o frontend e o backend, gerando os arquivos otimizados na pasta `dist/`.

### Executando em Modo de Produção

Após a construção, você pode iniciar o aplicativo em modo de produção:

```bash
pnpm start
```

## Estrutura do Projeto

```
netflix-clube/
├── client/             # Aplicação frontend (React, Vite)
│   ├── public/
│   ├── src/
│   └── ...
├── server/             # Aplicação backend (Node.js, Express)
│   └── index.ts
├── shared/             # Código compartilhado entre frontend e backend
│   └── const.ts
├── package.json        # Dependências e scripts do projeto
├── pnpm-lock.yaml      # Lockfile do pnpm
├── tsconfig.json       # Configurações do TypeScript
└── ...
```

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
