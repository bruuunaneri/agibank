Pré-requisitos

Antes de iniciar, tenha instalado na sua máquina:

Node.js (versão 16 ou superior)

NPM ou Yarn

Um editor de código (recomendado: VS Code)

Verifique se estão instalados com:

node -v
npm -v

Como rodar o projeto
Clonar o repositório
git clone <URL_DO_REPOSITORIO>
cd agibank-playwright-tests

Instalar as dependências
npm install

Instalar os navegadores do Playwright
npx playwright install

Executar os testes

Rodar em modo headless (padrão):

npm test


Rodar com interface gráfica:

npm run test:ui

Visualizar o relatório

Após executar os testes:

npm run report


Isso abrirá um relatório HTML com o resultado da execução.

Estrutura do Projeto
agibank-playwright-tests
├── tests
│   └── agibank-produtos.spec.ts
├── playwright.config.ts
├── package.json
└── README.md

Testes implementados

Validação de carregamento da página de produtos

Validação de abertura de um artigo e verificação do conteúdo

🛠 Tecnologias utilizadas

Playwright

TypeScript

Node.js
