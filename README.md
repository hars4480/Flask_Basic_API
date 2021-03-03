# Flask_Basic_API

 Activate venv

$ pipenv shell

 Install dependencies

$ pipenv install

 Create DB

$ python

>> from app import db

>> db.create_all()

>> exit()

Run Server (http://localhst:5000)

python app.py

Endpoints

GET /product

GET /product/:id

POST /product

PUT /product/:id

DELETE /product/:id
