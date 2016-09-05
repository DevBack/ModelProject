# Passos para se fazer antes de desenvolver
1. Verifique com o comando git branch se vc está na branch correta pra desenvolver
2. Instale as dependências novas do projeto: pip install -r requirements.txt
3. Rode o comando: python manage.py makemigrations booking
4. Rode o comando: python manage.py migrate
5. Rode o comando: python manage.py runserver para iniciar o servidor

Lembre-se sempre de mandar as alterações para somente a sua branch com o comando:

`git push remote branch`

Por exemplo:

`git push origin uc01_Gustavo`