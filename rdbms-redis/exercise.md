1. What is the difference between Strong and weak entity?

2. What do you mean by Integrity Constraints?

3. What do you mean by Entity and Entity set?

4. What are Advantages and Disadvantages of DBMS?

5. Explain how functional dependencies can be used to indicate the following:
   * A one-to-one relationship set exists between entity sets student and instructor.
   * A many-to-one relationship set exists between entity sets student and instructor.

6. Consider the following relational schema and briefly answer the questions that follow
   * Emp(eid: integer, ename: string, age: integer, salary: real)
   * Works(eid: integer, did: integer, pct time: integer)
   * Dept(did: integer, budget: real, managerid: integer)
   Define a table constraint on Emp that will ensure that every employee makes at least $10,000.

7. Consider the following relational schema and briefly answer the questions that follow
   * Emp(eid: integer, ename: string, age: integer, salary: real)
   * Works(eid: integer, did: integer, pct time: integer)
   * Dept(did: integer, budget: real, managerid: integer)
   Define a table constraint on Dept that will ensure that all managers have age > 30

8. A college maintains details of its lecturers' subject area skills. These details comprise:
Lecturer Number, Lecturer Name, Lecturer Grade, Department Code, Department Name, Subject Code, Subject Name, Subject Level
Normalise this data to Third Normal Form.

9. A software contract and consultancy firm maintains details of all the various projects in which its employees are currently involved.
These details comprise:
   * Employee Number
   * Employee Name
   * Date of Birth
   * Department Code
   * Department Name
   * Project Code
   * Project Description
   * Project Supervisor

  Assume the following:
   * Each employee number is unique.
   * Each department has a single department code.
   * Each project has a single code and supervisor.
   * Each employee may work on one or more projects.
   * Employee names need not necessarily be unique.
   * Project Code, Project Description and Project Supervisor are repeating fields.
Normalise this data to Third Normal Form.

10. Create conceptual ERMs for the following scenarios. State your assumptions and list unanswered questions in your document. Create a conceptual ERD for each scenario and clearly state the relationships of the entities in terms of cardinality and optionality. Share your answers on google drive.

    * A chess club decides to hold a chess tournaments and invites players from other chess clubs to join in the tournament. Chess matches need to be recoded as does the individual moves of each chess match.
    * A garage decides to offer MOTs to its customers. They require a system to store the MOT booking and allocate a mechanic to carry out the work on the car. Mechanics specialise in car models by manufacturer.
    * A cinema offers a loyalty card to customers and uses the information gathered in providing the card (age, sex, address) to determine the viewing preferences of its customers. Another requirement of the system is to allocate seats for film showings to customers and has more than one screen in the cinema.
    * A caravan site requires a booking system to allocate pitches to visiting caravans. Pitch prices vary depending upon the number of people using the caravan and the size of the caravan.
    * A bus timetabling system is required to allow a customer to enter a bus number and respond by listing all the destination stops for the bus requested. The customer can enter a from and to destination and the system will provide the customer with the price for the journey.

11. Explain with scenario where Set is most appropriate than List in Redis.

12. Explain with scenario where Hash is most appropriate than List.

13. After exicuting following three commands in REDIS what’ll be the o/p of last command
    * conn.zadd('zset-1', 'a', 1, 'b', 2, 'c', 3)
    * conn.zadd('zset-2', 'b', 4, 'c', 1, 'd', 0)
    * conn.zinterstore('zset-i', ['zset-1', 'zset-2'])
    * conn.zrange('zset-i', 0, -1, withscores=True)

14. After exicuting following three commands in REDIS what’ll be the o/p of last command
    * RPUSH mylist "Hello"
    * RPUSH mylist "World"
    * LINSERT mylist BEFORE "World" "There"
    * LRANGE mylist 0 -1

15. After exicuting following two commands in REDIS what’ll be the o/p of last command
    * HSET myhash field1 "foo"
    * HDEL myhash field1
    * HDEL myhash field2

16. Draw a ER diagram to capture the requirements as stated below.
In a hospital there are different department Patients are treated in the departments by the doctors assigned to patients. Usually each patients is treated by a single doctor, but in rare cases they will have two or three. Healthcare assistant is also attended to patients; Every department has many health care assistants. Each patient is require to take varity of drugs during different parts of the day such as morning, afternoon, night.

17. Draw a ER diagram to capture the requirements as stated below.
A toy manufacturing company manufactures different types of toys. The company has several manufacturing plants. Each plant manufactures different types of toys. A customer can place the order of these toys. Each order may contain one or more toys. Each customer has multiple ship-to addresses. To prompt the business, To prompt the business the company offers different schemes based on the order value.

18. What is indexing and what are the different kinds of indexing?

19. What are the types of join and explain each?

20. What is a constraint?
