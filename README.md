Download Link: https://assignmentchef.com/product/solved-cs313-assignment-5
<br>
<span class="kksr-muted">Rate this product</span>

Q1. See the following useful features of PostgreSQL from the manual. Download it if not already done.The link is ​https://www.postgresql.org/docs/9.6/index.html

The following refers to sections in the manual. 3.4 : transactions7.6 LIMIT and OFFSET clauses8.1.4 : serial type

8.2 : monetary type8.5 and 9.9 – date/time types and functions8.7 : enumerated type8.15 : arrays and 8.16 : composite types8.8 : geometric types5.6 : on privilegesRead create trigger statement details in reference part of the manual Ch. 35 : information schema

Q2. Find top 5 students (get their names and department) by tot_cred (i.e, those top 5 who have completed highest total credits). ​( This question needs to be submitted with query and output ).

Q3. ​Create a table called ‘offering’ containing offering_id of serial type with other columns as course_id, semester, year. Then, re-define the section table as ‘new-section’ table so that it uses this offering_id as foreign key without using the course id, semester and year. Load data into these two tables from the old section table and print 10 offerings after joining the offering table with the new-section table. Write a short note on how this design is useful in our university database.

Q4. Create a table which will store aggregate data about the department. It should have dept name,budget, total-salaries, no-of-faculty.

Then write a trigger for the following:– insert on faculty should change total salary and faculty count– update on instructor salary should adjust the total salary of the department.

Q5. Use begin transaction SQL statement along with commit/rollback.

( This question need to be submitted with query or statements of sql file and output )

You need to write insert statements for the following: i) add a courseii) create a section for it with some year/semester etc. iii) assign a teacher to it

Create a file (.sql type) containing the above statements with begin,commit or rollback transactions as per the following cases.Create separate .sql file for each of the following cases and execute :

Note : Load different data in each case as you might get errors if the data gets inserted and may cause insert rejection.

<ol>

 <li>Put commit after all three insert statements.</li>

 <li>Put rollback after second insert statement and commit after third insert statement.</li>

 <li>Put rollback after all three insert statements.</li>

</ol>