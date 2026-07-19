https://drive.google.com/drive/u/0/folders/15pEmmVz38rjjRO_xdBAKPkrmSVW62Pqy






Project Report: Ucab – Full-Stack Cab Booking Web Application
1. Project Overview
Ucab is a modern, responsive, and robust full-stack web application designed to simplify urban transportation. Built using the MERN (MongoDB, Express.js, React.js, Node.js) stack, the application provides a seamless, stress-free platform where users can book rides quickly, track drivers in real-time, and process secure automated payments. The platform implements sophisticated role-based access control, real-time fare estimations, and optimal route-matching to ensure high performance and an interactive user experience.
2. Technical Stack & Skills Utilized
The architecture follows a decoupled client-server model built using industry-standard engineering technologies:
Frontend Library: React.js (JavaScript Library)
Styling & UI: HTML5, CSS3, Bootstrap (for responsive design)
Backend Framework: Node.js with Express.js (for building scalable RESTful APIs)
Database: MongoDB (NoSQL database for storing user, driver, ride, and payment data)
API Client: Axios (for secure, real-time asynchronous backend data fetching)
Tools & Utilities: JSON Web Tokens (JWT) for authentication, Bcrypt.js for security, Postman for API testing, and Git/GitHub for collaborative version control.
3. Core Modules & System Architecture
The application is structurally divided into key independent modules that operate cohesively:
User & Driver Management: Supports registration and onboarding. Drivers undergo a strict verification process, while users can manage their saved payment options and profiles.
Cab Booking & Ride Lifecycle: Handles the complete CRUD workflow of booking, accepting, starting, and completing a ride. It includes searching nearby available cabs and selecting vehicle classes.
Algorithmic Estimation Engine: Calculates real-time estimated arrival times (ETA) and precise distance/fare estimates prior to booking confirmation.
Real-Time Live Tracking: An integrated mapping environment tracks the driver's journey from the pickup location directly to the drop-off destination.
Transaction Processing: An automated online payment system that handles transactions upon ride completion and generates automated customer receipts.
Historical Logging & Support: Features comprehensive ride history logs for all user tiers alongside an active customer support interface.
4. Security & Optimization Features
Role-Based Security: Restricts route access across three designated client levels: User, Driver, and Admin.
Data Encryption: Sensitive credentials and passwords are encrypted using bcryptjs before storage, maintaining safe session management over secure channels using JWT.
Database Performance: Optimizes complex MongoDB queries for rapid location tracking and driver-to-user proximity matching.
Robust Logging: Backed by robust global error-handling middlewares implemented throughout the Express application layer.
5. System Requirements
Software Specifications
Operating System: Windows 10/11, macOS, or Linux
Runtime Environment: Node.js (v16+) & npm (v8+)
Code Editor: Visual Studio Code (VS Code)
Testing Suite: Postman and modern web browsers (Google Chrome / Mozilla Firefox)
Hardware Specifications
Processor: Intel Core i5 (8th Gen or above) / AMD Ryzen 5 or better
RAM: 8 GB minimum (16 GB recommended for running concurrent development servers)
Storage: 1 GB of free disk space for local environment packages and local database setups
Display: 1366x768 resolution or higher
