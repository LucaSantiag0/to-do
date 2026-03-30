# To-Do List & Agenda Interativa 📝

Uma agenda interativa focada no gerenciamento de tarefas diárias e futuras. Este projeto permite a criação de listas de afazeres (TO-DO) para o dia atual e para os próximos dias, facilitando a organização pessoal e profissional.

Além do gerenciamento individual de tarefas, o sistema possui uma forte funcionalidade colaborativa: é possível convidar outras pessoas para participar, proporcionando uma experiência compartilhada na organização e no acompanhamento das atividades em equipe.

## 🚀 Funcionalidades

- **Gerenciamento de Tarefas:** Crie, edite e conclua tarefas facilmente.
- **Planejamento Futuro:** Organize tarefas para o dia atual ou agende para dias futuros.
- **Colaboração:** Convide outras pessoas para acessar e colaborar na mesma lista de tarefas.
- **Interface Moderna:** Design responsivo e interativo criado com Tailwind CSS.

## 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

- **[React](https://reactjs.org/)** (v18)
- **[TypeScript](https://www.typescriptlang.org/)**
- **[Vite](https://vitejs.dev/)** (Build tool e Dev Server)
- **[Tailwind CSS](https://tailwindcss.com/)** (Estilização)
- **[React Router DOM](https://reactrouter.com/)** (Navegação)
- **[Lucide React](https://lucide.dev/)** (Ícones)
- **[Axios](https://axios-http.com/)** (Requisições HTTP)

## ⚙️ Como rodar o projeto localmente

Siga o passo a passo abaixo para executar o projeto na sua máquina:

### Pré-requisitos

Certifique-se de ter o **[Node.js](https://nodejs.org/)** instalado (versão 18 ou superior recomendada) e um gerenciador de pacotes como **npm**, **yarn** ou **pnpm**.

### 1. Clone o repositório

```bash
git clone https://github.com/LucaSantiag0/to-do.git
```

### 2. Acesse a pasta do projeto

```bash
cd to-do
```

### 3. Instale as dependências

Se estiver usando npm:
```bash
npm install
```

Ou usando yarn:
```bash
yarn install
```

### 4. Execute o servidor de desenvolvimento

```bash
npm run dev
```
Ou com yarn:
```bash
yarn dev
```

### 5. Acesse no navegador

O terminal exibirá uma URL local (geralmente `http://localhost:5173`). Clique no link ou copie e cole no seu navegador para testar a aplicação.

## 📦 Scripts Disponíveis

No diretório do projeto, você pode rodar os seguintes comandos:

- `npm run dev` ou `yarn dev`: Inicia o servidor de desenvolvimento.
- `npm run build` ou `yarn build`: Cria a versão otimizada de produção na pasta `dist`.
- `npm run lint` ou `yarn lint`: Roda o ESLint para encontrar possíveis problemas de código.
- `npm run preview` ou `yarn preview`: Inicia um servidor local para visualizar a versão de produção gerada no build.