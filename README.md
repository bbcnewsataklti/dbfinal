Project Title
Library Management
Description of what your project does
To create a relational database for a library management system with student records, we can break it down into the following components:

Students Table – Stores information about students.

Books Table – Stores information about books.

Borrowing Table – Tracks which books are borrowed by students.

Authors Table – Stores information about authors.

Categories Table – Stores book categories (e.g., Fiction, Non-fiction).

Publishers Table – Stores information about book publishers.

We will also set up appropriate constraints, foreign keys, and relationships between tables. Below is the SQL code for creating this database.
ne-to-many relationships: Books have one author, one publisher, and one category.

Many-to-many relationship: A student can borrow many books, and a book can be borrowed by many students. This relationship is handled by the Borrowing table.

Constraints:

Primary Keys (PK) ensure uniqueness for each record.

Foreign Keys (FK) maintain the referential integrity between related tables.

UNIQUE constraints on email and isbn ensure no duplicates.

Screenshot or link to your ERD
![Table Relationships](https://github.com/user-attachments/assets/5eab3f54-9911-4ed6-8f6c-92216a2839c4)

