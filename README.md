# js_course_registration_system

Link: https://umesh3824.github.io/js_course_registration_system

## INTRODUCTION
The Course registration system is an application which refers to registration system that is generally small or medium in size. This application is easy to use and handle. It is used by customer to maintain records of courses and students. In this application we can add courses, register student to particular course and allocate specific seat to each student. It is also used for maintaining the records of seats, customer can easily find vacant seats for particular courses because if there is red seat, it indicates that they are allocated to other student and black seats indicates vacant seats.
In this application we provide validation for registering student records. If any field is blank and if customer enters wrong data then they can’t go ahead because each field has its own validations. We can easily find how many students are registered for particular courses. We can also view record of all students and courses. We can view seat layout of class room. We can delete course and if particular course deleted corresponding student’s record are automatically deleted. We can also delete record of specific student. Above Functionality covered by this application, therefore it is very useful for Course registration.


## IMPLEMENTATION

### Module 1:- Adding Course
In this module we can add courses with respective course id, course name and course description. Here course id is auto generated no need to enter manually. When customer enter all data properly and click on submit button then data are stored and display message to customer ‘Course is successfully added’. If customer enter wrong data or if any field is blank and click on submit button then course can’t be added.

### Module 2:- Adding Student Records
In this module we can add student for specific course with respective student id, student name, mobile number, specific selected course and seat. We display seat layout of class room. Customer can easily find vacant seats for particular courses because if there is red seat, it indicates that they are allocated to other student and black seats indicate vacant seats. We can book different seat for different course. When customer mouse over on any seat if that seat is booked then it display name of student who is booked that seat otherwise it display ‘seat not book’. When customer click on red seat then it display message ‘this seat was already booked please select another seat.’ When customer click black seat then it display message ‘seat number’ and it assign value of seat to confirm seat number. Here student id is auto generated customer have no need to enter student id manually. When customer enters all data properly and click on submit button then data are stored in local storage of browser and display message to customer that, ‘student name you have successfully registered’. If customer enter wrong data or if any field is blank and click on submit button then course can’t be added.

### Module 3:- All Course Records
In this module we can view records of all courses with respective course code, course name, course description. We can easily find how many students are registered for particular courses. We can also view records of all students for registered courses. Here we provide delete button to delete the particular course. When customer click on delete button then particular course deleted and corresponding student records related to that course are automatically deleted and display message to customer that ‘Course are successfully deleted’.

### Module 4:- Student Records
In this module there are two sections. In First section there is a menu and in second section records are displayed. In menu there are multiple buttons first button is to display records of all students. Remaining buttons display records of students related to specific course. When customer clicks on one of this buttons then all the records of students related to specific course are displayed in second section with respect to student id, student name, mobile number and seat number. Here we provide delete button to delete the particular course. When customer clicks on delete button then particular course is deleted and corresponding student records related to that course are automatically deleted and display message to customer that ‘Student are successfully deleted’

### Module 5:- Seat Record
This module maintains the records of seats here we can view how many are total seats, how many are booked seats and how many are vacant seats. We can also view records of all seats related to all courses. Seat is allocated to each student and we can easily find which seat is booked by which student.

### Module 6:- Seat Layout
In this module we can view seat layout of class room. This layout is useful for students because they can easily book the seat which they want.
