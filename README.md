# Hackathon 2016 

 Beschrijving: https://www.pleio.nl/events/event/view/45145812/hackathon-18-november-2016  <br>
 <br>
 Lokatie: https://www.google.nl/maps/place/Johan+Huizingalaan+763A,+1066+VH+Amsterdam/@52.3430429,4.8270918,17z/data=!3m1!4b1!4m5!3m4!1s0x47c5e18eae78495d:0x69f2205bc0250fb4!8m2!3d52.3430396!4d4.8292805 <br>

# Ideeën
Indien je geen idee hebt  wat te maken dan vindt je hier onder enkele ideeën . Natuurlijk kun je ook aansluiten bij een groepje die wat gaan maken wat je interessant lijkt. Veel plezier!

Simpele depot omgeving:
simpeler dan satellite die meerdere soorten aankan (zie bijvoorbeeld pulp)
  
Galaxy hub intern bruikbaar maken:
galaxy hub is opensource. Maak iets vergelijkbaars of pas aan, zodat intern ook ansible playbooks geupload kunnen worden en gedeelt onder elkaar

Change machine:
aanmaken van change software, met tijd vakken die klant kan kiezen en koppelingen met backend systemen (CMDB, server owner lijsten enz).
input change, check cmdb en output change window naar klant (die hij zelf kan kiezen).

!!!!!!!!!!!!!!Nog de brainstorm lijst toevoegen!!!!!!!!!!

# Tooling List
De meeste van ons hebben een eigen toolset die gebruikt worden tijdens het maken van applicaties. Hieronder vindt
je een lijst van tooling die handig zijn indien je niet zo'n lijst hebt. Zodat je snel kan beginnen zonder al te
veel zoeken.

## Editors
Atom                            - https://atom.io/

Eclipse                         - https://eclipse.org/downloads/

Notepad++                       - http://notepad-plus-plus.org

Sublime text                    - http://www.sublimetext.com/3

Visual Studio                   - http://www.microsoft.com/visualstudio/eng/products/visual-studio-overview

## Programming Tutorials
Python 3                        - https://docs.python.org/3/tutorial/

Tutorialspoint Python           - https://www.tutorialspoint.com/python/

C en C++ Tutorials              - https://www.codingunit.com

Bash Tutorials                  - http://tldp.org/LDP/Bash-Beginners-Guide/html/

Golang Tutorials                - https://gobyexample.com

HTML en CSS Tutorials           -  http://www.w3schools.com/html/

## Web framework tutorials
Flask Mega Tutorial             - http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

Django Tutorial                 - https://docs.djangoproject.com/en/1.10/intro/tutorial01/  

Ruby                            - http://rubyonrails.org

Codeignitor                     - https://www.codeigniter.com

Angularjs                       - https://angularjs.org

## Front-end Frameworks
Bootstrap                       - http://getbootstrap.com

Foundation                      - http://foundation.zurb.com

## JavaScript Libraries
jquery                          - http://jquery.com

Backbonejs                      - http://backbonejs.org

jquery UI                       - http://jqueryui.com

jquery Mobile                   - http://jquerymobile.com

##  Architecture  drawing
Lucidchart                      - https://www.lucidchart.com

Smartdraw                       - https://www.smartdraw.com

##  DB Tools
Flask  SQLAlchemy               -  https://www.tutorialspoint.com/flask/flask_sqlalchemy.htm

##  Debugging
Python3  debugger               -  https://docs.python.org/3/library/pdb.html

Golang  debugger                -  https://golang.org/doc/gdb

OWASP Zed Attack Proxy Project  -  https://www.owasp.org/index.php/ZAP


##  More links tool-list
Web dev tools 100+ list          - https://www.keycdn.com/blog/web-development-tools/

## Ansible Role  Structure
    roles
        |__ defaults

            |__ main.yml - includes information about default variables used by this role

    
        |__ files        - files which need to be deployed to your hosts without any modification.

    
        |__ templates    - using jinja2 templating system, configuration variables can
                            be passed to templates and those modified templates will be
                            placed on the hosts

        |__ tasks        - each play can contain multiple task, and each task can perform multiple actions.
    
             |__ main.yml

    
        |__ meta         - environment Description, Author, Licensing Attributes etc. are placed.
    
             |__ main.yml

    
        |__ vars         - variables as username, folder name are stored in vars.
    
             |__ main.yml

    
        |__ handlers     - tasks which are executed on completion of other tasks.
                   think of them as callbacks.
    
             |__ main.yml
