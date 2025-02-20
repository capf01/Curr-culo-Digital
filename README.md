Currículo Digital
GitHub license
Vue.js
Firebase
Node.js

O Currículo Digital é uma plataforma que permite aos usuários criar, editar e exportar currículos em PDF de forma fácil e rápida. Com templates prontos e integração com Firebase, os usuários podem salvar seus currículos na nuvem e acessá-los de qualquer lugar. Além disso, o projeto oferece funcionalidades premium para usuários assinantes.

Funcionalidades
🖋️ Editor de currículos: Crie e edite currículos com um editor intuitivo.

📄 Templates prontos: Escolha entre vários templates profissionais.

📤 Exportação para PDF: Exporte seu currículo em PDF com um clique.

🔒 Autenticação segura: Login e cadastro com Firebase Authentication.

💾 Armazenamento na nuvem: Salve seus currículos no Firebase Firestore.

💎 Funcionalidades premium: Assinaturas para desbloquear recursos avançados.

Tecnologias Utilizadas
Frontend: Vue.js (Composition API), Vue Router, Vuex, Axios.

Backend: Node.js, Express, Firebase Admin SDK.

Banco de Dados: Firebase Firestore.

Autenticação: Firebase Authentication.

Exportação para PDF: html2pdf.js.

Estilização: CSS3, Tailwind CSS (ou outro framework de sua preferência).

Como Executar o Projeto
Siga os passos abaixo para configurar e executar o projeto localmente.

Pré-requisitos
Node.js (v16 ou superior)

NPM ou Yarn

Conta no Firebase (para configurar o Firestore e Authentication)

Passos
Clone o repositório:

bash
Copy
git clone https://github.com/seu-usuario/curriculo-digital.git
cd curriculo-digital
Configure o Firebase:

Crie um projeto no Firebase Console.

Baixe o arquivo firebase-key.json e coloque-o em backend/config/.

Configure as variáveis de ambiente no arquivo .env (veja o exemplo em .env.example).

Instale as dependências do backend:

bash
Copy
cd backend
npm install
Instale as dependências do frontend:

bash
Copy
cd ../frontend
npm install
Execute o backend:

bash
Copy
cd ../backend
npm start
Execute o frontend:

bash
Copy
cd ../frontend
npm run serve
Acesse o projeto:

Abra o navegador e acesse http://localhost:8080.

Estrutura do Projeto
Copy
curriculo-digital/
├── backend/               # Pasta do backend (Node.js)
│   ├── src/
│   │   ├── controllers/   # Lógica de negócio
│   │   ├── routes/        # Rotas da API
│   │   ├── models/        # Modelos de dados
│   │   ├── config/        # Configurações (Firebase, banco de dados)
│   │   └── server.js      # Ponto de entrada do backend
│   ├── package.json       # Dependências do backend
│   └── .env               # Variáveis de ambiente
├── frontend/              # Pasta do frontend (Vue.js)
│   ├── public/            # Arquivos estáticos
│   ├── src/
│   │   ├── assets/        # Imagens, estilos globais
│   │   ├── components/    # Componentes reutilizáveis
│   │   ├── views/         # Páginas (Home, Editor, Login)
│   │   ├── router/        # Configuração de rotas
│   │   ├── store/         # Gerenciamento de estado (Vuex)
│   │   ├── services/      # Chamadas à API (Axios)
│   │   └── App.vue        # Componente principal
│   ├── package.json       # Dependências do frontend
│   └── vue.config.js      # Configuração do Vue.js
└── README.md              # Documentação do projeto
Contribuição
Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

Faça um fork do projeto.

Crie uma branch para sua feature (git checkout -b feature/nova-feature).

Commit suas alterações (git commit -m 'Adiciona nova feature').

Faça push para a branch (git push origin feature/nova-feature).

Abra um Pull Request.

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Contato
Se você tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato:

Nome: César Augusto Pacheco Ferreira

Email: cesaraugustopachecoferreira@gmai.com

GitHub: https://github.com/capf01

Agradecimentos
Equipe do Vue.js pela incrível framework.

Firebase por fornecer uma plataforma de backend tão poderosa.

Comunidade open source por todas as bibliotecas e ferramentas utilizadas.

Feito com ❤️ por César Augusto Pacheco. 🚀

Esse README.md é abrangente e cobre todos os aspectos do projeto. Você pode personalizá-lo conforme necessário, adicionando mais detalhes ou seções específicas. 😊
