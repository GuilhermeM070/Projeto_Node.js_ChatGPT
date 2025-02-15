# 🤖 Projeto Node.js - ChatGPT  

Este repositório contém um projeto desenvolvido em **Node.js** integrado à API do ChatGPT. O objetivo é criar uma aplicação que interage com o modelo de IA da OpenAI para fornecer respostas inteligentes e automatizadas.  

## 🚀 Tecnologias Utilizadas  

- **Node.js** — Ambiente de execução JavaScript  
- **Express.js** — Framework minimalista para APIs  
- **Axios** — Cliente HTTP para chamadas à API do ChatGPT  
- **Dotenv** — Gerenciamento seguro de variáveis de ambiente  

## 📌 Funcionalidades  

✅ Integração com a API do ChatGPT  
✅ Respostas dinâmicas a partir de prompts enviados pelo usuário  
✅ Estrutura modular para facilitar a escalabilidade  
✅ Configuração de variáveis de ambiente para segurança  

## 🛠️ Como Rodar o Projeto  

### 🔹 Pré-requisitos  

Antes de começar, certifique-se de ter:  
- **Node.js** instalado  
- Uma **chave de API** da OpenAI  

### 🔹 Passo a Passo  

1️⃣ Clone este repositório:  
```sh
git clone https://github.com/GuilhermeM070/Projeto-Node.js-chatGPT.git
2️⃣ Acesse a pasta do projeto:

sh
Copiar
cd Projeto-Node.js-chatGPT
3️⃣ Instale as dependências:

sh
Copiar
npm install
4️⃣ Crie um arquivo .env na raiz do projeto e adicione sua chave da OpenAI:

env
Copiar
OPENAI_API_KEY=SUA_CHAVE_AQUI
5️⃣ Inicie o servidor:

sh
Copiar
npm start
6️⃣ Acesse a API no navegador ou via Postman:

arduino
Copiar
http://localhost:3000
📂 Estrutura do Projeto
graphql
Copiar
📦 Projeto-Node.js-chatGPT
├── 📂 src
│   ├── 📜 server.js  # Configuração do servidor Express
│   ├── 📜 routes.js  # Definição das rotas da API
│   ├── 📜 chatService.js  # Comunicação com a API do ChatGPT
├── 📜 .env.example  # Exemplo de configuração das variáveis de ambiente
├── 📜 package.json  # Dependências e scripts do projeto
└── 📜 README.md  # Documentação do projeto
🎯 Próximos Passos
🔹 Melhorar o tratamento de erros
🔹 Criar uma interface web para interação com a API
🔹 Implementar autenticação para controle de acesso

📄 Licença
Este projeto está sob a licença MIT.
