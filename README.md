# DevAssistant AI

**DevAssistant AI** é um chatbot inteligente desenvolvido com React e a OpenAI API, projetado para ajudar profissionais de tecnologia, como desenvolvedores frontend, UI/UX designers, testers, Product Owners (POs), e equipes de backend e infraestrutura.

## 🚀 Tecnologias Usadas
- React.js
- OpenAI API (ChatGPT)
- TailwindCSS (para estilização)
- Context API ou Redux (para gerenciamento de estado)
- Axios (para comunicação com a API)
- Vite (para build e desenvolvimento)

## 💡 Funcionalidades
- **Sugestões de UI/UX:** Respostas rápidas sobre boas práticas, acessibilidade e design responsivo.
- **Ajuda para Frontend:** Dúvidas sobre React, Javascript, performance e frameworks.
- **Dicas de Backend e Infraestrutura:** Respostas sobre APIs, banco de dados e DevOps.
- **Estratégias para Testers:** Sugestões de ferramentas e abordagens de testes automatizados.
- **Apoio para POs:** Explicações sobre metodologias ágeis, refinamento de backlog e escrita de user stories.
- **Sugestões de Código:** Gerar snippets de código em diversas tecnologias.
- **Modo Interativo:** Oferece opções para perguntas abertas ou específicas.

## 🗂️ Importação de Arquivos para Análise de Código
O **DevAssistant AI** agora permite que você faça upload de arquivos de código para análise direta. Ao enviar arquivos `.js`, `.jsx`, `.ts`, `.html`, ou `.css`, o chatbot irá analisar o código e fornecer sugestões de melhoria, identificar possíveis erros ou sugerir boas práticas.

### Como Usar
1. Clique no botão "Carregar Arquivo" para selecionar um arquivo de código.
2. O arquivo será processado e você receberá feedback detalhado sobre o código enviado, incluindo:
   - Sugestões de refatoração
   - Melhorias de performance
   - Pontos de atenção em relação a boas práticas

## 🧑‍💻 Como Funciona
- Utiliza a API OpenAI para fornecer análises mais inteligentes, ou ferramentas como **ESLint** e **Prettier** para análise de código.


## 🔧 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/gihtarzia/DevAssistant-AI.git
Instale as dependências:
cd DevAssistant-AI
npm install

Configure a variável de ambiente REACT_APP_OPENAI_API_KEY com sua chave da OpenAI (Crie uma conta aqui e gere sua chave).

Inicie o servidor de desenvolvimento:
npm start
Abra seu navegador em http://localhost:3000 para usar o chatbot!

📌 Exemplo de Uso
Perguntas que você pode fazer ao DevAssistant AI:

"Como melhorar a performance de uma aplicação React?"
"Quais são as boas práticas para acessibilidade em UI/UX?"
"Como escrever uma user story para uma feature de login?"
"Me ajude a entender uma estratégia de testes automatizados para backend."
"Qual a melhor estrutura para um API RESTful?"

🧑‍💻 Como Contribuir
Fork o repositório.
Crie uma branch para sua feature (git checkout -b feature-nome-da-feature).
Commit suas alterações (git commit -am 'Adiciona nova feature').
Push para a branch (git push origin feature-nome-da-feature).
Abra um pull request.

📄 Licença
Esse projeto é licenciado sob a MIT License.

📸 Screenshot
(Adicione uma captura de tela aqui)

Estrutura de Diretórios
DevAssistant-AI/
│
├── public/                   # Arquivos públicos (imagens, fontes, etc.)
│   ├── index.html            # Arquivo HTML principal
│   └── ...
│
├── src/                      # Código fonte do aplicativo
│   ├── assets/               # Imagens, ícones, fontes
│   ├── components/           # Componentes React (ex: ChatBox, Message, Header)
│   ├── context/              # Gerenciamento de estado com Context API (se necessário)
│   ├── services/             # Funções para integração com a API OpenAI
│   ├── utils/                # Funções utilitárias, helpers
│   ├── App.js                # Componente principal do app
│   └── index.js              # Entrada do projeto
│
├── .env                      # Variáveis de ambiente (chave da OpenAI)
├── .gitignore                # Arquivos e pastas a serem ignoradas pelo Git
├── package.json              # Dependências e scripts
└── README.md                 # Documentação do projeto


