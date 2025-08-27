# Flaskr 📝

Um pequeno aplicativo de blog construído com **Flask**, baseado no [tutorial oficial do Flask](https://flask.palletsprojects.com/en/latest/tutorial/).  
O projeto serve como uma introdução prática ao framework, mostrando como estruturar uma aplicação, lidar com autenticação, banco de dados e templates.

---

## 📦 Requisitos

- Python 3.8+
- [Flask](https://flask.palletsprojects.com/)
- [Flit](https://flit.pypa.io/) (para empacotar o projeto)

---

## ⚙️ Instalação

Clone o repositório e entre na pasta:

```bash
git clone https://github.com/seu-usuario/flaskr.git
cd flaskr
```

Crie e ative um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

Instale as dependências:
```bash
pip install -r requirements.txt
```

Ou, se estiver usando o pyproject.toml com flit:
```bash
flit install
```

▶️ Executando o projeto
Inicialize o banco de dados e rode a aplicação:

```bash
flask --app flaskr init-db
flask --app flaskr run
```

Acesse em: http://127.0.0.1:5000/

📚 Funcionalidades
Registro e login de usuários
Criar, editar e deletar posts
Banco de dados SQLite simples
Templates HTML com Jinja2

🛠 Estrutura de Pastas
```bash
flaskr/
│── __init__.py
│── db.py
│── auth.py
│── blog.py
│── templates/
│── static/
tests/
pyproject.toml
```

📄 Licença
Este projeto segue a licença MIT.