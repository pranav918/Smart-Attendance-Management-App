# Smart Attendance Management Application

## TOPIC DESCRIPTION
This software is an Attendance Management System for schools & colleges. Basic idea behind the project is to ease the process of marking the attendance by the lecturer. 
More specifically, this system will be designed to help the lecturer mark the attendance using the latest technologies like Machine Learning (ML), Computer Vision. The system      also contains a database containing the data of the student.

## RELEVANCE OF TOPIC
Any organization, either large or small, requires an attendance tracking system for effective maintenance of projects and tasks. It is essential for the management to have records of the time and attendance of each student to handle discrepancies and variations within the organization. In today’s competitive world, each and every technology has drastic improvements when automated. Since, manual attendance tracking is a tedious and inefficient process for a group of students, the smart attendance management system with face recognition capabilities takes a huge leap in this scenario.
Automatic Facial Recognition is a competent biometrics technology that is used in human machine interaction, security systems, and image processing techniques. Smart attendance system with a modern face recognition system is a real-time solution to handle students with their day-to-day activities and can be used to detect human faces automatically by capturing the current date, time, and location.

## THE SOLUTION
The Smart Attendance Management System has four active actors and one cooperating system. The Student, whose attendance is to be taken, the Lecturer, who will take attendance. The Admin will have access to the whole system directly.
The Smart Attendance Management System first scans image of student through camera. This image is processed, and it is checked whether the student has already registered or not, if not then information like mobile number, address, roll number, PRN number is asked. This information gets stored in the NoSQL database and retrieved when required. Hence analyzing images with the help of machine learning recognizes the person accurately.

## FLOW DIAGRAM

<p align="center">
<img src="https://github.com/Aniruddha004/Smart_Attendance_Management_App/blob/master/images/Flow%20Diagram.png" height="400">
</p>

## DATABASE STRUCTURE
<p align="center">
<img src="https://github.com/Aniruddha004/Smart_Attendance_Management_App/blob/master/images/Database%20Structure.png" height="400">
</p>

## MACHINE LEARNING MODEL DETAILS
Face Recognition Model : [Click Here](https://drive.google.com/file/d/1EJnMNjI4fCBkewhpUShoGx9uZNw9uIQ7/view?usp=sharing) <br/>
Training Model Notebook: [Click Here](https://www.kaggle.com/omkaramilkanthwar/face-model)

# SCREENSHOTS
<img src="https://github.com/Aniruddha004/Smart_Attendance_Management_App/blob/master/images/login_dark.jpg" height="270">   <img src="https://github.com/Aniruddha004/Smart_Attendance_Management_App/blob/master/images/login_light.jpg" height="270">   <img src="https://github.com/Aniruddha004/Smart_Attendance_Management_App/blob/master/images/signup_dark.jpg" height="270">    <img src="https://github.com/Aniruddha004/Smart_Attendance_Management_App/blob/master/images/signup_light.jpg" height="270">  <img src="https://github.com/Aniruddha004/Smart_Attendance_Management_App/blob/master/images/a_dark.jpg" height="270">  <img src="https://github.com/Aniruddha004/Smart_Attendance_Management_App/blob/master/images/a_light.jpg" height="270"> &nbsp;

# USER INSTRUCTIONS
* Install Dependencies  
    `pip install -r requirements.txt` 
    
* Run Local Server  
    `python api.py`
    
* Run Desktop Client  
    `python UI.py`

# Meet the Makers
Made with 💖 by Team \
Omkar Amilkanthwar  &nbsp; -  [lnx2000](https://github.com/lnx2000)\
Aniruddha Deshmukh   - [Aniruddha004](https://github.com/Aniruddha004) \
Atharva Satpute     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [atharva-satpute](https://github.com/atharva-satpute) \
Pranav Deshmukh      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- [pranav918](https://github.com/pranav918)


