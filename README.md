# Todo List com Django

Este projeto é uma aplicação web para gerenciamento de tarefas, desenvolvido com o framework Django e estilizado com TailwindCSS. O objetivo principal é implementar funcionalidades completas de criação, leitura, atualização e exclusão de tarefas (CRUD).

## 🚀 Funcionalidades

- ✅ **Adicionar tarefas:** Usuários podem adicionar novas tarefas.
- ✏️ **Editar tarefas:** Tarefas existentes podem ser modificadas.
- 🔄 **Atualizar tarefas:** Mudanças feitas nas tarefas são salvas e atualizadas no banco de dados.
- ❌ **Excluir tarefas:** Usuários podem deletar tarefas da lista.

## 📂 Estrutura do Projeto

```
todo-list-django
├── tasks
│   ├── migrations
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
├── templates
│   ├── index.html
│   └── edit_task.html
├── todo_list
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
├── .gitignore
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
```

## 🛠️ Tecnologias

- **Python**
- **Django**
- **TailwindCSS** (via CDN)
- **SQLite**

## ⚙️ Como Executar

Clone o repositório:

```bash
git clone <url-do-repositorio>
cd todo-list-django
```

Crie e ative o ambiente virtual:

```bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute as migrações:

```bash
python manage.py migrate
```

Inicie o servidor:

```bash
python manage.py runserver
```

Acesse o projeto:

```
http://localhost:8000
```

## 🎨 Estilização

A estilização da aplicação é feita usando TailwindCSS via CDN, garantindo uma interface moderna e responsiva.

## 📌 Documentações

- [Django](https://docs.djangoproject.com/)
- [TailwindCSS](https://tailwindcss.com/)

## 📅 Data de Entrega

- **24/06/2025**

---

📌 **Nota:** Responda ao questionário sobre conceitos utilizados (estrutura Django, rotas, views, banco de dados, métodos HTTP) após a entrega do projeto na plataforma AVA.
