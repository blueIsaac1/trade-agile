# trade-agile
## INSTALAÇÃO:
'''
pip install -r reqg.txt
'''
## INICIALIZAÇÃO:
'''
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
'''
## INSERTS NO DB.SQLITE3:   
'''
!Verificar se está no mesmo diretório para execução do insert.py, insert2.py. (É necessário os inserts para a aplicação funcionar.)
> (on console):

> python .\insert.py

> python .\insert2.py

> (expected):

> Inserção de dados concluída com sucesso.
'''
## OBSERVAÇÕES:
'''
certifique-se de estar no mesmo diretório do manage.py.
ex: crud-with-django/manage.py
'''
## CRIAÇÃO DO SUPER USER:
'''
Nesse Projeto algumas funções são exclusivas para usuários staffs (superuser), como: realizar_venda, cadastrar_cliente, contact_delete, contact_update.
(on console):

> python manage.py createsuperuser

> Username: (Sua escolha)

> Email address: (Sua escolha)

> Password: (Sua escolha)
'''
