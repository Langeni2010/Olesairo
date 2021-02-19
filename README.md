# Python CRUD Operation

This is a program that can perform CRUD operations on a student’s MySQL table. It connects to a MySQL database and can perform all basic CRUD operations. The class can add a new student with first and last name, student contact number and marks. This program can perform the following operations: Sorting using first name, Finding minimum marks and Search contact.

# Code Review Suggestions
The program was not fully commented, the few lines that had comments did not explain what exactly my project was all about making it hard for code reviewers and non-technical persons to understand exactly what is going on. I found it necessary to at least put a header to explain each class.  
Another notable issue was that I noted is that there was no try-catch blocks to catch any exceptions. There were instances where users entered a name instead of a number and the program simply accepted the input instead of throwing out an error. In order to enhance this feature a while loop was used to ensure that the program keeps on prompting users to enter the correct details so as to have a correct output. 
The program does not allow users to store a large number of students for future reference and to enhance this it is necessary to store the students records in a text file or a database.
A variable is a symbolic name for information. The variable's name represents what information the variable contains in my case the variable names are not descriptive such as the use of I, I suggest the use of variable names such as “count” instead of letters with no meaning. Names like sname can be replaced by Surname making it easy for a novice to understand

#Adjustment suggestion
#Database
As at now this program does not have a dedicated storage for each student. Am looking at making it possible to list all the students marks in ascending or descending order, rank them according to the surname and to achieve I will need to have a standalone database or preferably a text file.
I can for example use text files to store students with the best scores.
#Data structures
Another enhancement that am considering from the current lists is to add more advanced data structures like vector, vector in programming is a type of array that is one dimensional and can be used to store data whose size can always be increased with time.
