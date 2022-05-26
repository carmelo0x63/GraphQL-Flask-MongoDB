# GraphQL-Flask-MongoDB
Access a MongoDB database using Python, Flask, and GraphQL

source: https://www.jitsejan.com/graphql-with-flask-and-mongodb
  https://github.com/jitsejan/flask-mongodb-graphene

----


python3 -m pip install --upgrade pip setuptools wheel

python3 -m pip install dnspython flask flask_graphql graphene graphene_mongo jsonpath mongoengine

docker run --name mongodb -p 27017:27017 -d mongo:latest

python3 database.py

python3 app.py

