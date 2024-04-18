# flask-docker

Intall docker,docker compose = ./install.sh
Run flask app in docker = ./start.sh
Stop flask app = ./stop.sh

requirements.txt = python requirements which will be installed when container is started (you can get them from your system by writing "pip freeze > requirements.txt)

FAQ: 
can't run scripts => "chmod 7777 name-of-the-script.sh"
can't start app without docker => "pip install -r requirements.txt"
can't do pip instal ... or pip install -r requirements.txt => "python3 -m venv ." and then "source bin/activate"