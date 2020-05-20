# SUMMARY #

### Why would a developer choose to make data models?
Models promote consensus among developers, customers and other stakeholders. A data model also promotes agreement on vocabulary and jargon. The model highlights the chosen terms so that they can be driven forward into software artifacts. The resulting software becomes easier to maintain and extend.

### What purpose do CRUD operations serve?
When we are building APIs, we want our models to provide four basic types of functionality. The model must be able to Create, Read, Update, and Delete resources. Computer scientists often refer to these functions by the acronym CRUD. A model should have the ability to perform at most of these four functions in order to be complete. If an action cannot be described by one of these four operations, then it should potentially be a model of its own.

The CRUD paradigm is common in constructing web applications because it provides a memorable framework for reminding developers of how to construct full, usable models. 

### What kind of database is Postgres? What kind of database is MongoDB?
MongoDB is used for non-relational database management systems, while PostgreSQL is used for the relational database management system.

### What is Mongoose and why do we need it?
Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB.


### Describe how NoSQL Databases scale horizontally
NoSQL databases are designed to expand horizontally and in Horizontal scaling means that you scale by adding more machines into your pool of resources.

### Give one strong argument for and against NoSQL Databases
When compared against relational databases, NoSQL databases are more scalable and provide superior performance, and their data model addresses several shortcomings of the relational model. The advantages of NoSQL include being able to handle: Large volumes of structured, semi-structured, and unstructured data.
NoSQL came along to handle the scale requirements as web apps and multi-tenant services were taking off. Given how hard the problems were to solve, it is understandable that these early attempts at dealing with scaling at the storage layer forced customers into a difficult set of trade-offs.  
But relational databases have evolved. They can handle nearly all of the workloads, with the scalability, reliability, and availability requirements that modern applications demand.  

### Name 3 cloud-based NoSQL Databases
Amazon DynamoDB.
Amazon SimpleDB.
Google Cloud Bigtable.

#### CRUD:
CREATE, READ, UPDATE, DELETE are the four basic functions of persistent storage.A model should have the ability to perform at most these four functions in order to be complete.

#### DataBase:
is an organized collection of data, generally stored and accessed electronically from a computer system. Where databases are more complex they are often developed using formal design and modeling techniques.

#### Data Model: 
is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities.

#### Schema: 
refers to the organization of data as a blueprint of how the database is constructed. The formal definition of a database schema is a set of formulas (sentences) called integrity constraints imposed on a database.

#### Sanitize:
In real world sanitize is to “clean” anything from “bad things”. In computer sciences it means the same thing. Mostly for security purposes, we protect the system from malicious data.
