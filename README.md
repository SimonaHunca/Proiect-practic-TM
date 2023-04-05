# **OrangeHRM Project**
# *TEST PLAN*
</br>

## Revision History

| Date | Description | Author | Comments |
| :-------------: | :-------------:| :-------------: | :-------------: |
| 11.03.2023  | v1.0 | Hunca Simona | Draft Plan |
| 18.03.2023  | v1.1  | Ioana Dunarean | Test Results for Functional Testing |
| 22.03.2023 | v1.2 | Andrei Murariu | More details added for Test Implementation | 
</br>
</br>

## 1. <ins>Introduction<ins>
   ### 1.1 Project objective
   ### 1.2 Functionalities in scope
   ### 1.3 Functionalities and tests out of scope
## 2. <ins>Test Process<ins>
   ### 2.1 Test Planning
   ### 2.2 Test Analysis
   ### 2.3 Test Design
   ### 2.4 Test Implementation
   ### 2.5 Test Execution
   ### 2.6 Test Completion
   ### 2.7 Test Monitoring and Control
## 3.<ins> Test Deliverables<ins> 
   ### 3.1 Test plan
   ### 3.2 Test conditions
   ### 3.3 Test cases
   ### 3.4 Daily test summary reports
   ### 3.5 Traceability matrix
   ### 3.6 Test case results
   ### 3.7 Bugs report
   ### 3.8 Test completion report
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
  
   > ** Screenshots from Jira with user story details

### 1.3 Functionalities and tests out of 
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
   - validation constraints on the fields might be to restrictive for the end user
   
### 2.2 Test Analysis
   - analyze business requirments to make sure that we have all information for creating the test condition
   - write test conditions that will be tested out in test process
> ** Screenshots with test conditions in section 3.2 from Jira.
   
### 2.3 Test Design
   - functional test cases will be created in Zephyr Squad 
   - GUI test cases will be created in Zephyr Squad
   - API test cases will be created in Postman 
   - the test design techniques used for generating test cases are: equivalence partitioning, boundary value analysis. 


![Test conditions 1](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/Screenshot%20(2).png)

![Test conditions 2](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/Screenshot%20(3).png)

![Test conditions 3](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/Screenshot%20(4).png)

![Test conditions 4](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/Screenshot%20(5).png)

![Test conditions 5](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/Screenshot%20(6).png)

![Test conditions 6](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/Screenshot%20(7).png)

![Test conditions 7](https://github.com/SimonaHunca/Proiect-practic-TM/blob/main/Screenshot%20(8).png)


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
> ** Screenshots with Jira general reports ( every week, every two weeks, montly ). 

## 3.<ins> Test Deliverables<ins> 
   ### 3.1 Test plan
   The test plan should be delivered to the Project Manager until the fifth week of the TM Courses of the ITF Company.
   
   
