# Testing Project for Demo Application Aeries #

<br>

## *Short Description of the Tool and Functionality Under Test* ##

<br>

Aeries is a Student Data Management System for California and Texas designed to facilitate day to day school matters for students, parents and teachers, who can access school data via separate portals.  

Testing is focused on the Aeries Student "Data Confirmation" Process, a re-enrollment activity happening at the start of each school year and which is done via a "Confirmation" form that Parents must complete via the Parent Portal.

The Testing Environments used for this process are the Aeries Demo Parent Portal and Aeries Demo Admin Portal

The Tools used for managing the testing process are Jira and Zephyr Squad

<br>

## *Jira Stories* ##

<br>

The two stories below were created in Jira to cover the Data Confirmation process from both a Parent and a Teacher perspective:

<br>

![Story 1](https://github.com/user-attachments/assets/1ef5e73d-3842-4b02-9d95-6268772aa790)


<br>

![Story 2](https://github.com/user-attachments/assets/7485e107-c832-4e0a-9b25-7649ab2e861e)

<br>

## *Test Planning* ##

The Test Plan aims to describe all testing details related to the "Data Connfirmation" process

<h4>1.1.1. Roles asigned to the project</h4>

| Team Member          | Responsibility      |                     
|----------------------|---------------------|
| Tom Smith            | Project Manager     |
| Coleen Howard        | Product Owner       |
| Andrew Hay           | Software Developer  |
| Irina-Mihaela Luca   | QA Engineer         |    


<h4> 1.1.2 Entry criteria defined </h4>

* Roles to be allocated
* Business Requirements to be finalized
* Project Risks to be identified and mitigated
* Testing Plan to be created

<h4> 1.1.3 Exit criteria defined </h4>

* All Tests to be executed
* All Defects to be fixed and re-tested
* Regression Testing to be finalized
* Product Risks to be identified and mitigated
* Test Completion Report to be sent to stakeholders
  
<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

* All tests in scope are related to the "Data Confirmation" process and they are functional tests meant to capture the end to end behaviour of the Data Confirmation Form from information input to final submission.
* All tests will be done using the Chrome browser.

<h5>Tests not in scope: </h5>

* The testing process will not include other Parent Portal/Admin Portal functionalities.
* No mobile testing will be done
* Non-functional testing is not in scope at this point

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

* Inadequate Testing due to lack of tool knowleddge or an ineffective testing strategy
* Resource Shortage in case of tester unavailability which could lead to insufficient testing coverage 
* Testing Process Delays in case of issues with the testing environment which could lead to the inability to honour project timeline

<h5> Product risks: </h5>

* Perfomance Issues which could lead to a tool that crashes when used by a large number of users
* Bad User Experience which could lead to bad user reviews diminishing trust in overall quality
* Tool Limitations which could lead to maintanance issues

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can be initiated.

<h3>1.2 Test Monitoring and Control<h3>
<h4></h4> -> The testing process will be closely monitored to make sure everything is on track and all factors will be taken into consideration to ensure a smooth execution.<br>
-> In case issues arise that might affect test completion according to the deadline, then further control measures will be taken to mitigate or lower such risks. <br>
-> Based on ongoing status reports, testing will be planned and replanned in the alloted timeframe.<h4></h4>

<h3> 1.3 Test Analysis </h3>
<h4></h4>The testing process will be executed based on the application requirements.<h4></h4>

According to the Early Testing Principle, the documentation and guidelines referencing "Data Confirmation" have been thoroughy analyzed, to capture the main requirements for succcessfully completing this process.

#### Test Conditions ####
The following test conditions have been identified upon reviewing the business requirements for this functionality  : 
<br>
* Check that a Data Confirmation banner with a link to the Data Confirmation form shows up at the bottom of the page for a parent who has not completed the confirmation process
* Check that the Data Confirmation banner is no longer displayed for parents who have completed the Data Confirmation process
* Check that the Data Confirmation form is read-only after the confirmation process has been completed
* In the "Family Information" section check that an error is thrown if an option has not been selected for each one of the surveys and the next step can't be reached
* In the "Income" section check that, once the income has been submitted, a notification is displayed and no further changes can be made
* In the "Income" section check that if an income is not selected a pop-up message is displayed to state that and ask for confirmation
* In the "Income" section check that the income figures are recalculated for the low, medium and high intervals based on the number of household members selected
* In the "Student" field check that a student mobile phone number can be added to the page
* In the "Contacts" section check that existing contact information can be edited or deleted and new contacts can be added to the list
* In the "Medical History" section check that medical conditions can be assigned to the student or removed if they no longer apply
* In the "Authorizations" section check that an error message is displayed if an option is not selected for the mandatory items and that data is successfully saved upon providing the required answer
* In the "Documents" section check that an error message is displayed if the parent does not acknowledge required documents
* In the "Final Data Confirmation" section check that the printed/saved Emergency card has a correct format and contains the information specified during the Confirmation process
* Check that all required admin setups are in place for the Data Confirmation Process
* Check that a teacher logging in as an admin can emulate a parent performing the  Data Confirmation process
* Check that a teacher logging in as an admin is able to restrict parent access to other portal tabs until the Data Confirmation process is completed

<h3>1.4 Test Design</h3>

* Functional test cases have been created based on the analysis of the specifications and can be accessed [here](https://github.com/Irina11-m/My-Repo/blob/main/Zephyr%20Test%20Steps%20for%20Aeries%20(Jira).pdf)
* Tools/Infrastructure necessary for testing needs to be identified
* Testing Data needs to be identified 

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:
* Testing Data needs to be created
* The Testing Environment needs to be validated for use through smoke testing
* All permisions for accessing the testing environment need to be granted

<h3>1.6. Test Execution </h3>

The test cases, executed on the Cycle summary Aeries_V_1.0.0.1, can be accessed [here](https://github.com/Irina11-m/My-Repo/blob/main/Zephyr%20Test%20Steps%20%2B%20Executions%20%2B%20Results_Aeries%20(Jira).pdf)

The following bug reports have been created based on the failed tests with a high priority for fixing: 
<br>

###### Bug Report 1 ######
![Bug 1](https://github.com/user-attachments/assets/c9a92523-1094-4db9-89fc-ef7e156139cd)

<br>

###### Bug Report 2 ######
![Bug 2](https://github.com/user-attachments/assets/1b9996e4-14b9-41fa-8e70-f58386853f38)

<br>

###### Bug Report 3 ######
![Bug 3](https://github.com/user-attachments/assets/b94f95ec-323e-4aa3-b289-94956bed86eb)


<h3> 1.7 Test Completion</h3>
Upon meeting the established Exit criteria, this feature will be able ‘Go Live’ once agreed by the Testing team
<br>
<br>
At that point, a Test Completion Report will be sent to the stakeholders so that they can take an informed decision regarding the tested functionality.

<br>

#### Traceability Matrix ####

A Traceability Matrix is used as well to show the level of testing coverage in relation to business requirements which also:
* helps the stakeholders to quickly determine the level of risk associated with getting the software pushed to production.
* tracks the association between test cases and requirements and it also
* helps to trace the root cause of any bug logged in the process
  
<br>

As seen the image below, all bugs can be traced to one Story, "Data Confirmation Process as a Parent":
<br>

![Bordered Traceability Matrix](https://github.com/user-attachments/assets/108e14c6-8771-439d-9dd9-76dda4759362)

<br>

#### Test Execution Chart ####

A Test Execution Chart was generated and can be found below:
<br>
![Bordered Jira PieChart Report](https://github.com/user-attachments/assets/3348f42f-05cb-4855-9490-bb8193a07fac)

<br>

#### Risk Matrix ####

A Risk Matrix was put together to show a full picture of both Project and Products risks identified in relation to this specific functionality across the Demo Parent and Admin Portals:

<br>

![image](https://github.com/user-attachments/assets/bfc8878c-dd1c-4ad7-9eb7-051b5cfe449c)


<br>

## *Final Testing Conclusions* ##

<br>

As part of this testing process, the functionality in scope for testing was the "Data Confirmation" form, whose analysis was divided into two stories, namely the "Data Confirmation Process as a Parent" and the "Data Confirmation Process as a Teacher/Admin".
The environment used for testing is a demo application, which both parents and teacher can use to familiarize themselves with how the process works.

In total, 16 tests have been executed which cover both stories and 3 bugs have been identified and reported.

The identified bugs are quite severe, since they affect a parent's ability to input and change data that is crucial for the wellbeing and security of the child, namely adding contact information for the student, including student's phone number and updating the list of contacts who are authorized to act in the benefit of the student. Moreover, the submitted data can be temporarily edited, and although, upon page refresh the intially submitted data is kept, this can create confusion and further distrust in the overall "Confirmation" process.

From a teacher's perspective, no actual bugs have been discovered, since the teachers can perform the setup for the "Confirmation" process, can block a parent from having access to other portal tabs until they finish submitting the "Confirmation" form and they can emulate a parent during the "Confirmation" process.

Therefore, the three bugs are critical and must be prioritized for fixing and re-testing and a subsequent regression testing must be done for the entire "Confirmation" process to ensure that no other defects have been produced by the fix applied to the system.
