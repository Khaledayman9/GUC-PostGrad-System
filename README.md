# PostGrad System
System built to provide alumni and post graduation services, keep track of students doing their postgrad studies as well as manage the process of students taking prerequisite courses for the postgrad studies. Created the website/front-end as an ASP.NET Web application (.NET Framework) using C# and the Database/back-end using Microsoft visual studio (Microsoft SQL server).



# Users:

There are 4 types of users on the system:
* Student (Can register for either Master or PhD).
* Supervisor (A supervisor is responsible for the supervision of students doing their theses).
* Examiner (examiners attend to evaluate the defense and provide his/her comments).
* Admin


# Functionalities:

* A Student can do the following:

(1) View my profile that contain all my information.

(2) List all my theses in the system.

(3) List all my courses and their grades in the system (nonGUCian student).

(4) Add and fill my progress report for my on going thesis.

(5) I can add a publication and link it to my on going thesis.


* A Supervisor can do the following: 

(1) List all my students names and years spent in the thesis.

(2) View all publications of a student.

(3) Add a defense for a thesis and add examiner(s) for the defense.

(4) Evaluate a progress report of a student, and give evaluation value 0 to 3.

(5) Cancel a Thesis if the evaluation of the last progress report is zero.


* An Admin can do the following: 

(1) List all supervisors in the system.

(2) List all Theses in the system and the count of the on going theses.

(3) Issue a thesis payment.

(4) Issue installments as per the number of installments for a certain payment every six months starting from the entered date.

(5) Update the number of thesis extension by 1.


* An Examiner can do the following: 

(1) Edit my personal information, my name and fieldOfWork

(2) List all theses titles, supervisors, and students names I attended defenses for.c

(3) Add comments for a defense.

(4) Add grade for a defense.

(5) Search for thesis where the title contains the entered keyword.


# The Enhanced Entity Relationship Diagram:

![Final EERD Diagram](https://user-images.githubusercontent.com/105018459/177216983-c09c60f3-7985-4a20-bc4d-fbf9fd00c382.PNG)


# Login page:

![Front end](https://user-images.githubusercontent.com/105018459/177217068-fa72b5a6-e8c0-4c36-a53c-75423fe54dc2.PNG)


# Register page:

![Register](https://user-images.githubusercontent.com/105018459/177217176-62729296-8447-4b00-b829-2fc4c3d9e6ed.PNG)


# Technologies:
-Microsoft Visual Studio
-Microsoft SQL Server (SQL)
-ASP.NET Web application (.NET Framework)
-C#

# Setup:
To run this project:

1- Download both zip folders GUCPostgradsystem and packages and extract the folders.

2- Download the GUCPostgradsystem.sln and PostGradOffice files.

3- Put all the files and folders in a single folder.

4- Open the GUCPostgradsystem.sln with Microsoft Visual Studio.

4- Run the project.
