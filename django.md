# 📖 Django — Guia Rápido

## 🌐 Ambiente Virtual Django
📄 Documentação oficial: [Como configurar no Windows](https://docs.djangoproject.com/en/5.1/howto/windows/)

## 📦 Instalação

```bash
# Criar ambiente virtual
py -m venv .venv

# Ativar ambiente virtual (Windows)
.venv\Scripts\activate

# Instalar Django
py -m pip install Django

django-admin startproject [nome do projeto]

cd [nome]

py manage.py runserver
```
## Criando um APP
```bash
py .\manage.py startapp app
