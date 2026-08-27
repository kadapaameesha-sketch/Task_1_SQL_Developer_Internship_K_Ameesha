# Task_1_SQL_Developer_Internship_K_Ameesha
Name:K.Ameesha   
 Domain: Digital Library Management System  
Tools: PostgreSQL / pgAdmin


📌 Project Overview


This project contains the relational database design, DDL scripts, and core DBMS conceptual answers for Task 1 of the SQL Developer Internship. The schema is modeled for a Digital Library Management System using PostgreSQL to handle authors, books, member registration, and borrowing activities while enforcing strict data integrity.




🗄️ Relational Schema Design

The database structure consists of four core tables connected via referential integrity constraints:  
● authors: Stores author identity details.  
● books: Catalogs available books linked to authors via a Foreign Key. 
● members: Manages registered library members.  
● borrowings: A junction table resolving the many-to-many relationship between members and books.



💡 DBMS Conceptual QA Highlights

● Normalization: Decomposing tables up to 3NF to eliminate insertion, update, and deletion anomalies while maintaining logical dependencies.  
● Primary Key vs Foreign Key: A Primary Key uniquely identifies rows without allowing NULL values, whereas a Foreign Key references a Primary Key in another table to  establish relationships.  
● Surrogate Key: An artificial, auto-generated unique identifier (like identity integers) with no external business meaning.  
● Composite Key: A primary key formed by joining multiple columns when single attributes are insufficient for uniqueness.  
MySQL Storage Engine (InnoDB): InnoDB provides ACID compliance, row-level locking, and full foreign key support
