# How to run it:
first download ollama from [here](https://ollama.com/) <br> and download an LLM (mistral for exapmle). 
create a __virtual environment__ in the folder <br>
open terminal in the folder location and run this command : `py -m install --user virtualenv` to install virtual env. <br>
then create an env using: `py -m venv env` <br>
now to activate it using _cmd_: `cd env/Scripts` and `.activate` or using _powershell_ `cd env/Scripts; /activate` <br> 
now go back `cd ../..` and install django, ollama and pillow: `pip install django` , `pip install pillow` `pip install ollama` <br>
make sure the ollama is running in the background and the proxy is off. <br>
now go to vscode and in the terminal ( make sure you're in the project folder) and type `py manage.py runserver` and click on the given link.


