# School Management System

## Introduction

Web based School Management System are designed to manage and store project information that are used in web based applications. This package was developed to help the school to manage various details pertaining to its students. This will help various departments like accounts, admin, teacher, student. Account department will maintain the details related to fees and basic details like security deposits etc. Administration department will maintain students basic details as well as keeping a check on fee details. 
The basic need for the package was to automate the whole procedure of maintaining of student details, teacher details, account, administration. It improved the efficiency, reduced the cost, reduced the time. 

## Features of the project

* Student Management - Add student, fee details, updating student details, view profile
* Teacher Management - Add teacher, edit teacher details, view salary
* Fees Management - Add fees, delete fees, pay fee, fee structure

## Technology used 

We have developed this project using the following technology-
* HTML - Page layout has been designed in HTML
* Python - All the business logic has been implemented in python
* SQLite - SQLite database has been used as database for the project
* Django - Project has been developed over Django framework

Front end: HTML, Bootstrap
* HTML : HTML is used to create and save web document
* Bootstrap : Responsive design mobile friendly site

Back end : SQLite, Python
* SQLite : SQLite is a database, widely used for accessing querying, updating, and managing data in database
* Python : Python is a very popular and trending programming language used in many IT sectors.

## Modules and description of the project

### Student Module:

The main purpose of this module is to provide all the functionality related to the students. It tracks all the information and details of the student. We have developed all type of Create, Read, Update, Delete operations of the students. This is a role based module where admin can perform each and every operation on data but the student will be able to view only his/her data, so access level restrictions has been implemented on the project.

* Features of student module

- Admin can add new students records
- Admin can edit, update, delete records of the student
- Student will be able to see and update his details.

### Fees Module :

This module has been developed for managing all the information of the fees, here admin and faculty can upload the fees and students can view and download the receipt. Access level restrictions has been implemented on this module so only admin and teacher will be able to upload/edit/delete the fees and students and only view the fees and download.

* Features of this module

- Admin can upload new assignments
- student can view and download fees
- admin can see and delete all the fees structure

### Attandance Module
  The main purpose for developing this module is to manage the attandance of the students datewise. So all the attandance will be marked by admin or faculty and student will be able to see only his/her attandance. Admin can see the list of all the attandance and filter it according to the students.

* Features of this module

- Admin can mark the student attandance
- admin can edit/delete the student attandance
- admin can see the list of all student attandance
- student can see his attandance

### Functionality performed by student user
 this are the functionality performed by the student users

- registeration of the student
- login for student
- forgot password for student
- change password 
- edit profile
- view his fee payment history
- view attandance history

### Functionality performed by the Admin User

This functionalities are performed by the Admin User

- Login for admin 
- Forgot password for admin
- Edit profile for admin

#### Manage Student
- Adding new student
- Edit existing student
- View profile of student
- Listing of all student

#### Manage Fees
- Add fees of the student
- View details of fees
- Listing of all fees
- Filter fees according to student

#### Manage Attandance
- Add attandance of student
- Edit attandance of student
- Listing of attandance
- Filter attandance according to student

### Python Explaination
- manage.py:
This file helps us to start the server that gives us the link to the start the website on the client side. We use Django for the server side.
#### school:
- admin.py:
In this file we give the admin the privilages to register a student, teacher. We also give admin the privilages to access the attendence, and also the admin is able to display and write any notices that they want everyone to see.
- forms.py:
In this file we configure the forms for admin, students and teachers. We make forms to store the information about the student, teacher or admin who is registering or is login-in. We also use forms to generate username and password for the user. In this file we also configure the form for attendence which is whether the student is present or absent.
- models.py:
In this file we configure models for the students and teachers. We also create models for attendence page and also we create a model for the notice page.
- views.py:
In this file we configure the pages and links with html templates. We link the fuctions with html pages for the users who have successfully logged in or throw an error if there was any error while login-in. This file also helps the fuctions that are used to sign-in/register to link with their respective html pages. This file also contains fuctions that help to authenticate the user and check if the username and password is right or wrong. So basically we use this file to link the html pages with thier respective fuctions and also this file checks the authentication process of the project.
#### schoolmanagement:
- asgi.py:
In this file we configure the ASGI for the project. 
- settings.py:
This file contains the Django settings for the project.
- urls.py: 
This file contains the path to all html links and fuctions used to link them.
- wsgi.py:
In this file we configure the WSGI for the project.


### Contribution Report

Swikar Omargekar (10608904@mydbs.ie)

As we have described above, We have various parts like the index page, admin page, teacher page, student page. I have mainly focused on the front end and database.
So, when we will run the project, we will see the "Take Admission" on the index page. Here, we can Sign in or Create new loign to take the attandance in the school. As we go further, we will see admin page where he/she can login and has access to everything. Admin can manage teacher's, student's, attandance section respectively. Furthermore, In teacher's section, we will get all the information related to teacher. For eg. Adding new teachers, Edit existing teacher details, Teacher's salary, Any pending request of the teacher. Whereas in Student section, We will see Number of students, Add new student, Edit existing student details, Student fees pending and attandance. In fees section, we will see the fee structure, pending fees of the students etc. In attandance section, only Admin and Teacher can access this part. They can alter the attandance of the student datewise. We have created database as back-end with SQLite where all this information get stored. 

Shaun Christopher Chaudhary (10622059@mydbs.ie)

My focus was mainly the back end of the project i.e the Python end of the project. I made the python pages to link the the html templates created my Swikar with the python code using various functions. I also created python fuctions that will check the login-in and sign-up process for students, teachers and admin in the project. I also linked the database to my code. My code checks the entire fuctionality of the project and helps the project run smoothly from the backend. I created the models and forms fuctions in the backend so that the forms for students, teachers and the admin run perfectly with thier models. I also created fuctions for the admin that gives the admin all the privillages to accept or reject a student's application or a teacher's job request, also I have configured the admin is such a way that the admin can access all the information about a teacher or student and also the admin is able to see and change the attendence.


### Attribution report
Licence: MIT Licence
Copyright: Sumit Kumar @ 2020

