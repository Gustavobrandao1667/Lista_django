📋 Todo List com Django
Projeto de gerenciamento de tarefas desenvolvido em Django, com funcionalidades completas de adição, edição, atualização e exclusão de tarefas, utilizando TailwindCSS para estilização moderna e intuitiva.

🚀 Objetivo
Este projeto visa aplicar boas práticas no desenvolvimento web com Django, demonstrando domínio sobre:

CRUD completo com Django.

Integração com banco de dados (SQLite).

Manipulação clara de métodos HTTP (GET e POST).

Uso eficiente da biblioteca TailwindCSS para design responsivo.

✅ Funcionalidades Implementadas
Adicionar tarefas: Inserir novas tarefas no banco de dados.

Editar tarefas: Alterar conteúdos de tarefas existentes.

Atualizar tarefas: Salvar alterações feitas nas tarefas.

Excluir tarefas: Remover tarefas da lista e banco de dados.

📂 Estrutura do Projeto
pgsql
Copiar
Editar
todo-list-django
├── tasks
│   ├── migrations
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── templates
│   ├── index.html
│   └── edit_task.html
├── todo_list
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── .gitignore
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
🛠️ Tecnologias Utilizadas
Python

Django

SQLite

TailwindCSS

⚙️ Como Executar o Projeto
1. Clone o repositório:
bash
Copiar
Editar
git clone <url-do-repositorio>
cd todo-list-django
2. Configure o ambiente virtual e dependências:
bash
Copiar
Editar
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
pip install -r requirements.txt
3. Execute as migrações para preparar o banco de dados:
bash
Copiar
Editar
python manage.py migrate
4. Execute o servidor local:
bash
Copiar
Editar
python manage.py runserver
Acesse a aplicação no navegador em http://localhost:8000.

🎨 Estilização com TailwindCSS
A interface é estilizada utilizando o CDN oficial do TailwindCSS, proporcionando um visual limpo e agradável, além de uma excelente experiência do usuário.

Documentação oficial: TailwindCSS.

📌 Links Úteis
Documentação Django: https://docs.djangoproject.com/

Documentação TailwindCSS: https://tailwindcss.com/

📝 Informações Acadêmicas
Disciplina: Desenvolvimento Web com Django

Data de Entrega: 24/06/2025
