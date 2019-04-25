#A TODO Restful API APP
This assignment is a basic form of a Restful TODO APP developed by Clinton Johnson.  It allows the user to add and delete todo items on a list that is put into a dictionary of key value pairs.

##How to start app
First you need to install all the dependencies of the application.  Once installed you can then run the application using "flask run".  Click on the link that it shows and change the end of the site to /todos which will load up an empty dictionary.

###How to operate app
Open up a new terminal and pass the following commands to it.
1. Get all todos: `curl http://127.0.0.1:5000/todos`
2. Post a todo: `curl http://127.0.0.1:5000/todos -d "title=pet all the dogs" -d "due_date=Forever" -d "completed=False" -X POST -v`
3. Get a single todo: `curl http://127.0.0.1:5000/todos/1`
4. Update a todo: `curl http://127.0.0.1:5000/todos/1 -d "title=PET ALL THE DOGS" -X PUT -v`
5. Delete a todo: `curl http://127.0.0.1:5000/todos/1 -X DELETE -v`

###In conclusion
This was an interesting project and it helped to dive deeper into what flask can actualy accomplish.