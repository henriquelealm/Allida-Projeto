# Allida-Projeto
## Equipe:
* [Henrique Leal](https://www.linkedin.com/in/henrique-leal-b24172234/)
* [Théo Moura](https://www.linkedin.com/in/theo-moura-011662232/)
* [Victor Montenegro](https://www.linkedin.com/in/victor-montenegro-833599234/)
* [Pedro Lino](https://www.linkedin.com/in/pedro-lino-4ab6621a1/)
* [Bernardo Nunes]()
* [Gabriella Tereza]()
* [Marina Simões]()
* [Elissa Vangasse]()
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
