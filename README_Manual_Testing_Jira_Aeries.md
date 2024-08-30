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
<br>

## *Test Planning* ##

The Test Plan aims to describe all testing details related to the "Data Connfirmation" process

<h4>1.1.1. Roles asigned to the project</h4>

<ul>
  <li>Project manager -  Tom Smith</li>
  <li>Product owner - Coleen Howard</li>
  <li>Software developer - Andrew Hay</li>
  <li>QA Engineer - Irina Mihaela Luca</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

* Roles to be allocated
* Business Requirements to be finalized
* Project Risks 
* Testing Plan to be created

<h4> 1.1.3 Exit criteria defined </h4>

* All Tests to be executed
* All Defects to be fixed and re-tested
* Regression Testing to be finalized
* Product Risks to be identified and mitigated
* Test Completion Report to be sent to stakeholders
  
<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

**(descrieti aici toate testele pe care intentionati sa le faceti. Puteti include functionalitati din aplicatie, tipuri sau tehnici de testare, dispozitive pe care veti testa etc)**
* All tests in scope are related to the "Data Confirmation" process and they are functional tests meant to capture the end to end behaviour of the Data Confirmation Form from information input to final submission.
* All tests will be done using the Chrome browser.

<h5>Tests not in scope: </h5>

**(descrieti aici toate testele pe care NU intentionati sau nu puteti sa le faceti. Puteti include functionalitati din aplicatie, tipuri sau tehnici de testare, dispozitive pe care veti testa etc)**
* The testing process will not include other Parent Portal/Admin Portal functionalities.
* No mobile testing will be done
* Non-functional testing is not in scope at this point

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

**(enumerati aici toate riscurile de proiect pe care le-ati identificat pentru proiectul vostru)**

* Inadequate Testing
* Resource Shortage
* Testing Process Delays

<h5> Product risks: </h5>

* Perfomance Issues
* Bad User Experience
* Tool Limitations

**(enumerati aici toate riscurile de produs pe care le-ati identificat pentru proiectul vostru)**

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can be initiated.

<h3>1.2 Test Monitoring and Control<h3>

The testing process will be closely monitored to make sure everything is on track and all factors will be taken into consideration to ensure a smooth execution.
In case issues arise that might affect test completion according to the deadline, then further control measures will be taken to mitigate or lower such risks.
Based on ongoing status reports, testing and will be planned and replanned in the alloted timeframe.

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

According to the Early Testing Principle, the documentation and guidelines referencing "Data Confirmation" have been thoroughy analyzed, to capture the main requirements for succcessfully completing this process.

The following test conditions have been identified upon reviewing the business requirements for this functionality  : <br>

**(aici puteti fie sa puneti o poza din jira cu titlurile tuturor testelor - din issues filtrare dupa type test sau sa scrieti cu bulinuta numele fiecarei conditii de testare pe care ati identificat-o)**

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

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed
**[here](https://github.com/Irina11-m/My-Repo/blob/main/Zephyr%20Test%20Steps%20for%20Aeries%20(Jira).pdf)**:
**(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**

### *Test Condition Analysis, Test Design and Test Execution:* ###

<br>

The following test cases have been generated and executed based on the identified test conditions:

<br>

 #### 1. Check that a Data Confirmation banner with a link to the Data Confirmation form shows up at the bottom of the page for a parent who has not completed the confirmation process ####

<br>

![LIT 28_Test Condition_Bordered](https://github.com/user-attachments/assets/bcf17f59-3875-441e-825b-6dcc50bd3abb)

![LIT 28_Test Steps_Bordered](https://github.com/user-attachments/assets/a256ae4e-c933-41e1-a0b3-0513f2c8149a)

<br>

 #### 2. Check that the Data Confirmation banner is no longer displayed for parents who have completed the Data Confirmation process ####

<br>

![LIT 29_Test Condition_Bordered](https://github.com/user-attachments/assets/0d1b01a3-ac54-4ba9-9617-022f8aa24f89)

![LIT 29_Test Steps_Bordered](https://github.com/user-attachments/assets/6ff58500-1955-43c9-b7f3-9180d9b07a4c)

<br>

 #### 3. Check that the Data Confirmation form is read-only after the confirmation process has been completed ####

<br>

![LIT 30_Test Condition_Bordered](https://github.com/user-attachments/assets/53abc0a1-8521-439f-8c9c-6bbdd0a5023d)

![LIT 30_Test_Steps_Bordered](https://github.com/user-attachments/assets/533c565b-6bc3-44cb-8bf1-fa2649f018e0)

<br>

 #### 4. In the "Family Information" section check that an error is thrown if an option has not been selected for each one of the surveys and the next step can't be reached ####

<br>

![LIT 32_Test_Condition_Bordered](https://github.com/user-attachments/assets/005a0e00-45e8-48df-a4aa-38c0dc23e64d)

![LIT 32_Test_Steps_Bordered](https://github.com/user-attachments/assets/841405c6-b8d6-4a93-99e8-a5e7421a817f)

<br>

 #### 5. In the "Income" section check that, once the income has been submitted, a notification is displayed and no further changes can be made ####

<br>

![LIT 33_Test Condition_Bordered](https://github.com/user-attachments/assets/c6eb388d-c599-4055-bdb3-7587ecf6abd0)
 
![LIT 33_Test_Steps_Bordered](https://github.com/user-attachments/assets/2b3948c3-a23d-4edf-8707-f6f01a86b865)

<br>

 #### 6. In the "Income" section check that if an income is not selected a pop-up message is displayed to state that and ask for confirmation ####

<br>

![LIT 34_Test_Condition_Bordered](https://github.com/user-attachments/assets/5cdc106c-98e3-4379-b0b8-a42c9eb1a30d)

![LIT 34_Test_Steps_Bordered](https://github.com/user-attachments/assets/85fc6718-e9ef-4fe8-ae29-15fb234bb8a1)

<br>

 #### 7. In the "Income" section check that the income figures are recalculated for the low, medium and high intervals based on the number of household members selected ####

<br>

![LIT 35_Test Condition_Bordered](https://github.com/user-attachments/assets/695b3240-e99b-49bf-aede-a317b71ee33a)

![LIT 35_Test_Steps_Bordered](https://github.com/user-attachments/assets/d5643b54-c902-4373-8389-e914a5074097)

<br>

 #### 8. In the "Student" field check that a student mobile phone number can be added to the page ####

<br>

![LIT 36_Test_Condition_Bordered](https://github.com/user-attachments/assets/045cb163-73db-4bd2-b0f6-d854454211a7)

![LIT 36_Test_Steps_Bordered](https://github.com/user-attachments/assets/1f366be1-c6d7-4da0-8170-127e4c118184)

<br>
  

 #### 9. In the "Contacts" section check that existing contact information can be edited or deleted and new contacts can be added to the list ####

<br>

![LIT 38_Test Condition_Bordered](https://github.com/user-attachments/assets/fe1d60fe-e3b2-4f90-bebf-30ed97ed2ebd)

![LIT 38_Test_Steps_Bordered](https://github.com/user-attachments/assets/6fd5a489-0ba8-4bd5-bca2-830aa6b92c19)

<br>
  
 #### 10. In the "Medical History" section check that medical conditions can be assigned to the student or removed if they no longer apply ####

<br>

![LIT 39_Test Condition_Bordered](https://github.com/user-attachments/assets/30ab7532-89f8-4d8f-81a5-2a18dd7e8734)
  
![LIT 39_Test_Steps_Bordered](https://github.com/user-attachments/assets/201f4a7f-6a81-4051-b42e-126303e3cd4b)

<br>

 #### 11. In the "Authorizations" section check that an error message is displayed if an option is not selected for the mandatory items and that data is successfully saved upon providing the required answer ####

<br>

![LIT 41_Test Condition_Bordered](https://github.com/user-attachments/assets/484dcdda-24f8-42ad-ba59-c916bd74feca)

![LIT 41_1_Test_Steps_Bordered](https://github.com/user-attachments/assets/e621122f-f077-4833-b688-64a978c2efe6)
![LIT 41_2_Test_Steps_Bordered](https://github.com/user-attachments/assets/d4c4cdde-7aae-4e34-bcbb-d9968979b141)

<br>

 #### 12. In the "Documents" section check that an error message is displayed if the parent does not acknowledge required documents ####

<br>

![LIT 47_Test Condition_Bordered](https://github.com/user-attachments/assets/3e638ccf-f962-463a-8629-9736f07673df)

![LIT 47_Test_Steps_Bordered](https://github.com/user-attachments/assets/26d7aaba-97ba-43f2-a7d6-65f629736ed8)

<br>

 #### 13. In the "Final Data Confirmation" section check that the printed/saved Emergency card has a correct format and contains the information specified during the Confirmation process ####

<br>

![LIT 42_Test Condition_Bordered](https://github.com/user-attachments/assets/835828d2-93fd-4bc1-9aac-37e081e281f4)

![LIT 42_Test_Steps_Bordered](https://github.com/user-attachments/assets/a5d1218f-b2d7-4ae5-aa74-de802abab0ef)

<br>

 #### 14. Check that all required admin setups are in place for the Data Confirmation Process ####

<br>

![LIT 44_Test Condition_Bordered](https://github.com/user-attachments/assets/e6fb16af-73f3-4e69-a19a-27587e9e95ec)

![LIT 44_Test_Steps_Bordered](https://github.com/user-attachments/assets/6f689d61-67d4-4c36-9766-acb01542926f)

<br>

 #### 15. Check that a teacher logging in as an admin can emulate a parent performing the  Data Confirmation process ####

<br>

![LIT 45_Test Condition_Bordered](https://github.com/user-attachments/assets/9b0e15c7-fed6-4c3a-83dd-9bcc3f2f12da)

![LIT 45_Test_Steps_Bordered](https://github.com/user-attachments/assets/f4f230d1-4d8f-40b1-b048-91920a975494)

<br>

 #### 16. Check that a teacher logging in as an admin is able to restrict parent access to other portal tabs until the Data Confirmation process is completed ####

<br>

![LIT 46_Test Condition_Bordered](https://github.com/user-attachments/assets/fc84c666-377c-41ac-9ff1-925f8f0695c7)

![LIT 46_Test_Steps_Bordered](https://github.com/user-attachments/assets/fdcbf39e-36b7-4629-86c8-813707d6f336)


<br>

## *Bug Reports* ##

<br>

Following test execution, 3 bugs have been identified and a bug report was created for each of them:

<br>

###### Bug Report 1 ######
![Bug 1](https://github.com/user-attachments/assets/c9a92523-1094-4db9-89fc-ef7e156139cd)

<br>

###### Bug Report 2 ######
![Bug 2](https://github.com/user-attachments/assets/1b9996e4-14b9-41fa-8e70-f58386853f38)

<br>

###### Bug Report 3 ######
![Bug 3](https://github.com/user-attachments/assets/b94f95ec-323e-4aa3-b289-94956bed86eb)


<br>
<br>

## *Overall Status* ##

<br>

An overall status can be observed in this Jira dashboard PieChart:
![Bordered Jira PieChart Report](https://github.com/user-attachments/assets/3348f42f-05cb-4855-9490-bb8193a07fac)



<br>
<br>

## *Traceability Matrix* ##

<br>

The Traceability Matrix points to the story to which all three bugs are related, namely the "Student Data Confirmation Process as Parent":

<br>

![Bordered Traceability Matrix](https://github.com/user-attachments/assets/108e14c6-8771-439d-9dd9-76dda4759362)



<br>

## *Risk Matrix* ##

<br>

The Risk Matrix points to both Project and Products risks identified in relation to this specific functionality as well as during the overall use of the Demo Parent and Admin Portals:

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
