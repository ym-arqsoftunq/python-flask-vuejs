# python-flask-vuejs
*Instalación en desarrollo
-Node
Para instalar Node
$ curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
$ sudo apt-get install -y nodejs
Para instalar dependencias con Node, ejecutar adentro del proyecto
$ npm install
-Flask (con virtualenv)
$ sudo apt-get install python-virtualenv
Adentro de la carpeta del proyecto
$ . venv/bin/activate
$ pip install Flask
Para correr la aplicacion
$ FLASK_APP=core/app.py flask run

