# Selenium-Jenkins
This project will guide you to run your selenium project with Jenkins, also explain you about installation of Jenkins(in case you are not aware of that)


Start by downloading Jenkins on your system 
The file can be found at jenkins.io/ . Download the war file. 

Try to open the file using command prompt with command java - jar jenkins.war (filename) : This would start the Jenkins server at port 8080

if you wish to host the server at some other serve, change the command to: 
java - jar jenkins.war --HTTPport9191

Get into Jenkins and create new file by giving it a name & selecting freestyle project from the list of project types. 

You will get a next page somewhat like settings, in order to have basic execution. We will go to build option and select Execute Windows Batch Command (if using Windows) and if you are on MAC OS, select Execute shell. 

Provide the command to run the selenium test 

Copy the project location and go to command line & try to exceute it through it.

Perform the same command instructions on desktop as well as Jenkins. 

