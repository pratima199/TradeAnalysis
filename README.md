# TAS : Trade Analysis System
## Technical Details :
### Database
      Used H2 InMomery Database.
      Can be enabled/disabled from properties file. On Disabling no code changes required to use persistant db

### Application Details

Application will run on port 8000. this can be change from propeties file

end point : localhost:8000/
Data to be uploaded from Resouces folder
### API Details

url : localhost:8000/uploadTradeData, 
Type : POST
body : {"filepath" : ""}

url : localhost:8000/allTrade, 
Type : GET

url : localhost:8000/getFrontOffice, 
Type : GET

url : localhost:8000/getByCustomerID/{customerId}, 
Type : GET

url : localhost:8000/getIntraDayForShare/{id}, 
Type : GET

### How to Run :
Clone and Extract TAS folder
Make sure to have spring and maven setup in your machine.
use "mvn clean install"
for skip test "mvn clean install -DskipTests"
run the "Application.java" file

try : localhost:8000 with valid endoints.
