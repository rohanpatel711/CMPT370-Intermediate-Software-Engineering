# Domain Model

![Image of Domain Model Diagram(Rock A Job)](https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Domain%20Model%20Diagram(Rock%20A%20Job).jpg)

#### Software used for UML Diagram: IBM Rational Rose

# Glossary 

### The Domain model was made using the IBM Rational Rose software. The Model Has following Classes in the Class Diagram. 

### User (Actor): 

Here we have two kinds of Users. One is who will post a job and another one is who will pick a job. The job poster can post jobs and from them, the job seeker can select the job. One user can post one to many jobs and similarly the user can select one to many jobs. Any of the user must have to login before searching or posting a job. If they are not registered before, they need to fill the registration page and there they must give necessary information like name, email, phone number etc.

### Pick: 
In this class, it will have the pick_job( ) function, “pick a job” feature will be using this class. It will also hold some attributes of that specific jobs and that user. This class can have one to many users. And one to many jobs.

### Post: 
In this class, it will have the postJob( ) function, “post a job” feature will be using this class. It will also hold some attributes of that specific jobs and that user. Each post will have one and only one user who posts.This class can have only one job.

### Assign: 
This class will only assign jobs using the function assignJob( ). This class has one and only one user. But can have one to many jobs. 

### Job: 
This class will have all the specifications for the jobs. It also has the option to modify jobs. The jobs have valid date, job categories, job priority, job status and others. Job status must be done from both sides before making any payments. Jobs with high priority will be shown in the top of the home page. The job category will help the users to find the jobs according to their interests.

### Payment: 
The whole payment part is done over here. This class will have all the necessary information from the assign class and the user class. This has the function of chargebill( ), paytopicker( ) and Job_status_confirmation( ). The payment is made with aggregation, which means the user must pay once the job status confirmation is yes from both the sides of the job poster and the job worker(user).

# Database Schema

![Image of Databse Schema(Rock A Job)](https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Databse%20Schema(Rock%20A%20Job).png)

### Details

#### Master user datadabe.
* User id (primary unique key)
    * Foren key for job_picker and job_poster
* User first name and last name 
  * Same for job picker and poster first name and last name
* Password varchar hashed with MD5 and a custom python hashing script before saving to database.
* All the rest values are stored in the database without modification.

#### Job poster
* Will have First name and Last name same as saved in the user database
* Will have a poster id
  * Foreign key from master user
* Will also save links to previously posted jobs
* Review for the poster reviewed by the users that have done a job for the poster.

#### Job picker
* Will have First name and Last name same as saved in the user database
* Will have a picker id
  * Foreign key from the master user
* Will also save links to previously done jobs
* Will have an experience column.
* Review for the picker reviewed by the users that they have done jobs for.

#### Job
Database that saved the posted job details posted by a user
* Will have a job id 
  * Foreign key from the job poster id 
* Have values saved as Money associated with the job, Location, Job description, and Job type.

# Prioritized Product Backlog

1)	Create the design for the website 
2)	As an unauthorized user I want to create a new account 
3)	As a user with already a account I want to login
4)	Proof of knowledge for the skills they list for any technical/professional jobs from job seeker
5)	Make sure all the job seekers are above the age of 17 year (minimum age to work in Canada)
6)	Create a script to add a new user(Job seeker or job poster) to the database
7)	Create a script to add a new job to the database and they displaying it 
8)	As a job poster I want to edit the job I posted 
9)	A chat box function for the job poster and job seeker to communicate negotiate etc
10)	Should have 3 options professional jobs as well as odd jobs as well as a student section
11)	On the day of the jobs notify both the seeker and the poster
12)	Add database encryption for passwords and user names
13)	Users can pay more money to display their jobs on the top to gain more attention and get it done quickly
14)	Displaying jobs near to a specific location/ A user can look at the already posted jobs in the locality and pick a desired one.
15)	Displaying all jobs with all the information related to it-(Pictures, Money offered, Description, Time, Location, etc)
16)	Displaying jobs based on profession 
17)	To specifically search for the jobs the person wants
18)	Make sure the ratings and recent job history of a user are collected and displayed on his profile 
19)	If there are no jobs available in a current profession, there should be a option to get notified by email or text message when a job is posted under the following job category
20)	Payment module – The job poster should pay the amount he is going to while posting the job that way we can ensure no one can post a spam/fake jobs. After the job seeker completes the job upto the requirements  of the job, after confirming this with the job poster we transfer the money to the person who completed the job. This way we can make sure no one can be a fraud. 
21)	Both the job seeker and the job poster should have a feedback option for each other
22)	Write test plan for the project


# Technology

#### We will be using:

* Front end -> HTML, CSS, JavaScript, Bootstrap.
* Back end  -> PHP
* Database -> MySQL
* APIs- Google Signup. (Will be added as the project progresses)
* Data format – JSON 
* Docker

