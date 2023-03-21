# Automated-Time-table-scheduling

The purpose of this project is to generate an automated timetable for a school/college just given no. of lectures conducted per subject for a class and by which teacher. This data is stored in a MySQL Database and from there can be fetched into Python. We primary use a backtracking algorithm to help schedule the time table. Many further optimizations like limiting number of lectures for a particular subject in a day can also be added. 

The implementation of the software is completely done in Python. The program uses MySQL as an input linkage method and also acting as a security blanket. The program is based upon modelling each class or a teacher as an object using the concept of Object Oriented Programming. The solutions generated are completely accurate and the results are produced in a fraction of second. 

Two temporary constraints (modifiable) which I have added are:-
1. Max no. of lectures for a subject in day can be at most 2. 
2. Max no. of lectures by a teacher in a day can be 6.


The need for Computerization of Scheduling arises from the fact that many Schools and Institution face problem in scheduling Time Tables. As the size of the institute grows and there are common Lecture Halls and Labs. This problem becomes more adverse and as a consequence Student and the School has to deal with frequent change in Time Tables due to change of teacher, change of labs etc. Computerization is an excellent way to reduce the manual work that goes in the process and also increasing the net output.


While researching for the project, I came across many techniques which can be used to enhance our Project. Our Project lacks in optimising the solution.  

Various Algorithms like Genetic Algorithm(which I'm working on) can be used to improve the result and make the system learn from previous results. Further Machine Learning can be used in handy way to optimise the solution.  

The System can also be further developed to help in Substitution Scheduling. This basic model of can also be used to schedule other various kinds of activities like Flight Management, Traffic Light Scheduling based upon no. of vehicles.  The various possibilities are endless.  
