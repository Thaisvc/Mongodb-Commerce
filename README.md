# Mongodb-Commerce 🛍️📦

Projeto de estudo em **Back-end com Node.js e MongoDB**, criado para praticar operações de banco NoSQL e lógica de uma aplicação de comércio (como catálogo de produtos, buscas e manipulação de dados).

MongoDB é um banco de dados orientado a documentos, que armazena dados em JSON/BSON com esquema flexível e alto desempenho. 

## 📌 Sobre

Esse projeto tem como foco:

✔️ Modelagem de dados para um sistema de comércio usando **MongoDB**  
✔️ Operações básicas de **CRUD** (criar, ler, atualizar, excluir)  
✔️ Integração com **Node.js/Express** (supondo que seja backend)  
✔️ Aprendizado prático de NoSQL em contexto de e-commerce


---

## 📁 Estrutura

```plaintext
.
├── assets/                   # Imagens ou recursos estáticos
├── challenges/               # Desafios ou exercícios relacionados
├── package.json              # Dependências e scripts
├── queres.mongodb            # Possível arquivo de configuração/modelos
├── README.md                 # Este arquivo
└── .eslintrc.json            # Configurações de lint
````


---

## 🚀 Como rodar

### 🛠 Pré-requisitos

Antes de tudo, certifique-se de ter:

* **Node.js** instalado (v14+ recomendado)
* **npm** ou **yarn**
* **MongoDB** rodando localmente ou via Atlas/Docker

### 📦 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/Thaisvc/Mongodb-Commerce.git
cd Mongodb-Commerce
```

2. Instale as dependências:

```bash
npm install
```

ou

```bash
yarn install
```

3. Configure as variáveis de ambiente

Crie um arquivo `.env` com as configurações de conexão do MongoDB, por exemplo:

```env
MONGO_URI=mongodb://localhost:27017/commerce
PORT=3000
```

4. Inicie o servidor

```bash
npm start
```

ou, em modo de desenvolvimento com *nodemon*:

```bash
npm run dev
```

---

## 🧪 Funcionalidades (exemplos)


* `GET /products`  — lista produtos
* `POST /products` — adiciona produto
* `GET /products/:id` — busca produto por ID
* `PUT /products/:id` — atualiza produto
* `DELETE /products/:id` — remove produto

---

## 🧠 O que você aprende aqui

✔️ Estruturar REST API com Node/Express <br>
✔️ CRUD completo com MongoDB <br>
✔️ Modelagem de dados em NoSQL <br>
✔️ Conexão e consultas ao banco com driver ou ORM (Mongoose, se usado) <br>

---
