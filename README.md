# OPENCART Project - TEST PLAN


**Revision History**
|Date|Description|Author|Comments|
|---|---|---|---|
|29.04.2023|v1.0|Cristian TANASESCU||
|08.05.2023|v2.0|Cristian TANASESCU||

1. Introduction
         
        1.1	Project objective
        1.2	Functionalities in scope
        1.3	Functionalities and tests out of scope
2. Test process

        2.1	Test planning
        2.2	Test analysis
        2.3	Test design
        2.4	Test implementation
        2.5	Test execution
        2.6	Test closure
        2.7	Test monitoring and control
3. Test deliverables

        3.1	Test plan
        3.2	Test conditions
        3.3	Test cases
        3.4	Daily test summary reports
        3.5	Traceability matrix
        3.6	Test case results
        3.7	Bugs report
        3.8	Test completion report
        

# 1. Introduction #
         
This test plan document describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage testing process for Opencart.
OpenCart is free open source e-commerce platform for online merchants. OpenCart provides a professional and reliable foundation from which to build a successful online store. This foundation appeals to a wide variety of users; ranging from seasoned web developers looking for a user-friendly interface to use, to shop owners just launching their business online for the first time. OpenCart has an extensive amount of features that gives you a strong hold over the customization of your store. With OpenCart's tools, you can help your online shop live up to its fullest potential.

         
   ### 1.1 Project objective ###
   
The purpose of the final project for ITFactory Manual Testing Course is to use all gained knowledge through the course and apply them in practice, using a live application. 

Application under test is [OPENCART](https://demo.opencart.com/) and the focus will be only on ***Browsing the Store Front*** section.

Application documentation: [https://docs.opencart.com/en-gb/store-front/](https://docs.opencart.com/en-gb/store-front/)

Tools used: Jira, Postman, MySQL 


   ### 1.2 Functionalities in scope ###
   
 Features of ***Browsing the Store Front*** section which were defined in business requirements that should be tested: functional testing, GUI testing and API testing 
The below user story was created in JIRA and describes functional specifications of the Browsing the Store Front module.

***!!!!!!!!!!!!!!!!Screenshots din Jira cu user story-ul***

   ### 1.3 Functionalities and tests out of scope ###
   
- Non-functional testing like stress, performance is beyond scope of this project.
- No QA support for mobile applications developed. Only web applications will be tested.
- Automation testing is beyond scope.
- Compatibility testing with multiple browsers is beyond scope.
   
# 2. Test process #

  ### 2.1 Test planning ###
  - **Roles and responsibilities assigned and persons allocated**
  
  |Role|Name|
  |---|---|
  |Product owner|Popescu Ion|
  |Software Developer|Popescu Maria|
  |Tester|Tanasescu Cristian|
  
- **Entry criteria defined** 

                  - Business specifications are defined
                  - Availability of test environment
                  - Availability of necessary test tools
                  - Availability of test data and other necessary resource      
                  - Roles needed for the project are allocated 
                  - Initial project risks were detected and mitigated 

- **Exit crtieria defined**

                  - All test cases have been executed                   
                  - The unresolved bugs/defects have low priority                  
                  - No detected major risks remained un-mitigated                   
                  - All resolved bugs have been retested and approved by the testers                  
                  - Regression testing have been ran and no major bugs detected                    
                  - All business requirements have been covered by test cases                   
                  - All business requirements have been met 
                  - The evaluated levels of reliability, performance efficiency, usability, security, and other relevant quality characteristics are sufficient

- **Risks detected**

                  -Project risks: lack of experience of QA team, lack of tools, short deadline for Jira and Zephyr Squad trial, unavailability of Opencart demo environment
                  -Product risks: Validation constraints on the fields might be too restrictive to the end user 


 ### 2.2 Test analysis ###
  
Analyze the business requirements to make sure that we have all the details to identify testable features and create the test conditions. 
Write test conditions that will be tested in out test process. 


  ### 2.3 Test design ###

Test cases will be designed and prioritized. Functional test cases will be created in Jira alongside GUI test cases. API test case will be created in Postman and the DB queries will be done in MySQL.

  ### 2.4 Test implementation ###

Verify if the following elements are ready before test execution:
-	Test environment is up and running: https://demo.opencart.com
-	Access to test environment is given
-	Cycle summary was created 
-	Test cases were added to the cycle summary 
-	Postman collection with the API methods was created 
-	Authorization token was created accessing the API and it is valid 
  
  ### 2.5 Test execution ###

-	Test cases are executed on the created cycle summary 
-	Bugs have been created based on the failed test cases. The complete bug reports can be found here: *se poate pune link catre un fisier cu bug reports in Github 
-	API tests are executed based on the checklist (requirements)
-	Full regression pack is executed after changes made to the application 

  ### 2.6 Test closure ###

-	All exit criteria were met as mentioned in the Test Planning section (2.1)
-	The traceability matrix was generated to demonstrate the business requirements coverage
-	Test execution chart was generated, the final report shows a number of 3 failed test cases of a total 30
-	There are still 3 opened defects but they have low priority

  ### 2.7 Test monitoring and control ###
  
  Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.

# 3. Test deliverables #

  ### 3.1 Test plan ###

The plan identifies the items to be tested, the features to be tested, the type of testing to be performe, the roles and responsibilities for the testing process, the resources and schedule required to complete testing and the risks associated with the plan. 

  ### 3.2 Test conditions ###

  ### 3.3 Test cases ###

  ### 3.4 Daily test summary reports ###

  ### 3.5 Traceability matrix ###

  ### 3.6 Test case results ###

  ### 3.7 Bugs report ###

  ### 3.8 Test completion report ###
