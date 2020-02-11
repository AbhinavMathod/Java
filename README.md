This is a java project executed in order to provide basic services to veterans who , for whatsoever reason are not able to avail these services. So, this project contains six organization in and between which service requests are raised by the user that is the veteran and resolved by the admins of each respective organizations. 
These organizations are 
MentalHealthCare 
PhysicalHealthCare
VocationalEducation
GraduateEducation
PermanentHousing
TemporaryHousing

The end user is a veteran or a guest who can register a veteran on their behalf.

How to execute the project?

1. Install and setup netbeans on your system.

2. File -> Open Project -> EZVeteran

3. You will find there are errors in the project. This error is due to a jar file we have used for implementing email. If you create a veteran login with your email you will receive emails of service requests raised by you. So, to resolve this error you will have to right click on the project name on the left tab in netbeans -> properties -> libraries -> Add jar folder -> Add the mail.jar file present in the folder downloaded-> ok -> Clean and build the project and the errors should be resolved.

4. Run the project 

5. The database used by us is DB4O. We have saved a few logins to save the trouble for you to create all admins and logins and because of this reason due to an exception you will not be able to access the admin page to create all the enterprise and organizational admins. The following are the usernames and passwords foreach admin : 

Mental healthcare admin login 
Username : mhc
Pwd : mhc

Physical healthcare admin login
Username : phc
Pwd : phc

Vocational Education admin login
Username : vs
Pwd : vs

Graduate Education admin login
Username : gs
Pwd : gs

Permanent Housing admin login
Username : ph
Pwd : ph

Temporary Housing admin login
Username : th
Pwd : th

Veteran login
Username : a
Pwd : a

6. If you want to access the admin and create all these admins from the scratch just delete the databank.Db4o file and clean and build and run the project again. 



