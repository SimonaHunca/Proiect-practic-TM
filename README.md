# **OrangeHRM Project**
## *TEST PLAN*
</br>

### Revision History

| Date | Description | Author | Comments |
| :-------------: | :-------------:| :-------------: | :-------------: |
| 11.03.2023  | v1.0 | Hunca Simona | Draft Plan |
| 18.03.2023  | v1.1  | Ioana Dunarean | Test Results for Functional Testing |
| 22.03.2023 | v1.2 | Andrei Murariu | More details added for Test Implementation | 
</br>
</br>

#### 1. <ins>Introduction<ins>
   #### 1.1 Project objective
   #### 1.2 Functionalities in scope
   #### 1.3 Functionalities and tests out of scope
#### 2. <ins>Test Process<ins>
   #### 2.1 Test Planning
   #### 2.2 Test Analysis
   #### 2.3 Test Design
   #### 2.4 Test Implementation
   #### 2.5 Test Execution
   #### 2.6 Test Completion
   #### 2.7 Test Monitoring and Control
#### 3.<ins> Test Deliverables<ins> 
   #### 3.1 Test plan
   #### 3.2 Test conditions
   #### 3.3 Test cases
   #### 3.4 Daily test summary reports
   #### 3.5 Traceability matrix
   #### 3.6 Test case results
   #### 3.7 Bugs report
   #### 3.8 Test completion report
</br>
</br>
   
## 1. <ins>Introduction<ins>
   This test plan describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage testing process for OrangeHRM browser application, ADMIN Module, Submenu: USER MANAGEMENT and JOB .
### 1.1 Project objective
   The scope of the final project for ITF Manual & Automation Testing Course is to use all gained knowledge through the course and apply them in practice using a live application. 
   
   [Application under test](https://opensource-demo.orangehrmlive.com/web/index.php/admin/viewSystemUsers)
   
   [Application documentation](https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf 
)
   
   **Tools**: Jira, Postman, MySql
</br>  
   
### 1.2 Functionalities in scope
   All features of **Admin** ( Submenu:USER MANAGEMENT and JOB ) module which were defined in software requirement specification need to be: Functional testing, GUI testing, API testing.  
  
[User story 1.pdf](https://github.com/SimonaHunca/Proiect-practic-TM/files/12039489/User.story.1.pdf)


### 1.3 Functionalities and tests out of scope
  - All OrangeHRM features except SUBMENU from Admin menu : USER MANAGEMENT and JOB 
  - Non-functional testing like stress, performance is beyond scope of this project.
  - No QA support for mobile application developed. Only web application will be tested.
  - Automation testing is beyond scope.
## 2. <ins>Test Process<ins>
  ### 2.1 Test Planning 
   
#### Roles and responsabilities:
| **Role** | **Name** |
| :-------------: | :-------------:| 
| Software Developer | Maria Marinescu | 
| Product Owner | Alisa Rădoi |
| Project Manager| Gabriela Radulescu |
| QA Engineer|   Simona Hunca |
| Senior QA Engineer | Rafael Popescu |
   
#### Entry criteria :
   - functional specification defined
   - roles needed for the project are allocated 
   - initial project risks were detected and mitigated
#### Exit criteria : 
   - all test cases have been executed
   - the number of unresolved bugs is insignificant or have low priority
   - all resolved bugs have been re-tested and closed by the QA team 
   - deadline was reached
   - no detected major risks remained un-mitigated 
   
#### Risks :
   ***Project risks***:
   - lack of experience of the QA team
   - only one QA in the QA team
   - unavalability of the test environment 
   - short deadline of Zephyr Squad and Jira tools
   
   ***Product risks***:
   - software security breaches the realease of confidential employee information
   
   
### 2.2 Test Analysis
   - analyze business requirements to make sure that we have all information for creating the test condition
   - write test conditions that will be tested out in test process
   
   ***Test Conditions:***
   
   1. Verify that all submenus in Admin Module are present
   2. Verify that Add User window has all the input fields and dropdowns available
   3. Verify that Job Menu has all the submenus available
   4. Verify that all the fields in Add User page are marked as required fields
   5. Verify that System User List looks like in the picture 1.3 from business requirements
   6. Verify that user is not allowed to complete with special characters the field Name on Add pay Grades page
   7. Verify that user is not allowed to complete the field Name from Add Job Category with number or special characters
   8. Verify that user cannot upload an document bigger than 1mb on Job Specification field from Add Job Title page
   9. Check that users cannot write more than 50 letters on Job Title input field from Add Job title page
   10. Check if we have an info tip when we write more than 400 characters on the Note field and Job Description on the Add Job Title page
   11. Verify if user can search in the dropdown Currency by typping the currency name
   12. Verify that on Add Workshift page all the required fields are marked with a red star
   13. Check that Admin User can add an Employment Status
   14. Check that admin can delete one or multiples entries from the Employment Status window
   15. Check that Admin can delete one or multiples entries from the Job Categories window
   16. Checking that Admin can create a job category
   17. Check that we can delete one or multiples entries from the Job Title window
   18. Check that Admin user can create a Job title
   19. Verify that the HR Admin can define a pay grade
   20. Verify that only the HR Admin can define the Pay Grade
   21. Check that user can delete one or multiples entries from the Pay Grade window
   22. Verify that the HR Admin can define multiple currencies to an employee pay grade
   23. Check that user can fill the Minimum Salary field with an amount bigger than in the Maximum Salary field on Add Currency page
   24. Check that we can create with success an ESS Supervisor USER TYPE
   25. Verify that we cannot create any type of User without previously creating the corresponding employee
   26. Verify that the Admin User has full access to the system
   27. Check that we can create with success an ESS Employee USER TYPE
   28. Verify that ESS Supervisor has access to his personal information and to his subordinates personal information
   29. Check that we can delete one or multiples entries from the System Users window
   30. Check that ESS Users has limited access to the system
   31. Check that user can delete one or multiples entries from the Work Shift Lists
   32. Verify that user can create work shifts for employees
   33. Verify that the mandatory fields from Edit Pay Grade page are marked with a red star
   34. Verify that user can upload an 1mb document on Job Specification field from Add Job Title page
   35. Verify that on Add User page the dropdowns are available and with all the options 
   36. Check that users cannot write numbers and special characters on Employee Name input field from Add User page
   37. Check that user cannot fill with a negative number the Minimum and Maximum Salary field
   
### 2.3 Test Design
   - functional test cases will be created in Zephyr Squad 
   - GUI test cases will be created in Zephyr Squad
   - API test cases will be created in Postman 
   - the test design techniques used for generating test cases are: equivalence partitioning, boundary value analysis. 


### 2.4 Test Implementation
   Verify that the following elements are ready before the test execution phase: 
   - test environment is up and running: [OrangeHRM Admin] (https://opensource-demo.orangehrmlive.com/web/index.php/auth/login) 
   - access to the test environment is given: username Admin, pass: admin123
   - cycle summary (*test cases colection from Jira) was created and the test cases were added to the cycle summary 
   - Postman collections were created 
   
### 2.5 Test Execution
   - test cases are executed on the created Cycle summary 
   - bug reports were created based on the failed test cases. 
   - API test cases were executed 
   - full regression tests pack was executed 

### 2.6 Test Completion
   As the exit criteria were met and satisfied as mentioned in the 2.1 section, this feature is suggested to go live by the QA team. 
   
### 2.7 Test Monitoring and Control   
   Generate periodic reports to check the project status: status for the test cases executed, status for the converge of the business requirements, etc 

[Two weeks report 1](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/daily%20report%2019.04.2023%20(2).png)

[Two weeks report 2](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/daily%20report%2019.04.2023.png)

## 3.<ins> Test Deliverables<ins> 
   ### 3.1 Test plan
   The test plan should be delivered to the Project Manager until the fifth week of the TM Courses of the ITF Company.
   
   ### 3.2 Test conditions

 [Test condition 1](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20condition%201.png)
 
 [Test condition 2](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20condition%2010.png)
 
 [Test condition 3](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20condition%202.png)
 
 [Test condition 4](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20condition%203.png)
 
 [Test condition 5](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20condition%204.png)
 
 [Test condition 6](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20condition%205.png)
 
 [Test condition 7](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20condition%206.png)
 
 [Test condition 8](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20condition%207.png)
 
 [Test condition 9](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20condition%208.png)
 
 [Test condition 10](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20condition%209.png)
 
   ### 3.3 Test cases
 
 [Test cases](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/Test%20Cases.pdf)
   
   ### 3.4 Daily test summary report
   
   
 ![Daily report 18.04.2023](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/daily%20report%2018.04%20(2).png)
 
 
 ![Daily report 18.04.2023](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/daily%20report%2018.04.png)
   
 
 ![Daily report 19.04.2023](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/daily%20report%2019.04.2023.png)
   
 
 ![Daily report 19.04.2023](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/daily%20report%2019.04.2023%20(2).png)
 

   ### 3.5 Traceability matrix

[Traceability matrix](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/Forward%20Traceability_19_4_2023.xlsx)


   ### 3.6 Test case results

[Test Cases Results](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/OSH-5-combined.pdf)

   ### 3.7 Bugs report
   
[Bugs](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/OSH-59-combined_1.pdf)

[Bugs report](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/Forward%20Traceability_19_4_2023%20(1).xlsx)

   ### 3.8 Test completion report

![Test completion report](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/test%20execution%20report.png)
   

   ### 3.9 Schedule 
   
   | Tasks  | Date | Executed by |
   |---------|-------------|----------|
   | Run GUI Testing for User management module  | 05.04.2023 | Simona Hunca |
   | Run GUI Testing for Job module | 08.04.2023 | Simona Hunca|
   | Run Functional testing for Job Titles and Job Category submenu | 12.04.2023 | Simona Hunca |
   | Run Functional testing for Employment Status and Pay Grade submenu | 18.04.2023 | Simona Hunca |
   | Export daily report | 18.04.2023 | Simona Hunca |
   | Run Functional testing for User Management and Work Shifts | 19.04.2023 | Simona Hunca |
   | Export traceability and general reports | 19.04.20.23 | Simona Hunca |
   | Handover the project | 08.05.2023 | Simona Hunca |
   
   
