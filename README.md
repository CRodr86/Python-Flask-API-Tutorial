<p align="center">
  <img src="./src/img/4geeks.jpg">
</p>

------------

# Todo List API in Python Flask

## Flask exercises

##### Made by Rodrigo Carvalho

------------

### Project:
 
It's my solution for a series of interactive tutorial that will teach us how to create an API using the Python Flask framework using Python and Pipenv.

In this tutorial we are going to be building a REST API that exposes 3 endpoints to the internet:

```txt
GET /todos
POST /todos
DELETE /todos/<int:position>
```

### GET /todos

Will return the list of all todos like this:

```javascript
[
    {
        "done": true,
        "label": "Sample Todo 1"
    },
    {
        "done": true,
        "label": "Sample Todo 2"
    }
]
```

### POST /todos

It's going to add a new todo to the list, it will receive the following request body:

```javascript
{
    "done": true,
    "label": "Sample Todo 1"
}
```

And return the updated list of todos.

### DELETE /todos/<int:position>

It's going to remove one todo based on a given position at the end of the url, and return the updated list of todos.

------------

Exercises made during the **Full Stack Developer Coding Bootcamp** at **4Geeks Academy**