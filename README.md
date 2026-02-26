# DriverPass Portfolio: System Analysis and Design

This repository contains the core documentation and system design for the **DriverPass** platform, developed as part of CS 255. These documents demonstrate the process of gathering business requirements and translating them into a technical system architecture.

---

## 📂 Included Artifacts

1.  **Business Requirements Document**: A comprehensive guide detailing the client's needs, functional requirements, and project constraints.
2.  **System Design Document**: A technical blueprint featuring UML diagrams (Use Case, Activity, Sequence, and Class) and infrastructure specifications.

---

## 📝 Reflection

### Project Summary
The **DriverPass** project was designed for the client, **Liam (Owner)**, to address a critical business problem: a student failure rate exceeding 65% at the DMV. The goal was to build a secure, cloud-based system that manages 10 cars and multiple instructors while providing students with a structured path consisting of online practice exams and coordinated on-the-road training.

### What I Did Well
I believe the **technical architecture planning** was the strongest aspect of my work. By selecting a **PostgreSQL RDBMS**, I ensured that the complex relationships between Student IDs, Appointments, and Test History were handled without data redundancy. Using **Lucidchart** as a CASE tool allowed me to create a logically sound blueprint, ensuring that the system's data integrity was protected before any development began.

### Areas for Revision
If I were to revise these documents, I would expand the **Security Protocols** section. While the current design includes SSL/TLS encryption, I would like to add a more granular breakdown of the **Role-Based Access Control (RBAC)**. Specifically, I would define a more detailed permission matrix for the "Secretary" versus the "Driver" roles to ensure the principle of least privilege is strictly followed.

### Interpreting User Needs
I interpreted the user's needs by focusing on **Accountability and Accessibility**. Liam specifically needed to know "who is responsible if something goes wrong," which led me to implement a requirement that every record change must include a user identity and timestamp. Understanding the user's needs is vital; for instance, identifying that instructors are "in the field" led to the requirement for **LTE-enabled tablets**, ensuring the system remains functional in real-world driving scenarios.

### Design Strategy & Future Approach
My approach to software design is **Visual-First**. I utilize UML modeling (Activity and Sequence diagrams) to "stress-test" the logic of a system before coding. In the future, I plan to continue using **Responsive Web Frameworks (like React.js)** and **Cloud-Hosting (AWS/Azure)** strategies to ensure that any system I design is both scalable and accessible from any device.

---
*This project was completed as part of the Computer Science program at SNHU.*
