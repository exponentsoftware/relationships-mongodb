# Title
Relations between collections mongodb/mongoose

## Introduction

Relationships in MongoDB database represent a link between two data collections. They allow the database to handle data that is related and to query it efficiently. In MongoDB, there are two types of relationships: one-to-one and one-to-many.

In a one-to-one relationship, each record in one collection is related to exactly one record in another collection. For example, a customer can have one address and an address can belong to only one customer.

To complete this tutorial, you should learn about how to create models and schemas with Mongoose, the MongoDB object modeling library. You should also learn how to use Mongoose to define and store relationships between models.


## Assignment

We will be following the below tutorial and will be adding relationships between our collections from the previous assignments.

- [One to One relationship](https://www.bezkoder.com/mongoose-one-to-one-relationship-example/)
- [One to Many relationship](https://www.bezkoder.com/mongoose-one-to-many-relationship/)
- [Many to Many relationship](https://www.bezkoder.com/mongodb-many-to-many-mongoose/)

Based on these tutorials, you need to understand when to use 1-1, 1 - many and many to many relationship between two collections/models.

You will be creating models for User comments on tutorials and Tags for the tutorials. 
Create routes and ensure that you add proper permissions and implement pagination on get all routes.

