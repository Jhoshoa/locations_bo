# locations_bo
Departamentos, provincias, municipios de Bo

## On Windows
```bash
$ py -3.6 -m venv .venv
$ pyAI3.6/Scripts/activate
```
if you get an error while activating the virtual env, run this command
```bash
$ set-executionpolicy remotesigned -Scope CurrentUser
$ pyAI3.6/Scripts/activate
```
To deactivate run 
```bash
$ deactivate
```
## Dependencies
```bash
$ pip install jupyter
```
or
```bash
$ pip install -r requirements.txt
```
## To export the dependencies of the app
```bash
$ pip freeze > requirements.txt
```

Also  install vscode extencion for Jupyter Notebook => Jupyter
### Notes while running the code
When I try to run i have the code in from the .ipynb I get two option **Python environment** and **Jupyter existing server**, and accoring to the AI:
Use the Python Environment from Your Virtual Environment:
- This ensures that your code runs with the correct dependencies.
- You can activate your virtual environment before starting Jupyter Notebook to ensure that it uses the correct interpreter.
- Dependency Management
- Isolation
