# JenkinsDevOpsCA
/*
Aim is to get you to use Jenkins on your local machine by implementing a simple pipeline.

Install Jenkins by downloading the stable WAR release
run using java -jar jenkins.war
a first password is automatically generated it is available on the terminal output or in ~\.jenkins\secrets\initialAdminPassword
Browse to http://localhost:8080
Possibly setup proxy if asked
Install the suggested Plug-Ins
Setup an admin user as asked
in Global Tool Configuration setup path to your JDK

Checkout the Example
The example for this project is located at: https://github.com/echancrure/studentAttendance it is made up of a single java class and a JUnit4 test file. 
Create a Java project using whatever IDE you wish (e.g. Eclipse, IntelliJ) using these two files.
Ensure you can compile and run the tests (note that some of test fail but leave the code as-is for now).
Put your project under version control and check it in using a configuration management service (such as Github).
Create a Pipeline
Step 1 Create a pipeline that:
fetches the project from your remote repository
builds your project
[2 Marks, deliverables:  Jenkins file, screenshot of pipeline]
Step 2 Complement  your pipeline by:
adding a testing stage using a JUnit task using the tests provided
[1 Marks, deliverables: Jenkins file, screenshot of pipeline]
Step 3 Fix the code:
fix the code to ensure the tests provide pass given that the specification of getAttendanceGrade method is:
Student class attendance is graded according to the following table:
Attendance Percentage
Grade
0
absent
<30
very poor
<70
average
<90
good
>= 90
very good

An exception should be raised whenever the attendance percentage is below 0 or greater than 100.
 [2 Marks, deliverable: updated Student class, screenshot of pipeline]
Give me commenting rights (do not send me the link) to your single Google Docs file containing your steps:
your document needs to be highly readable;
add your name and date to it;
make sure the screenshots are cropped to the relevant text so that it is actually readable.
 


*/