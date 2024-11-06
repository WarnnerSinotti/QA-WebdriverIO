# 🎉 Bem-vindo ao Projeto de Testes WebdriverIO QA! 🚀

Este projeto foi desenvolvido para facilitar e guiar novos QAs no universo do framework [**WebdriverIO**](https://webdriver.io/), trazendo práticas de automação de testes E2E e API para validar a qualidade e a performance das aplicações.

---

## 📦 Configuração do Projeto

### Pré-Requisitos

-   **Node.js**: Para rodar o projeto, é necessário ter o [Node.js](https://nodejs.org/en/) (preferencialmente a versão LTS).
-   **Git**: Usamos o [Git](https://git-scm.com/) para controle de versão. Recomendamos o [GitHub Desktop](https://desktop.github.com/) para quem prefere uma interface gráfica.
-   **Editor de Código**: Recomendamos o uso do [Visual Studio Code](https://code.visualstudio.com/) (VS Code) para edição de código, com as extensões sugeridas abaixo.
-   **[Allure Reporter](https://docs.qameta.io/allure/)**: Ferramenta opcional para visualização de relatórios de testes interativos.
-   **[Docker Compose](https://docs.docker.com/compose/)**: Para executar e manter a consistência dos testes em ambientes virtualizados.

### 1. Instalação do WebdriverIO

Siga as instruções de instalação do WebdriverIO com base no seu sistema operacional no link: [WebdriverIO](https://webdriver.io/docs/gettingstarted).

---

### 2. Extensões Recomendadas para o VS Code 🔌

-   [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Para formatação de código.
-   [Pretty TypeScript Errors](https://marketplace.visualstudio.com/items?itemName=yoavbls.pretty-ts-errors): Melhor visualização de erros em TypeScript.
-   [Git Extension Pack](https://marketplace.visualstudio.com/items?itemName=donjayamanne.git-extension-pack): Pacote de extensões para uso do Git.
-   [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next): Última versão para suporte a TypeScript.
-   [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Para linting do código.

---

### 3. Instalação das Dependências 📥

Na **branch `develop`**, execute:

```bash
# Escolha o comando adequado ao seu ambiente
yarn install
# ou
npm install
# ou
pnpm install
```

---

### 4. Executando o Projeto ▶️

Crie um arquivo `wdio.conf.js` com base no `wdio.conf.exemplo.js`.

Para iniciar o projeto, execute:

```bash
npx wdio run wdio.conf.js
```

Se tudo estiver correto, o projeto executará o WebdriverIO em modo CLI 🚀.

---

### 🐳 Executar os testes com Docker Compose

Para executar os testes, simplesmente execute o seguinte comando no terminal:

```bash
docker compose up
```

## 🗂 Estrutura do Projeto

Organizamos o projeto para proporcionar máxima clareza e organização:

-   **Testes E2E e API**: scripts organizados para facilitar a manutenção e compreensão dos testes.
-   **Fixtures e Comandos WebdriverIO**: separados por contexto, com modularização e reutilização de código.
-   **Ambientes (.env)**: variáveis sensíveis e específicas por ambiente, garantindo segurança e flexibilidade na execução dos testes.

## ✨ Funcionalidades Extra

Este projeto adota práticas avançadas e automações para simplificar o dia a dia dos QAs:

-   **Docker Compose**: executar os testes com `docker compose up` para um ambiente configurado e pronto para uso.
-   **ESLint e Prettier**: garantem código limpo e organizado.
-   **Relatórios de Testes (Allure Report)**: relatórios detalhados e prontos para análise.
-   **Modularidade**: testes, fixtures e comandos WebdriverIO são estruturados para fácil acesso e reutilização.

## 📜 Licença

-   Este projeto é público, com o objetivo de compartilhar conhecimento e promover estudos.
-   O uso do projeto é de responsabilidade do usuário.
-   Todos os recursos utilizados são gratuitos e adequados para uso livre.

### 💻 QA Engineer

-   Desenvolvido por **Warnner**
