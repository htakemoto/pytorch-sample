# PyTorch Sample

## Requirements

- [pyenv](https://github.com/pyenv/pyenv)
- [pipenv](https://pipenv.pypa.io/en/latest/)

## Setup

```bash
pipenv shell
pipenv install --dev
```

## Run

```bash
pipenv shell
make start (or pipenv run start)
```

## Tips

```bash
# generate requirements.txt
pipenv lock -r > requirements.txt
# install from requirements.txt
pipenv install -r requirements.txt
```