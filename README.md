# Attendance_Management_System
Attendance Management System using Face Recognition

Problem Statement: Attendance Management System using Face Recognition

This project can be understood in 4 major steps:

1. First One, 'Add Students' module which adds a new student to the system. The image is captured through the WebCam. Image's Binary Data is sent from the web application FrontEnd architecture through the local server to the BackEnd architecture which is responsible for saving the image 
file in the ‘.jpeg’ format in the local directory (assets) 
where the application is residing. 
After that
all the images are loaded one by one from the assets folder and 
then their 128-d face encodings are determined through the OpenCV library of Python.

2. 'Take Attendance' module is mainly responsible for fulfilling the objectives of the project that is it receives the images from the webcam’s live server 
and then faces are detected using the different inbuilt algorithms of OpenCV and their 128-d encodings are then computed and the computed face encodings are then compared to the encodings stored in the Data Base which yields the student whose face is obtained by showing their roll number on their face And then the excel sheet is updated accordingly to the required Roll Number of the Identified Face with name of the student.

3. Trigger an email with attachement of attendance excel sheet of that day to the particular admin.

4. UI which shows features of the Attendance Management System Using FC(Face Recognition) - 'Take Attendance' , 'Add Students' and 'Send Email'.

5. Furthur exploring and doing some innovation overall.

Project Structure :- 


 Contains              
 >Assets : Images of the new students a/c to roll no/name captured for training the model 
 
 >Web : All the front end files like home page etc
 
 >attendance.py : Python code for establishing server and doing OpenCV work
 
 >requirements.txt : Requirements file for the project to run the application....




Usage/Steps to test ( CommandLine Commands ):- 

> Start the application 

python attendance.py (In Web Browser Mode)


>Registering new students with details then stop the application with Ctrl+C.

>For Attendance Verification and start the server by the command
python attendance.py and then Click On 'Take Attendance' Button.



PROJECT PLAN
Week1: Analysis and finalising the problem statement.
       Preparing a basic modal and deciding functionalities.
       Installation of required softwares and libraries.

Week2: Developing the UI
       Working on Dataset
       Coding and implementation

Week 3:Introducing new features and functionalities.(Innovation)
       Testing

       
                
 
