# web_accounting
## Setup

- Install required module
```sh
pip install -r requirements.txt
```

- Run python shell

```sh
python

```

```python
>>> from app import db
>>> db.create_all()
>>> exit()
```

## Usage

```sh
set FLASK_APP=app.py
flask run
```