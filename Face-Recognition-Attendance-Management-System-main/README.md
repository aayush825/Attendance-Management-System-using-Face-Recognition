# Face-Recognition-Attendance-Management-System-using Python and OpenCV
Python 3.10

An Attendance Management System in which there are features of Entry, Exit, View Attendance, and Generate Database using Face Recognition.

Face Recognition
================
Recognize and manipulate faces from Python or the command line with the world's simplest face recognition library.
Built using `dlib <http://dlib.net/>`__'s state-of-the-art face recognition
This also provides a simple "face_recognition" command-line tool that lets you do face recognition on a folder of images from the command line!

Features
--------
Mark the Attendance according to the time gap between the entry and exit phase, using face recognition features that are updated in the database.

 What steps do you have to follow??
------------------------------------

- Download or clone my Repository to your device.
- type pip installs -r requirements.txt in command prompt(this will install the required package for the project).
- Create a Training_Images folder in a project folder.
- open main.py change all the paths according to your system.
- Run main.py file.


 Project flow & explanation
--------------------------------
- After you run the project a window will pop up and you will see 4 buttons(Entry, Exit, Mark Attendance, and Generate Database) in it.
- Firstly you have to register your face so that system can identify you, so click on Generate Database Button.
- After you click Generate Database Button, a small Camera window will pop up in that you have will have to write your name and then click Update Button, then it will take your image.
- After that your image will be registered and displayed in Traing Images Folder. 
- Now, click the Entry Button then, a camera window will pop up and it will detect your Face. After that your entry will be marked.
- To close the camera window click "Q".
- Then you have to click on Exit Button ater 1 min(or we can change the time limit accoring to our privilege).
- After clicking Exit Button, camera window will pop up and it will detect your Face, and your exit will be marked.
- Again, to close the camera window click "Q".
- After Exit, your attendance will be marked.
- You can view the attendance by clicking View Attendance button. It will show record in the csv file.
- And accordindly the csv files will be generated of specific dates.

Screenshots
-----------

## Simple UI
![GUI](https://user-images.githubusercontent.com/78672930/170862376-a92b5f76-21bb-47ca-812e-0ea4599b595d.PNG)

## While Taking Image
![1](https://user-images.githubusercontent.com/78672930/170864393-470d3273-7e75-4165-b662-05c097a0a087.PNG)

## While making Entry/Exit
![2](https://user-images.githubusercontent.com/78672930/170864408-517cec72-a215-43a3-be08-c9ba6d79d7e7.PNG)

## Marking Attendance
![3](https://user-images.githubusercontent.com/78672930/170864495-b5ccad1d-8af1-47ca-88c6-4cd4022a896a.PNG)

## Timings of Entry and Exit
![4](https://user-images.githubusercontent.com/78672930/170864995-26bd6866-f345-460b-9bb0-4fc18fcaccc4.PNG)
![5](https://user-images.githubusercontent.com/78672930/170865050-6f458a26-9b1a-4e1a-960d-097c00e23c3d.PNG)
