# FlaskProducts
A backend project using Flask, SQLAlchemy and Marshmallow to add, update and delete products in a database


  
##Overview

Project uses Flask as the framework, SQLAlchemy as the database tool and Marshmallow as the serializer to return json data

##Installation

pipenv install flask, flask-sqlalchemy, flask-marshmallow, marshmallow-sqlalchemy

##input in json format (I used Postman)

Fields: Product name, description, price and quantity. Like this: 

{ "name": "Product One",
  "description": "I am product one",
  "price": 30.05,
  "qty": 25
  }
  
 ##Output
 SQLAlchemy and Marshmallow work together to add, delete, update an individual product and to get the full list of
 products. SQLAlchemy turns the basic SQL database into Python objects and classes making the CRUD code simpler and 
 easier to use.
 
 #Resources
 This is a demo app based on
 Brad Traversy's tutorial https://www.youtube.com/watch?v=PTZiDnuC86g
 
  
