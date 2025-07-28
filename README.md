# 🚀 Aplicação DIO Clone - Cadastro e Feed

Este projeto é uma aplicação web que simula uma plataforma de cadastro de usuários e feed de conteúdo. Foi desenvolvido usando React e styled-components, proporcionando uma experiência de usuário responsiva e interativa.

## ✨ Funcionalidades

  * **Registro de Usuários:** 📝 Embora a versão atual se concentre no login, a estrutura sugere um fluxo de cadastro.
  * **Login de Usuários:** 🔑 Usuários podem fazer login com credenciais predefinidas gerenciadas por um servidor JSON local.
  * **Feed Dinâmico:** 📰 Exibe uma lista de cartões de conteúdo e um ranking de usuários "Top 5 da Semana", simulando um feed social.
  * **Design Responsivo:** 📱 Estilizado com `styled-components` para garantir adaptabilidade em diferentes tamanhos de tela.
  * **Componentes Reutilizáveis:** 🧩 Construído com uma arquitetura baseada em componentes, incluindo `Button`, `Card`, `Header`, `Input` e `UserInfo`.

## 🛠️ Tecnologias Utilizadas

O projeto é construído com as seguintes tecnologias chave:

  * **React:** Uma biblioteca JavaScript para a construção de interfaces de usuário.
  * **Styled-components:** Para escrever CSS em JavaScript e estilizar componentes.
  * **React Router DOM:** Para roteamento declarativo em aplicações React, lidando com a navegação entre páginas (Home, Login, Feed).
  * **React Hook Form:** Para validação e gerenciamento eficiente de formulários.
  * **Axios:** Um cliente HTTP baseado em Promises para fazer requisições API ao backend.
  * **JSON Server:** Utilizado como uma API REST simulada para servir dados de usuário (`db.json`) para autenticação.
  * **React Icons:** Uma biblioteca que fornece pacotes de ícones populares como componentes React.

## 📂 Estrutura do Projeto

Os principais diretórios e seus propósitos são:

```
├── public/                     # Ativos públicos e arquivo HTML principal 🌐
│   ├── favicon.ico
│   ├── index.html              # Arquivo HTML principal
│   └── ...
├── src/                        # Código-fonte 💻
│   ├── assets/                 # Imagens (banner, logo) 🖼️
│   ├── components/             # Componentes de UI reutilizáveis (Button, Card, Header, Input, UserInfo) 🧩
│   ├── pages/                  # Páginas da aplicação (Feed, Home, Login) 📄
│   ├── services/               # Configuração da API ⚙️
│   └── styles/                 # Estilos globais 🎨
├── db.json                     # Banco de dados simulado para JSON Server 🗄️
├── package.json                # Dependências e scripts do projeto 📦
└── README.md                   # README do projeto (este arquivo) 📖
```

## 🚀 Como Começar

Siga estas instruções para ter uma cópia do projeto em execução na sua máquina local.

### 📋 Pré-requisitos

Certifique-se de ter o Node.js e o npm (ou Yarn) instalados.

### ⬇️ Instalação

1.  **Clone o repositório:**

    ```bash
    git clone <url-do-repositorio>
    cd clone-tela-cadastro-dio
    ```

2.  **Instale as dependências:**

    Usando npm:

    ```bash
    npm install
    ```

    Ou usando Yarn:

    ```bash
    yarn install
    ```

### ▶️ Executando a Aplicação

Este projeto requer dois processos separados para serem executados simultaneamente: o servidor de desenvolvimento React e o JSON Server para a API simulada.

1.  **Inicie o JSON Server (API Simulada):**
    Abra uma nova janela de terminal na raiz do projeto e execute:

    ```bash
    npm run server
    # ou
    yarn server
    ```

    Isso iniciará o JSON Server em `http://localhost:5000` (ou outra porta disponível). A configuração da API da aplicação (`src/services/api.js`) está definida para `http://localhost:5000` por padrão.

2.  **Inicie o Servidor de Desenvolvimento React:**
    Abra outra janela de terminal na raiz do projeto e execute:

    ```bash
    npm start
    # ou
    yarn start
    ```

    Isso abrirá a aplicação em seu navegador em `http://localhost:3000`. A página será recarregada automaticamente quando você fizer alterações.

## 📜 Scripts Disponíveis

No diretório do projeto, você pode executar:

  * **`npm start`**: 🚀 Executa o aplicativo em modo de desenvolvimento. Abre [http://localhost:3000](https://www.google.com/search?q=http://localhost:3000) em seu navegador.
  * **`npm test`**: 🧪 Inicia o executor de testes em modo de observação interativo.
  * **`npm run build`**: 🏗️ Compila o aplicativo para produção na pasta `build`.
  * **`npm run eject`**:  eject Isso é uma operação unidirecional. Ela removerá a única dependência de build do seu projeto e copiará todos os arquivos de configuração e dependências transitivas para o seu projeto, dando-lhe controle total sobre eles. Você não precisa usar `eject`.

## 📚 Saiba Mais

Você pode aprender mais na [documentação do Create React App](https://facebook.github.io/create-react-app/docs/getting-started).
Para aprender React, confira a [documentação do React](https://reactjs.org/).

## ⚖️ Licença

Este projeto é de código aberto.
