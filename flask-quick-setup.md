# Install
Installeer een rhel of centos 7 systeem:

 # yum -y install python-virtualenv.noarch
 
 # yum -y install python python-flask python-jinja2 curl wget git

 # yum -y install postgresql-devel gcc
 
Zelf poorten toevoegen of voor bouw server firewalld uit:
 # systemctl disable firewalld 
 
 # systemctl stop firewalld

Indien er in de update een kernel update is geweest:
 # reboot


 $ mkdir build

 $ cd build

 $ python -m virtualenv flask    of  virtualenv flask

 $ source flask/bin/activate

 $ mkdir app

 $ mkdir app/static

 $ mkdir app/templates

 $ mkdir tmp


Via easy_install de benodigde pakketten installeren:
 # python setup.py install

of via pip:

Handige zijn (install):
 $ flask/bin/pip install flask
 
 $ flask/bin/pip install flask-login
 
 $ flask/bin/pip install flask-mail
 
 $ flask/bin/pip install flask-sqlalchemy
 
 $ flask/bin/pip install flask-wtf
 
 $ flask/bin/pip install psycopg2


 $ pip freeze > requirements.txt
 
 $ pip install -r requirements.txt



Enkele andere die handig zijn maar niet altijd gebruikt worden zijn:
 $ flask/bin/pip install flask-openid
 
 $ flask/bin/pip install sqlalchemy-migrate

 $ flask/bin/pip install flask-whooshalchemy
 
 $ flask/bin/pip install flask-babel
 
 $ flask/bin/pip install guess_language
 
 $ flask/bin/pip install flipflop
 
 $ flask/bin/pip install coverage



Als user:
$ vi app.py

  #! usr/bin/python
  from flask import Flask

  app = Flask(__name__)

  @app.route("/")
  def hello():
      return "Hello World!\n"

  if __name__ == "__main__":
      app.run()



Run de code:
 $ python app.py



In second connection:
 $ curl http://127.0.0.1:5000/
