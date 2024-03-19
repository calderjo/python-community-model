# python-community-model

Python package can be installed directly via git. This provides an easier option to share packages as the package does not need to be published to pypi, which invloves setting up an credentials and keys.

Install default branch
```
> mkdir my-env
> cd my-env
> python -m venv .env
> activate .env/Scripts/activate
(.env) > python install pip install git+https://github.com/neshdev/python-community-model.git
```


Install specific branch
```
> mkdir my-env
> cd my-env
> python -m venv .env
> activate .env/Scripts/activate
(.env) > python install pip install git+https://github.com/neshdev/python-community-model.git@branch_name
```


Install Release/Tag
```
> mkdir my-env
> cd my-env
> python -m venv .env
> activate .env/Scripts/activate
(.env) > python install pip install git+https://github.com/neshdev/python-community-model.git@v1
```