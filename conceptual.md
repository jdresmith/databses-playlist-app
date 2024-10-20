### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
PostgreSQL is a relational database management sytem which is used to store and manage data in a structured format through columns and rows.

- What is the difference between SQL and PostgreSQL?
SQL is a language used in the querying and managing relational databases while PostgreSQL is the a relational database management system which implements SQL to be used.

- In `psql`, how do you connect to a database?
PSQL connects to a database through various methods but the command line tool using psql is the easiest method.


- What is the difference between `HAVING` and `WHERE`?
WHERE filters rows before grouping while HAVING filters after grouping, which means WHERE is akdo applied first while HAVING is applied last.


- What is the difference between an `INNER` and `OUTER` join?
An INNER JOIN returns only the rows that have matching values in both tables while OUTER JOIN can be broek into LEFT or RIGHT JOIN to return all rows from either side and match rows from the other.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
LEFT JOIN returns all rows from the left table and the matched rows from the right table and vice versa for RIGHT JOIN.

- What is an ORM? What do they do?
ORMs provide a powerful way to interact with relational databases using an object-oriented approach. They simplify database operations, enhance productivity, and help ensure code maintainability and security.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  1. AJAX runs in the browser (client-side), while requests runs on the server (server-side).

  2. AJAX requests are often user-driven, while requests can be part of backend processes.

  3. AJAX directly impacts user experience by enabling dynamic content updates, while requests indirectly affects user experience through backend processing and data availability.

- What is CSRF? What is the purpose of the CSRF token?
CSRF (Cross-Site Request Forgery) is a type of security vulnerability in web applications. The main purpose of the CSRF token is to prevent CSRF attacks by ensuring that the request made by the client is intentional and originates from the legitimate source.

- What is the purpose of `form.hidden_tag()`?
The purpose of form.hidden_tag() in a web form is to render hidden fields that are necessary for the form to function correctly. 