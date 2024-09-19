# Hospital Management System

## Steps to configure this HMS web-application on your system:

1. To import this project to your system, you need to first install below softwares: 
   - Eclipse for Java EE Developers and Tomcat server. You can refer this video: https://youtu.be/9iHKCnxUWqQ
   - MySQL Workbench. You can refer this video: https://youtu.be/OM4aZJW_Ojs

2. Then get the code from this GitHub repository on your system. You can clone this repository or download as zip file.

3. Choose 'import existing maven project' option in eclipse. 
<br> You can search for those steps online, just search 'how to import existing maven project in eclipse'. 

<br> If you want to add more users just login as admin and choose 'add employee' option and fill all the details. It will create new employee with his own login credentials. The Aadhar no. will be the default password and Empid will be the username.

## Technologies Used-

### 1. Front end Technologies:
  - HTML
  - CSS
  - Bootstrap
  - JavaScript
  
### 2. Back end Technologies:
  - SpringMVC 
  - Hibernate
  
### 3. Database:
  - MySQL
  
### 4. Project management tool:
  - Maven
  
### 5. Webserver:
  - Apache Tomcat
  

## Issues that proposed system overcomes-
   - It is digital system rather than paper based.
   - Inappropriate data keeping (receptionist used register for patients entry and doctor used prescription pad).
   - Time wastage in data storage and retrieval.
   - Human error possibility in maintainance.
   - Patient's were unable to understand prescriptions due to handwriting issue.
   - Durability issues (data may lost if prescriptions goes missing).


## Features-
  1. Doctor module:
      - Seperate accounts for doctors
      - Each patients previous visits history is easily to access.
      - Doctor can generate prescription and it will be automatically sent to receptionist.
      - Doctor can remove patient from OPD queue.
      
  2. Receptionist module:
      - Register/add new patient's info.
      - Modify patients personal details
      - Search existing patient by name/ mobile no./ PID/ aadhar no.
      - Remove patient from OPD queue.
      - Take print of prescriptions.
      
  3. Administrator module:
      - Add new employee for following roles,
                      i) Doctor
                     ii) Receptionist
                    iii) Admin (another one)
      - Remove/edit existing employee. 
      - Displays currently active employees in system.
      
  4. Password Encryption:
      - *_Bcrypt Encoding_* is used for password encryption. Bcrypt is a password hashing function designed by Niels Provos and David Mazières. It is based on the Blowfish cipher. Bcrypt uses adaptive hash algorithm to store password. BCrypt internally generates a random salt while encoding passwords and hence it is obvious to get different encoded results for the same string. But one common thing is that everytime it generates a String of length 60.


### Thank You !
