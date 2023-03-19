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
   ### 2.5 Test Execute
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
   This test plan describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage testing process for OrangeHRM browser application, ADMIN Module.
### 1.1 Project objective
   The scope of the final project for ITF Manual & Automation Testing Course is to use all gained knowledge through the course and apply them in practice using a live application. 
   
   [Application under test](https://opensource-demo.orangehrmlive.com/web/index.php/admin/viewSystemUsers)
   
   [Application documentation](https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf 
)
   
   **Tools**: Jira, Postman, MySql
</br>  
   
### 1.2 Functionalities in scope
   All features of **Admin** module which were defined in software requirement specification need to be: Functional testing, GUI testing, API testing.  
  
   > ** Screenshots from Jira with user story details

### 1.3 Functionalities and tests out of 
  - All OrangeHRM features except Admin module
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
| Project Manager| Radu Pintilie |
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
   
   *** Product risks***:
   - validation constraints on the fields might be to restrictive for the end user
   
### 2.2 Test Analysis
   - analyze business requirments to make sure that we have all information for creating the test condition
   - write test conditions 
   
