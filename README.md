# WEB-DEV_JobPortal
A Spring Boot application that performs CRUD functionalities and makes the networking and job application smoother between A student and Employer.


## User roles and its functionalities:
1. Registration and Login based on 2 roles, 'Employer' and 'Student'

### The Employer role performs the following functionalities:

- Post a new job
- Update or delete the existing jobs which he has posted
- View all his jobs
- View all students who have applied for the job post

### The Student role performs the following functionalities:

- View all the jobs also search for a specific job
- Apply for a job including uploading of resume and cover letter
- View all his applied jobs
- Withdraw application, i.e. delete his job
- Validation of inputs along with XSS filters

2. Registration validation using query criteria

## Technologies used:

### Backend technologies:
- Spring MVC 4.0 framework
- Hibernate with MySQL database for persistence
- Web-Server: Apache Tomcat 8

### Front-end and Web Technologies:
- HTML 5
- CSS 3/ Bootstrap 4
- Javascript, JQuery
