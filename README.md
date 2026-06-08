# EmployeeInfoMap – AI-Powered Employee Lifecycle Management and Workforce Intelligence Platform

## About the Project

EmployeeInfoMap is a full-stack employee management system developed to simplify employee onboarding, workforce administration, and employee record management.

The platform supports three user roles: Admin, HR, and Faculty. It provides secure authentication, role-based access control, resume parsing, employee onboarding workflows, smart employee search, workforce analytics dashboards, employee ID generation, QR-enabled verification, profile management, and chatbot support.

The objective of this project is to reduce manual HR effort and provide a centralized platform for managing employee information efficiently.


## Key Features

### Authentication & Security

* Secure login system
* Forgot password functionality
* JWT-based session management
* Password hashing using bcrypt
* Role-based access control

### HR Module

* Upload candidate resumes
* Extract information from PDF resumes
* Create and manage new hire records
* View onboarding information
* Access workforce statistics

### Admin Module

* Manage employee records
* Assign departments and official details
* Generate employee IDs
* Update employee information
* Delete employee records
* Access analytics dashboards
* Generate employee ID cards
* Use Smart Search functionality

### Faculty Module

* View and update personal profile information
* Access assigned department details
* Download employee ID cards
* Access chatbot support

### Resume Parsing

* Upload PDF resumes
* Automatically extract candidate details
* Store candidate information in MongoDB
* Simplify onboarding workflow

### Smart Search

* Search employees by department
* Search using employee IDs
* Search by designation
* Display results in a structured format

### Dashboard & Analytics

* Total employee statistics
* Active employee count
* New hire tracking
* Department-wise employee distribution
* Recent activity monitoring
* Interactive charts and visualizations

### Employee ID Generation

* Automatic employee ID generation
* QR-enabled employee ID cards
* Downloadable PDF ID cards
* Employee profile verification through QR codes

### Chatbot Support

* Available for Admin, HR, and Faculty
* Assists users with system-related queries
* Improves user navigation and accessibility


## User Roles

### Admin

* Manage employee records
* Assign departments
* Generate employee IDs
* Generate QR-enabled ID cards
* Access workforce analytics
* Perform CRUD operations
* Use Smart Search
* Access chatbot support

### HR

* Upload resumes
* Parse candidate information
* Manage new hires
* Access dashboards
* Track onboarding activities
* Access chatbot support

### Faculty

* Manage personal profile information
* View assigned department details
* Download employee ID cards
* Access dashboards
* Access chatbot support


## System Workflow

1. HR uploads candidate resumes.
2. Resume information is extracted and stored as candidate records.
3. Candidate records are saved as New Hires.
4. Admin reviews and assigns department information.
5. Employee IDs are generated automatically.
6. New Hires are converted into Active Employees.
7. Faculty members complete their personal profile information.
8. Workforce information becomes available through dashboards and Smart Search.
9. QR-enabled employee ID cards are generated and downloaded.


## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Tailwind CSS
* Chart.js
* Fetch API

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Security

* JWT Authentication
* bcrypt.js

### AI & Automation Tools

* pdf-parse (Resume Parsing)
* natural (NLP-Based Smart Search)
* node-nlp (Chatbot)
* pdfkit (PDF Generation)
* qrcode (QR Code Generation)


## AI Components

### Resume Intelligence

The system processes uploaded PDF resumes and extracts candidate information automatically to simplify employee onboarding.

### NLP-Based Smart Search

Natural language processing techniques are used to improve employee search functionality and information retrieval.

### Conversational Assistance

An integrated chatbot assists users with navigation and basic system-related queries.


## Project Structure

EmployeeInfoMap/
│
├── backend/
│   ├── models/
│   │   ├── candidate.js
│   │   ├── employee.js
│   │   └── user.js
│   │
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── candidateRoutes.js
│   │   ├── employeeRoutes.js
│   │   └── employees.js
│   │
│   ├── .env
│   ├── package.json
│   └── server.js
│
├── Frontend/
│   ├── public/
│   │   ├── admin/
│   │   ├── hr/
│   │   ├── user/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── css/
│   │   ├── js/
│   │   └── pages/
│   │
│   ├── index.html
│   ├── login.html
│   ├── qr-verify.html
│   ├── script.js
│   └── style.css
│
├── resume_parser_python/
│   ├── app.py
│   ├── models.py
│   ├── parser.py
│   └── requirements.txt
│
├── uploads/
│
└── README.md


## Future Enhancements

* Advanced workforce analytics
* Enhanced chatbot capabilities
* Skill-based employee insights
* Attendance and performance tracking
* Cloud deployment improvements
* Additional reporting and visualization features


## Domain

Artificial Intelligence (AI)
Natural Language Processing (NLP)
Workforce Analytics
Employee Management Systems


## Project Type

Development Project


## License

This project was developed for academic and learning purposes.
