# Cap1: System Analysis and Design – Project Plan

## 1. Course Information

| Item | Details |
| :--- | :--- |
| **Course Name** | Cap1: System Analysis and Design |
| **Team Name** | Nova Team |

---

## 2. Team Members

The team members and their roles in the project are listed below:

| Name | Student ID | Group | Role |
| :--- | :--- | :--- | :--- |
| **Atajanova Laylo** | 202590164 | I25B | **Project Leader** (planning, coordination, final review) |
| **Normurodova Nigina** | 202590210 | I25B | **Database Designer** (ERD and data dictionary) |
| **Nurullayeva Fazilat** | 202590213 | I25A | **System Analyst** (requirements and Use Case models) |
| **Xasanboyeva Iroda** | 202590244 | I25A | **Business Process Analyst** (BPM diagrams) |

---

## 3. Project Title

**Restaurant Ordering System (Dine-in Order and Payment)**  
A centralized digital restaurant management platform designed to allow dine-in customers to browse menus, place orders, and pay directly, while enabling kitchen staff and managers to track order processing, inventory, and sales performance in real time.

---

## 4. Problem Statement

Many traditional restaurants still rely on manual paper-based ordering, check pads, and verbal communication between floor waitstaff and kitchen personnel. During peak dining hours, this manual process leads to frequent errors, such as miscommunicated dish modifications, lost order tickets, delayed table service, and long customer wait times for billing.

Additionally, tracking inventory usage and daily sales across shifts manually is time-consuming and prone to human error. Restaurant managers lack real-time visibility into top-selling dishes, table turnover rates, and revenue metrics. The business requires a centralized, automated system to streamline order intake, speed up kitchen processing, accept payment accurately, and provide management with real-time operational reports.

---

## 5. Project Objectives

The project is guided by the following objectives:
* **Analyze** the operational requirements of a dine-in restaurant ordering and payment system, including user workflows, seating management, menu customization, and billing rules.
* **Design** comprehensive system models including Business Process Models (BPM), Use Case diagrams with detailed specifications, and Entity Relationship Diagrams (ERD) with complete data dictionaries.
* **Create** user interface screen layouts (wireframes) for customer ordering, kitchen display systems, and manager dashboards.
* **Document** functional and non-functional requirements clearly to establish a reliable blueprint for software development.
* **Understand** the importance of system analysis and design before software development begins.

---

## 6. Scope of the System

The proposed system covers four key functional areas:

| Functional Area | Coverage |
| :--- | :--- |
| **User Registration & Authentication** | Account access and role-based permissions for Customers, Waitstaff, Kitchen Staff, Managers, and System Administrators. |
| **Menu & Table Management** | Digital menu creation, item customization (add-ons/modifiers), pricing updates, item availability toggle, and table layout/QR code configuration. |
| **Order Processing & Kitchen Tracking** | Dine-in order placement, real-time ticket transmission to kitchen display screens (KDS), order status updates (Received, Preparing, Ready, Served), and special request notifications. |
| **Payment & Sales Reporting** | Bill generation, split-billing options, multi-method payment processing (digital wallet, card, cash), digital receipts, and operational sales reports by shift, item, or table. |

> **Out of Scope:** External delivery fleet management, third-party food delivery integrations (e.g., UberEats, DoorDash), supply chain purchasing, and low-level payment gateway software implementation. This project covers system analysis and design only.

---

## 7. Expected Users

The system is intended for five primary user groups:

* **Customer:** Scans table QR code or uses dining terminals to browse the digital menu, customize items, place dine-in orders, request bills, and make payments.
* **Waitstaff / Server:** Assists customers with orders, verifies table status, delivers meals when ready, and assists with cash/manual payments.
* **Kitchen Staff / Chef:** Views incoming digital order tickets on the Kitchen Display System (KDS), manages preparation status, and alerts floor staff when food is ready.
* **Restaurant Manager:** Updates menu pricing/availability, monitors table turnover, views live sales dashboards, and generates daily operational reports.
* **System Administrator:** Manages user roles, system credentials, security settings, and data backups.

---

## 8. Project Timeline

Work is organized into four weekly phases, each producing a specific set of system design deliverables:

| Phase | Activities | Deliverables |
| :--- | :--- | :--- |
| **Week 1** | **Project Planning & Requirement Analysis:** Define scope, identify stakeholders, collect functional & non-functional requirements, and establish GitHub repository setup. | Project Plan / Proposal |
| **Week 2** | **Business Process Modeling (BPM):** Model current ("As-Is") manual dining operations vs. proposed ("To-Be") digital process. Prepare presentation slides and speech. | Minimum 3 BPM Diagrams |
| **Week 3** | **Use Case Diagrams & Descriptions:** Identify actors and system boundaries. Write detailed step-by-step use case specifications. *(Presentation on Oct 21)* | Minimum 3 Use Case Diagrams & Written Descriptions |
| **Week 4** | **ERD & Screen Layouts:** Identify entities, attributes, primary/foreign keys, and relationships. Design data dictionaries and user interface screen layouts. Review for consistency and finalize submission. *(Submission on Nov 3)* | Minimum 3 ERD Diagrams, Data Dictionary, & 3 Screen Layouts |

---

## 9. Expected Outcomes

By completing this project, **Nova Team** expects to gain:
* Practical, hands-on experience in system analysis and software architecture.
* Advanced skills in UML modeling, BPMN process design, and relational database ERD design.
* A complete, publication-ready design repository hosted on GitHub containing:
  1. Project Proposal Document
  2. At least 3 BPM Diagrams (Order Placement, Kitchen Preparation, Payment)
  3. At least 3 Use Case Diagrams with detailed specifications
  4. At least 3 User Interface Screen Layouts
  5. At least 3 ERD Schemas with complete Data Dictionaries

---

## 10. Conclusion

A Restaurant Ordering System modernizes traditional dining operations by seamlessly connecting customers, floor waitstaff, kitchen personnel, and management. By analyzing the workflow and modeling it with BPM, Use Case, and ERD diagrams before development begins, the team can identify operational bottlenecks early and enforce consistent business rules. These models provide the proposed system with a robust foundation, demonstrating how thorough system analysis improves service speed, accuracy, and overall operational efficiency.

---

## 11. References

* Course lecture notes (*Cap1: System Analysis and Design*).
* Dennis, A., Wixom, B. H., & Roth, R. M. (2012). *Systems Analysis and Design* (5th ed.). Wiley.
* Elmasri, R., & Navathe, S. B. (2016). *Fundamentals of Database Systems* (7th ed.). Pearson.
* Object Management Group. (2017). *Unified Modeling Language (UML)*, Version 2.5.1 (formal/17-12-05). https://www.omg.org/spec/UML/About-UML/
* Object Management Group. (2011). *Business Process Model and Notation (BPMN)*, Version 2.0 (formal/11-01-03). https://www.omg.org/spec/BPMN/2.0