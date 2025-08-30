Staff Management System

A full-stack Staff Management System built using Spring Boot (Backend) and React.js (Frontend). The system allows
you to manage staff details with basic CRUD operations (Create, Read, Update, Delete).

### Features
- Add new staff members
- View all staff members in a list
- Update staff details
- Delete staff records
- RESTful API built with Spring Boot
- Frontend connected via Axios
  
### Tech Stack
- Frontend: React.js, Axios
- Backend: Spring Boot, Java, REST API
- Database: MySQL Database

### Prerequisites
- Java 17+
- Node.js & npm
- Maven (for Spring Boot build)
- Database (configure in application.properties)

### API Endpoints
Method Endpoint Description
- GET /api/staff : Get all staff members
- GET /api/staff/{id} : Get staff by ID
- POST /api/staff : Add new staff
- PUT /api/staff/{id} : Update staff
- DELETE /api/staff/{id} : Delete staff

### Future Enhancements
- Add authentication (Admin/User roles)
- Pagination & search filters
- Validation for input fields
- Deploy on cloud (AWS / Render / Heroku)

### Screenshots
- Add Staff
  
![image alt](https://github.com/PratikPDahale/Staff-Management-System/blob/5bd81718d62dc66133c49cba17a54b7cb04f08fd/screenshots/add%20Staff.png)

- View Staff

![image alt](https://github.com/PratikPDahale/Staff-Management-System/blob/5bd81718d62dc66133c49cba17a54b7cb04f08fd/screenshots/view%20staff.png)
