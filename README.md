# ExcelDVIRProject
Program for reading DVIR(Driver Vehicle Inspection Report) files

This program is written to read a folder of text files(DVIR's from truck drivers) and print the 
pertinant information from the text files out for viewing such as Driver Name, Truck and Trailer #, the problem
that has occured and the status of the repairs. This program is also tied with an email script that takes the 
emails that we recieve from the drivers and automatically converts the ones that have the field "Defect found?: Yes"
to a text file and stores it in the folder I chose on our companies shared drive. 

The program searches each individual file for certain words like "Driver name:" and stores that line of text in a colection. These collections are later trimmed of the original word searched for and printed out line by line on the worksheet. There is no minimum or maximum number of files you can have in this folder, it will just make a difference in how long the worksheet is. The longer the worksheet the harder it is to maintain. With this in mind when we are first rolling this out we will empty the folder completely and start with the trucks that get DVIR's from that point on so we can keep up on the list. This first worksheet is very important to keep up on because if things are not accurate on this worksheet the Truck-Trailer Evaluation worksheet will also be inaccurate. We need to keep accurate data so it makes sense for every truck and trailer in use. 

The spreadsheet has user functionality as it will allow the user to select if the request is Pending, In Shop, Not in Yard, or Completed. Once In Shop is selected in the status field, it writed "Status: In The Shop" to the correct text file. Once it is completed it adds "Status: Complete" with a timestamp of the current time to the file. This completed file is then added to a folder with all of the completed DVIR's and it gets deleted from the folder that has all of the requests in it. Our shop will be using this to keep records of all of our DVIR's for every truck and trailer, and makes the proccess of completing the DVIR's go smoother.

Download the program, enable the macros, and change the folder location in Module 1 of the VBA code to match whichever folder you want the files to be read from. Download the example files and place them in that folder. You are ready to go!

This program will continually need updating and maintenance. Our team is working to make this easier to read and more user firendly. Stay tuned for updates and future rollouts. There will be upgrades in the near future. We are still developing this second spreadsheet, and hope to be fully integrated to this new way of doing things in the coming weeks. There will possibly be more user functionality in the future where the user will be able to change the priority of each DVIR. Also the programming is continually being modified and shortened to make it run more efficiently. There are a lot of If...Then... statements used, and we are working on a way to reduce that code. 

If you run this program and run into issues feel free to contact me with comments and concernt.

Any questions contact cvaughan@stewarttransport.com
