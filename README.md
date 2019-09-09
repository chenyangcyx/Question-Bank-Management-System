# Question-Bank-Management-System
题库管理系统，软件工程课程设计

1 design background

With the rapid development of the Internet, more and more things can be processed more quickly on the Internet.Similarly, if students can complete homework and exercises on the Internet, they can get enough exercises more quickly, and can complete and submit them at any time according to their own needs, thus avoiding students' difficulty in obtaining exercises of corresponding subjects to practice the learning content.For teachers, correcting exercises done by students has always been a time-consuming and laborious task. However, if the exercises can be completed and submitted online, the homework can be corrected by computer, greatly reducing the burden on teachers. In addition, teachers can release exercises at any time as required.

At present, many universities or institutions in China have designed their own question bank management system, but there are many systems for examination paper making, and relatively few systems for students to practice.Most foreign universities have perfect question bank management system.

2 design significance

In the process of learning, students need enough questions to practice and test the knowledge they have learned. However, sometimes it is difficult for students to master which parts are the objects that need to be practiced, and when they need to practice, they do not have corresponding exercises, which is even more difficult to achieve the key exercises of specific difficulty.Correspondingly, the teacher has a sufficient understanding of the key parts of the course and a large number of exercises, but it is difficult to communicate with the students in need at any time.And students in the completion of exercises, exercises to correct and explain is also a huge amount of work.

In view of the above contradictions, a question bank management system is designed to solve them, so that students can master the key content of the course at any time, screen the difficulty of exercises done, carry out self-adaptive exercises, and get correction and explanation of exercises in time.At the same time, teachers can adjust the content of the question bank for students to practice at any time, and check students' practice.The realization of these functions can alleviate and even solve the contradiction mentioned above to a large extent.

Through this system, students can practice exercises they need at any time, and facilitate teachers to set up exercises for students, and eliminate the steps of correcting exercises.

3 design requirements

3.1 demand analysis

The system is oriented to teachers and students, and its function is suitable for teachers and students' daily problem setting and doing.Meanwhile, in order to better manage the accounts of teachers and students, the concept of "administrator" should also be introduced.Of course, in practical use, the specific functions and details are more complex.In order to make the system better conform to the use habits of teachers and students, it is necessary to carefully study the detailed functions of the current system before development, and improve the functions of the system through data collection, questionnaire survey and other means, which can greatly facilitate the daily use of teachers and students.

Through the analysis and integration of the information obtained in the demand analysis stage, the design scheme and requirements of this system are divided into system design requirements and user functional requirements.

3.2 system design requirements

The main functions of this system are divided into 9 modules:

1. Login module

Administrators, teachers and students can log in the system through corresponding user names and passwords;

2. Registration module

Teachers and students can register as new users as required.For security reasons, administrators do not provide registration functions.The registration information required by teachers and students is different.

3. Account management module

The administrator has the right to manage the accounts of teachers and students in the system, including: account deletion and account information modification;

4. Course modules

(1) the administrator can add, delete and modify the recorded process in the system;

(2) teachers can select and operate the courses taught in the system;

(3) students can select courses in the system;

5. Announcement module

The administrator can release announcement messages to teachers or students, and the posted messages will be displayed automatically when teachers and students log in the system. Meanwhile, teachers and students can check the release time of the messages.

6. Topic module

(1) teachers can add or delete questions as required;

(2) students can conduct tests to meet the requirements of subjects, difficulty and other conditions;

7. Record module

(1) teachers can inquire the data of students' overall problem solving and a certain problem;

(2) students can check the record and situation of the questions they have done;

(3) students can inquire all their wrong questions records and information;

8. Password modification module

Teachers and students can modify the login password under the login state;

9. Message module

Students can send messages to designated teachers, who can view the messages they receive from the student office.

3.3 user functional requirements

The system has three different types of users, including "administrator", "teacher" and "student", as well as all three different types of users in the system.The functions they need are as follows:

Administrator:

1. Administrator login.Provides login functions for system administrators to log into the system.

2. Account management.Administrators can manage the accounts of teachers and students, including account information modification and account deletion.

3. Course management.The administrator can manage the current existing course information, including course addition and course deletion.

4. Announcement management.Administrators can issue announcements to teachers and students.

Teacher:

1. System login.The teacher logs into the system with an account name and password.

2. Account registration.The teacher fills in the relevant information to register the account, the specific requirements are: user name, teacher number, real name, password.

3. Teach the course.Teachers choose the course information they currently teach, which will directly affect the subject information of the topic created by the "create topic" function.

4. Create a topic.Teachers create questions in their own class categories for students to work on.The specific information needed to create the question is: question number, question description, question option information, correct answer, answer resolution.

5. Check the status of the problem.Teachers can check their students' past problems.This feature will provide multiple data charts and views to show the teachers the statistical records of all the questions the students have done.

6. Get your message.Teachers can check the messages they receive.

Change your password.The teacher changes the password of the current login account.

Student:

1. System login.Students use account names and passwords to log into the system.

2. Account registration.Students fill in the relevant information to register the account, the specific requirements are: user name, student number, name, class, password.

3. Choose a course.Through this function, students can choose the courses they are currently studying.

4. Test questions.After students select the current course of study, they can view all the current topics of the course through this function.Complete information and difficulty levels will be provided for each topic.

5. Check the status of the problem.Students can check their past work.This feature will provide multiple data charts and views to show students the statistical records of all the questions they have done.

6. Check error records.Students can check their past wrong questions, and the system will display the specific answers and analysis of the wrong questions.

7. Leave a message.Students can send messages to the designated teacher.

Change your password.Students change the password of the current login account.