# NLW Agents 🤖

Projeto desenvolvido durante o evento NLW (Next Level Week) da Rocketseat para demonstrar o uso de agentes inteligentes na web, integrando frontend com uma API de backend.

## 🚀 Tecnologias

- **React 19.1** - Biblioteca para interfaces de usuário.
- **TypeScript 5.8** - Superset JavaScript com tipagem estática.
- **Vite 7.0** - Build tool e servidor de desenvolvimento.
- **TailwindCSS 4.1** - Framework CSS utility-first.
- **React Router Dom 7.6** - Biblioteca de roteamento.
- **TanStack React Query 5.8** - Gerenciamento de estado do servidor e cache.
- **Radix UI** - Componentes primitivos acessíveis.
- **Shadcn/ui** - Sistema de componentes.
- **Lucide React** - Biblioteca de ícones.

## 📂 Padrões de Projeto

- **Component-based Architecture** - Arquitetura baseada em componentes React.
- **File-based Routing** - Roteamento baseado em arquivos com React Router.
- **Server State Management** - Gerenciamento de estado do servidor com React Query.
- **Variant-based Components** - Componentes com variantes usando CVA (Class Variance Authority).
- **Composition Pattern** - Padrão de composição com Radix Slot.
- **Path Aliasing** - Alias de caminhos (`@/` aponta para `src/`).

## ⚙️ Configuração do Projeto

Siga os passos abaixo para executar o projeto localmente.

### Pré-requisitos

- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

### Instalação

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Execute o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

4. Acesse a aplicação em `http://localhost:5173`.

### Backend

O projeto consome uma API que deve estar rodando na porta `3333`. Certifique-se de que o backend esteja configurado e executando antes de iniciar o frontend.

## 🛠️ Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento.
- `npm run build` - Gera o build de produção.
- `npm run preview` - Executa um servidor local para visualizar o build de produção.

## 📁 Estrutura do Projeto

A estrutura de pastas principal do projeto está organizada da seguinte forma:

```
src/
├── app.tsx          # Componente raiz da aplicação
├── lib/             # Utilitários e configurações (ex: axios, react-query)
├── pages/           # Páginas da aplicação (roteamento baseado em arquivos)
└── components/
    └── ui/          # Componentes de UI (Shadcn)
