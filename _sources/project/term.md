# Term Project

## Web Architecture Design and Implementation

## Objectives

- Design and implement a complete web system with a clear architectural structure.
- Apply web architecture principles, including frontend–backend separation.
- Gain experience with backend services, cloud-based databases, and deployment.
- Work collaboratively on a moderately complex web application and document design decisions.

## Project Overview

You will work in **groups (up to 4 members per team)** to design, implement, and deploy a full-stack web application.

This project emphasizes web application architecture, not only feature implementation. Your system must include a modern frontend, a backend service layer, a cloud-based database, and a public deployment.

The project consists of two major written components:

- a **project proposal**, which focuses on the application idea and high-level design
- a **final report**, which documents the complete system architecture, implementation details, and engineering considerations

You may draw inspiration from existing web or mobile applications, but your design and implementation must be original. Learning from tutorials is allowed; submitting an unmodified tutorial project is not permitted.

All team members must actively contribute to the shared codebase. Participation will be verified through Git repository logs.

---

## Project Requirements

### Core Requirements

1. **Complete & Realistic Application Features**
   - The application should implement realistic features found in comparable real-world systems.
   - Example: An e-commerce application should support browsing, user accounts, and order management.

2. **User Authentication & Authorization**
   - Support multiple users with login and logout functionality.
   - Implement appropriate access control for user-specific and shared data.

3. **Backend Service Layer**
   - Implement a backend layer using one of the following:
     - Node.js REST API (Express, Fastify, NestJS, or similar)
     - Firebase Cloud Functions
     - Another serverless or containerized backend service

   - Business logic must not reside entirely in the frontend.
   - Although a cloud database is used, database access must be mediated through this backend layer for write operations and sensitive logic.

4. **Cloud Database Design**
   - Use Firebase Cloud Firestore (or a comparable cloud database).
   - Include at least three collections with a clear and well-structured data model.

5. **Database Operations**
   - Implement **CRUD operations** (Create, Read, Update, Delete).
   - Queries should be designed clearly and efficiently.

6. **Private & Shared Data Management**
   - Store **user-specific data** accessible only to its owner.
   - Include **shared data** accessible by all users.
   - Example: Personal order history versus public product listings.

7. **Modern Frontend Framework**
   - Use **Vue.js** or a comparable modern JavaScript framework.
   - Apply component-based design and appropriate state management.

---

### Architecture & Engineering Quality

The requirements in this section are **primarily evaluated based on the final report and in-class presentation**, not the initial proposal.

8. **System Architecture Documentation**
   - Clearly document the system architecture, including:
     - an architecture diagram
     - frontend and backend responsibilities
     - data flow between components
     - API design overview

9. **Non-Functional Design Considerations**
   - Address at least two of the following:
     - security
     - scalability
     - performance
     - reliability

   - Briefly explain how your design choices support these goals.

---

### Git Repository & Development Process

- Maintain all project code in **one shared GitHub repository**.
- Commit history should show **steady progress** throughout the semester.
- All team members must make meaningful contributions.

---

### In-Class Presentation

- Each group must present their project in class.
- The presentation should cover:
  - application motivation and goals
  - system architecture
  - key features
  - live demonstration

- **All team members must participate.**

---

## Project Repository Setup

Each group must create **Project GitHub repository** using this link: [https://classroom.github.com/a/d7M8Pab7](https://classroom.github.com/a/d7M8Pab7)

All team members must collaborate within this repository.

---

## Deliverables & Timeline

| Deliverable | Description | Deadline |
| --- | --- | --- |
| **Project Proposal (15%)** | Submit a **one-page proposal** focusing on the application idea and early design. The proposal should include: <br> - **Application Idea & Motivation**: what problem is addressed and who the users are <br> - **Core Features**: main functionality of the application <br> - **Preliminary Architecture**: high-level description of frontend, backend, and database components (no detailed justification required) <br> - **Preliminary Database Design**: proposed collections and key fields <br> - **Team Responsibilities** | **02/23** |
| **Final Application, Report & Deployment (75%)** | Submit the **completed web application** and a **final report**. The submission must include: <br> - Public application URL <br> - GitHub repository link <br> - Test account credentials (if applicable) <br> - **Final Report**, which documents: <br>   • system architecture and data flow <br>   • backend and database design <br>   • implementation details <br>   • non-functional design considerations | **04/27** |
| **In-Class Presentation (10%)** | Live presentation and demonstration of the final system. | **04/27** |
