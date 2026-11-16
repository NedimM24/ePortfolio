# Computer Science ePortfolio

## About Me

Hello, my name is Nedim Mulahusic. Welcome to my Computer Science ePortfolio.

I have a **Bachelor's degree in Computer Science** with a focus on software engineering, full-stack development, database design, and application development.

I am currently working as a **Software Engineer Intern at Boomer Roomers**, a startup where I contribute to React Native mobile development and React web development. My work has included improving mobile accessibility, testing with iOS Dynamic Type and VoiceOver, implementing WCAG-focused improvements, developing responsive web interfaces, and collaborating with senior engineers through code reviews, sprint planning, technical documentation, and pull requests.

Through my academic projects, personal projects, and professional experience, I have developed experience building applications from the database and backend layers through the frontend and deployment process.

My goal is to continue growing as a software engineer while building reliable, maintainable, accessible, and user-focused software.

---

# Professional Experience

## Software Engineer Intern — Boomer Roomers

**Remote | Aug 2026 – Present**

At Boomer Roomers, I contribute to web and mobile application development with a focus on accessibility, responsive interfaces, debugging, and software quality.

### Responsibilities & Contributions

- Audited and improved **React Native mobile accessibility** across multiple screens, using iOS Dynamic Type and VoiceOver to identify text clipping, focus order, form navigation, and component accessibility issues.
- Implemented accessibility improvements for **Dynamic Type, screen-reader focus management, WCAG AA contrast, and touch targets**, remediating 4 interactive elements below the 44×44pt accessibility target.
- Redesigned and implemented a **responsive React web signup flow** using progressive disclosure and adaptive progress indicators that switch between sidebar and linear layouts across screen sizes.
- Drove defects from **root-cause analysis through implementation and validation**, collaborating with senior engineers through code reviews, sprint planning, technical documentation, Linear, and pull requests.

### Technologies & Skills

- React Native
- React
- JavaScript
- TypeScript
- Accessibility
- WCAG
- iOS VoiceOver
- Dynamic Type
- Responsive Design
- UI/UX
- Debugging
- Root-Cause Analysis
- Git
- Code Reviews
- Linear

---

# Featured Project

## Backcountry Journal

**Full-Stack Outdoor Blog Platform**

Backcountry Journal is a production-deployed full-stack blogging platform built as a monorepo containing separate user and administrative React applications and a TypeScript/Express REST API.

The platform allows authenticated users to browse outdoor articles and participate through comments, while administrators can create, edit, publish, and manage blog content.

### Project Architecture

```text
backcountry-journal/
│
├── server/
│   ├── prisma/
│   └── src/
│       ├── config/
│       ├── controllers/
│       ├── middleware/
│       ├── queries/
│       ├── routes/
│       ├── validation/
│       └── app.ts
│
├── admin-frontend/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── pages/
│       ├── routes/
│       └── App.tsx
│
├── user-frontend/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── pages/
│       ├── services/
│       └── App.tsx
│
└── README.md

---

### Technologies

- TypeScript
- JavaScript
- React
- Vite
- Node.js
- Express.js
- Prisma
- PostgreSQL
- JWT Authentication
- bcrypt
- REST API
- HTML
- CSS
- Git/GitHub
- Railway
- Vercel
- Postman
- Autocannon

### Skills Demonstrated

- Full-Stack Web Development
- REST API Development
- Authentication and Authorization
- JWT Authentication
- Role-Based Access Control
- Relational Database Design
- Prisma ORM
- PostgreSQL
- API Validation
- CRUD Operations
- React Component Development
- Responsive Web Design
- API Integration
- Production Deployment
- API Testing
- Performance Optimization
- Git/GitHub

### Performance Optimization

I performed measured performance improvements on both the frontend and backend.

#### Frontend

- Resized the homepage hero image from **2560×1440 to 1200×675**
- Compressed the image, reducing its file size by approximately **79%**
- Replaced a CSS background image with an HTML `<img>` element
- Added `fetchPriority="high"` to prioritize the hero image

#### Backend

- Reduced unnecessary database fields using Prisma `select`
- Reduced API response payloads by returning shortened post excerpts for the published-post listing
- Preserved full article content for individual post endpoints

### Measured Results

Using Autocannon against the deployed Railway API with 5 concurrent connections over 10 seconds:

| Metric          | Before      | After       |
| --------------- | ----------- | ----------- |
| Response Size   | 8,374 bytes | 2,857 bytes |
| Average Latency | 39.74 ms    | 34.69 ms    |
| p97.5 Latency   | 58 ms       | 43 ms       |
| Throughput      | 122.6 req/s | 140.7 req/s |

**Results:**

- **65.9% smaller API response payload**
- **12.7% lower average latency**
- **25.9% lower p97.5 latency**
- **14.8% higher throughput**

### API Testing

Used **Postman to test and validate individual API endpoints against the deployed production backend**, verifying API functionality, HTTP responses, authentication/authorization behavior, and request/response handling.
 
# Professional Self-Assessment

Throughout my Computer Science degree, I developed a strong foundation in programming, problem-solving, software engineering, database design, and application development.

My development experience has progressed from individual academic applications to complete full-stack systems and production-deployed applications.

My professional internship at Boomer Roomers has also given me experience working within a real software development environment. I have worked with existing codebases, investigated defects, implemented changes, participated in code reviews, collaborated with senior engineers, and considered accessibility and responsive design as part of the development process.

I also use AI-assisted development tools such as ChatGPT, Claude, and GitHub Copilot to support debugging, code exploration, documentation, and development workflows while independently evaluating and validating the resulting solutions.

My projects have allowed me to develop experience across the full software development lifecycle, including:

- Designing application architecture
- Developing frontend interfaces
- Building backend APIs
- Designing relational databases
- Implementing authentication and authorization
- Validating and testing applications
- Debugging and troubleshooting
- Deploying applications to cloud platforms
- Optimizing application performance
- Using Git and GitHub for version control
- Collaborating through code reviews and pull requests

These experiences have strengthened my ability to approach software development from both a technical and user-focused perspective.

---

# Technical Skills

## Programming Languages

- Java
- JavaScript
- TypeScript
- Python
- SQL

## Front-End Development

- React
- React Native
- HTML
- CSS
- Vite
- React Router
- Responsive Web Design
- Accessibility
- WCAG
- iOS VoiceOver
- Dynamic Type

## Backend Development

- Node.js
- Express.js
- REST APIs
- EJS
- RESTful Routing
- Server-Side Validation
- MVC Architecture

## Authentication & Security

- JWT Authentication
- Passport.js
- bcrypt
- Authentication and Authorization
- Role-Based Access Control
- Session Management
- Password Hashing

## Databases

- PostgreSQL
- SQLite
- MongoDB
- Prisma
- PyMongo
- Relational Database Modeling
- SQL Queries
- CRUD Operations
- Database Relationships

## Testing & Quality

- Unit Testing
- JUnit
- Vitest
- Postman
- API Testing
- Validation
- Debugging
- Root-Cause Analysis
- Performance Testing
- Autocannon

## Software Engineering

- Object-Oriented Programming
- Software Design
- Data Structures and Algorithms
- Git
- GitHub
- Code Reviews
- Pull Requests
- Technical Documentation
- Responsive Design
- Accessibility
- Agile/Sprint Development

## Development & Deployment Tools

- Visual Studio Code
- IntelliJ IDEA
- Android Studio
- Railway
- Vercel
- Linear
---
 
# Additional Projects
 
## Full-Stack Issue Tracking Platform
 
**Project:** TicketFyx
 
A full-stack issue tracking platform built with **TypeScript, Node.js, Express, PostgreSQL, Passport.js, and EJS**. This project demonstrates authentication, session management, role-based authorization, relational database design, and cloud deployment.
 
The application allows users to sign up, submit tickets, track their progress, and collaborate through comments. Access is controlled through a three-tier role system (Worker, Developer, Admin), with permissions enforced at both the interface and route level. Developers can update ticket status and priority, while admins can assign developers to tickets, delete tickets and comments, and manage the platform.
 
### Technologies:
 
- TypeScript
- JavaScript
- Node.js
- Express.js
- PostgreSQL
- Passport.js
- bcrypt
- SQL
- EJS Templates
- HTML
- CSS
- Railway Deployment
- Git/GitHub
### Skills Demonstrated:
 
- Full-Stack Web Development
- Authentication and Session Management
- Role-Based Access Control
- Backend Development
- MVC Architecture
- RESTful Routing
- Database Design
- Relational Database Modeling
- CRUD Operations
- SQL Queries
- PostgreSQL Integration
- Server-Side Validation
- Password Hashing and Security
- Debugging and Troubleshooting
- Responsive Web Design
- Version Control
- Cloud Deployment
### Features:
 
- User registration and login with hashed passwords and persistent sessions
- Role-based access control for Workers, Developers, and Admins
- Ticket creation, viewing, and status/priority updates
- Comment system tied to tickets and users
- Admin controls for assigning developers, deleting tickets, and deleting comments
- Server-side validation with express-validator
- Parameterized SQL queries throughout
- Railway deployment with hosted PostgreSQL database and persistent session storage
GitHub:
https://github.com/NedimM24/ticketfyx
 
Live Demo:
https://ticketfyx-production.up.railway.app
 
---
 
## Full-Stack Inventory Management Application
 
**Project:** Summit Supply Co Inventory Management System
 
A full-stack inventory management application built with **TypeScript, Node.js, Express, PostgreSQL, and EJS**. This project demonstrates backend development, database design, CRUD functionality, server-side validation, MVC architecture, and cloud deployment.
 
The application allows users to manage outdoor equipment inventory by creating, viewing, updating, and deleting categories and items. The project uses a relational PostgreSQL database with category-to-item relationships and cascading deletes.
 
### Technologies:
 
- TypeScript
- JavaScript
- Node.js
- Express.js
- PostgreSQL
- SQL
- EJS Templates
- HTML
- CSS
- Railway Deployment
- Git/GitHub
### Skills Demonstrated:
 
- Full-Stack Web Development
- Backend Development
- MVC Architecture
- RESTful Routing
- Database Design
- Relational Database Modeling
- CRUD Operations
- SQL Queries
- PostgreSQL Integration
- Server Development
- Form Handling
- Server-Side Validation
- Object-Oriented Programming Concepts
- Debugging and Troubleshooting
- Responsive Web Design
- Version Control
- Cloud Deployment
### Features:
 
- Create, read, update, and delete inventory categories
- Create, read, update, and delete inventory items
- PostgreSQL database integration
- One-to-many database relationships
- Cascading deletes using foreign keys
- Server-side validation with express-validator
- Dynamic page rendering with EJS
- Responsive inventory card layouts
- Railway deployment with hosted PostgreSQL database
GitHub:
https://github.com/NedimM24/hiking-inventory-app
 
Live Demo:
https://hiking-inventory-app-production.up.railway.app/
 
---
 
## React Ecommerce Application
 
A front-end ecommerce application built with React demonstrating reusable components, routing, responsive design, and testing.
 
Technologies:
- React
- JavaScript
- React Router
- CSS Modules
- Vitest
View Project:
[React Ecommerce Application](./Additional-Projects/React-Ecommerce-Application.md)
 
GitHub:
https://github.com/NedimM24/react-marketplace
 
Live Demo:
https://react-marketplace-pi.vercel.app/
 
---
 
### Animal Rescue Analytics Dashboard
 
A full-stack Python analytics dashboard built with Dash, MongoDB, and Plotly. This project demonstrates database integration, CRUD operations, interactive data visualization, and user-focused dashboard development.
 
Technologies:
 
- Python
- Dash
- MongoDB
- PyMongo
- Plotly
- Dash Leaflet
- Pandas
- NumPy
Skills Demonstrated:
 
- Full-Stack Development
- Database Integration
- CRUD Operations
- Data Visualization
- Dashboard Development
- Backend Development
- Data Processing
- Debugging and Testing
Features:
 
- Interactive animal data filtering
- Searchable and sortable data tables
- Dynamic charts based on user selections
- Geolocation mapping
- MongoDB database connectivity
GitHub:
https://github.com/NedimM24/animal-rescue-analytics-dashboard
 
---
 
# Portfolio Artifacts
 
## Artifact 1: Software Engineering
 
**Project:** Software Testing Application
 
A Java application demonstrating object-oriented design, validation, exception handling, automated testing, and software quality practices.
 
Skills:
- Java
- OOP
- JUnit Testing
- Validation
- Software Design
View Artifact:
[Software Engineering](./Artifact-1-Software-Engineering)
 
---
 
## Artifact 2: Algorithms and Data Structures
 
**Project:** Android Weight Tracker Application
 
An Android application demonstrating data structures, sorting, searching, object-based storage, and application design.
 
Skills:
- Java
- Android Development
- ArrayLists
- Sorting Algorithms
- Searching Algorithms
View Artifact:
[Algorithms and Data Structures](./Artifact-2-Algorithms-And-Databases)
 
---
 
## Artifact 3: Database Design
 
**Project:** Android Weight Tracker Database Application
 
An Android application using SQLite to demonstrate database integration and CRUD operations.
 
Skills:
- SQLite
- Database Design
- Data Modeling
- CRUD Operations
View Artifact:
[Database Design](./Artifact-2-Algorithms-And-Databases)
 
---
 
Thank you for reviewing my ePortfolio.
