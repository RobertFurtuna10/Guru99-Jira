# Guru99 Project
### Revision History

| Date | Description   | Author   | Comments |
| :-----: | :---: | :---: | :---: |
| 18.10.2023 | Test Plan for version 1.0   | Robert Furtuna   | draft test plan |
| 20.10.2023 | v1.1  | Robert Furtuna  | Added more details for Test Process |
| 21.10.2023 | v1.2  | Robert Furtuna  | Added more details for Test Process |

### Table of Content:
1. Introduction
    
            1.1 Project Objective 
            
            1.2 Functionalities in scope

            1.3 Functionalities and tests out of scope 
            
 2. Test process
            
            2.1 Test planning

            2.2 Test analysis

            2.3 Test design

            2.4 Test implementation
    
            2.5 Test execution

            2.6 Test closure

            2.7 Test monitoring and control

 3. Test deliverables

            3.1 Test conditions

            3.2 Test cases

            3.3 Daily test summary reports
    
            3.4 Traceability matrix

            3.5 Test case results

            3.6 Bugs report
    
            3.7 Test completion report

### 1. Introduction
-The Guru99 Bank project aims to provide net banking facility to its customers.

-This release will have limited features. Over a period of time , new and new functionalities will be added to the site

### 1.1 Project Objective
-We need to raise the trust in the quality of the project as high as possible before releasing it to customers. The Purpose of this document is to outline the requirements for the Guru99 Banking website to be developed for Guru99 Tech. Pvt. Ltd. This document will be used by all stakeholders including developers and testers.

-Application under test: [Guru99 Bank](https://demo.guru99.com/V4/index.php).

-Documentation: [Guru99 Documentation](https://docs.google.com/document/d/1rPW5DV82VJT6vtA1VDSrfxaCBuAduxW0zb1yfTh_VMk/edit).

### 1.2 Functionalities in scope
- All the features of New Account, Edit Account, and Delete Account module defined in Guru99 business requirements will be tested using functional testing and GUI testing.
- To ensure that new customers can successfully register and access the Guru99 Bank services
- Functional testing & external interfaces are in scope and need to be tested
- The banking site will be only compatible with Chrome version 27 and above
- Here we should write all the functionalities that are included in the release.
- Testing the functionalities related to account management, including account creation, updating, and deletion.


### 1.3 Functionalities and tests out of scope
-All the features that are not under My account module 
  
-Non-functional testing like stress, performance is beyond scope of this project.

-Automation testing is beyond scope.

-No QA support for mobile applications developed. Only web applications will be tested.

### 2 Test process
### 2.1 Test planning
#### Roles and responsabilities
| Role | Responsabilities  | 
| :-----: | :---: |
| Robert - Tester | will test: Login, Register, Forgotten Password  | 
|  Robert - Tester | will test: New Account module  |
| Robert - Tester  | will test: Edit Account module  | 
| Robert - Tester  | will test: Delete Account module  | 

#### Entry criteria
-smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)

-testing environment is up and running

-roles needed for the project are allocated 

-functional specifications are defined 

-Test Data is prepared

-The necessary equipment and software are installed for testing

#### Exit Criteria:
- 90% of tests are passed.
- exploratory testing was performed on New Account, Edit Account and Delete module.
- To provide a detailed record of the test and the obtained results.


#### Risks
**Project Risks:**
- The risk of team members committing human errors at various stages of the project, including testing activities.
- The risk that one or more team members may become unavailable, thus affecting the progress of the project.
- Uncertainty or lack of communication following testing or the review process, leading to delays or misunderstandings of identified issues.

**Product Risks:**
- Stability risks (crashes, disconnects, etc)
- IE browser might have performance issues
- The web page pagination could be impacted when opened on mobile devices
- Stress conditions might impact the web application
- New browser might not be supported 

### 2.2 Test analysis
-Test Login Account to check the functionality of the login menu.

-Test the New Account module to check the functionality of: Customr id, Account type and Initial deposit and also to check the functionality of Submit and reset buttons. 

-Test the Edit Account module to check the functionality of Account number and also to check the functionality of Submit and reset buttons.

-Test the Delete Account module to check the functionality of Account number and also to check the functionality of Submit and reset buttons.

### 2.3 Test design
-defining the testing process

-all the test cases are written and then examined 

-Jira will be used as test management tool

### 2.4 Test implementation
-all the test data is available and reviewed

-this test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority

-Test suites are created (Cycle Summary was created)


### 2.5 Test execution
-the tests will be executed on the following browsers: Chrome, Mozilla. If time will be available we will extend tests on Opera and Brave browsers

-Bugs will be created based on the failed test cases 

-The full regression testing will be done after new application changes 

-Retesting will be done after a bug is fixed 

-If the site will shut down, we will execute full retesting

-The regression test will be executed when a problem is solved

### 2.6 Test closure
-New account: 100% tests were executed and passed

-Edit account: 100% tests were executed and 75% of them are passed 

-Delete account: 100% tests were executed and 86% of them are passed 

### 2.7 Test monitoring and control
-Various periodic reports will be generated to reflect the current status of testing process, in case of major problems control measures could be taken. 

-Offering feedback to the QA team and other stakeholders regarding the progress.

-Conveying test results achieved so far to all relevant parties

-Identifying and tracking relevant test metrics

-Planning and Estimation to determine the future course of action based on the metrics being tracked

-Prioritize testing efforts in a different way

-Reorganize test schedules and deadlines

-Restructure the test environment

-Reprioritize the test case and conditions

### 3. Test deliverables
### 3.1 Test conditions

### 3.2 Test cases
- Test cases are designed to cover various scenarios and functionalities of the Guru99 application.
- Each test case includes detailed steps, expected results, and preconditions.
[Test cases](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/test%20cases.pdf)

### 3.3 Daily test summary report
![Daily report](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/daily%20report.PNG)
![Daily report](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/daily%20report%202.PNG)

### 3.4 Traceability matrix
![TraceabilityMatrixPNG](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/Traceability%20Matrix.PNG)
- Regular updates to the [Traceability matrix](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/TraceabilityMatrix.xlsx) help maintain transparency and alignment between testing and project objectives throughout the test life cycle.
- The matrix indicates the current status of each test case, helping to monitor the testing process and identify any gaps or missing coverage
- The matrix can be used for compliance purposes and to demonstrate that all requirements have been adequately tested and verified

### 3.5 Test case results
-Test Cases and Results for the Guru99 Application,
[Here](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/test%20case%20results.pdf) you will find a list of all the test cases result created, along with their results, for the Guru99 application. These test cases cover various aspects of the project and are used to assess its correctness and performance for the functionalities: "New Account," "Edit Account," and "Delete Account".

### 3.6 Bugs report
- A total of 3 bugs were discovered and through retesting it was confirmed that they have been fixed
[Bug report](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/bugs%20report.pdf)

### 3.8 Test completion report
- This is the [Test completion report](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/test%20completion%20report.png) for the Guru99 application. It provides a comprehensive overview of the testing process, including test cases, their execution status, and any associated observations or issues encountered during testing.
