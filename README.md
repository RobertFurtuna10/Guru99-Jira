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

-Application under test: https://demo.guru99.com/V4/index.php

-Documentation: [Guru99 Documentation]https://docs.google.com/document/d/1rPW5DV82VJT6vtA1VDSrfxaCBuAduxW0zb1yfTh_VMk/edit)https://docs.google.com/document/d/1rPW5DV82VJT6vtA1VDSrfxaCBuAduxW0zb1yfTh_VMk/edit

### 1.2 Functionalities in scope
-All the features of Account module which were defined in Guru99 business requirements will be tested using the following testing types: functional testing, GUI testing, API testing.
  
-The Guru99 application will be tested on latest versions of Mozilla and Chrome.


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

#### Risks
-stability risks (crashes, disconnects, etc)

-stress conditions might impact the web application

-new browser might not be supported

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
[Test cases](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/test%20cases.pdf)

### 3.3 Daily test summary report
![Daily report](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/daily%20report.png)
![Daily report](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/daily%20report%202.png)

### 3.4 Traceability matrix
![Traceability matrix](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/traceability%20matrix.png)

### 3.5 Test case results
[Test case results](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/test%20case%20results.pdf)

### 3.6 Bugs report
[Bug report](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/bugs%20report.pdf)

### 3.8 Test completion report
![Test completion report](https://github.com/RobertFurtuna10/Guru99-Jira/blob/main/test%20completion%20report.png)
