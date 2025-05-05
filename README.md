# Barber Shop Front

Este repositório contém o front-end do sistema de gerenciamento de uma barbearia.

## 🚀 Funcionalidades

- **Cadastro de Clientes**: Permite o registro de novos clientes.
- **Edição de Informações**: Atualização de dados dos clientes.
- **Visualização de Lista de Clientes**: Exibe todos os clientes cadastrados.
- **Design Responsivo**: Interface adaptável para diferentes tamanhos de tela.
- **Integração com APIs**: Persistência de dados por meio de integração com APIs.

## 🛠️ Tecnologias Utilizadas

- **Frontend**: TypeScript e HTML
- **Estilização**: SCSS
- **Automação**: Shell Scripts
- **Containerização**: Docker

## 📂 Estrutura do Projeto

- `src/app/clients/components/client-form/` - Componentes relacionados ao formulário de cadastro e edição de clientes.
- `src/app/clients/` - Módulo principal do gerenciamento de clientes.
- `src/app/` - Código principal da aplicação.
- `public/` - Arquivos públicos, como imagens e fontes.
- `.vscode/` - Configurações específicas do editor VS Code.
- `Dockerfile` - Criação de imagem Docker.
- `package.json` - Configurações e dependências do projeto.
- `tsconfig.json` - Configuração do TypeScript.

## ▶️ Como Executar o Projeto

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/Lucassml-boop/barber-shop-front.git
   ```

2. **Navegue até o Diretório do Projeto**

   ```bash
   cd barber-shop-front
   ```

3. **Instale as Dependências**

   Certifique-se de ter o Node.js (versão 16 ou superior) instalado e execute:

   ```bash
   npm install
   ```

4. **Execute o Projeto**

   ```bash
   npm start
   ```

5. **Acesse a Aplicação**

   Abra o navegador e acesse: `http://localhost:3000`.

## 🐳 Usando Docker

Você também pode rodar o projeto utilizando o Docker:

1. **Construa a Imagem Docker**

   ```bash
   docker build -t barber-shop-front .
   ```

2. **Execute o Container**

   ```bash
   docker run -p 3000:3000 barber-shop-front
   ```

3. **Acesse a Aplicação**

   A aplicação estará disponível em `http://localhost:3000`.
