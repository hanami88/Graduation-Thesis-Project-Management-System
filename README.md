# Graduation-Thesis-Project-Management-System

## 📌 Project Overview

This is a team-developed graduation project management system designed to digitalize the entire workflow — from topic registration to final evaluation.  
The platform supports role-based access for students, lecturers, and academic staff, allowing efficient communication and tracking throughout the project lifecycle.

It was developed by a team of 4 members over 3 months using **C# ASP.NET MVC** and **vanilla HTML/CSS/JavaScript**.  
As the **team leader**, I was responsible for coordinating development and implementing the frontend interface.

- 👥 Team size: 4 members (2 Frontend, 2 Backend)  
- 👨‍💼 Role: Team Leader + Frontend Developer  
- ⏱️ Duration: 3 months (from planning to deployment)

---

## 🛠️ Technologies Used

### 👨‍💻 Frontend
- HTML5  
- CSS3  
- JavaScript (ES6+)  
- Razor View Engine (ASP.NET MVC)

### ⚙️ Backend

- C# ASP.NET MVC  
- Entity Framework  
- MySQL  

### 🔐 Authentication & Authorization

- Role-based access control (Admin / Lecturer / Student)  
- Session-based login management

### 📦 File Handling & Data Import

- Excel file processing using EPPlus  
- Manual & bulk grade entry via Excel upload

---

## 🔍 Project Insight

> Since this was a new and rarely implemented topic, we conducted our own research by interviewing lecturers and students to understand their real workflow.  
> Based on these insights, we designed the system to closely match the actual graduation project process used in universities.

---
## 🖼️ User Interface Preview

### 🔐 Login Page
<img width="983" height="552" alt="image" src="https://github.com/user-attachments/assets/baf79d11-b7e5-4c5b-83cf-61ad2f11dafc" />

### 🙍‍♂️ Student

Students can perform the following actions within the system:

- 📋 **Register a project topic**: Select or submit a graduation project topic.
- 📈 **Update project progress**: Record milestone updates and upload related documents.
- 💬 **Receive feedback from lecturers**: View comments and suggestions from supervisors.
- 📑 **View detailed project information**: Includes topic name, description, timeline, status, and assigned lecturer.
- 📊 **Check scores after defense**: View scores for supervision, review, defense panel, and final average.
- 🔐 **Change password**: Secure their personal account.

<img width="983" height="554" alt="image" src="https://github.com/user-attachments/assets/b1c4bf1f-394f-4045-a19e-d19e5e20625f" />
<img width="981" height="552" alt="image" src="https://github.com/user-attachments/assets/0a64f917-248a-4c48-a662-4ccb7c019248" />

### 👩‍🏫 Lecturer

Lecturers can perform the following actions within the system:

- ✅ **Approve project topics**: Review and approve project topics submitted by students.
- 📂 **Supervise assigned projects**: Track the progress of students they are guiding.
- 📝 **Provide feedback**: Comment on student progress and guide their work throughout the project.
- 📜 **View detailed student and project info**: Includes student details, project description, and current progress.
- 📚 **Access supervision history**: View previously guided projects to track workloads and detect topic duplication.
- 🔐 **Change password**: Secure their personal account.

<img width="983" height="551" alt="image" src="https://github.com/user-attachments/assets/dfdc6b0b-01c5-447f-a0e2-3c7dfc9e70a9" />
<img width="986" height="602" alt="image" src="https://github.com/user-attachments/assets/4807545d-2fed-42ad-9f67-3acde2eed5d3" />

### 🧑‍💼 Academic Staff (Admin)

Academic staff are granted full administrative control over the system. They can:

- 👥 **Manage user accounts**: Add, edit, or delete student and lecturer accounts.
- 🔄 **Assign lecturers to projects**: Approve topics and assign appropriate supervisors.
- 📊 **View statistics**: Filter and view project data by year, lecturer, or student.
- 📋 **Monitor all ongoing and past projects**: View detailed project and student information across the system.
- 📎 **Import scores via Excel**:  
  Upload and process Excel files to enter student grades in bulk using the **EPPlus** library, saving time and ensuring accuracy.

> 🔥 The Excel import feature was designed to handle batch updates efficiently and is one of the standout features of the system.
<img width="1021" height="601" alt="image" src="https://github.com/user-attachments/assets/13dcf946-8ebf-468f-984e-a88be9c74fc0" />

- 🔐 **Change personal password**: Maintain account security.

<img width="986" height="569" alt="image" src="https://github.com/user-attachments/assets/468c56d5-37bc-4c6d-b79b-90a6977fc86f" />

## 🙏 Thank You

Thank you for taking the time to review my project.  
I appreciate your attention and welcome any feedback or suggestions.


















