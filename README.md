🚀 Augury: Centralized Schedule and Reminder Management System
SE1 Group Project | Web-Based Task Orchestration Platform

🎯 Introduction: Precision in Schedule Management
In an era of accelerating complexity, managing myriad personal and professional commitments requires a robust and centralized solution. Augury is engineered to address the inherent fragmentation in modern schedule and reminder management. This web-based application provides a comprehensive system for users to consolidate, categorize, and track diverse responsibilities, ranging from routine vehicle maintenance (e.g., annual registration, oil changes) and critical healthcare appointments (e.g., dental check-ups, physical examinations) to complex family logistics. Our core objective is to deliver an intuitive and powerful platform that enhances user organization and minimizes missed obligations through proactive notification.

💡 Project Objective
The primary technical objective is the design and implementation of a Software-as-a-Service (SaaS) solution that abstracts the complexity of scheduling and notification into a unified, accessible interface. This system is intended to maximize user efficiency and provide a single source of truth for all personal and professional temporal commitments.

👥 Target Audience
Our primary users are proactive individuals and small groups (families, teams) seeking a unified, technologically sophisticated platform to manage and synchronize heterogeneous task categories, thereby transitioning from reactive to predictive schedule adherence.

⚙️ System Capabilities (Functional Requirements)
👤 User Lifecycle Management
Account Provisioning: Secure user registration, authentication, and personalized profile management.
Preference Configuration: Define user-specific settings, including default notification channels and time zone preferences.

🗂️ Dynamic Categorization Module
Custom Category Creation: Enable users to define and customize logical task hierarchies (e.g., Vehicle Maintenance, Healthcare/Wellness, Financial Deadlines).
Metadata Integration: Attach category-specific attributes for enhanced filtering and reporting.

✅ Task Orchestration Engine
Item Definition: Detailed creation of specific tasks or events (e.g., Q3 Tax Filing, Semi-Annual Tire Rotation) within defined categories.
Rich Detail Capture: Support for mandatory fields (due date, priority level) and optional fields (detailed description, file attachment upload, recurrence patterns).

🔔 Integrated Notification Service
Multi-Channel Reminders: Support for configurable, tiered notifications across multiple delivery protocols: Email, SMS, and Push Notifications (where supported by the deployment architecture).
Interval Customization: Users can specify lead-time reminder intervals (e.g., T-7 days, T-24 hours) for critical task acknowledgment.

🔎 Advanced Query & Filtering
Event Aggregation: A dashboard view providing a consolidated timeline of upcoming tasks, sortable by due date, priority, and category.
Parametric Search: Implementation of a robust search interface supporting full-text search and filtering based on user-defined criteria (e.g., status, tag, date range).

🖥️ System Access & Deployment
Minimum Viable Product (MVP): A standalone, web-based interface accessible via standard desktop browsers.
Preferred Architecture: A responsive web application optimized for cross-platform compatibility, including mobile devices, to ensure ubiquitous schedule management capability.

🔒 System Requirements (Non-Functional Specifications)
Usability (UX/UI): The interface must adhere to modern HCI (Human-Computer Interaction) principles, ensuring low cognitive load and intuitive task flow.
Reliability (Notification SLA): The notification service must maintain an exceptionally high Service Level Agreement (SLA) for delivery, ensuring reminders are reliably dispatched at the precisely configured time.
Security: Adherence to best practices for data encryption (at rest and in transit) and user authentication (OWASP Top 10 considerations).
Scalability: The architecture must be designed to accommodate future growth in user base and data volume.

🛠️ Design & Development Technology Stack Requirements
UML and System Modeling
Mandatory: Utilization of a dedicated UML CASE tool (e.g., IBM Software Architect, Rational Rose, or StarUML) for the formal creation of all architectural and behavioral diagrams (Class Diagrams, Sequence Diagrams, Use Case Models).

Project Management & Tracking
Mandatory: Use of Microsoft Project for comprehensive Work Breakdown Structure (WBS) development, task assignment, critical path analysis, and ongoing project progress monitoring.

Data Modeling and Flow
Optional: Microsoft Visio may be utilized for generating formal Entity-Relationship Diagrams (ERDs) and Data Flow Diagrams (DFDs) to articulate data schema and system processes.

Quality Assurance & Testing
Mandatory: Integration of a Unit Testing Framework (e.g., JUnit, NUnit, CppUnit) to enforce automated testing protocols and ensure code quality and regression prevention.

Source Code Management
Mandatory: Employment of a robust Version Control System (VCS) such as GitHub, GitLab, Subversion, or Microsoft Team Foundation Server to maintain code integrity, facilitate collaboration, and manage deployment branches.
