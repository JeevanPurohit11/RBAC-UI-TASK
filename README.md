# ** Management System**

The **School Management System** is a feature-rich web-based platform designed using the MERN stack (MongoDB, Express.js, React.js, Node.js). It streamlines school operations, supports dynamic Role-Based Access Control (RBAC), and enhances communication and collaboration among students, teachers, and administrators.

---

### Deployment Link : https://rbac-ui-task-gkk9.vercel.app/

## **Technologies Used**

- **Frontend**: React.js, Material UI, Redux  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  

---

## **User Roles and Features**

The system supports three primary user roles, each with specific functionalities and access levels:

### **1. Admin Role**

Admins are responsible for managing the system's core functionalities. Their permissions include:

- **User Management**:
  - Add, update, delete, and manage **Students** and **Teachers**.
  - **Workflow**:
    1. Create a class.
    2. Add subjects to the class.
    3. Add teachers to the created class and subject.
    4. Add students to the respective class.

- **Attendance Tracking**:
  - Record and manage attendance for students.
  - Update or delete attendance records as required.

- **Performance Assessment**:
  - View, update, and delete student marks and progress reports.

- **General Notices**:
  - Send notifications or announcements to students and teachers.

- **Full System Control**:
  - Create, update, delete, and oversee all functionalities, including classes, subjects, and system settings.

### **2. Teacher Role**

Teachers have specific permissions aligned with their responsibilities:

- **Attendance Management**:
  - Mark students as present or absent during classes.
  - Generate attendance reports for their assigned subjects.

- **Performance Assessment**:
  - Evaluate students' performance by assigning marks and providing feedback.
  - Update student progress reports as needed.

- **Complaints**:
  - Submit complaints or issues to the administration through the system.

- **Communication**:
  - Interact directly with students by sending and receiving messages for effective collaboration.

### **3. Student Role**

Students have limited but essential access to ensure an engaging and productive experience:

- **Performance Visualization**:
  - View progress reports and analyze academic performance through interactive charts and tables.

- **Complaints**:
  - Submit complaints or raise concerns to teachers or administrators.

- **Communication**:
  - Receive notifications and interact with teachers to clarify doubts or access study materials.

---

## **Key Functionalities**

### **Dynamic Role-Based Access Control (RBAC)**

- **Dynamic Permissions**:
  - Roles and permissions are assigned dynamically.
  - Admins can update roles and permissions in real-time to meet organizational needs.

### **Admin Dashboard**
- Add and manage students and teachers.
- Oversee classes, subjects, and system-wide settings.
- Monitor system activities and ensure smooth operations.

### **Attendance Tracking**
- Teachers can record daily attendance and generate reports.
- Admins can view, update, or delete attendance records.

### **Performance Assessment**
- Teachers evaluate student performance by assigning marks and providing feedback.
- Students can track their academic progress over time.

### **Data Visualization**
- Interactive charts and tables help students and teachers analyze performance and attendance data effectively.

### **Communication**
- Effortless communication between users:
  - Teachers and students can exchange messages to enhance collaboration.
  - Admins can send general notices to all users.

---

## **System Workflow**

1. **Admin Workflow**:
   - Log in and create classes and subjects.
   - Add teachers to specific classes and subjects.
   - Add students to their respective classes.
   - Manage attendance, marks, and notifications seamlessly.

2. **Teacher Workflow**:
   - Log in and view assigned classes and subjects.
   - Record attendance and evaluate student performance.
   - Communicate with students and submit complaints when needed.

3. **Student Workflow**:
   - Log in and view academic performance and attendance.
   - File complaints or communicate with teachers for assistance.

---

## **Installation**

Follow the steps below to set up the project locally:

### **Clone the Repository**

```bash
git clone https://github.com/JeevanPurohit11/RBAC-UI-TASK.git
```
Open 2 terminals in separate windows/tabs.
Terminal 1: Setting Up Backend
```bash
cd backend
npm install
npm start
```
Create a .env file in the backend folder and add the following:
```bash
MONGO_URL = mongodb://URL
```
Terminal 2: Setting Up Frontend
```bash
cd frontend
npm install
npm start
```

### Notes:
1. Replace `https://your-backend-url.onrender.com` and `https://your-frontend-url.vercel.app` with the actual URLs provided by Render and Vercel after deployment.
2. Ensure proper testing of the deployed backend and frontend to confirm they work seamlessly together.

### Deployment
1. Server Side -> Render
2. Client Side -> Versal
