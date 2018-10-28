Proposed project
================

API to allow Product CMS to create and manage products that they would like to sell.

Requirements:
============
* Written in Python
* Unit tests


Suggestions:
============
* Use [Flask](http://flask.pocoo.org/)
* Use [Postgresql](https://www.postgresql.org/)
* Use [Docker](https://www.docker.com/) to make development easier


Conversation starting:
======================
GET /products

```json
[{
   "id": 1,
   "name": "Name of product",
   "description": "The description goes here",
}]
```

Post /products
```json
{
   "name": "Name of product",
   "description": "The description goes here",
}
```

PUT /products/1
```json
[{
   "id": 1,
   "name": "Name of product",
   "description": "The description goes here",
}]
```

I would say this is a small part of a much larger project.

Other elements:
===============
* CMS where you add manage products in a user friendly UI
* Search service to help search for products
* Purchasing service 
* Frontend user facing site to display products and purchase them.
* and more...