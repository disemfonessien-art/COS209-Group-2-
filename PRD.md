# Development of a Student Lost and Found Management System for Babcock University

## Problem Definition

Loss of student property at Babcock University is the recurring situation where students' personal belongings (phones, laptops, calculators, books, ID cards, clothing, and so on) go missing on campus through misplacement, theft, or mix-ups, and are rarely recovered by their owners. It leads to financial loss, disrupted academic work, and distrust among Babcock students.

## Why the Problem Exists

* **Carelessness:** Students often leave belongings in classrooms, libraries, cafeterias, and halls while rushing between activities, without checking their surroundings. Items get forgotten or misplaced.
* **Poor security:** Many classrooms, hostels, and public areas at Babcock University have no lockers, limited surveillance, and weak access control, so unattended items are easy to take or lose.
* **High population of students:** Large numbers of Babcock students share the same spaces, so areas are crowded and busy. Items easily get mixed up, picked up by mistake, or lost in the crowd, and it is hard for staff to monitor everyone.
* **Theft:** Where there is little accountability, some individuals take advantage of unattended belongings. Because stolen items are rarely traced, theft continues.
* **Lack of identification systems:** Most belongings are unmarked and look alike (same phone model, calculator, or bottle). Even when an item is found, there is no way to prove who owns it or contact the owner.

## Product Overview

The Campus Lost and Found Management System is a digital platform designed to help students and staff of Babcock University report, locate, and recover lost properties within the university environment.
The platform will provide a centralized system for reporting lost and found items, searching for missing belongings, and verifying ownership before items are returned.

## Proposed Solution: Development of a Student Lost and Found Management System for Babcock University

This is a web-based (and mobile-friendly) system that gives Babcock University one organized platform for reporting, tracking, and returning lost items.

## Business Objectives

The objectives of the Campus Lost and Found Management System are to:
Reduce the number of unrecovered lost properties within Babcock University.
Provide a centralized platform for reporting lost and found items.
Make it easier for students to search for and recover missing belongings.
Improve the management and tracking of recovered properties.
Promote responsibility and accountability among students.

## Target Users

The target users of the system are:
Students: Students who lose or find personal belongings within the university.
Lecturers: Lecturers who may lose or find items in classrooms and lecture halls.
University staff: Staff members who may discover lost properties or assist in returning them.
Lost and Found administrators: Individuals responsible for managing reports and keeping recovered items safe.

### How It Will Work

1. **User registration:** Babcock students and staff sign up with their matric number or Babcock university email. This ensures only verified members of the university can use the system.
2. **Optional item registration:** Students can register valuable items (laptop, phone, calculator) with a description, photo, and serial number. The system generates a unique QR code or ID label to stick on the item, which addresses the lack of identification.
3. **Reporting a lost item:** A student who loses something fills out a form with the item's name, category, description, photo (if available), and where and when it was lost on the Babcock campus.
4. **Reporting a found item:** Anyone who finds an item submits its details and photo, then drops it at the designated Babcock University lost-and-found office (e.g., the Security unit or Student Affairs). Staff confirm receipt and log it in the system with a storage location.
5. **Automatic matching:** The system compares lost reports with found items by category, description, location, and date. When there is a likely match, it notifies the owner by email or SMS.
6. **Search and browsing:** Students can search or browse all listed found items by category, date, or location, so they don't have to physically visit the office just to check.
7. **Claiming and verification:** The owner submits a claim, and the admin asks for proof of ownership ( a unique feature, serial number or registered QR code). Only after verification is the item released, which prevents false claims and theft
8. **Admin dashboard:** Babcock University staff manage all records, update item status (Lost, Found, Claimed and Unclaimed), and view reports showing which areas and times have the most losses. This helps the university improve security where needed.
9. **Unclaimed items protocol:** Lost items take a certain period (e.g., 30 days) are flagged by the system for donation, disposal, or other action according to Babcock university policy.

## How It Addresses Each Problems

* **Carelessness:** Easy reporting and notifications make recovery likely even when students forget items.
* **Poor security:** Logged records, verified claims and location data show where security need improvement on Babcock campus.
* **High population of students:** A centralized online platform handles large number of students without relying on word of mouth.
* **Theft:** Ownership verification and registered items discourage theft and resale, and make stolen items easier to trace.
* **Lack of identification systems:** QR codes and item registration give every belonging a traceable identity.

## Stakeholders
 
Stakeholders are individuals or groups who are involved in or affected by the product.
The stakeholders include:
Babcock University management.
Students of Babcock University.
Lecturers and academic staff.
Non-academic staff.
University security personnel.
The development team responsible for building and maintaining the system.

## User Stories

User stories describe what users want to accomplish using the system.
-As a student, I want to report a lost item so that I can increase my chances of recovering it.
-As a student, I want to report a found item so that its rightful owner can locate it.
-As a student, I want to search for lost items so that I can check whether my belongings have been found.
-As a student, I want to receive notifications when an item matching my lost property is reported.
-As a Lost and Found administrator, I want to verify ownership before returning an item so that properties are given to their rightful owners.

## Functional requirements

The system should have the following functional requirements:
1. User Registration and Login: The system shall allow students and staff of Babcock University to create accounts and log in securely.
2. Report Lost Items: The system shall allow users to report lost properties by providing the item's name, description, category, location, and date it was last seen.
3. Report Found Items: The system shall allow users to report items they have found by providing details and, where possible, uploading an image of the item.
4. Search for Items: The system shall allow users to search for lost and found items using keywords, categories, and locations.
5. Item Matching: The system shall compare lost-item reports with found-item reports to identify possible matches.
6. Notifications: The system shall notify users when a found item matches the description of their lost property.
7. Ownership Verification: The system shall allow administrators to verify the rightful owner of an item before it is returned.
8. Manage Reports: The system shall allow administrators to view, update, approve, or remove lost and found item reports.
9. Claim Items: The system shall allow users to submit a claim for an item they believe belongs to them.
10. Mark Items as Recovered: The system shall allow administrators to mark items as recovered or returned to their rightful owners.

## Non-Functional Requirements

The system should meet the following non-functional requirements:
1. Usability: The system shall have a simple and user-friendly interface that students and staff can easily understand and use.
2. Performance: The system shall respond to user requests and display search results within a reasonable time.
3. Security: The system shall protect users' personal information and prevent unauthorized access to accounts and reports.
4. Reliability: The system shall operate consistently and provide accurate information about lost and found items.
5. Availability: The system should be accessible to users whenever they need to report or search for missing properties, subject to maintenance and internet availability.
6. Compatibility: The system shall work on common web browsers and be accessible through smartphones, tablets, and computers.
7. Scalability: The system should be able to accommodate an increasing number of users and item reports as the university community grows.
8. Maintainability: The system shall be designed so that developers can easily update, fix, and improve its features when necessary.
9. Data Integrity: The system shall ensure that item reports are stored accurately and that important information is not changed or lost without authorization.
10. Privacy: The system shall limit access to sensitive information and avoid publicly displaying private details such as users' phone numbers or account information.

## Scope and Priorities

### Features included in the MVP
Feature                                        Priority
Student and staff registration and login       High
Reporting lost items                           High
Reporting found items                          High
Searching for lost and found items             High
Viewing item descriptions and pictures         High
Claiming lost properties                       High
Administrator verification of item ownership   High
Marking items as recovered                     High

### Features not included in the MVP
The following features may be added in future versions:
Automatic matching of lost and found items.
Email or SMS notifications.
Advanced search filters.
Mobile application.
Location tracking of lost properties.
These features can be introduced after the basic system has been developed and tested.

## Acceptance Criteria
Acceptance criteria explain how we will verify that the system's features work correctly.
The system will be considered acceptable when:
1.A user can successfully register and log into the system.
2.A user can report a lost item by entering the required information.
3.A user can report a found item and upload an image.
4.Users can search for lost and found items and view relevant results.
5.A user can submit a claim for an item they believe belongs to them.
6.An administrator can verify ownership before returning an item.
7.An administrator can mark an item as recovered after it has been returned.
8.Unauthorized users cannot access administrative features.
9.The system displays appropriate messages when users submit incomplete or incorrect information.
10.The system works properly on common web browsers and mobile devices.

## Assumptions and Open Questions
This section explains what we currently assume about the project and what still needs to be confirmed.

### Assumptions
1.Students and staff of Babcock University will have access to the internet.
2.Users will provide accurate information when reporting lost or found items.
3.The university will support the development and use of the system.
4.A designated administrator will be responsible for managing item reports.
5.A physical Lost and Found collection point will be available for keeping recovered properties.

### Open Questions
1.Will users register using their Babcock University email addresses or their matriculation and staff identification numbers?
2.Who will be responsible for managing the system and verifying ownership of items?
3.Where will recovered items be kept before they are collected?
4.Will the system send notifications through email, SMS, or only within the platform?
5.Will the system be available to students only, or will staff members also be allowed to use it?

## CONCLUSION
## Summary: Why Every Student Needs It

Loss of student property at Babcock University is caused by carelessness, poor security, a high student population, theft, and the lack of identification systems. These problems reinforce one another, leaving students with little chance of recovering what they lose. The Student Lost and Found Management System offers a practical, organized solution by combining item registration, online reporting, automatic matching, and verified claims on a single platform. By making lost items easier to trace, return, and protect, the system will reduce losses and theft, and give the university useful data for improving campus security. With proper implementation and student awareness, it can build a more responsible and trustworthy campus community.
