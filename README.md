# 📦 API RESTful de Controle de Inventário - SENAI

## 📝 Descrição do Projeto
Este projeto consiste em uma API RESTful para gerenciamento e controle de inventário de equipamentos. A aplicação permite realizar operações completas de CRUD (Criar, Ler, Atualizar e Deletar itens), além de contar com persistência de dados em formato JSON, validação de campos obrigatórios e prevenção de duplicidade de patrimônio.

---

## 🛠️ Tecnologias Utilizadas
- **Node.js** (Ambiente de execução)
- **Express.js** (Framework web)
- **ES Modules (ESM)** (Sintaxe com `import`/`export`)
- **JSON** (Persistência de dados em arquivo)
- **Thunder Client & Browser** (Testes de endpoints)

---

## 🚀 Como Executar o Projeto

1. Instale as dependências executando no terminal:
   ```bash
   npm install
   ```

2. Inicie o servidor:
   ```bash
   npm start
   ```

3. O servidor estará rodando em `http://localhost:3000`.

---

## 📌 Endpoints da API

- **`GET /inventario`** -> Lista todos os itens (suporta filtros: `nome`, `local`, `valorMin`).
- **`GET /inventario/:id`** -> Busca um item específico pelo ID.
- **`GET /inventario/total`** -> Retorna o total de itens e a soma do valor do inventário.
- **`GET /inventario/patrimonio/:numero`** -> Verifica se um número de patrimônio já está cadastrado.
- **`POST /inventario`** -> Cadastra um novo item (aceita JSON e Form-encode).
- **`PUT /inventario/:id`** -> Atualiza as informações de um item por ID.
- **`DELETE /inventario/:id`** -> Remove um item do inventário por ID.

---

## 📸 Evidências do Projeto e Testes

### 1. Estrutura e Código do Projeto
![Código do Projeto](./Evidencias/00-codigo-projeto.png)

### 2. Listagem de Itens no Navegador (GET)
![Listar Inventário](./Evidencias/01-get-inventario.png)

### 3. Cadastro via Formulário no Thunder Client (POST)
![Cadastrar Item](./Evidencias/02-post-cadastrar.png)

### 4. Remoção de Item por ID no Thunder Client (DELETE)
![Remover Item](./Evidencias/03-delete-remover.png)
"# Controle-Inventario" 
