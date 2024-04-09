# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > C-create
    R-read
    U-update
    D-delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > C - post
    R - get
    U - put
    D - delete

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > Object relational mapping. We use mongoose

04. Which two `HTTP` request types include a body?

  > post and put

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > synchronous and asynchronous 

06. What are the three types of data relationships? Provide an example of each.

  > -One to one: Basically ties data on a 1 to 1 scale. Where the person making the request only has one specific request and the end returning the request only has one thing it can send back.

    -One to many: a blog would be an example here as a blog can have many posts but a post can only belong to one blog

    -Many to many: a movie would be an example here were a movie can have many writers and a writer can have wrote many movies.

07. What is middleware?

  > Software that bridges actions from the operating system and the database/applications that are being interacted with.

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > request and response respectively.

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > const tagInfo = await dbContext.Things.find({ tag : winter}) or http://...api/things/?tag=winter

10. What is a ***virtual property***?

  > A field for a given model
