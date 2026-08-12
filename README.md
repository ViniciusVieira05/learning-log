# Learning Log

Aplicação web desenvolvida com **Django** com o objetivo de praticar e consolidar os principais conceitos do framework.

## Sobre o projeto

O **Learning Log** é uma aplicação que permite registrar assuntos que estão sendo estudados, organizar conteúdos e acompanhar o aprendizado.

Este projeto está sendo desenvolvido como parte dos meus estudos de **Django e desenvolvimento web com Python**.

## Objetivos

O projeto tem como objetivo praticar:

* Fundamentos do Django
* Estrutura de projetos e aplicações
* URLs e roteamento
* Views
* Templates
* Models
* Banco de dados
* Formulários
* Autenticação de usuários
* CRUD
* Organização de aplicações Django
* Git e GitHub

## Tecnologias utilizadas

* **Python**
* **Django**
* **SQLite**
* **HTML**
* **CSS**
* **Git**
* **GitHub**

## Estrutura do projeto

```text
learning_log/
│
├── learning_log/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── learning_logs/
|   ├── migrations/
|   |   └──__init__.py
|   ├── templates/
|   |   └── learning_logs/
|   |       ├── base.html
|   |       ├── index.html
|   |       ├── topic.html
|   |       └── topics.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
|   ├── tests.py
│   └── views.py
├── manage.py
├── .gitignore
└── README.md
```

> A estrutura poderá ser modificada conforme novas funcionalidades forem adicionadas ao projeto.

## Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/ViniciusVieira05/learning-log.git
```

### 2. Entre na pasta do projeto

```bash
cd learning-log
```

### 3. Crie um ambiente virtual

No Windows:

```powershell
python -m venv ll_env
```

### 4. Ative o ambiente virtual

```powershell
.\ll_env\Scripts\activate
```

### 5. Inicie o servidor

```powershell
python manage.py runserver
```

Depois, acesse:

```text
http://127.0.0.1:8000/
```

## Funcionalidades

### Atualmente

* [ ] Estrutura inicial do projeto
* [ ] Configuração do Django
* [ ] Sistema de páginas
* [ ] Cadastro de assuntos
* [ ] Cadastro de tópicos
* [ ] Sistema de usuários

### Futuras implementações

* [ ] Autenticação de usuários
* [ ] Login e logout
* [ ] Criação de registros
* [ ] Edição de registros
* [ ] Exclusão de registros
* [ ] Interface responsiva
* [ ] Melhorias na organização do projeto

## Aprendizados

Durante o desenvolvimento deste projeto estou utilizando o **Learning Log** como projeto prático para compreender como o Django funciona e como seus principais componentes se relacionam.

O projeto será evoluído gradualmente conforme novos conceitos forem estudados.

## Autor

**Vinicius Vieira Romão**

Projeto desenvolvido para fins de estudo e aprendizado em desenvolvimento web com Python e Django.
