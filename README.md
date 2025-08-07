# 🌟 Projeto Educacional: Galeria de Estrelas

Este é um projeto desenvolvido com **Django** que tem como objetivo educar e informar sobre **estrelas** — seus tipos, classificações, curiosidades e muito mais!

O site foi desenvolvido com foco em **boas práticas de desenvolvimento**, especialmente o princípio **Don't Repeat Yourself (DRY)**, garantindo um código limpo, modular e reutilizável.

---

## 🚀 Tecnologias Utilizadas

- Python 3
- Django
- SQLite3
- HTML5 e CSS3
- Padrão DRY

---

## 📁 Estrutura de Pastas

Abaixo está a estrutura do projeto conforme a organização dos arquivos:

├── .venv/ # Ambiente virtual
├── galeria/ # Aplicação principal com regras de negócio
├── setup/ # Configurações adicionais do projeto
├── static/ # Arquivos estáticos (CSS, JS, imagens)
├── templates/
│ └── galeria/
│ ├── partials/ # Arquivos HTML reutilizáveis
│ │ ├── base.html
│ │ ├── imagem.html
│ │ └── index.html
├── .env # Variáveis de ambiente sensíveis
├── .gitignore # Arquivos/pastas ignorados pelo Git
├── db.sqlite3 # Banco de dados local
├── manage.py # Script de gerenciamento do Django
└── requirements.txt # Dependências do projeto
## 🔒 Segurança com `.env`

O arquivo `.env` é usado para armazenar **informações sensíveis**, como:

- Chaves secretas (`SECRET_KEY`)
- Configurações de debug
- Credenciais de banco de dados (em produção)

Esse arquivo **não é versionado no Git**, graças ao `.gitignore`, o que ajuda a evitar o vazamento de informações confidenciais, tornando o projeto mais seguro.

---

## 📚 Objetivo Educacional

O projeto foi pensado como uma plataforma interativa para:

- Ensinar sobre os diferentes tipos de estrelas
- Apresentar curiosidades astronômicas
- Estimular o interesse pela ciência e astronomia

---

## 🧠 Princípio DRY (Don't Repeat Yourself)

Aplicado principalmente nas views, templates e estrutura de pastas, o princípio DRY permitiu:

- Uso de **templates parciais** para componentes reutilizáveis
- Centralização de lógicas e estilos
- Redução de código redundante e melhoria da manutenção

---

## ✅ Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   python -m venv .venv
2.Crie e ative um ambiente virtual:
 ```bash
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate     # Windows
3.Instale as dependências:
```bash
pip install -r requirements.txt
4.Execute as migrações:
```bash
  python manage.py migrate
5.Inicie o servidor de desenvolvimento:
```bash
  python manage.py runserver

