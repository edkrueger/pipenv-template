# template-python-project
A template for a simple python script with resources; uses GitLab CI, Pipenv and Pytest.

## Setup
Run `pipenv install` to install the env.
Run `pipenv run pre-commit install` to initialize the git hooks.
Run `pipenv run pre-commit run --all-files` if there are file that were committed before adding the git hooks.

## Use
Activate the shell with: `pipenv shell`
Run local tests: `pipenv run pipenv run pytest --cov-config=.coveragerc --cov=resc`
Write out the requirement: `pipenv run pipenv_to_requirements`