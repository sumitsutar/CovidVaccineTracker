# CovidVaccineTracker
Just thought of making a single page application which can be run from any machine without having to install any additional software.
 It will display real-time Vaccine Availability on Selected pincodes as well as other nearby pincodes.

Please note - this provide very limited functionality. I just developed it to help people find vaccines more easily.

All you have to do is - 

Step 1 : 
Choose District. It shall show you the list pincodes where the vaccines are currently available in that district.

Step 2 : 
Enter Comma Separated list of pincodes that is closest to your location. 

Step 3 : 
Hit Start tracking button. It should start fetching the data from Cowin website every 5 seconds. and the table will get reflected in real-time.

 
Limitation - 

There are only 100 api calls that are allowed from a single IP address (device) in 5 minute window. Once that limit is exhausted you will have to wait for 5 minutes and try again. 
