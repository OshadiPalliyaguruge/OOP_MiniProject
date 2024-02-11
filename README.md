## Hospital Management and Telemedicine System

### Mini Project: Object-Oriented Programming (Console-based project)


This project aims to create a comprehensive hospital management and telemedicine system using object-oriented programming principles in C++. It consists of two main modules: one for users (patients) and the other for administrators (hospital staff), each designed to fulfill specific functionalities.

<div align='center'>
    <img src="https://github.com/OshadiPalliyaguruge/OOP_MiniProject/blob/master/Images/login%20screen.jpg" width="500" align="center">
</div>

There are two operation modes. You can choose the operation mode as education mode or regular mode.
<div align='center'>
    <img src="https://github.com/OshadiPalliyaguruge/OOP_MiniProject/blob/master/Images/operation%20mode.jpg" width="500" align="center">
</div>

### Class Diagram

<div align='center'>
    <img src="https://github.com/OshadiPalliyaguruge/OOP_MiniProject/blob/master/Images/diagram.jpg" width="500" align="center">
</div>



#### User Module
•	As a user, individuals can access various subcategories such as patient appointments, telemedicine services, hospital details, dispensary information, medicine records, payment options, and logout functionalities.
•	Upon selecting a subcategory, users can provide the necessary information and proceed with the desired task, facilitating seamless interaction with the system.


<div align='center'>
    <img src="https://github.com/OshadiPalliyaguruge/OOP_MiniProject/blob/master/Images/user%20menu.jpg" width="500" align="center">
</div>


#### Admin Module
•	Administrators have access to a range of subcategories including doctor information, staff details, patient records, emergency protocols, hospital specifics, dispensary management, medicine inventory, password settings, and logout functionalities.
•	By selecting a subcategory, administrators can efficiently manage hospital operations, oversee patient care, and ensure smooth functioning of the system.

##### Enter the password to go to admin menu
<div align='center'>
    <img src="https://github.com/OshadiPalliyaguruge/OOP_MiniProject/blob/master/Images/admin%20menu1.jpg" width="500" align="center">
</div>


<div align='center'>
    <img src="https://github.com/OshadiPalliyaguruge/OOP_MiniProject/blob/master/Images/admin%20menu2.jpg" width="500" align="center">
</div>


### Structure of a Class

   • Variables/Attributes

   • Constructor

   • Member functions

   • Destructor


#### Base Class (Parent Class)
1. UserInfo
2. PatientInfo
3. Hospital
4. Dispensary


#### Derived Classes (Child Class)
1. StaffInfo (Child class of UserInfo)
2. DocInfo (Child class of UserInfo)
3. PatientAppointment (Child class of PatientInfo)
4. Telemedicine (Child class of PatientInfo)
5. EmergencyPatient (Child class of PatientInfo)
6. AdmittedPatient (Child class of PatientInfo)
7. EGuardientInfo (Child class of PatientInfo)
8. AGuardientInfo (Child class of PatientInfo)
9. Payment (Child class of Hospital)
