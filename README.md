# project-FORUM

The project was developed during Databases course on my studies. I cooperated with akaras161, LukeXwas and Ne0-exe. The project was written in Python using the MySQL database. The program simulates a forum where users can create an account and then post and view product reviews. A system of assigning users ranks has also been implemented. Administration uses ranks to accept or reject opinions posted by users.

## How to run it?

For run FORUM, you need the main.py file, MySQL database server with imported file forum_database.sql and the connectros.cnf configuration file, where you must provide data to connect to your database server. The structure of the database was also prepared with sample data in the forum_datebase.sql file.

The main idea was to host the database server on AWS, but this requires fees.

## composition_generator.py

This script generates sample data for the database. It also uses the connectors.cnf configuration file to conect to database server.
