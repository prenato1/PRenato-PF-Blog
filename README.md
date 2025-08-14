# ProjetoBlog
Site estilo blog em Django (pt-BR) com páginas, perfis e mensagens.

## Como rodar no CMD (Windows)
```cmd
cd ProjetoBlog
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py seed   # cria usuários e páginas de exemplo
python manage.py runserver
```
Acesse: http://127.0.0.1:8000/

### Usuários de exemplo
- admin / admin123
- autor / autor123

## Apps
- Blog: páginas (CRUD com CKEditor)
- contas: autenticação e perfis
- mensagens: mensagens entre usuários

## Importante
- Não versionar `db.sqlite3` nem `media/` (estão no `.gitignore`).
