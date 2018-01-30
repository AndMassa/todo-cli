# todo-cli-andmassa

A command line interface used to track to do items in a software project.
Use the cli to create todo items, list todo items, mark a todo item as complete, and remove  todo item

## Commands

Add a todo-cli item

```
todo add <some text describing the todo item>
```

**example**

```
todo add feed the cat
```

### List Todos

List all todos in your todo list.

```
todo ls
```

### Mark todo complete

toggle a todo item as complete

```
todo-cli-andmassa check <TODO ID GOES HERE>
```

**Example**

Marks the 2nd todo item as complete or not complete if it is complete.
```
todo-cli-andmassa check 2
```

## Remove todo

deletes a specific todo by providing the todo id.

```
todo-cli-andmassa rm <TODO ID GOES HERE>
```

**Example**

```
todo-cli-andmassa rm 1
```

## Future Features

- Show percent of todos completed
- Assign a todo to a person
- Record the data and time completed
- Export the todo items to github as issues
- Export to trello as a List
