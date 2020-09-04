# To start using this code
```
$ python3 -m venv venv
$ source venv/bin/activate
(venv) $ pip install -r requirements.txt
```
Then setup the database (with psql working on your machine):
```
(venv) $ createdb warbler
(venv) $ python seed.py
```
Now start the server:
```
(venv) $ flask run
```