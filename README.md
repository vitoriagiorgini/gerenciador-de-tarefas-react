# 🚀 Gerenciador de Tarefas Simples com React

Este projeto é um aplicativo web básico de gerenciamento de tarefas, desenvolvido em React. Ele permite aos usuários adicionar novas tarefas, visualizar uma lista de tarefas existentes e acompanhar o status de cada uma, com indicadores visuais claros.

## ✨ Funcionalidades

Baseado nos requisitos do exercício, este gerenciador de tarefas oferece as seguintes funcionalidades:

*   **Criação de Tarefas:** Um formulário intuitivo para registrar novas tarefas, incluindo:
    *   `Título da tarefa`
    *   `Descrição da tarefa`
    *   `Data de vencimento`
    *   `Status` (Pendente ou Concluída)
*   **Gestão de Estado com `useState`:** O estado do formulário e a lista de tarefas são gerenciados de forma eficiente utilizando o hook `useState` do React, centralizando a lógica de dados.
*   **Validação de Entrada:** Impede que tarefas sejam salvas sem um `título` ou `descrição`, garantindo a integridade dos dados.
*   **Visualização em Tabela:** Apresenta todas as tarefas cadastradas em um formato de tabela organizado, com colunas para `Título`, `Descrição`, `Data de Vencimento` e `Status`.
*   **Estilização Condicional:** As linhas da tabela mudam de cor para indicar o status da tarefa:
    *   🟢 Verde: Tarefa `Concluída`
    *   🔴 Vermelho: Tarefa `Pendente`
*   **Interatividade:** Utiliza eventos `onClick` e `onChange` para capturar as interações do usuário com o formulário e elementos da interface.
*   **Componentização:** A aplicação é estruturada em componentes React modulares (`Formulario`, `Tabela`), facilitando a manutenção e a reutilização do código.

## 🛠️ Tecnologias Utilizadas

*   **React:** Biblioteca JavaScript para construção de interfaces de usuário.
*   **JavaScript (ES6+):** Linguagem de programação principal para a lógica da aplicação.
*   **HTML5 & CSS3:** Para a estrutura e estilização da interface.
*   **Create React App:** Ambiente de desenvolvimento para inicializar e executar o projeto React.
*   **Node.js & npm (ou Yarn):** Para gerenciamento de pacotes e dependências.

## 🚀 Como Rodar o Projeto

Siga os passos abaixo para configurar e executar o projeto em sua máquina local.

### Pré-requisitos

Certifique-se de ter o [Node.js](https://nodejs.org/en/download/) (que inclui o `npm`) instalado em seu sistema.

### Instalação

1.  **Clone o repositório** (se você o tiver no GitHub, caso contrário, navegue até a pasta do seu projeto):
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd nome1-nome2-tarefas # Ou o nome da pasta do seu projeto
    ```
2.  **Instale as dependências:**
    ```bash
    npm install
    # ou
    yarn install
    ```

### Execução

1.  **Inicie o servidor de desenvolvimento:**
    Se você usou **Vite** para criar o projeto:
    ```bash
    npm run dev
    # ou
    yarn dev
    ```
    Se você usou **Create React App**:
    ```bash
    npm start
    # ou
    yarn start
    ```
2.  Abra seu navegador e acesse `http://localhost:5173/` (para Vite) ou `http://localhost:3000/` (para Create React App) para ver a aplicação em funcionamento.

## 📂 Estrutura do Projeto

```
nome1-nome2-tarefas/
├── public/
├── src/
│   ├── index.js          # Ponto de entrada da aplicação e lógica principal
│   ├── Formulario.jsx    # Componente para criação de novas tarefas
│   ├── Tabela.jsx        # Componente para exibição da lista de tarefas
│   ├── App.css           # Estilos específicos da aplicação (incluindo cores condicionais)
│   └── index.css         # Estilos globais
├── package.json
└── ... outros arquivos de configuração
```

## 👥 Autores

Este projeto foi desenvolvido por:

*   [Vitória Beatriz][(http://github.com/vitoriagiorgini)
*   [Isabela Corte]((https://github.com/isaacortee))

---
