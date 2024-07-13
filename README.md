# FaceRec_Attendance

Attendance Management System based on Face Recognition using Python and OpenCV

Code Requirements
Opencv(pip install opencv-python)
Tkinter(Available in python)
PIL (pip install Pillow)
Pandas(pip install pandas)
Steps to follow
Download my Repository
Create a TrainingImage folder in a project.
Open a AMS_Run.py and change the all paths with your system path
Run AMS_Run.py.
Working of this project
After running, you need to enter your ID and name in box than click on Take Images button.
It will collect ~70 images of your faces and save them in TrainingImage folder
After that we need to train a model(to train, click on Train Image button.)
It will take around 10 seconds for each person's image to train.
After training click on Automatic Attendance ,it fills attendance by recognizing your face using the trained model (model will be saved in TrainingImageLabel )
it will create .csv file of attendance according to time & subject.
You can store data in database (install wampserver),change the DB name according to your in AMS_Run.py.
Manually Fill Attendance Button in UI is to fill attendance manually(without face recognition),it creates a .csv and stores in a database.
Screenshots

Homepage

![homepage](https://github.com/user-attachments/assets/610fc171-5a20-4a7a-be6d-08c41cd5a636)


GUI


![GUI](https://github.com/user-attachments/assets/fb9c4c97-3b57-4b8c-bc68-fc64cac85289)


Checking students list

![StudentList](https://github.com/user-attachments/assets/81ca964d-0d43-46fe-86ea-34f416477d19)


Model Trained message

![trainedPopup](https://github.com/user-attachments/assets/178f8f52-6932-44f4-af5b-8c33458a6df4)


Note:
It requires high processing power(I have 8 GB RAM)
Noisy image can reduce the accuracy.
