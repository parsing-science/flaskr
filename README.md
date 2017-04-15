# Flaskr

My version of the Flaskr tutorial (http://flask.pocoo.org/docs/0.12/tutorial/).

Flaskr is a basic blog.

## To run the blog locally
``` sh
git clone https://github.com/parsing-science/flaskr.git
cd flaskr
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
export FLASK_APP=flaskr
export FLASK_DEBUG=true
flask initdb
flask run
```

## To run unittests
``` sh
source venv/bin/activate
python -m unittest discover -cv
```
