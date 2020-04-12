# Introduction
* The most important quality assurance strategies we are implementing is unit testing, that is testing small components before finalizing them.
* The completion aim is to maintain the simplistic design whilst making implementing and a good functionality also maintaining the unit testing approach.  
* A simplistic design and User interface makes is less prone to user errors and provides a elegant design. The design makes the product open easy to user for all kinds of people of all age levels.

# Scope
### Functional Requirements:

* The Rock a job software automatically validates the user when the user is logged in by using cookies.
 
* The website will be responsive for laptop, computer and mobile phones. All the works will be done within one page so it doesn’t take much time to reload into the another page. AJAX and JASON will be used for this feature.

* Only Admin level employees will have the authorization to delete a job on exceptional cases.

* The job should be searchable by location, categories.

* User should be able to logged in using the Google account by API provided by Google.

* User should be able to see all the request and offers for his posted jobs.

* The job picker will be able to see all the jobs assigned to him.

### Non-functional requirements: 
* A website should be capable enough to handle 50,000 users with affecting its performance for first six months.

* The admins will never be able to update any existing information in posted jobs.

* The user password should be encrypted.

* User will be verified by the email account when signed up.

* The system should record the posted, assigned and requested job records.

# Quality objective

Fortunately, there are a couple of apps available on app stores that are quite similar to our project. Aside from using those apps ourselves, we have studied through their review sections and noted the problems their users posted. The main problems users encounter while using this kind of product are security, complications and user-unfriendly interface. We will take steps to address and solve these problems. 

# Testing methodology

* **Functional Testing**

We will check if our product is as per the specifications that we designed it for, as well as if it follows the functional requirements planned by us in our developmental documentation
Testing to see if all the links are functional or not, which will include,
Testing for the outgoing links from all the pages to the specific domain under test.  
Testing for all internal links.  
Testing for links jumping on the same pages.  
Testing for links used to send email from web pages. (MailTo Links)  
Finally, link checking includes, check for broken links in all the above-mentioned links.    
Testing to see if all the forms are working as expected, which will include,  
Forms would be an integral part of our website. Forms are used for receiving information from users and to interact with them.
Scripting checks on the form are working as expected.   For example- if a user does not fill a mandatory field in a form an error message is shown. Once submitted, the data in the forms is submitted to a live database or is linked to a working email address, Forms are optimally formatted for better readability.   First, check all the validations on each field. Check for default values of the fields. Wrong inputs in the forms to the fields in the forms. Options to create forms if any, form delete, view or modify the forms.  
Testing to see if Cookies are working as expected.      
Cookies are small files used by websites to primarily remember active user sessions, so you do not need to log in every time you visit a website.   Cookie Testing will include: Testing cookies (sessions) are deleted either when cache is cleared or when they reach their expiry.   Delete cookies (sessions) and test that login credentials are asked for when you next visit the site.  
Testing to ensure that search engines can crawl their way in the website with the HTML and CSS easily.         
If you are optimizing your site for Search engines, then HTML/CSS validation is the most important one.   Mainly validate the site for HTML syntax errors.   Check if the site is crawlable to different search engines, which will include,   
Checking for Syntax Errors, Readable Color Schemas, Standard Compliance. Ensure standards such W3C, OASIS, IETF, ISO, ECMA, or WS-I are followed.       

* **Usability testing**

It has become a vital part of any web-based project. We are going to check Ease of learning, Navigation, user satisfaction, general appearance.    
Testing the website navigation is smooth and works correctly,
Menus, buttons or Links to different pages on your site should be easily visible and consistent on all webpages    
Testing the Content of the website which will include,  
Content should be legible with no spelling or grammatical errors. Images are well presentable.    

* **Database Testing**

Data consistency is also very important when developing a web application. Checking for data integrity and errors while you edit, delete, modify the forms or perform any database related functionality. Database is one critical component of your web application and stress must be laid to test it thoroughly. Testing activities will include-    
Testing if there are any error shown while executing database queries.     
Data integrity is being maintained while creating, updating or deleting data in the different tables of the database.    
Check the response time of queries and fine tune them if necessary. Testing if the data retrieved from our database is shown accurately in your web application.   
Data is being retrieved and updated correctly. More testing on database would be related to the amount of load the database can handle.    

* **Compatibility testing**

The compatibility of the website is a really an important aspect of testing, this would include testing for, Browser compatibility, Mobile browsing, Printing options.    
Testing in browser compatibility would include,  
Some applications are very dependent on browsers. Different browsers have different configurations and settings that your web page should be compatible with.    
Your website coding should be a cross-browser platform compatible. Checking if the validations then give more stress on browser compatibility testing of your web application. Test web application compatibility on different browsers like Internet Explorer, Firefox, Safari, Opera browsers with different versions.    
Mobile Browsing:
Mobile browsing is an important part. The website should be compatible with the size of the screen, Test your web pages on mobile browsers. Compatibility issues may be there on mobile devices as well.     
Printing Options:  
If someone tries printing one of the pages then it is important to make sure the fonts, page alignment, page graphics, etc. are getting printed properly. Pages should fit the paper size or as per the size mentioned in the printing option.    

* **Security testing**  

It is vital as we would store sensitive customer information. Security testing activities will include, testing Network Scanning, Vulnerability Scanning, Password Cracking, Log Review, Integrity Checkers, Virus Detection.  
Testing pasting the internal URL directly into the browser address bar without login. internal pages should not open.  
If you are logged in using username and password and browsing internal pages, then try changing URL options directly. i.e. 
Trying to directly change the URL site ID parameter to different site ID which is not related to the logged-in user. Access should be denied for this.    
Trying some invalid inputs in input fields like login username, password, input text boxes, etc. Check the system's reaction to all invalid inputs.    
Testing the CAPTCHA for automating script logins.    
All transactions, error messages, security breach attempts should get logged in log files somewhere on the webserver.    
The primary reason for testing the security of a web is to identify potential vulnerabilities and subsequently repair them.      
 
* **Interface Testing**

In web development, the server-side interface is important and should be tested to make sure the website runs properly. This would be done by verifying that the server communication is done properly. Compatibility of the server with software, hardware, network, and the database will be tested. Three areas that will be tested are - Application, Web and Database Server Test system response when connection between the three layers (Application, Web and Database) cannot be established and appropriate message is shown to the end user.  
Application:   
Testing the request are sent correctly to the Database and output at the client side is displayed correctly. Errors if any must be caught by the application and must be only shown to the administrator and not the end user.  
Web Server:   
Testing the web server is handling all application requests without any service denial.
Database Server:   
Making sure all the queries are sent to the database give expected results.

# **Inspection methodology**

Out of a couple of Inspection and evaluation methodologies, we as a group decides to proceed with the Heuristic evaluation methodology to Inspect our product. Provided by Jakob Nielsen, ten Heuristics that help developers identify problems in the user interface. The following are the ten heuristic and how our product satisfies them.
* Visibility of system status: The user is informed at all times with popups and text's of what they are doing and how it should be done.
* Match between system and the real world: The simplicity of the webpage make it easy to use and the pages that require user input are standard like the post a job page and the user knows exactly what to do when there.
* User control and freedom: The user had complete freedom, they can cancel posting a job at the very last at any step, the user who has requested to pick a job can cancel it at anytime before they get assigned and the user who has posted a job can withdraw at any time.
* Consistency and standards: With the use of consistent large font and same images, we provide the user familiar surroundings at all pages.
* Error prevention: Blocking the input of illegal inputs and giving appropriate feedback covers this heuristic. For example when at the post a job page because we are only in Saskatoon right now, if the user selects any other province they are informed with a popup and the input is not accepted.
* Recognition rather than recall: Simple design helps cover this heuristic. All the relative information is displayed on same pages and the user never has to assume anything or carry over any information.
* Flexibility and efficiency of use: The user experienced or inexperienced in technology will have no hurdles navigating through or product and this was made possible because of the early recognition of possible users for our products by making epics and user stories.
* Aesthetic and minimalist design: This is a key component of our product which makes it stand out from all the similar products in the market and will possible attract and encourage users to use Rock A Job rather than any other similar products.
* Help users recognize, diagnose, and recover from errors: Error Popups and messages when invalid or null input is given covers this heuristic 
* Help and documentation: Help while using the product is given such as when on the post a job page, the user can not leave certain columns blank, if they do so, a relative message is shown, same goes for the invalid emails and passwords. 
