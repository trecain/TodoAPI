# Lab 19 - Web API's

This is a simple to do app using entity framework and C#.  The application uses a cusom API and database.

## Routes

POST: api/todolist
Creates a new todolist which only requires a name.

POST: api/todo
Creates a new todoitem. 

GET: api/todolist
Gets all of the todolists.

GET: api/todolist/:id
Where :id is the todolists id number. 

GET: api/todo
Gets all of the todoitems

GET: api/todo/:id
Where :id is the todoitem id number. 

PUT: api/todo/:id
Allows a user to update a specific todoitem.

PUT: api/todolist/:id
Allows a user to update a specific todolist. 

DELETE: api/todo/:id
Deletes the todoitem with the designated id number.

DELETE: api/todolist/:id
Deletes the todo list.