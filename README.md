# Cadastro de Usuários 

Projeto web desenvolvido com **Django** para realizar o cadastro e a listagem de usuários de forma simples e prática.

A aplicação permite inserir informações básicas de um usuário, como **nome** e **idade**, armazenando os dados em um banco de dados SQLite e exibindo os usuários cadastrados em uma tabela.

---

## Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de praticar os conceitos fundamentais do framework **Django**, incluindo:

* Criação de projeto e aplicação Django
* Configuração de rotas
* Criação de models
* Integração com banco de dados
* Uso de templates HTML
* Envio de dados por formulário
* Listagem de registros cadastrados

---

## Funcionalidades

* Cadastro de usuários
* Armazenamento dos dados no banco SQLite
* Listagem dos usuários cadastrados
* Interface simples com Bootstrap
* Navegação entre páginas usando templates Django

---

## Tecnologias Utilizadas

* Python
* Django
* SQLite
* HTML
* Bootstrap

---

## Estrutura do Projeto

```txt
projeto-django-main/
├── projeto_cad_usuarios/
│   ├── app_cad_usuarios/
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── templates/
│   │   │   └── usuarios/
│   │   │       ├── base.html
│   │   │       ├── home.html
│   │   │       └── usuarios.html
│   │   └── migrations/
│   ├── projeto_cad_usuarios/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── db.sqlite3
│   └── manage.py
└── README.md
```

---

## Como Executar o Projeto

1. Clone este repositório:

```bash
git clone https://github.com/yuriserra1/cadastro-usuarios-django.git
```

2. Acesse a pasta do projeto:

```bash
cd projeto-django-main/projeto_cad_usuarios
```

3. Instale o Django, caso ainda não tenha instalado:

```bash
pip install django
```

4. Execute as migrações:

```bash
python manage.py migrate
```

5. Inicie o servidor:

```bash
python manage.py runserver
```

6. Acesse no navegador:

```txt
http://127.0.0.1:8000/
```

---

## Como Funciona

Na página inicial, o usuário informa seu **nome** e sua **idade** em um formulário.

Após enviar os dados, as informações são salvas no banco de dados e exibidas em uma tabela com todos os usuários cadastrados.

---

## Autor

Desenvolvido por **Yuri Oliveira Serra**.

Projeto acadêmico desenvolvido para estudo de desenvolvimento web com Django.

---

## Licença

Este projeto possui finalidade acadêmica e educacional.
*Projeto para realizar cadastros de usuarios*
