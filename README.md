Flix API 

O **Flix API** é um sistema de back-end desenvolvido para gerenciar um catálago completo de filmes, atores, gêneros e avaliações. O projeto foi construído utilizando Django e Django REST framework (DRF), seguindo as melhores práticas de desenvolvimento de APIs.

Tecnologias Utilizadas

Python
Django
Django Rest Framework (DRF)
SQLite
Flake8

Funcionalidades

Gêneros: CRUD completo de categoria de filmes.
Atores: Gerenciamento de elenco.
Filmes: Cadastro de títulos vinculados a gêneros e atores.
Avaliações: Sistema de notas e comentários para os filmes.
Autenticação: Sistema de login e permissões de acesso.

Como executar o Projeto

1. **Clone o repositório:**
  bash
git clone [https://github.com/renantito95/flix_api.git]
  cd flix_api

2. **Crie e ative um ambiente virtual:**
   bash
python -m venv venv
Windows -> .\venv\Scripts\activate
Linux/Mac -> source venv/bin/activate

3. **Instale as dependências**
  bash
pip install -r requirements.txt

4. **Execute as migrações do banco de dados**
   bash
python manage.py migrate

5. **Inicie o servidor**
   bash
python manage.py runserver
Acesse a API em: http://127.0.0.1:8000/

6. **Endpoints Principais**

GET      /genres/    Lista todos os gêneros
POST     /movies/    Cadastra um novo filme
GET      /actors/    Lista todos os atores
GET      /reviews/   Lista todas as avaliações

Desenvolvido por Renan Tito


