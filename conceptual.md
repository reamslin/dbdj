### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

PostgreSQL is a database management system. It allows users to communicate with their database.

- What is the difference between SQL and PostgreSQL?

SQL is a language. It is a set of standards for communication with a database. PostegreSQL is a database management that allows users to actually work with their data. It is an extension and integration of SQL

- In `psql`, how do you connect to a database?

using the \c command with the name of the database

- What is the difference between `HAVING` and `WHERE`?

WHERE is used to filter queries before or without grouping, while HAVING is used to filter queries after grouping. HAVING utilizes aggregate functions like COUNT, MAX and MIN

- What is the difference between an `INNER` and `OUTER` join?

An inner join focuses on data that has some commonality, while an outer join return all rows of one table and fills in matching data from another leaving attributes blank if they do not exist.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

A left outer join takes all the data from the first table, but only the corresponding data from the second. Right join takes all the data from the second row and only corresponding data from the first.

- What is an ORM? What do they do?

Object Relational Mapper. They make it easier to perform SQL operations within an object oriented programming language.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

Client side requests with AJAX allow requests and changes to be made without reloading or redirecting to a new page. Requests on the server side allow integration with server side database and also allow for requests to be made that require authentication.

- What is CSRF? What is the purpose of the CSRF token?

Cross-site request Forgery. This is attack where someone tries to make a post request from an external source. The CSRF token verifies that the request was made from the appropriate source.

- What is the purpose of `form.hidden_tag()`?

This puts in the CSRF token without the user having to see it on the form.