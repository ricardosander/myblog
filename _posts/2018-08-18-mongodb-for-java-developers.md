---
layout: post
title:  "MongoDB - Conceitos Básicos"
date:   2018-08-18 17:37:00 -0300
categories: mongo mondodb database nosql
---

[MongoDB University](https://university.mongodb.com)

M101J: MongoDB for Java Developers

About MongoDB
- Document dababase
- JSON - JavaScript Object Notation
- can design databases based on data access patterns (less queries), design based on application needs
- scaling out


Tools
- mongod - mondo database process
- mongo - mongo shell client application

JSON - string, numbers, boolean, array, object - [json.org](http://json.org)

BSON (MongoDb store documents as BSON) = Binary JSON bsonspec.org
lighweight
traversable 
efficient (encode to and decode form is quickly)
extand JSON data types (date, some objects, other numbers values)


CRUD
_id, mondo adds if you don't provide. insert return a object with the _id and the acklodge. 
find - query by example
find - return a cursor

renational x no relational blog queries. How many collection x how many tables example

to embed x not to embed : access pattern / application needs

Fontes :  
[MongoDB University](https://university.mongodb.com)  
[json.org](http://json.org)