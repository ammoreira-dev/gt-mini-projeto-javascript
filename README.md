
# 📝 Lista de Tarefas (Task List) - Node.js &amp; JSON Server

Aplicação web interativa para gerenciamento de tarefas desenvolvida durante o curso de JavaScript. O projeto demonstra a integração entre manipulação do DOM, estruturas de repetição, estruturas condicionais e consumo de uma API REST simulada usando **Node.js** e **JSON Server**.

---

## 🎯 Objetivo do Projeto

Construir uma aplicação funcional de Lista de Tarefas para consolidar os conceitos fundamentais de desenvolvimento web com JavaScript, incluindo:
- Execução de requisições HTTP (`GET`, `POST`, `DELETE`).
- Manipulação dinâmica do DOM.
- Validação e envio de formulários.
- Filtragem e busca de dados em tempo real.
- Estilização responsiva e criação de modais interativos.

---

## 🚀 Funcionalidades

- **Listagem de Tarefas (`GET`)**: Busca as tarefas cadastradas na API simulada e exibe-as dinamicamente em cards organizados na tela.
- **Criação de Tarefas (`POST`)**: Interface modal com formulário para adicionar novas tarefas com título e descrição obrigatórios.
- **Exclusão de Tarefas (`DELETE`)**: Remoção de tarefas específicas pelo ID através do ícone de lixeira em cada card.
- **Busca em Tempo Real**: Campo de pesquisa que filtra as tarefas visíveis pelo título conforme o usuário digita.
- **Interface Modal Interativa**: Abertura e fechamento de modal de cadastro com fundo semi-transparente (`overlay`) e transições suaves em CSS.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 &amp; CSS3**: Estruturação semântica, Flexbox, transições CSS e design responsivo.
- **JavaScript (ES6+)**: Funções assíncronas, manipulação do DOM, Fetch API, eventos e métodos de array.
- **Node.js &amp; NPM**: Ambiente de execução JavaScript e gerenciador de pacotes.
- **JSON Server (`v0.17.4`)**: Ferramenta de mock para simulação de uma API REST baseada num arquivo JSON local (`api.json`).
- **Boxicons**: Biblioteca de ícones web para os botões de fechar e excluir.

---

## 📂 Estrutura do Projeto

```text
.
├── api.json            # Banco de dados simulado do JSON Server
├── index.html          # Estrutura HTML principal da aplicação
├── index.css           # Estilização visual, layout e animações
├── index.js            # Lógica da aplicação, eventos e requisições HTTP
├── package.json        # Configurações do projeto e dependências
└── README.md           # Documentação do repositório

```

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter o [Node.js](https://www.google.com/url?sa=E&amp;q=https%3A%2F%2Fnodejs.org%2F) instalado em sua máquina.

### Passo a Passo

1. **Clonar o Repositório**

```
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio

```

1. **Instalar as Dependências**

```
npm install

```

1. **Iniciar a API Simulada (JSON Server)**

```
npm run api

```

O servidor rodará em `http://localhost:3300`, expondo o endpoint `/tarefas`.

1. **Abrir a Aplicação** Abra o arquivo `index.html` diretamente no seu navegador de preferência.

---

## 🌐 Endpoints da API (JSON Server)

| Método   | Endpoint       | Descrição                            |
| -------- | -------------- | ------------------------------------ |
| `GET`    | `/tarefas`     | Retorna todas as tarefas cadastradas |
| `POST`   | `/tarefas`     | Cria uma nova tarefa                 |
| `DELETE` | `/tarefas/:id` | Remove uma tarefa pelo seu ID        |

---

## 👤 Autor

Desenvolvido por **Adriano Moreira** durante o curso Geração Tech 4.0.
