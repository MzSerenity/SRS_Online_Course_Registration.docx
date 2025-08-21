# SRS_Online_Course_Registration.docx
“Software Requirements Specification for Online Course Registration and Enrollment System.”



Tia’ Ailes

CST499

Instructor Charmelia Butler

8/10/2025
 


Introduction

Purpose

The purpose of this document is to define the requirements for the Online Course Registration and Enrollment System (OCRES). This system will allow students to register, create profiles, browse courses, enroll, manage waitlists, and cancel enrollments in a secure and efficient manner. The SRS provides a clear description of the functional and non-functional requirements, ensuring all stakeholders have a shared understanding of the system.

Scope

The OCRES will serve as a web-based application accessible via standard web browsers. It will allow students to create accounts with unique IDs and passwords, maintain personal profiles with contact details, log in at any time to manage enrollment activities, view course offerings by semester (spring, summer, fall), enroll in courses up to capacity limits, join waitlists when courses are full, and cancel enrollments, triggering waitlist notifications for the next available student. Administrators will be able to manage course offerings, enrollment limits, and semester schedules.

Definitions, Acronyms, and Abbreviations

SRS – Software Requirements Specification
UI – User Interface
ID – Unique Identifier
OCRES – Online Course Registration and Enrollment System

References

Sommerville, I. (2015). Software Engineering (10th ed.). Pearson.

Pressman, R. S., & Maxim, B. R. (2020). Software Engineering: A Practitioner’s Approach (9th ed.). McGraw-Hill Education.

Overall Description

Product Perspective

The OCRES will be an independent, web-based system deployed to a cloud hosting environment. It will integrate with a secure database to store user profiles, course offerings, and enrollment data. The system will follow industry security best practices, including password encryption and input validation.

Product Functions

The main functions of the OCRES will include:
1. User registration and profile creation
2. Secure login/logout functionality
3. Course listing by semester
4. Course enrollment up to specified capacity
5. Waitlist management
6. Enrollment cancellation and automated waitlist notifications

User Classes and Characteristics

Students – Can register, log in, enroll in courses, manage profiles, and join waitlists.
Administrators – Manage course offerings, set enrollment limits, and oversee semester schedules.

Constraints

Unique IDs must be enforced during registration. Course capacities must be respected, with waitlists activated when full. The system must comply with institutional data privacy policies.

Specific Requirements

Functional Requirements

FR1 – The system shall allow users to register with a unique ID and password.
FR2 – The system shall validate that no two users have the same ID.
FR3 – The system shall store profile data including name, phone number, and email address.
FR4 – The system shall allow users to log in using their ID and password.
FR5 – The system shall display available courses for each semester.
FR6 – The system shall enforce course enrollment limits as specified by the administrator.
FR7 – The system shall allow students to join a waitlist if a course is full.
FR8 – The system shall allow users to cancel course enrollments.
FR9 – The system shall notify the first student on a waitlist when a seat becomes available.
FR10 – The system shall allow administrators to add, edit, and remove course offerings.

Non-Functional Requirements

NFR1 – The system shall provide 99% uptime, excluding scheduled maintenance.
NFR2 – The system shall encrypt all stored passwords.
NFR3 – The system shall ensure that all pages load within 2 seconds under normal load conditions.
NFR4 – The system shall be compatible with major browsers (Chrome, Firefox, Edge, Safari).
NFR5 – The system shall comply with applicable data protection regulations (e.g., FERPA).

References

Pressman, R. S., & Maxim, B. R. (2020). Software Engineering: A Practitioner’s Approach (9th ed.). McGraw-Hill Education.

Sommerville, I. (2015). Software Engineering (10th ed.). Pearson.

