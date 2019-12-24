# CyberSec
<p>
About Cyber Security Base Blog:
</p>
Application “Cyber Security Base Blog" was made in Django – one of the most popular Python Web framework. The idea to create application was to give Cyber Security Base participants another tool to exchange knowledge about course and cyber security in general. Application has most important blog features like: authentication system, registration, log in, logout, user profile customization, user profile update and of course also allows to add, update, view and delete posts. However there are many thinks that can be added (for example pagination), blog is fully functional. As described in the task, Cyber Security Base Blog has five flaws. 
<br />
<p>
Installation instructions:
</p>
First of all You have to install Python for Your OS. 
Link: https://www.python.org/downloads/ 
From there You can download Python for Windows, Linux/UNIX, Mac OS X or other OS.
You will also need PIP - standard package-management system used to install and manage software packages written in Python. 
In latest version of Python (2.7.9 (or greater) or Python 3.4 (or greater)) PIP comes installed with Python by default. 
You can download PIP from: https://pypi.org/project/pip/
You can install all required packages in the virtual environments or in default Python environment. Virtual Environments in Python allows to keep project-specific dependencies in a separate place than global site-packages. This is extremely useful when You have different versions of packages for different projects. To do it You can use virtualenv.
To install virtualenv in Windows type in console:
$ pip install virtualenv
In non-Windows systems it is discouraged to run pip as root including with sudo.
Virtualenv has one basic command: 
$ virtualenv ENV
where  ENV is a directory in which to place the new virtual environment
Now python in your new virtualenv will be effectively isolated from the python that was used to create it.
In a newly created virtualenv there will also be a activate shell script. For Windows systems, activation scripts are provided for the Command Prompt and Powershell.
On Posix systems, this resides in ENV/bin/, so you can run:
$ source /path/to/ENV/bin/activate
This will change Your $PATH so its first entry is the virtualenv’s bin/ directory.
More information: https://virtualenv.pypa.io/en/latest/userguide/
In Your new virtual environments or in default Python environment install django. Installation is similar for Windows, Linux/UNIX and Mac OS X operating systems.
In Your OS console go to directory for the project and type:
$ pip install django
You can check if installation was successful by typing:
$ python -m django --version
If that runs, Django was installed correctly
You will need also 2 more things.
- Django-crispy-forms - an application that helps to manage Django forms
- Pillow - library to work with images in Python
To install them type in console:
$ pip install django-crispy-forms
$ pip install Pillow
<p>Now You have everything to run project so download Cyber Security Base Blog application from Github.
Link: https://github.com/PawelCiszewski/CyberSec
In console go to Your directory and type:
$ django-admin startproject CyberBlog 
It will create CyberSec folder in Your directory.
Copy downloaded files there (change existing files)
Type in console:
$ python manage.py runserver
Now You can open Cyber Security Base Blog. 
In Your web browser go to http://127.0.0.1:8000/
Everything is set!
</p>
