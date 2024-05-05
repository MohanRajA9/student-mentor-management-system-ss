# Student Mentor Management System
--------------------------------

The Student-Mentor Management System is designed to facilitate the management of mentors and students within an educational Institution. This App allows for the creation of mentors, assignment of students to mentors, and retrieval of information related to mentors and their assigned students.

## Setup

1.  Clone the repository: `git clone <repository-url>`
2.  Navigate to the project directory: `cd mentor-student-management`
3.  Install dependencies: `npm install`
4.  Create a `.env` file in the project root and define the MongoDB connection string.
5.  Start the server: `npm start`
6.  Access the application at `http://localhost:<port>`

## API Endpoints

### Student Routes

-  `POST /api/student/create`: Create a new student.
-  `GET /api/student/students`: Get all students.
-  `PUT /api/student/assign/:id`: Assign a mentor to a student.
-  `GET /api/student/get-particular/:id`: Get the assigned mentor for a student.
![student](Output/create_student1.png)
![student](Output/Listing_students1.png)
![student](Output/Student_Assigned_to_Mentor.png)
![student](Output/Student_Info_with_Assigned_Mentor_ID.png)



### Mentor Routes

-  `POST /api/mentor/create`: Create a new mentor.
-  `GET /api/mentor/mentors`: Get all mentors.
-  `PUT /api/mentor/assign/:id`: Assign students to a mentor.
-  `GET /api/mentor/ment-student/:id`: Get students assigned to a specific mentor.
![mentor](Output/Atlas_Mentor_Info_with_Assigned_Student_ID.png.png)
![mentor](Output/Create_mentor1.png)
![mentor](Output/Listing_mentor.png)
![mentor](Output/Mentor_Assign1.png)
![mentor](Output/Mentor_Assign2.png)
![mentor](Output/Mentor_Info_from_Student_ID.png)


## Features

-  **Creating Mentor**
-  **Listing Mentors**
-  **Assigning Students to Mentors**
-  **List Students by Mentor**
-  **Creating Student**
-  **Listing the Students**
-  **Assigning Mentor to Student**
-  **Fetching Assigned Mentor for a Student**
  
## Project Schema

-  **Controllers**
-  **Models**
-  **Routers**
-  **Database**
-  **index.js**
  
## Technologies Used

-  **Node.js**
-  **Express.js**
-  **MongoDB**
-  **Mongoose**
-  **cors**