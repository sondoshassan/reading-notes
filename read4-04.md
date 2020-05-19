# summary class 04

## Answer questions
**the same questions in read 3 just add question 5,6 and 8**
1- Why would a developer choose to make data models?
there are many benefit of using data models, ensure data objects, it provide clear of the base data, help to identify the messing data and helps to define the relational tables, primary and foreign keys.
to connect the data with each other.

2- What purpose do CRUD operations serve?
CRUD: it's create, read, update and delete.
the curd using in many function underlying relational databases. instead of using SQL we using the crud.

3- What kind of database is Postgres? What kind of database is MongoDB?
in Postgres is a general-purpose object-relational database management system, in MongoDB is NoSQL database

4- What is Mongoose and why do we need it?
is an object data modling 
make the mongoDB flexible and powerful, maintaining mongoDB.

5- Describe how NoSQL Databases scale horizontally?
at first the horizontal scaling is scale horizontal by adding more machine.
it focus on increase the number of machines.
6- Give one strong argument for and against NoSQL Databases.
join

7- Define three related pieces of data in a possible application.

ex1: chat application might be account, profile and masseges. it related by each account h

8- Name 3 cloud based NoSQL Databases.
- Azure Cosmos DB
- MongoDB 
- Google Cloud Bigtable

### test mongo
by using mock it is difficult to manage all the situation, it takes a lot time. but by using this package `mongodb-memory-server`, the test will be simple and easy.
the method to use this test first install this dependecy `npm install --save-dev jest mongodb-memory-server`,

### Repository Design Pattern
sparates data and map it to the business entities in the business logic.
the benefit of sparates this data, business and data access logic can be tested separately, reduces duplication of code, and lower chance for making programming errors.
