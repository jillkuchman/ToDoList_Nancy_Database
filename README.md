# To Do List

#### To do list application with tasks and categories, 2016-02-24

#### By Jill Kuchman

## Description

This is a to do list application with tasks and categories. It demonstrates database usage with one-to-many relationships. Finished app at the end of learnhowtoprogram lesson here: [Nancy with databases](https://www.learnhowtoprogram.com/c/c-database-basics/nancy-with-databases)

## Setup/Installation Requirements

* Clone this repo
* Navigate to the project folder in shell and run the following commands for access to shell commands:

```
> dnu restore
```

* This app requires a database called `todo` with a `tasks` and `categories` table. To create this database, connect to your server and use the following commands:<br>

> CREATE DATABASE todo;<br>
> GO<br>
> USE todo;<br>
> GO
> CREATE TABLE categories (id INT IDENTITY(1,1), name VARCHAR(255));<br>
> CREATE TABLE tasks (id INT IDENTITY(1,1), description VARCHAR(255), category_id INT);<br>
> GO

* Testing requires a clone of this database named `todo_test`
* To run tests, navigate to the project folder in shell and run

```
> dnx test
```

* To run this app, navigate to project folder in shell and run

```
> dnx kestrel
```


## Known Bugs

If you find any, please let me know!

## Support and contact details

Feel free to contact me through GitHub.

## Technologies Used

C# v4.0, DNX 451, Nancy v1.3, xunit v2.1.0, kestrel server

### License

*{Determine the license under which this application can be used.  See below for more details on licensing.}*

Copyright (c) 2016 **Jill Kuchman**
