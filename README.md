**Task Master**

This is a Task Management Application built with a MERN stack. The front end is developed using React with Vite, and the back-end is built using Express.js with MongoDB for the database.

**Features**
- User authentication using JWT
- Secure password handling with bcrypt.js
- State management with Redux Toolkit
- User-friendly interface
- Toast notifications for feedback
- RESTful APIs for seamless communication between frontend and backend.

**Core Functionalities**

- User Authentication:

  - Users can register and log in.  
  - Only authenticated users can create and manage tasks.

- Task Management:

  - Create tasks with properties like priority, optional due dates, categories and the ability to share tasks with others.
  - Update tasks, including title, priority , due dates and delete tasks.
  - Change task statuses across four categories: Backlog, To-Do, In-Progress and Done.
  
- User Management:

  - Users can update their name, email or password via the settings page.

- Analytics & Filtering:

  - Review task analytics in a dedicated section.
  - Filter tasks by Today, This Week or This Month (default is the current week).

- User-Friendly Interface:

  - Mandatory fields are marked with a red asterisk (*).
  - Notifications and alerts are provided via toast messages.
  
- Collaboration:

  - Add members to task boards.
  - Assign members to tasks during creation.

- Additional Features
  - Visual indicators for task statuses based on due dates:
     - Red: Overdue tasks in active categories.
     - Green: Tasks marked as done.

**🛠️ Tech Stack**

**Frontend**  
React: UI library  
React Router DOM: For routing  
Redux Toolkit: State management  
React Icons: Icon library  
React Toastify: Notification handling  
Vite: Frontend build tool  

**Backend**  
Express.js: Backend framework  
Mongoose: MongoDB object modeling  
JWT: Secure token-based authentication  
Bcrypt.js: Password encryption  
