## Create virtual environment to manage dependencies:

```
python3 -m venv venv
source venv/bin/activate
```

## With the virtual environment activated, install Flask:

```
pip install Flask
```

## Freeze the installed packages to a requirements file:

```
pip freeze > requirements.txt
```

## You can run the script from the command line:

```
fastapi dev main.py
```
