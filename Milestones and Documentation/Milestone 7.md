
# Custom inspection checklist
## 1. Relational Databases testing 
 
![Image of Relational Databases Testing(Rock A Job)](https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Relational%20Databases%20Testing(Rock%20A%20Job).jpg)

[Image Refrence](http://www.agiledata.org/essays/databaseTesting.html)   
[Testing Stratagy Refrence](https://www.softwaretestinghelp.com/database-testing-process/)     

1.1 Data Mapping
  * Check whether the fields in the UI/frontend forms are mapped consistently with the corresponding fields in the DB table.
  * Whenever a certain action is performed at the front end of an application, a corresponding CRUD (Create, Retrieve, Update and Delete) action gets invoked at the back end.

1.2 ACID Properties Validation
  * Atomicity means that a transaction either fails or passes. This means that even if a single part of the transaction fails- it means that the entire transaction has failed. Usually, this is called the “all-or-nothing” rule.
  * Consistency: A transaction will always result in a valid state of the DB
  * Isolation: If there are multiple transactions and they are executed all at once, the result/state of the DB should be the same as if they were executed one after the other.
  * Durability: Once a transaction is done and committed, no external factors like power loss or crash should be able to change it.

1.3 Database Schemas
  * Primary keys to be created before any other fields are created.
  * Foreign keys should be completely indexed for easy retrieval and search.
  * Field names starting or ending with certain characters.
  * Fields with a constraint that certain values can or cannot be inserted.

1.4 Triggers
  * When a certain event takes place on a certain table, a piece of code (a trigger) can be auto-instructed to be executed.

1.5 Field Constraints
  * The Default value, Unique value, and Foreign key all should be defined and used wisely.

## 2 Front End Testing 

### 2.1. Code reusability:
Check that the code is written with likely future use-cases in mind. For example, if we are reviewing code for a marketplace that is rapidly expanding its product range, make sure that the code can easily be updated to support new kinds of products in the future.
### 2.2. Readability (understandability):
Readability in software means that the code is easy to understand. In this case, understanding code means being able to easily see the code’s inputs and outputs, what each line of code is doing, and how it fits into the bigger picture. When reading through the code, it should be relatively easy for you to discern the role of specific functions, methods, or classes.
### 2.3. Speed and Performance:
Consider performance across two dimensions: performance for users and resource consumption. Performance for users reflects a focus on how quickly your code performs for the end user. Lengthy database queries, unoptimized assets, and multiple API requests can all work to make your code feel slow.
### 2.4. Documentation: 
Check whether the code you’re reviewing requires extra documentation to go along with it. If it’s a new project, this means ensuring it has an adequate readme that explains why the project exists and how to use it. If it’s new code added to an existing project, it’s worth thinking about whether the project’s readme needs to be updated to document the new functionality or new tools.
### 2.5. Patterns: 
whether it matches the patterns that your team have already established.

