# Women Who Code Cleveland presents: Introduction to SQL
Work in progress: [Google Slides](https://docs.google.com/presentation/d/1Za_wcYI-QbJy2OePYTL2YTA8L2vMf9NZhNw1h5WnZ1k/edit?usp%253Dsharing)

This workshop focuses on composing SQL queries for READING data from a database. This is valuable for those interested in Data Analysis.

### Pre-Requisites
- [Download pgadmin4](https://www.pgadmin.org/download/)
- [Download the DVD movie rental database](https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/)
- [Import database into pgadmin4](https://www.postgresqltutorial.com/postgresql-getting-started/load-postgresql-sample-database/)

the following may be helpful for Mac users
```bash
# unzip to convert to tar
unzip dvdrental.zip -d dvdrental
```


### What will be covered in this workshop?
- What is structured data?
- Why RDBMS? Why SQL?
- Import data troubleshooting
- Anatomy of an SQL statement
- Practice Exercises
- Next Steps

## Why SQL?
SQL or Structured Query Language is a way to access relational data stored in a database. Relational data preceeds SQL, but both started in the 70s, and have dominated the market ever since.

A benefit to using a database and SQL is its persistence feature, meaning any updates or changes made to the database will be consistent among all users (humans, and other creatures). 

### Data is powerful
Think of your favorite apps.
- A user experience based on a database which stores different interactions with the app

Think of decision makers, like business owners and project managers.
- These folks use all information available, much of which is stored in databases to deliver value, coordinate inventory, staffing, and logistics

Think of Researchers.
- Use increasingly larger, (hopefully) more representative data to test hypotheses, quantify observations, validate trends



## SQL Notes

We will be answering questsions about the DVD Rental database such as:
- What Geographic region do these DVD Rental shops serve?
    - Select all columns in the address table
    - Select all columns in the country table
    - List each district in the address table
    - How many countries are in the country table?
    - List the address of each store (subqueries simple)
    - LIst the country of each store (subqueries advanced)
- How long do people check out DVDs?
    - Sort rentals table by longest rental time
    - Filter out Null values
- Films and Actors
    - Select all columns from the table film_actor where the actor_id =1 (simple)
    - Show which actors are in the most movies (inner join, group by)



---
SQL can be used to create, read, update, and delete databases AND database permissions, adminstered through [ROLES and USERS](https://www.w3resource.com/sql/database-security/create-users.php). 

Here are some commands for manipulating databases:

`UPDATE` - updates data in a database

`DELETE` - deletes data from a database

`INSERT INTO` - inserts new data into a database

`CREATE DATABASE` - creates a new database

`ALTER DATABASE` - modifies a database

`CREATE TABLE` - creates a new table

`ALTER TABLE` - modifies a table

`DROP TABLE` - deletes a table

`CREATE INDEX` - creates an index (search key)

`DROP INDEX` - deletes an index


## Resources

- [Database Analyst salaries by state](https://www.zippia.com/database-analyst-jobs/salary/#salary-by-state)

WWC Data Science Track Events:
- [SQL Coding Series - Basics I](https://www.youtube.com/watch?v=ypMYEEvLkdQ&list=PLVcEZG2JPVhcOGRWbtmocId5_TBNi-ZG2&index=30&t=446s&pp=iAQB)
- [SQL Coding Series - Basics II](https://www.youtube.com/watch?v=V8hn5LUoYDk&list=PLVcEZG2JPVhcOGRWbtmocId5_TBNi-ZG2&index=29&pp=iAQB)
- [SQL Coding Series - Intermediate I](https://www.youtube.com/watch?v=O5KAQWfpGqQ&list=PLVcEZG2JPVhcOGRWbtmocId5_TBNi-ZG2&index=27&pp=iAQB)
- [SQL Coding Series - Intermediate II](https://www.youtube.com/watch?v=QdK-hM_pihU&list=PLVcEZG2JPVhcOGRWbtmocId5_TBNi-ZG2&index=26&pp=iAQB)
- [SQL Coding Series - Advanced](https://www.youtube.com/watch?v=nszcEc8j0U4&list=PLVcEZG2JPVhcOGRWbtmocId5_TBNi-ZG2&index=25&pp=iAQB)


