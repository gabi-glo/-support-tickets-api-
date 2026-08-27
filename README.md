
---

## 📋 **README.md - Versão para copiar e colar no GitHub**

```
# 🎫 Support Tickets API

API para gerenciamento de tickets de suporte - projeto de estudos com Node.js.

## 🚀 Tecnologias

- **Node.js** + **Express**
- **Insomnia** (testes de API)
- **VS Code** (ambiente de desenvolvimento)

## 📂 Estrutura do Projeto

```
support-tickets/
├── src/
│   ├── controllers/    # Lógica das rotas
│   ├── database/       # Configuração do banco
│   ├── middlewares/    # Middlewares (validação, autenticação, etc)
│   ├── routes/         # Definição das rotas
│   └── utils/          # Funções auxiliares
├── server.js           # Ponto de entrada
└── package.json        # Dependências
```

## 🔧 Como rodar o projeto

```bash
# Instalar dependências
npm install

# Rodar em desenvolvimento
npm run dev

# Rodar em produção
npm start
```

## 📌 Funcionalidades

- [ ] Criar ticket
- [ ] Listar tickets
- [ ] Atualizar status do ticket
- [ ] Excluir ticket
- [ ] Autenticação de usuários (futuro)

## 🛠️ Testando a API

Você pode testar os endpoints usando o **Insomnia** ou **Postman**.

| Método | Rota | Descrição |
|--------|------|-----------|
| `GET` | `/tickets` | Listar todos os tickets |
| `POST` | `/tickets` | Criar um novo ticket |
| `PUT` | `/tickets/:id` | Atualizar um ticket |
| `DELETE` | `/tickets/:id` | Deletar um ticket |

> 💡 Se você exportar suas requisições do Insomnia, pode adicionar o arquivo `insomnia.json` na raiz do projeto para facilitar os testes.

## 📚 Aprendizados

- Estrutura MVC com Node.js
- Middlewares no Express
- Gerenciamento de rotas

## 📄 Licença

Este projeto é de uso educacional - sinta-se à vontade para estudar e modificar!

---

Desenvolvido por **Gabriela Oliveira** durante estudos de Backend com Node.js na Rocketseat. 🚀
```

---

