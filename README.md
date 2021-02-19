by Raphael Sairo
# Python CRUD Operation

This is a program that can perform CRUD operations on a student’s MySQL table. It connects to a MySQL database and can perform all basic CRUD operations. The class can add a new student with first and last name, student contact number and marks. This program can perform the following operations: Sorting using first name, Finding minimum marks and Search contact.

# My Journey
My Computer science journey way back in the year 2000 when I enrolled for a diploma in information technology at the then Mombasa polytechnic now known as The Technical University of Mombasa so far so good no regrets!
After completing my diploma, I went back to my home village in Oloitokitok where I opened up a small community college where I taught basic computer packages like MS word, Excel etc. after a year I decided to close shop and moved to the capital city to find a job where I could practice my information technology knowledge job. After a few months of internship, I landed a job as a desktop technician but at times I would do networking jobs too. After a few years I finally settled a printer technician, I enjoyed performing “surgeries” on printers before finally relocating to the US.
When I landed I US in 2013 I did a course in CompTIA A+ which landed me a field service technician job with Georgia lottery, I found myself enjoying hands on jobs plus I did a lot of travel. After a few years I felt that I needed a change of career and decided to look for a technical support job and also enrolled in southern New Hampshire for a degree in computer science that was two and a half years ago! Within the last three years I have developed a liking for database management and big data, I decided to pursue this path by taking an oracle business intelligence certification, I want to be part of business management providing data that can help businesses make informed decisions.
I have really enjoyed the fast-paced courses offered by SNHU; I have also helped a lot of my friends who wanted to enroll at my university by making them understand how easy it is to take online classes. After taking different classes I have been able to showcase my strength in software development and in particular class CS-350-Q5399 Emerging Sys Arch class where I used raspberry PI hardware and python programming language to create a weather station app My original prototype was a simple weather station which recorded temperature humidity at intervals of one minute then incrementally stored in a JSON file while updating on a real time dashboard. The major objective was to create a real time weather station to enable users plan their day, carry umbrella if it is raining or boots if it is snowing.
I also enjoyed collaboration and teams project class, I found it extremely helpful where I collaborated with other students using Git hub working on the same project but committing changes at different times. Am looking forward to using Git in the new future.
Having gone through different courses at SNHU has shaped my professional goals as well. From my experience I can tell that I do not have a future in software development I definitely do not want to become a software engineer. I really enjoyed networking and hardware course partly because I was and have been a technician before. 
This is a program that can perform CRUD operations on a student’s MySQL table. It connects to a MySQL database and can perform all basic CRUD operations. The class can add a new student with first and last name, student contact number and marks. This program can perform the following operations: Sorting using first name, Finding minimum marks and Search contact.

# Demo & Code Review
Link to my code review video https://youtu.be/gH9yDl4eKw4
This project is supposed to address and enhance the following:
•	Software Design and Engineering
•	Algorithms and Data Structures
•	Databases

# Software Design and Engineering
The artifact I selected is a program that can perform CRUD operations on a student’s MySQL table. It connects to a MySQL database and can perform all basic CRUD operations. The class can add a new student with first and last name, student contact number and marks. This program can perform the following operations: Sorting using first name, Finding minimum marks and Search contact.
The program was not fully commented, the few lines that had comments did not explain what exactly my project was all about making it hard for code reviewers and non-technical persons to understand exactly what is going on. I found it necessary to at least put a header to explain each class.  
Another notable issue was that I noted is that there was no try-catch blocks to catch any exceptions. There were instances where users entered a name instead of a number and the program simply accepted the input instead of throwing out an error. In order to enhance this feature a while loop was used to ensure that the program keeps on prompting users to enter the correct details so as to have a correct output. 
The program does not allow users to store a large number of students for future reference and to enhance this it is necessary to store the students records in a text file or a database.
A variable is a symbolic name for information. The variable's name represents what information the variable contains in my case the variable names are not descriptive such as the use of I, I suggest the use of variable names such as “count” instead of letters with no meaning. Names like sname can be replaced by Surname making it easy for a novice to understand. Some of the adjustments that am currently looking at includes:

# Database
As at now this program does not have a dedicated storage for each student. Am looking at making it possible to list all the students marks in ascending or descending order, rank them according to the surname and to achieve I will need to have a standalone database or preferably a text file.
I can for example use text files to store students with the best scores.

# Data structures
Another enhancement that am considering from the current lists is to add more advanced data structures like vector, vector in programming is a type of array that is one dimensional and can be used to store data whose size can always be increased with time.

# Enhancement Two: Algorithms and Data Structure
This application consists of a simple file-based student management system that maintains the records in the files. It consists of the following features:
Add New Student
•	View Students
•	Search Student
•	Update Student
•	Delete Student
•	Search student 
While adding the students, the user only has to enter his/her First Name, Last Name, Phone number, marks etc., the user can view all these students lists from the view section the user can also search for student’s name in order to know whether the student’s record exists in the system or not. This program provides the simplest management of student’s list and scored mainly focusing on CRUD.
Authorized users will be provided with specific rights to the application. I have chosen this artefact in order to test my skills in python and database management. From the previous code review I think the code needs to be corrected and modified, while writing my code I forgot to include security aspect, this system must only allow authorized users. Advancing the code will be a great idea especially when it comes to error corrections.
The reason of including this project in my portfolio is to enable me advanced and sharpen my python skills especially in data structures and algorithms. One of the most important features in data structures and algorithm that I will showcase will be the searching technique, retrieving data from the database while holding an array list for easy presentation.
During my code review I outlined some of the weakness brought about by using unreliable variable names. The application I used had no algorithms making it difficult to sort out data. I also found out that retrieving data was very slow. To enhance my project, I worked on the slow retrieval by developing an array list to hold data that is retrieved from the database. After all the improvement I find now faster to search and retrieve data. Am still in the process of researching the best algorithm that can work fast even in slow low memory devices.


