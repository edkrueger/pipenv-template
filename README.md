# template-python-project
A template for a python package; uses Pipenv, Black, Pylint and Pytest.

## Dev Setup
Run `pipenv install --dev` to install the env.  
Run `pipenv run pre-commit install` to initialize the git hooks.  
Run `pipenv run pre-commit run --all-files` if there are file that were committed before adding the git hooks.  

## Use
Activate the shell with: `pipenv shell`  

Run local tests: `pipenv run pipenv run pytest --cov=tests`  
Write out the requirements: `pipenv run pipenv_to_requirements`  
Lint with: `pipenv run pylint mypythonpackage/ tests/`
