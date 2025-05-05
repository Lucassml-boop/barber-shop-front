## Barber Shop Front
Este é o repositório para o front-end de um sistema de gerenciamento para uma barbearia. Este projeto é construído utilizando tecnologias modernas como TypeScript e Docker, e segue boas práticas de desenvolvimento.

### 🛠️ Tecnologias Utilizadas
TypeScript: Para uma tipagem estática e mais robustez no código.
HTML: Estrutura do front-end.
SCSS: Estilização avançada e modularizada.
Docker: Para facilitar a execução do projeto em ambientes consistentes.
Shell Scripts: Para automação de tarefas.
### 🚀 Funcionalidades
Cadastro de clientes.
Edição de informações de clientes.
Visualização de lista de clientes.
Design responsivo para diferentes tamanhos de tela.
Integração com APIs para persistência de dados.
### 📁 Estrutura de Pastas
Abaixo, uma breve descrição das principais pastas do projeto:

src/app/clients/components/client-form: Componentes relacionados ao formulário de cadastro e edição de clientes.
src/app/clients: Módulo de gerenciamento de clientes.
src/app: Código principal da aplicação.
public: Arquivos públicos, como imagens e fontes.
.vscode: Configurações específicas do editor VS Code.
### 📦 Como Executar o Projeto
Pré-requisitos
Certifique-se de ter instalado:

# Node.js (versão 16 ou superior)
Docker (opcional, caso deseje rodar o projeto em um container)
Passo a Passo
Clone este repositório:

```bash
git clone https://github.com/Lucassml-boop/barber-shop-front.git
cd barber-shop-front
Instale as dependências:
```
```bash
npm install
Execute o projeto:
```
```bash
npm start
Abra o navegador e acesse: http://localhost:3000.
```

#Usando Docker
Se preferir, você pode rodar o projeto utilizando Docker:

1.Construa a imagem Docker:

```bash
docker build -t barber-shop-front .

```
2.Execute o container:

```bash
docker run -p 3000:3000 barber-shop-front
```
3.Acesse a aplicação em: http://localhost:3000.

