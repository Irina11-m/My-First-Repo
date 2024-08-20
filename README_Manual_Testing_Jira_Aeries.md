# Testing Project for Demo Application Aeries #

<br>

___Short Description of the Tool and Functionality Under Test___

<br>

Aeries is a Student Data Management System for California and Texas designed to facilitate day to day school matters for students, parents and teachers, who can access school data via separate portals.  

Testing is focused on the Aeries Student Data Confirmation Process, a re-enrollment activity happening at the start of each school year and which is done via a Confirmation form that Parents must complete via the Parent Portal.

The Testing Environments used for this process are the Aeries Demo Parent Portal and Aeries Demo Admin Portal

The Tools used for managing the testing process are Jira and Zephyr Squad

<br>

___Functional Specifications:___

<br>

The two stories below were created in Jira to cover the Data Confirmation process from both a Parent and a Teacher perspective:

<br>

![Story 1](https://github.com/user-attachments/assets/1ef5e73d-3842-4b02-9d95-6268772aa790)


<br>

![Story 2](https://github.com/user-attachments/assets/7485e107-c832-4e0a-9b25-7649ab2e861e)

<br>
<br>

___Testing Process:___

<br>

Testing was performed based on the following test conditions:

<br>


* Check that a Data Confirmation banner with a link to the Data Confirmation form shows up at the bottom of the page for a parent who has not completed the confirmation process    
![LIT 28_Test Steps_Bordered](https://github.com/user-attachments/assets/a256ae4e-c933-41e1-a0b3-0513f2c8149a)

<br>

* Check that the Data Confirmation banner is no longer displayed for parents who have completed the Data Confirmation process
![LIT 29_Test Steps_Bordered](https://github.com/user-attachments/assets/6ff58500-1955-43c9-b7f3-9180d9b07a4c)

<br>

* Check that the Data Confirmation form is read-only after the confirmation process has been completed
![LIT 30_Test_Steps_Bordered](https://github.com/user-attachments/assets/533c565b-6bc3-44cb-8bf1-fa2649f018e0)

<br>

* In the "Family Information" section check that an error is thrown if an option has not been selected for each one of the surveys and the next step can't be reached
![LIT 32_Test_Steps_Bordered](https://github.com/user-attachments/assets/841405c6-b8d6-4a93-99e8-a5e7421a817f)

<br>

* In the "Income" section check that, once the income has been submitted, a notification is displayed and no further changes can be made
![LIT 33_Test_Steps_Bordered](https://github.com/user-attachments/assets/2b3948c3-a23d-4edf-8707-f6f01a86b865)

<br>

* In the "Income" section check that if an income is not selected a pop-up message is displayed to state that and ask for confirmation
![LIT 34_Test_Steps_Bordered](https://github.com/user-attachments/assets/85fc6718-e9ef-4fe8-ae29-15fb234bb8a1)

<br>

* In the "Income" section check that the income figures are recalculated for the low, medium and high intervals based on the number of household members selected
![LIT 35_Test_Steps_Bordered](https://github.com/user-attachments/assets/d5643b54-c902-4373-8389-e914a5074097)

<br>

* In the "Student" field check that a student mobile phone number can be added to the page
![LIT 36_Test_Steps_Bordered](https://github.com/user-attachments/assets/1f366be1-c6d7-4da0-8170-127e4c118184)

<br>
  

* In the "Contacts" section check that existing contact information can be edited or deleted and new contacts can be added to the list
![LIT 38_Test_Steps_Bordered](https://github.com/user-attachments/assets/6fd5a489-0ba8-4bd5-bca2-830aa6b92c19)

<br>
  
* In the "Medical History" section check that medical conditions can be assigned to the student or removed if they no longer apply
![LIT 39_Test_Steps_Bordered](https://github.com/user-attachments/assets/201f4a7f-6a81-4051-b42e-126303e3cd4b)

<br>

* In the "Authorizations" section check that an error message is displayed if an option is not selected for the mandatory items and that data is successfully saved upon providing the required answer
![LIT 41_1_Test_Steps_Bordered](https://github.com/user-attachments/assets/e621122f-f077-4833-b688-64a978c2efe6)
![LIT 41_2_Test_Steps_Bordered](https://github.com/user-attachments/assets/d4c4cdde-7aae-4e34-bcbb-d9968979b141)

<br>

* In the "Documents" section check that an error message is displayed if the parent does not acknowledge required documents
![LIT 47_Test_Steps_Bordered](https://github.com/user-attachments/assets/26d7aaba-97ba-43f2-a7d6-65f629736ed8)

<br>

* In the "Final Data Confirmation" section check that the printed/saved Emergency card has a correct format and contains the information specified during the Confirmation process
![LIT 42_Test_Steps_Bordered](https://github.com/user-attachments/assets/a5d1218f-b2d7-4ae5-aa74-de802abab0ef)

<br>

* Check that all required admin setups are in place for the Data Confirmation Process
![LIT 44_Test_Steps_Bordered](https://github.com/user-attachments/assets/6f689d61-67d4-4c36-9766-acb01542926f)

* Check that a teacher logging in as an admin can emulate a parent performing the  Data Confirmation process
![LIT 45_Test_Steps_Bordered](https://github.com/user-attachments/assets/f4f230d1-4d8f-40b1-b048-91920a975494)

<br>

* Check that a teacher logging in as an admin is able to restrict parent access to other portal tabs until the Data Confirmation process is completed
![LIT 46_Test_Steps_Bordered](https://github.com/user-attachments/assets/fdcbf39e-36b7-4629-86c8-813707d6f336)



<br>

Following test execution, 3 bugs have been identified and a bug report was created for each of them:


###### Bug Report 1 ######
![Bug 1](https://github.com/user-attachments/assets/c9a92523-1094-4db9-89fc-ef7e156139cd)



###### Bug Report 2 ######
![Bug 2](https://github.com/user-attachments/assets/1b9996e4-14b9-41fa-8e70-f58386853f38)



###### Bug Report 3 ######
![Bug 3](https://github.com/user-attachments/assets/b94f95ec-323e-4aa3-b289-94956bed86eb)


<br>

___Overall Status___

An overall status can be observed in this Jira dashboard PieChart:
![Bordered Jira PieChart Report](https://github.com/user-attachments/assets/3348f42f-05cb-4855-9490-bb8193a07fac)



<br>

___Traceability Matrix___

The Traceability Matrix points to the story to which all three bugs are related, namely the "Student Data Confirmation Process as Parent"

![Bordered Traceability Matrix](https://github.com/user-attachments/assets/108e14c6-8771-439d-9dd9-76dda4759362)



<br>

___Risk Matrix___

The Risk Matrix points to both Project and Products risks identified in relation to this specific functionality as well as during the overall use of the Demo Parent and Admin Portals:

<br>

![image](https://github.com/user-attachments/assets/bfc8878c-dd1c-4ad7-9eb7-051b5cfe449c)

<br>

___Final Testing Conclusions___

As part of this testing process, the functionality in scope for testing was the "Data Confirmation" form, whose analysis was divided into two stories, namely the "Data Confirmation Process as a Parent" and the "Data Confirmation Process as a Teacher/Admin".
The environment used for testing is a demo application, which both parents and teacher can use to familiarize themselves with how the process works.

In total, 16 tests have been executed which cover both stories and 3 bugs have been identified and reported.

The identified bugs are quite severe, since they affect a parent's ability to input and change data that is crucial for the wellbeing and security of the child, namely adding contact information for the student, including student's phone number and updating the list of contacts who afre authorized to act in the benefit of the student. Moreover, the submitted data can be temporarily edited, and although, upon page refresh the intially submitted data is kept, this can create confusion and further distrust in the overall confirmation process.

From a teacher's perspective, no actual bugs have been discovered, since the teachers can perform the setup for the "Confirmation" process, can block a parent from having access to other portal tabs until they finish submitting the "Confirmation"form and they can emulate a parent during the "Confirmation" process.

Therefore, the three bugs are critical and must be prioritized for fixing and re-testimng and a subsequent regression testing must be done for the entire "Confirmation" process to ensure that no other defects have been as part of the fix applied to the system.
