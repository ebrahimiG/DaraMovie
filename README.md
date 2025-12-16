# How to run it:
in the folder create a __virtual environment__ <br>
open terminal in the folder and run this command : `py -m install --user virtualenv` to install virtual env. <br>
then create an env: `py -m venv env` <br>
now to activate it using cmd: `cd env/Scripts` and `.activate` or using powershell `cd env/Scripts; /activate` <br> 
now go back `cd ../..` and install django, ollama and pillow: `pip install django` , `pip install pillow` `pip install ollama` <br>
now go to vscode and in the terminal ( make sure you're in the project folder) and type `py manage.py runserver` and click on the given link.

