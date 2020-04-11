# Design Storyboard

#### Low Fidelity Storyboard sketches.

1) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Design%20Storyboard-%20Low%20Fidelity%20Storyboard%20Sketch.jpg
2) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Design%20Storyboard-%20Low%20Fidelity%20Storyboard%20Sketch%201.jpg
3) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Design%20Storyboard-%20Low%20Fidelity%20Storyboard%20Sketch%202.jpg
4) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Design%20Storyboard-%20Low%20Fidelity%20Storyboard%20Sketch%203.jpg
5) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Design%20Storyboard-%20Low%20Fidelity%20Storyboard%20Sketch%204.jpg
6) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Design%20Storyboard-%20Low%20Fidelity%20Storyboard%20Sketch%205.jpg

#### High Fidelity Layout (Using AdobeXD)

1) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Homepage%20Adobe%20XD%20Design.png
2) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Log%20In%20Adobe%20XD%20Design.png
3) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Pick%20a%20Job%20Adobe%20XD%20Design.png
4) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Post%20a%20Job%20Adobe%20XD%20Design.png
5) https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Sign%20Up%20Adobe%20XD%20Design.png

#### Description

* The user will start from the home page.
  * User has the option to log in, sign up, post a job or pick a job
* If the user does not have an account, he can sign up.
  * Sign up is required to post or pick a job.
* If the user has already signed up, they can use the login link to access the posts or make a new one
* If the user wants to post a job, they can click the post a job button and fill out the form.
  * Feilds like images and addresses (except province and city) are optional.
  * Money associated with the job can be kept open for offers which will make to job pickers send offers to the job poster who later can pick the desired one.
* If the user wants to pick a job, they can click the pick a job button.
  * If signed in, they will be able to see all the job posts in their city.
  * If a job is open to offers, the user can submit his offer to the job poster.
  * If the job has solid money assigned to it, the user can straight-up pick it.


# System Architecture

### Component Diagram: 

https://github.com/rohanpatel711/CMPT370-Intermediate-Software-Engineering/blob/master/Diagrams/Component%20Diagram(Rock%20A%20Job)%20.jpg

### Description

* System Architecture component diagram was done in Rational Rose. 
* User can only access function part of the classes.
* System admin has access over all the data for all the classes
* For security user password gets encrypted before using to make sure the system's security
* Job is the key component in the diagram. It is the product of the software. 

# Deployment Nodes: 

 - User Interface - HTML, CSS, JAVASCRIPT
 - Database – MySQL 
 - Communicator - PHP
 - Docker Image and Container.

# Epics Annotated:

1) I would like to know the approximate time it would take to complete a job so that I know how much am I getting paid and is it reasonable according to the hours I am working.
2) I would like to learn more about the company and its history.
3) Knowing information about the company’s history can be found in the information component.
4) I want a service that is quick and easy to understand without prior knowledge.
5) I want to be able to keep a track of my previous jobs and the employers should be able to see it as my experience.
6) I want to see more reasonable job postings considering my convenience, free time and comfort.
7) I want the application to be user-accessible and friendly so that many people use it. This should be considered during the creation of the GUI.
8) I want to be able to search job listings by keywords, location, skill description and salary so I can focus my job search
9) As a job poster, I want to edit the job I posted for any updates in time or requirement or money
