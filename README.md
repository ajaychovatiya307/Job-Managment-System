# Job-Management-System (DBMS)

##### Project assigned by : Prof. Pokhar Mal Jat (DAIICT) College : Dhirubhai Ambani Institute of Information and Communication Technology (DAIICT).
##### Group Members(2) : Darshan Gami, Ajay Chovatiya.

### Project Overview :
* Name : Job-Management System.
* Technologies Used : PostgreSQL, pgAdmin.
* Concepts Used : ER Diagram, Functional Dependencies, Relational Database Design.
* Purpose : To facilitate companies to register and post job openings, and for users to apply for jobs and check their application status.

### Features :
* Company Registration : Companies can create an account and register their company details. Companies can post job openings.
* User Functionality : Users can create an account. Users can browse and apply for job openings. Users can check the status of their job applications.

### Database Design:
* ER Diagram : Entities - Company, User, Application...
* Relationships : A company can post multiple jobs, a user can apply to multiple jobs, each application is linked to a specific job and user.
* Functional Dependencies : Ensuring the database is normalized by identifying and organizing functional dependencies.
* Relational Schema : Designing relational schemas based on the ER diagram.

### PostgreSQL & pgAdmi:
* PostgreSQL : Database management system used to implement the relational schema. Writing SQL queries to handle CRUD operations (Create, Read, Update, Delete) for companies, jobs, users, and applications.

### Application Process :
Users can apply for a job by selecting a job posting and submitting an application. Companies can review applications and update the application status (e.g., received, pending, accepted, rejected).
