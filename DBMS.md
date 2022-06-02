Which of the following is/are the content(s) of a data dictionary?
- [ ] Database schema
- [ ] Database instance
- [ ] Integrity constrains
- [ ] Authorizations

Accepted Answers:
- [X] Database schema
- [ ] Database instance
- [X] Integrity constrains
- [X] Authorizations

Which among the following is/are not a part of Query Processing?
Options :
A. Optimization
B. Parsing and translation
C. Indexing
D. Evaluation Engine


16. Consider the relational schema given in Figure 13.

Figure 13: Employee Schema

If the relations employee, designation and department have 100, 6, 5 rows respec-
tively, what is the maximum number of rows returned by the following query?

[NAT: 4 points]

SELECT * FROM employee FULL OUTER JOIN designation
ON employee.desgID = designation.desgID;
Answer: 105

Solution: desgID is the foreign key in table employee that references designation

table. It follows that the desgID in any row of employee table will have a corre-
sponding entry in the designation table. However, the converse is not always true.

That is, corresponding to each desgID in the designation table, there need not be
an entry in the employee table. Hence, the minimum number of rows in the outer

join is the number of rows in the employee table, which is 100. However, the maxi-
mum may not be 100 because, there could be rows in the designation table that do

not have a matching entry in the employee table. Note that there should be at least
one desgID in department table that has a matching entry in the employee table
since desgID in employee table is a foreign key. If we assume all 100 rows in the
employee table have the same desgID, then there will be five rows from designation
table that do not have matching entries in the employee table, but will appear in the
output of the outer join. Therefore, the maximum number of rows returned by the
given query is 100 + 5 = 105.


Answer:
C. Indexing
Managing the task of designing and maintaining a database is performed by:
Options :
A. Storage Manager
B. Transaction Manager
C. Concurrency-control Manager
D. Database Administrator

Answer: 
D. Database Administrator

Which of the following stores information regarding how much space is currently used by a table
in the database?
Options :
A. Concurrency Control Manager
B. Transaction Log
C. Data Dictionary
D. None of these

Accepted Answers:
C. Data Dictionary
Which of the following is/are true about Object Relational Data Model?
- [ ] It contains atomic values.
- [ ] It was originally intended as a document markup language and not as a database language.
- [ ] It provides upward compatibility with existing relational languages.
- [ ] It allows attributes of tuples to have complex data types.


Accepted Answers:
- [X] It contains atomic values.
- [X] It provides upward compatibility with existing relational languages.
- [X] It allows attributes of tuples to have complex data types.


Which of the following is/are true for Normalization Theory?
- [ ] It is associated with a diagrammatic representation known as E-R diagram.
- [ ] It models a real world enterprise into collections of entities and relationships.
- [ ] It is a query language
- [ ] It tries to formalize and evaluate a design as good or bad, and also tests the quality of design.


Accepted Answers:
- [X] It tries to formalize and evaluate a design as good or bad, and also tests the quality of design.

By the concept of Logical Data Independence, a change in the logical level of DBMS should not affect which other level(s) of abstraction?
- View Level
- Physical Level
- Both Physical and View Level
- None of the above


Accepted Answers:
View Level

By the concept of Physical Data Independence, a change in the physical level of DBMS should not affect which other level(s) of abstraction?
- View Level
- Logical Level
- Both Logical and View Level
- None of the above


Accepted Answers:
Both Logical and View Level

Which among the following is a good option for exchanging data among different systems over the internet?
- HTML
- MS Access
- SQL
- XML


Accepted Answers:
XML

An attribute is:
- a set of entities of the same type that share the same properties.
- a set of descriptive properties possessed by all members of an entity set.
- a subset of descriptive properties of an entity that uniquely identifies each member of the set.
- an association among several entities.

Accepted Answers:
a set of descriptive properties possessed by all members of an entity set.



A company needs to maintain the following information about each of its employees: \textit{Name, Date of Birth, Date of Joining, Monthly Salary, Annual Salary and Years of Completion}Name, Date of Birth, Date of Joining, Monthly Salary, Annual Salary and Years of Completion. From among the given options, choose the attributes that can be configured as derived attributes.
- [ ] Name
- [ ] Date of Birth
- [ ] Date of Joining
- [ ] Monthly Salary
- [ ] Annual Salary
- [ ] Years of Completion
Yes, the answer is correct.
Score: 2
Accepted Answers:
Annual Salary
Years of Completion



2 points
In Figure 6, addressaddress is a . . . . . . . . . attribute.
![](https://backend.seek.onlinedegree.iitm.ac.in/21t3_cs2001/assets/img/DBQ26.png)

- multi-valued
- composite
- derived
- simple


Accepted Answers:
composite

The relationship associating the weak entity set with the identifying entity set is called ______.
- Weak relationship
- Own relationship
- Identifying entity
- Identifying relationship

Accepted Answers:
Identifying relationship
2 points
Which among the following statements is/are true regarding weak entity sets?
- Every weak entity must be associated with an identifying entity.
- An entity set that is not a weak entity set is termed as a strong entity set.
- The identifying entity set is said to own the strong entity set that it identifies.
- All of the above.

Accepted Answers:
Every weak entity must be associated with an identifying entity.
An entity set that is not a weak entity set is termed as a strong entity set.
