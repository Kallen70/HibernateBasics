## Fork [this](https://github.com/NOVA-Uncommon-Coders/HibernateBasics) repo

![screenshot](http://i.imgur.com/zXqdsXK.gif)

## Description

Use Hibernate to store the microblog messages in PostgreSQL. Add editing functionality as well.

## Requirements

* In PostgreSQL, create a database for your project called `microblog`
* Add the necessary lines to `application.properties`
* Modify the `Message` class to mark it as a Hibernate entity and make it store an `int id` with the proper annotations so it is treated as an id and is automatically generated
* Create an interface that extends `CrudRepository<Message, Integer>`
* In your controller, add the repository with `@Autowired` and use it instead of the `ArrayList<Message>`
* Add a way to edit messages and use the repository to update the object