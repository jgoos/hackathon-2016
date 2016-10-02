# Hackathon 2016 

# Ideeën
Indien je geen idee hebt  wat te maken dan vindt je hier onder enkele ideeën . Natuurlijk kun je ook aansluiten bij een groepje die wat gaan maken wat je interessant lijkt. Veel plezier!

Change Management     - Input change, check cmdb en output change window naar klant (die hij zelf kan kiezen).
Update  Host          - Geen satellite, maar standaard  repos tooling  om na image installatie een systeem te updaten.

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
