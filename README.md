# Technical_Support-


# Project Brief

The GBC Sporting Technical Support website consists of web pages that support two types of users. First, it lets administrators manage the products, technicians, customers, incidents, and product registrations that are in the database. Second, it lets technicians update incidents that have been assigned to them.

# The Database
The database for the application stores the data that’s needed to track technical support incidents. You may build the database up incrementally, but ideally for the completed web application, the database should include tables for storing data about the company’s products, technicians, customers, incidents, and registrations (you do not need all these tables for assignment 1, the recommendation is you develop only the elements of the schema you need for assignment 1, and defer the remaining tables/relationships for the final assignment, assignment 2).
The Table Entity Relationships
The Incidents table contains one row for each technical support incident. Each row in the Incidents table is related to one row in the Customers table, which contains data about the company’s customers; one row in the Products table, which contains data about the company’s products; and one row in the Technicians table, which contains data about the company’s technical support staff.
In addition, each row in the Customers table is related to one row in the Countries table, which stores a list of available countries. The Registrations table, on the other hand, is a linking table (join table) that creates a many-to-many relationship between the Customers and Products tables. As a result, each row relates one customer to one product. This allows one customer to register many products, and it allows one product to be registered by many customers.

# The Assignment
The description of the assignment includes one or more screen captures (wireframes) that conveys how the pages should conceptually appear when they’re completed as well as specifications for how the assignment should be coded. Please note however, the design of each page, and the overall application however, is ultimately left up to each team. A level of creativity and originality is much appreciated.
This information is detailed enough for you to complete the assignment. However, you’ll need to use your best judgment on how to code many of the details. To do that, write the code in the way that you think is best.
For some requirements, the assignment’s specifications will require your team to perform a certain amount of research. For example, some requirements will require the study of technologies/enhancements related to the course material, but may perhaps have yet to be formally covered in the course lectures.
