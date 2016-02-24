# To Do List

#### To do list application with tasks and categories, 2016-02-24

#### By Jill Kuchman

## Description

This is a to do list application with tasks and categories. It demonstrates database usage with one-to-many relationships. Finished app at the end of learnhowtoprogram lesson here: [Nancy with databases](https://www.learnhowtoprogram.com/c/c-database-basics/nancy-with-databases)

## Setup/Installation Requirements

* _This is a great place_
* _to list setup instructions_
* _in a simple_
* _easy-to-understand_
* _format_

This app requires a database called `todo` with a `tasks` and `categories` table. To create this database, connect to your server and use the following commands:<br>

> CREATE DATABASE todo;<br>
> GO<br>
> USE todo;<br>
> GO
> CREATE TABLE categories (id INT IDENTITY(1,1), name VARCHAR(255));<br>
> CREATE TABLE tasks (id INT IDENTITY(1,1), description VARCHAR(255), category_id INT);<br>
> GO



## Known Bugs

If you find any, please let me know!

## Support and contact details

Feel free to contact me through GitHub.

## Technologies Used

_{Tell me about the languages and tools you used to create this app. Assume that I know you probably used HTML and CSS. If you did something really cool using only HTML, point that out.}_

### License

*{Determine the license under which this application can be used.  See below for more details on licensing.}*

Copyright (c) 2016 **Jill Kuchman**
