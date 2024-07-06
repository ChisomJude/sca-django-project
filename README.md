# Deploy a Python (Django)  - Sample Application

This is the sample Django application, can be used to test your deployment process


## For local development

Fill in a secret value in the `.env` file.

For local development, use this random string as an appropriate value:

```shell
py -m venv .venv
.venv\scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

```
When done Deactivate using `deactivate`

Reference: this repo was cloned from [Azure Samples](https://github.com/Azure-Samples/msdocs-python-django-webapp-quickstart) and modifed for other uses