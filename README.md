# task-test-case-for-student-management
🎓 Student Management System — Complete Testing Problem
1. Problem Statement
A college wants to develop a Student Management System to manage student information.
The system should allow an authorized user to:
1.	Login 
2.	Add a student 
3.	View student details 
4.	Search for a student 
5.	Edit student details 
6.	Delete a student 
7.	Enroll a student in a course 
8.	Enter/view marks 
9.	Logout 
The system should:
•	Accept valid information. 
•	Reject invalid information. 
•	Validate mandatory fields. 
•	Prevent duplicate student IDs. 
•	Allow only authorized users to access restricted functions. 
•	Display appropriate success/error messages. 
Our job as testers is to verify that all these requirements work correctly.
________________________________________
2. Requirements
Let's assume the project has these 10 requirements:
Req ID	Requirement
R01	User should be able to login
R02	User should be able to add a student
R03	User should be able to view student details
R04	User should be able to search students
R05	User should be able to edit student details
R06	User should be able to delete a student
R07	User should be able to enroll students in courses
R08	User should be able to enter marks
R09	User should be able to view results
R10	User should be able to logout
________________________________________
3. Test Scenarios
Remember:
Test Scenario = WHAT we are going to test.
Based on the requirements:
Scenario ID	Test Scenario
TS01	Verify Login functionality
TS02	Verify Add Student functionality
TS03	Verify View Student functionality
TS04	Verify Search Student functionality
TS05	Verify Edit Student functionality
TS06	Verify Delete Student functionality
TS07	Verify Course Enrollment functionality
TS08	Verify Marks Entry functionality
TS09	Verify Result functionality
TS10	Verify Logout functionality
Your notes define a scenario as what to test, while a test case explains how to test it. One scenario can have multiple test cases. 
________________________________________
4. Test Cases
Now we go one level deeper.
Test Case = HOW we test the scenario.
TS01 — Login
TC ID	Test Case	Expected Result
TC01	Enter valid username and password and click Login	User successfully logs in
TC02	Enter invalid username and valid password	Error message displayed
TC03	Enter valid username and invalid password	Error message displayed
TC04	Leave username/password blank	Validation message displayed
________________________________________
TS02 — Add Student
TC ID	Test Case	Expected Result
TC05	Add student using valid details	Student added successfully
TC06	Leave mandatory field blank	Validation message displayed
TC07	Enter invalid email	Invalid email message displayed
TC08	Enter duplicate student ID	Duplicate ID rejected
________________________________________
TS03 — View Student
TC ID	Test Case	Expected Result
TC09	View existing student	Correct details displayed
TC10	View non-existing student	Student-not-found message displayed
________________________________________
TS04 — Search Student
TC ID	Test Case	Expected Result
TC11	Search using valid student ID	Correct student displayed
TC12	Search using invalid ID	No student found
TC13	Search using student name	Matching student displayed
________________________________________
TS05 — Edit Student
TC ID	Test Case	Expected Result
TC14	Edit valid student details	Details updated successfully
TC15	Change student email	New email saved
TC16	Clear mandatory field during edit	Validation message displayed
________________________________________
TS06 — Delete Student
TC ID	Test Case	Expected Result
TC17	Delete existing student	Confirmation displayed
TC18	Click Cancel	Student remains
TC19	Confirm deletion	Student deleted
________________________________________
TS07 — Course Enrollment
TC ID	Test Case	Expected Result
TC20	Enroll student in valid course	Enrollment successful
TC21	Enroll same student twice	Duplicate enrollment prevented
TC22	Enroll without selecting course	Validation message displayed
________________________________________
TS08 — Marks Entry
TC ID	Test Case	Expected Result
TC23	Enter valid marks	Marks accepted
TC24	Enter marks greater than maximum	Validation message displayed
TC25	Enter negative marks	Validation message displayed
________________________________________
TS09 — Results
TC ID	Test Case	Expected Result
TC26	View student's result	Result displayed
TC27	Verify total marks	Correct total displayed
TC28	Verify grade	Correct grade displayed
________________________________________
TS10 — Logout
TC ID	Test Case	Expected Result
TC29	Click Logout	User logged out
TC30	Try accessing system after logout	Login required
________________________________________
5. Test Execution
Now we execute the test cases.
We have:
Total Test Cases = 30
Suppose the execution results are:
•	24 executed 
•	21 passed 
•	3 failed 
•	6 not executed 
So now we have actual testing data.
This is where Test Metrics & Analytics starts.
________________________________________
6. Requirement Coverage
We have:
•	Total requirements = 10 
•	Requirements tested = 8

________________________________________
7. Test Execution %
We have:
•	Total test cases = 30 
•	Executed = 24 
 ________________________________________
8. Pass Rate
We have:
•	Executed = 24 
•	Passed = 21 
 
________________________________________
9. Fail Rate
We have:
•	Executed = 24 
•	Failed = 3  ________________________________________
10. Defect Density
Suppose during testing we found:
50 defects
and the application contains:
 ________________________________________
11. Critical Defect Percentage
Suppose the 50 defects contain:
•	Critical = 5 
•	High = 15 
•	Medium = 20 
•	Low = 10 
Total = 50.  
________________________________________
12. Defect Distribution
Now calculate each category.
 ________________________________________
13. Mean
Suppose during performance testing, we recorded these response times:
2, 3, 4, 3, 8 seconds
 ________________________________________
14. Median
Same data:
2, 3, 4, 3, 8
Step 1 — Sort
2, 3, 3, 4, 8
Step 2 — Find middle
Middle = 3
Median=3 seconds
