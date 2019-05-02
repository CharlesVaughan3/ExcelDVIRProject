# ExcelDVIRProject
Program for reading DVIR(Driver Vehicle Inspection Report) files

This program is written to read a folder of text files(DVIR's from truck drivers) and print the 
pertinant information from the text files out for viewing such as Driver Name, Truck and Trailer #, the problem
that has occured and the status of the repairs. This program is also tied with an email script that takes the 
emails that we recieve from the drivers and automatically converts the ones that have the field "Defect found?: Yes"
to a text file and stores it in the folder I chose on our companies shared drive. 

The spreadsheet has user functionality as it will allow the user to select if the request is Pending, In Shop, or Completed.
Once In Shop is selected in the status field, it writed "Status: In shop" to the correct text file. Once it is completed it 
adds "Status: Complete" with a timestamp of the current time to the file. This completed file is then added to a folder with all of the 
completed DVIR's and it gets deleted from the folder that has all of the requests in it. We will be using this to keep records of all of
our DVIR's for every truck and trailer, and makes the proccess of completing the DVIR's go smoother.

Any questions contact  cvaughan@stewarttransport.com
