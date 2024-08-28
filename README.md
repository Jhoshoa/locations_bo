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
```bash
$ pip install -r requirements.txt
```
## Notes
It seems that after installing jupyther it comes with ipykernel library, but if not please install this way
```bash
$ pip install ipykernel    
$ pip show ipykernel     -- To verify if it is installed

$ pip install psycopg2-binary
$ pip install psycopg2
$ pip install pandas
```
To ensure that the jupyter uses the vistual environment use this command:

- Replace .venv with a name that represents your virtual environment.
- The --display-name option specifies what will be shown in the Jupyter Notebook interface.

```bash
$ python -m ipykernel install --user --name=.venv --display-name "Python (venv)"
```

To launch jupyter notebook in the localhost run this
```bash
$ jupyter notebook
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

## Run docker composer
```bash
$ docker compose up -d
$ docker-compose logs db
```

Search here
https://fichacomunidad.ine.gob.bo/
https://es.wikipedia.org/wiki/Municipios_de_Bolivia
https://es.wikipedia.org/wiki/Anexo:Municipios_de_Bolivia
https://es.wikipedia.org/wiki/Departamento_de_Chuquisaca
