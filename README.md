# INFORMATION
Writtern report is in both .docx and .pdf format
Old and current sql files are uploaded. Regular SQL.sql is the newest one. 


# Fullstack-Assessment1
The assesssment 1 for my Fullstack assessment
Scenario The scenario presented here sets the context for the design of your proposed database solution for this assessment. The context is the design of a traffic correction notice database for the New York State Patrol department. A traffic correction notice is issued to the driver of a vehicle who has committed a traffic violation. For example, this could be speeding (breaking the road speed limit), using a phone while driving, or driving with a vehicle where one or more of its lights are not operating correctly.   
To get started with how you might design the database, consider the traffic correction notice shown in the figure below, a table containing the main data fields from the correction notice is also included to provide further clarity. First, study the figure and table, as you will use it to design and implement the required database system for the given scenario. In particular, you should note the different data entities represented on the correction notice, the clear separation of the data shown on the notice should provide some helpful hints on how such entities will inform the design of your database. It is important to note that all correction notices have a unique identifying number that is not shown on the copy of the notice issued against the vehicle. This unique number will exist regardless of whether the correction notice is issued or not. You must use the supplied correction notice information as part of your database design solution.  
To help assist you with an understanding of the type of basic business rules that should be applied to your database design, please see below (note these are basic examples and not exhaustive):  
1. Unique identifier: Each notice must have a globally unique number ID
2. Mandatory fields: Each notice record must contain the relevant values in the correction notice issued to the vehicle
3. Valid primary and foreign keys: A notice must be linked to a valid patrol officer and vehicle
4. Date Constraints: Ensuring violation dates retain integrity
5. Role-Based Access: Citizen can only view notices linked to their vehicle. Officers can create new notices

Must contain:
 1. Last Name
 2. Drivers Licence
 3. First Name
 4. State (Drivers Licence Issued)
 5. Address
 6. Birth Date
 7. City
 8. Height
 9. State
 10. Weight
 11. Zip Code
 12. Eyes (colour)
 13. Vehicles
 14. Licence
 15. State (Vehicle Licence)
 16. Colour
 17. Year
 18. Make
 19. Type
 20. VIN
 21. Registered Owner Address
 22. Violation Date
 23. Violation Time
 24. District
 25. Detachment
 26. Location
 27. Violations
 28. Officer name
 29. Personal Number

Database Design Tasks 
a. Devise a comprehensive conceptual data model using an Entity Relationship Diagram (ERD) using Chen’s notation or Crows foot’s notation. The ERD will form the design of a centralised database system to be installed and managed at the New York State Patrol department headquarters. As a minimum, the basic model should be based around the business rules given, you are expected to build on these rules to create an enhanced solution. Your conceptual model should clearly show all entity types, their relationships, cardinality, and participation constraints of each relationship, together with clear explanations of the business rules or assumptions that are being modelled. 
b. Provide detail of any normalisation you have carried out to remove redundant data replication and other anomalies.

Database Implementation Tasks 
a. Implement the relational and logical model devised from Database Design Tasks (a) as a database system in a MySQL environment by writing SQL statements for creating the tables, users, and populating them with data. 
b. Write at least 10 SQL queries that will manipulate the data, including examples that will retrieve data from at least 3 tables within the same query (for example using JOIN). Three of your queries should retrieve data and filter it using Boolean, comparison and other related filters and functions. 
c. Some basic examples of how these queries could be formed are below: 
• Create a new record for a correction notice 
• Count the number notices issued to those under the age of 21 
• Search for specific text terms for violation description 
• Update a correction notice 
• Count of violations at a given location grouped by patrol officer for the last 6 months 

Assessment Submission Components There are two submission components for this assessment as described below. You must submit both. 

Part 1 – Report (50%) This assessment requires you to write a comprehensive report that details your solution for the provided scenario. The report should list all the database tables, (views where necessary) you have developed, and includes a screenshot of the data returned when you use any data definition language (DDL)/data control language (DCL)/data manipulation language (DML) statements. 

The report structure must follow the structure/sectioning described below: 
1. Design: Introduce your database design by including and discussing your ERD and provide a rationale for the design choices you made.
2. Implementation:Each of the below subsections must be present and include the SQL statements used and screenshots of query outputs:
   i. DDL Include your SQL statements for database creation and table creation.
   ii. DCL Include your SQL statements for creating the different users for your database and the privileges each type of user will have to interact with the database.
   iii. DDL Include your SQL statements for inserting and retrieving data (at least 10 queries), these should include JOIN statements that evidence data retrieval from 3 or more tables.  
3. Reflection: Discuss the challenges of designing and implementing your database solution and how it could be improved with future work.
4. References: Provide a reference list for covering all sections/subsections.   Remember, you must do this to avoid plagiarism. 

Part 2 – MySQL Database (.sql) script (50%) 
You must create an .sql script file that can be imported and executed against the MySQL database management system. Each of the main components of your script must include code comments. When the script is run, it must complete the following tasks based on your database solution:  
• Create a new database 
• Create the tables using DDL statements (including all columns, keys etc.) 
• Create the users with relevant privileges using DCL statements 
• Insert data into the tables 
• Includes all required DML SQL queries as described under the DDL section of your report (at least 10 queries) 
The script must be able to run without errors and complete all above tasks from the script, with no manual intervention. 








