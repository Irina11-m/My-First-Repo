**Testing Project for Demo Application Aeries **

Aeries is a Student Data Management System for California and Texas designed to facilitate day to day school matters for students, parent and teachers.

Specific function under test: Aeries Student Data Confirmation Process  
Background: The Confirmation process is a re-enrollment activity that happens at the start of each year and which is done via a Confirmation form that Parents must complete via the Parent Portal

Testing Environments: Aeries Demo Parent Portal and Aeries Demo Admin Portal

Tools used: Jira, Zephyr Squad.


Functional specifications:

The two below stories were created in Jira to cover the Data Confirmation process from both a Parent and a Teacher perspective:
![image](https://github.com/user-attachments/assets/79b778da-50b0-4fa3-b3e3-055e65419270)

![image](https://github.com/user-attachments/assets/70b15e12-c843-4ced-a23c-8350ebadbb32)

Testing Process:

In total 16 test cases have been executed and 3 bugs have been identified for which a bug report was created:

![Jira PieChart Report](https://github.com/user-attachments/assets/a8cbaf5d-a3cd-4d61-8d4d-4a7f6d92d50e)



The Traceability Matrix points to the story to which all three bugs are related, namely the "Student Data Confirmation Process as Parent"

![Traceability Matrix](https://github.com/user-attachments/assets/22437061-c7a2-46e9-86aa-59c7d705af1f)



The Risk Matrix points to both Project and Products risks identified in relation to this specific functionality as well as during the overall use of the Demo Parent and Admin Portals

![image](https://github.com/user-attachments/assets/9501b290-cf71-42d4-bb95-043fd715213d)


The three bugs found during testing significantly affect the data confirmatiion process, since parents can't input contact information for the student nor does the form remain read-only upon submission.
