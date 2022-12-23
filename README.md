# SQL
query lanaguage (used for big data)
ORCAL DEVELOPERS ARE THE LARGEST DATABASE MANAGEMENT COMPANY
most cloud computing platforms provides MYSQL IN AWS AND AZURE 

**MYsql
INONDB is a default storage engine for high performance and reliability 

##  Data 
data is a collection of raw facts 
## information 
is a processed data 
##database
collection of processed data and raw facts in large volumne / collection of schema 
## schema 
its a collection of tables 
## DBMS
its a process of storingand retrieving data or information 
  1. *relational database (sql ,tables) *
  2. *hierarchial database (nosql)*
  3. *network (neo-4 j)*
  4. *object oriented *
##ER -diagram 
represenation of entities and attributes , describes relationship btw each other 

**entity**
its a non living or real things where data is maintained 

** attribute**
property of an entity 
1. key attribute 
2. composite attribute 
3. derived attribute 
4. multivalued attribute 

primary key is unique key and doesnt have null values in the table

**Realationship**
it is a process of describe a realationship between enitity 
1. one to one
2. one to many
3. many to one
4. many to many 

**cardinality ratio:**
its a process of expressing the relationship to find out how are participating in the event 
 
The commands available in SQL can be broadly categorised as follows:

**Data Definition Language (DDL):**

1. Create  
(create database )( create table name)
2. Alter
3. Drop 
(which will drope the entire table ) drop table test;
4. Rename

**Data Manipulation Language (DML):**

1. Insert  
insert into <table name> values(--,--);
2. Update  
update table name set name ='',address='' where zip='89'; null -values
3. Delete  
delete from table name where name ='';   / delete from table name ;-( delete the entire table values ) 
4. Select
5. Truncate

## schema 
its a collection of tables 

##code for creating database ##
DDL
```
create database ;
create databse database_name;
create table;
create table table_name(column_name datatype key);
show tables;
desc table name

alter table by adding column
alter table table_name add column column_name constraint;
 alter table by deleting column
alter table table_name drop column column_name;
alter table by changing an existing column and constraint
alter table table_name change old_column_name new_column_name constraint;

drop database
drop database database_name;
 drop table
drop table table_name;
```

##to use the database after importing the file ##
```
show datbases
use world
show tables
```

##join clause ##
ability to join the rows from diffrent tables and find relationship between them.

```
select a.artist as artist,a.title ,t.title as album,t.title,t.track_number,t.duration
from album as a join track as t on a.id=album_id
order by a.artist,a.title,t.track_number;
```


