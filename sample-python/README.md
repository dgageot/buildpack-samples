Sample Python
-------------

[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run)

Setup Local Python Environment:

(If the Python install fails, see: https://github.com/pyenv/pyenv/wiki/Common-build-problems)

```
git clone https://github.com/pyenv/pyenv.git .pyenv
export PYENV_ROOT=.pyenv
.pyenv/bin/pyenv install
eval "$(.pyenv/bin/pyenv init -)"
python -m venv venv
source venv/bin/activate
pip install -U pip
pip install -r requirements.txt
```

Run the server locally:
```
FLASK_APP=web.py flask run
```

Check it out: http://127.0.0.1:5000/

