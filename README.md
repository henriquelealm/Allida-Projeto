# Allida-Projeto
# Utilização

Instalar o projeto usando o venv é recomendado, porém é possível instalar sem usá-lo também.

Ative o virtualenv no projeto:

    $ virtualenv project-env
    $ source project-env/bin/activate

Caso não tenha o django instalado ainda execute:

    $ pip3 install django
    

# Começando

Primeiramente clone esse repositório do Github e entre em seu diretório:

    $ git clone https://github.com/henriquelealm/Allida-Projeto.git
    $ cd Allida-Projeto
    
Instale os requirements:

    $ pip install requirements.txt
    
    
Aplique as migrações do banco de dados:

    $ python manage.py migrate
    

Agora, basta apenas rodar o servidor localmente:

    $ python manage.py runserver

Dentro dessa pasta, haverá um arquivo databaseC.exe, que ao ser executado pelo próprio windows. irá enviar informações de quedas para o Django
