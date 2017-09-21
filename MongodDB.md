## Account Rep 
mark.szemplinski@mongodb.com


## Training
Directions for accessing MongoDB University on-demand. 

Steps to Access On-Demand Training

•	STEP 1 - Click the License Link: Please click https://university.mongodb.com/?next=/license/activate%3Fkey%3Dfab9c668-4b75-4957-8071-5e54b3a9ae62 to activate your training account.

•	STEP 2 - Create Your Account: Create your MongoDB University login account (you must enter a valid @stonybrookmedicine.edu email).

•	STEP 3 - Enroll in Courses: Go to the main page of MongoDB University and select the “On-Demand” Catalog. Here you will locate and enroll in your courses.

If you have any questions / issues, you can contact our team directly at OnDemand@MongoDB.com. 


## Ops Manager
Use UHMC login

http://uhmc-mongo-opsmgr01a.uhmc.sunysb.edu:8080


## Compass
W:\IT-HIS\Software\MongoDB\Mongo Compass


## Backup Policy
We will be following the hospital policy when it comes to backup’s. We will keep 30 days of backup’s and will be able to recover to a point in time for the last 7 days. If you  have any questions please let me now. Please make note of this and inform your staff.


## Connection String

From Linux
 
mongo -u rglaser -p --authenticationMechanism PLAIN --authenticationDatabase '$external' --ssl --sslAllowInvalidCertificates --host uhmc-mongod-dev01a.uhmc.sunysb.edu --port 27017
 
From Windows Command Line
 
mongo -u rglaser -p --authenticationMechanism PLAIN --authenticationDatabase $external --ssl --sslAllowInvalidCertificates --host uhmc-mongod-dev01a.uhmc.sunysb.edu --port 27017
 
From PowerShell
 
mongo -u rglaser -p --authenticationMechanism PLAIN --authenticationDatabase '$external' --ssl --sslAllowInvalidCertificates --host uhmc-mongod-dev01a.uhmc.sunysb.edu --port 27017
