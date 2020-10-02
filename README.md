# Database-for-coaching-center
To design a normalised database for a coaching institute 

## Problem Statement : 
In the current competitive environment growing in this country, many tution centres have emerged that prepare aspiring candidates for various competitive examinations. While some of these centres are locally operating while others are distributed across multiple areas and cities. These private training centres who operate across multiple cities have many teachers working under them. Many students enroll themselves in various courses offered by these institutes. Our aim is to design a database that will store data of all the centres of an operating institute, the teachers working under them, students taking admission in the institute along with other information such as which student goes to which centre, the study materials being delivered to which student(s) and the mock tests being conducted by the institute along with the information of each students' participation and performance in each mock test.

Hence we declare a data centric problem statement where we mention the requirement specifications of the database we have designed as follows:

 The entity sets have been identified as follows:
 
 1) Employee- To store the information of each employee of the institute.
 2) Teacher-To store the information of a teacher who is an employee with some special attributes.
 3) Non-teaching staff- To store the information of each non teaching staff who is an employee with some special attributes.
 4) Centre- To store the information of each operating centre of the institute.
 5) Manager- A manager who is also a teacher manages a particular centre.
 6) Student- To store the information of each student studying at a particular centre of the instuitute.
 7) Mock Test- To store the information of each mock test being conducted by the institute.
 8) Study Material- To store the information of each study material packet being delivered by the institute.
 9) Course Fees-To store the information of the fees of each course offered by the institute.
 10) Workshop-To store the information of each workshop being conducted by a specific group of teachers of the institute.

 The constraints are as follows :
 
 1) A teacher will teach at 0 or many centres at particular slot.
 2) A centre can have 0 or many teachers.
 3) One non teaching staff member will work in one and only one centre.
 4) A centre can have 0 or many non teaching staff members.
 5) A student will be advised by only one teacher and a teacher can have 0 or many students to advise.
 6) A student will visit only one centre and a cantre will have 0 or many students visiting it.
 7) A student will take 0 or many mock tests and a mock test can be taken by 0 or many students.
 8) A student will make 0 or many payments for the course(s) the person has registered in.
 9) A course fee will be paid by 0 or many students.
 10) A study material will be delivered to only one student.
 11) A student will receive one or many study material packets.
 12) A teacher alone or along with other teachers can conduct 0 or many workshops.
 13) A workshop can be conducted by 1 or many teachers.  
