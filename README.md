# Library-Management-Project

- Project had been created using python, pymysql(library to connect with mysql) & tkinter(library for GUI for python)

- To run this project run "main.py"

Also run the following commands in mysql (before running "main.py"):
- create database db1;
- create table books(bid varchar(20) primary key, title varchar(30), author varchar(30), status varchar(30));
- create table books_issued(bid varchar(20) primary key, issuedto varchar(30));

Don't forget to change password

- Following functionalities have been added in this project:

- 1.) You can "add book in the database(or library)"
- 2.) You can "delete book in the database(or library)"
- 3.) You can "issue book from the database(or library) by changing the status of the book (see in the project)"
- 4.) You can "view the book list".
- 5.) You can "return book from the database(or library) by changing the status of the book (see in the project)"
