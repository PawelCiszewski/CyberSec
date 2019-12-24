# CyberSec

<h2>About Cyber Security Base Blog:</h2>

<p>Application “Cyber Security Base Blog" was made in Django – one of the most popular Python Web framework. The idea to create application was to give Cyber Security Base participants another tool to exchange knowledge about course and cyber security in general. Application has most important blog features like: authentication system, registration, log in, logout, user profile customization, user profile update and of course also allows to add, update, view and delete posts. However there are many thinks that can be added (for example pagination), blog is fully functional. As described in the task, Cyber Security Base Blog has five flaws. </p>


<h2>Installation instructions:</h2>

<p>First of all You have to install Python for Your OS. </p>
<p>Link: https://www.python.org/downloads/ </p>
<p>From there You can download Python for Windows, Linux/UNIX, Mac OS X or other OS.</p>
<p>You will also need PIP - standard package-management system used to install and manage software packages written in Python. </p>
<p>In latest version of Python (2.7.9 (or greater) or Python 3.4 (or greater)) PIP comes installed with Python by default. 
<p>You can download PIP from: https://pypi.org/project/pip/</p>
<p>You can install all required packages in the virtual environments or in default Python environment. Virtual Environments in Python allows to keep project-specific dependencies in a separate place than global site-packages. This is extremely useful when You have different versions of packages for different projects. To do it You can use virtualenv.</p>
<p>To install virtualenv in Windows type in console:</p>
<p>$ pip install virtualenv</p>
<p>In non-Windows systems it is discouraged to run pip as root including with sudo.</p>
<p>Virtualenv has one basic command: </p>
<p>$ virtualenv ENV</p>
<p>where  ENV is a directory in which to place the new virtual environment</p>
<p>Now python in your new virtualenv will be effectively isolated from the python that was used to create it.</p>
<p>In a newly created virtualenv there will also be a activate shell script. For Windows systems, activation scripts are provided for the Command Prompt and Powershell.</p>
<p>On Posix systems, this resides in ENV/bin/, so you can run:</p>
<p>$ source /path/to/ENV/bin/activate</p>
<p>This will change Your $PATH so its first entry is the virtualenv’s bin/ directory.</p>
<p>More information: https://virtualenv.pypa.io/en/latest/userguide/</p>
<p>In Your new virtual environments or in default Python environment install django. Installation is similar for Windows, Linux/UNIX and Mac OS X operating systems.</p>
<p>In Your OS console go to directory for the project and type:</p>
<p>$ pip install django</p>
<p>You can check if installation was successful by typing:</p>
<p>$ python -m django --version</p>
<p>If that runs, Django was installed correctly</p>
<p>You will need also 2 more things.</p>
<p>- Django-crispy-forms - an application that helps to manage Django forms</p>
<p>- Pillow - library to work with images in Python</p>
<p>To install them type in console:</p>
<p>$ pip install django-crispy-forms</p>
<p>$ pip install Pillow</p>
<p>Now You have everything to run project so download Cyber Security Base Blog application from Github.</p>
<p>Link: https://github.com/PawelCiszewski/CyberSec</p>
<p>In console go to Your directory and type:</p>
<p>$ django-admin startproject CyberBlog </p>
<p>It will create CyberSec folder in Your directory.</p>
<p>Copy downloaded files there (change existing files)</p>
<p>Type in console:</p>
<p>$ python manage.py runserver</p>
<p>Now You can open Cyber Security Base Blog. </p>
<p>In Your web browser go to http://127.0.0.1:8000/</p>
<p>Everything is set!</p>

