**Testing Project for Demo Application Aeries **

Aeries is a Student Data Management System for California and Texas designed to facilitate day to day school matters for students, parents and teachers.

Specific function under test: Aeries Student Data Confirmation Process  
Background: The Confirmation process is a re-enrollment activity that happens at the start of each year and which is done via a Confirmation form that Parents must complete via the Parent Portal

Testing Environments: Aeries Demo Parent Portal and Aeries Demo Admin Portal

Tools used: Jira, Zephyr Squad.


Functional specifications:

The two below stories were created in Jira to cover the Data Confirmation process from both a Parent and a Teacher perspective:
![image](https://github.com/user-attachments/assets/79b778da-50b0-4fa3-b3e3-055e65419270)

![image](https://github.com/user-attachments/assets/70b15e12-c843-4ced-a23c-8350ebadbb32)

Testing Process:

The following test conditions have been set for testing the "Data Confirmation" form and these tests have been performed as part of the Cycle Summary "Aeries_Data_Confirmation_Tests":

Check that a Data Confirmation banner with a link to the Data Confirmation form shows up at the bottom of the page for a parent who has not completed the confirmation process
Check that the Data Confirmation banner is no longer displayed for parents who have completed the Data Confirmation process
Check that the Data Confirmation form is read-only after the confirmation process has been completed
In the "Family Information" section check that an error is thrown if an option has not been selected for each one of the surveys and the next step can't be reached
In the "Income" section check that, once the income has been submitted, a notification is displayed and no further changes can be made
In the "Income" section check that if an income is not selected a pop-up message is displayed to state that and ask for confirmation
In the "Income" section check that the income figures are recalculated for the low, medium and high intervals based on the number of household members selected
In the "Student" field check that a student mobile phone number can be added to the page
In the "Contacts" section check that existing contact information can be edited or deleted and new contacts can be added to the list
In the "Medical History" section check that medical conditions can be assigned to the student or removed if they no longer apply
In the "Authorizations" section check that an error message is displayed if an option is not selected for the mandatory items and that data is successfully saved upon providing the required answer
In the "Documents" section check that an error message is displayed if the parent does not acknowledge required documents
In the "Final Data Confirmation" section check that the printed/saved Emergency card has a correct format and contains the information specified during the Confirmation process
Check that all required admin setups are in place for the Data Confirmation Process
Check that a teacher logging in as an admin can emulate a parent performing the  Data Confirmation process
Check that a teacher logging in as an admin is able to restrict parent access to other portal tabs until the Data Confirmation process is completed

Following test execution, 3 bugs have been identified and for each a bug report was created:

![LIT-37 - Bug](https://github.com/user-attachments/assets/ae615988-cfda-4dc4-adc3-f7e04baaa219)
![LIT-40- Bug](https://github.com/user-attachments/assets/34c08475-4110-4f38-aa29-ef46ad7fc0a8)
![LIT-31 - Bug](https://github.com/user-attachments/assets/0cb1d1de-e63c-4e8d-b746-b67b7d966e7d)


An overall status can be observed in this Jira dashboard PieChart:
![Jira PieChart Report](https://github.com/user-attachments/assets/a8cbaf5d-a3cd-4d61-8d4d-4a7f6d92d50e)


The Traceability Matrix points to the story to which all three bugs are related, namely the "Student Data Confirmation Process as Parent"

![Traceability Matrix](https://github.com/user-attachments/assets/22437061-c7a2-46e9-86aa-59c7d705af1f)


The Risk Matrix points to both Project and Products risks identified in relation to this specific functionality as well as during the overall use of the Demo Parent and Admin Portals:

![image](https://github.com/user-attachments/assets/bfc8878c-dd1c-4ad7-9eb7-051b5cfe449c)




The three bugs found during testing significantly affect the data confirmation process, since parents can't input contact information for the student nor does the form remain read-only upon submission.
