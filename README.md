# 🔗Attendance_Tracking_using_face_recognition 🖳

It’s a Python GUI (using tkinter library) integrated attendance system which  will be using face recognition for taking attendance.
    


- In this application , I have made an attendance system which will use face recognition for taking attendance. It's been integrated with GUI so that it can be easy for anyone to use it.It is using OpenCV for taking images and face recognition where in Haar cascade classifier alogorithm is used which is a machine learning detection program. 

- Basically this app is using a protected password students/employees which will be used for registration and then they will be able to mark their attendance everyday on their own.

- If the user is trying to mark attendance without being registered then it will pop up a error message showing that the person need to register first.So, the person get notified that getting registered is prerequisite in order to mark his/her attendance.

- The password which need to be entered will be protected and can only be changed if admin wants to change it through admin password check. On whole it is safe and comfortable to use.



## TECH USED :

   1. tkinter which is a standard GUI library for python.
   2. OpenCV for taking images and for face recognition where in Haar cascade  classifier algorithm  is used which is an object detection algorithm used to identify faces in this application.
   3. numpy , pandas, CSV, datetime ,pillow etc for making excels and displaying live clock on the window and etc.
## Install dependencies required to run the app :

First requirement is that 'python' should be installed 
and make sure pip is available along with it(generally it is included by default with the Python binary installers).
I have also included all these commands in the '*requirements.txt*'.

```bash
  pip install tk-tools
  pip install opencv-contrib-python
  pip install datetime
  pip install pytest-shutil
  pip install python-csv
  pip install numpy
  pip install pillow
  pip install pandas
  pip install times
```

After all these were done just run the **main.py** file to use the application.
-  For new registrations password - **TrainingImageLabel folder->psd.txt -> (1234)**                                                                   
-  For Admin password - **TrainingImageLabel folder->Admin.txt -> (D|vy@1234)**
 
 
## Features :
1. It’s interactive with GUI support, password is asked while a user is newly registering.
2. Takes images during registration for using face recognition further in attendance marking.
3. When a new user is registered, a CSV file(can be opened as a Excel spreadsheet) where in all the details entered will be as it is stored.
4. Before getting registered if the user tries to mark his/her attendance then it will pop up a message saying ‘Please complete your registration first!!!’ by which the person will be notified very quickly that he/she need to register without wasting memory.
5. While taking attendance it uses face recognition and displays recognised user name there below then after name appears ,user need to press 'y' in order to mark his/her attendance.
6. Live attendance is shown in a tabular form having id,name,date and time as columns just after taking attendance.
7. Simultaneously a CSV file(can be opened as Excel spreadsheet) will be created ‘every day’ where in the attendance for that day, having the users login time and their details.Hence will very easy to check attendance reports on whole for a week or a month as they were present date-wise.
8. If the attendance of the user has already been marked for that day then it pops up a message as "You have already marked your attendance for today" which saves more memory and makes the attendance reports more easy to handle.
9. 'Admin help centre' option is provided in menubar in case if the admin wants to change the protected password used for registrations then he/she need to enter admin password there and later can change the password.
10. ’Student help centre’ also provided where the students can get a mail id to contact the admin(teacher) which will be popped up when he/she choose to contact admin option.

## 🔗Demo :

For demo video, please follow the link below.


## Challenges faced and Lessons Learned :

- Basically I just know basic development and never did projects like this. So, it took more time for me to explore before doing project.But I found that development projects like this were more fun and I really enjoyed making this.
- When I came to know about tkinter library in python, I decided to make GUI app. And I am sure now that I have learnt something new which I didnot know all those days before.
- When I started developing the project, I had a lot of thoughts about what what features I need to add but then I continued to do the things that were possible in time and I have gained much confidence that I can do more projects like this in future.  
- The fun fact is that the readme files which I created before are lot different from this one and I came to know many techniques to write a readme file during this period. I am writing about this experience in readme file itself :)
- So with all these challenges and new learnings I am very grateful to this one month period.


## Future Scope of the project :

- In these days technology being improved day to day and we are able to see new things everyday. 
- What matters is that how long one application or a device being used.
- So in my opinion as long as education/employment persists the concept of tracking attendance will always have its value.
- The more simpler we make it for the users the more comfortable will be their work. So smart attendance tracking which uses the face recognition is a simple but still comfortable application one can use.
- There will be certainly more features that can be added anytime which will make this application much more comfortable to use and easy to manage.
