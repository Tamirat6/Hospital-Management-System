
                               Description 
The Hospital Management System (HMS) is a software application designed to improve the 
management of hospital activities by organizing patient registration, doctor information, 
appointment scheduling, medical records, and billing. The system will allow authorized hospital 
staff to manage patient information, doctors to access relevant patient records, and 
administrators to oversee hospital operations. The main objective of the project is to reduce 
paperwork, improve the accuracy and accessibility of information, save time, and make hospital 
services more efficient. The system will be designed using UML diagrams, developed using Java, 
managed collaboratively through Git and GitHub, and tested using JUnit.x 
 
                               Actors 
                                            Admin 
                                           Receptionist 
                                           Doctor 
                                           Patient 
                                           Cashier 
                          UML diagram 
A. Use Case Diagram 
Example:  
.Admin → Manage Users  
.Receptionist → Register Patient  
.Receptionist → Book Appointment  
.Doctor → View Patient Records  
.Doctor → Update Medical Record  
.Cashier → Process Payment  
.Patient → Request Appointment 
B. Activity Diagram 
Example: patient Registration 
.Start  
.  Enter patient information  
.  Validate information  
.  Is the information valid?  
.  If yes, save patient information.  
.  If no, display an error.  
.  End 
 
 
 
                                         C.Sequence Diagram 
           Example: patient Registration 
                      Receptionist → PatientForm → PatientController → Patient → Database 
                                                         D:Class Diagram 
                                                             .User  
                                                             .  Admin  
                                                             .  Doctor  
                                                             .  Patient  
                                                             .  Receptionist  
                                                             .  Appointment  
                                                             .  MedicalRecord  
                                                             .  Bill  
                                                             .  Payment 
 
 
 
 
 
 
## Group Members

| No. | Name | ID | Email | GitHub Link |
|---|---|---|---|---|
| 1 | Tamirat Semagn | 0621/17 | arsenal.t2026@gmail.com | https://github.com/Tamirat6 |
| 2 | Selamawit Kindye | 0581/17 |  |  |
| 3 | Mulat Berihun | 0482/17 |  |  |
| 4 | Alehegn Biset | 0865/17 |  |  |
| 5 | Solomon Tilahun | 0610/17 |  |  |
| 6 | Nardos Getahun | 1741/17 |  |  |






