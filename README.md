# Restaurant Ordering System (Dine-in Order and Payment)

**Course:** Cap1 – System Analysis and Design
**Team:** Nova Team

A system analysis and design project for a centralized digital restaurant platform. Dine-in customers browse the menu, place orders, and pay directly, while kitchen staff and managers track orders, inventory, and sales in real time.

> This repository covers **analysis and design only**. No software is implemented.

---

## Team Members

| Name | Student ID | Group | Role |
| :--- | :--- | :--- | :--- |
| Atajanova Laylo | 202590164 | I25B | Project Leader (planning, coordination, final review) |
| Normurodova Nigina | 202590210 | I25B | Database Designer (ERD and data dictionary) |
| Nurullayeva Fazilat | 202590213 | I25A | System Analyst (requirements and use case models) |
| Xasanboyeva Iroda | 202590244 | I25A | Business Process Analyst (BPM diagrams) |

---

## Problem Statement

Many restaurants still use paper orders and verbal communication between waitstaff and the kitchen. During busy hours this causes lost tickets, mistakes with dish changes, late service, and long waits for the bill. Tracking sales and inventory by hand is slow and error-prone, and managers have no real-time view of top dishes, table turnover, or revenue.

## Project Objectives

- **Analyze** the operational requirements of a dine-in restaurant ordering and payment system
- **Design** Business Process Models (BPM), Use Case diagrams with specifications, and Entity Relationship Diagrams (ERD) with data dictionaries
- **Create** screen layouts for customer ordering, the kitchen display system, and the manager dashboard
- **Document** functional and non-functional requirements as a blueprint for development

## System Scope

| Functional Area | Coverage |
| :--- | :--- |
| User Registration & Authentication | Role-based access for Customers, Waitstaff, Kitchen Staff, Managers, and Administrators |
| Menu & Table Management | Digital menu, item modifiers, pricing, availability toggle, table layout and QR codes |
| Order Processing & Kitchen Tracking | Dine-in orders, real-time tickets on the kitchen display (KDS), status updates (Received, Preparing, Ready, Served) |
| Payment & Sales Reporting | Bill generation, split bills, card / wallet / cash payments, digital receipts, sales reports |

**Out of scope:** delivery fleet management, third-party delivery integrations, supply-chain purchasing, and payment gateway implementation.

## Users

Customer · Waitstaff / Server · Kitchen Staff / Chef · Restaurant Manager · System Administrator

---

## Repository Structure

```
Cap1-Restaurant-Ordering-System/
├── README.md
├── 01-project-plan/     Project plan document
├── 02-use-case/         Use case diagrams (UC1–UC3) and specifications
├── 03-bpm/              Business process models (BPM1–BPM3)
├── 04-erd-chen/         Chen ERDs (Chen1–Chen3)
├── 05-erd-ie/           IE (crow's foot) ERDs (IE1–IE3)
└── presentation/        Presentation slides and speech
```

## Deliverables

| # | Deliverable | Files | Status |
| :--- | :--- | :--- | :--- |
| 1 | Project Plan | `01-project-plan/` | Done |
| 2 | Use Case Modeling (3 diagrams) | `02-use-case/` | Diagrams done |
| 3 | Business Process Models (3 diagrams) | `03-bpm/` | Done |
| 4 | Chen ERD (3 diagrams) | `04-erd-chen/` | Done |
| 5 | IE ERD (3 diagrams) | `05-erd-ie/` | Done |
| 6 | Presentation slides and speech | `presentation/` | Draft |

### Use Case Diagrams

| File | Description |
| :--- | :--- |
| `UC1_customer_ordering_payment` | Customer and waitstaff: scan QR, order, track, request bill, pay |
| `UC2_kitchen_floor_operations` | Kitchen staff and waitstaff: view tickets, update status, deliver, mark served |
| `UC3_management_administration` | Manager and administrator: menu, tables, dashboard, reports, roles, backups |

### Business Process Models (To-Be)

| File | Description |
| :--- | :--- |
| `BPM1_order_placement` | From scanning the QR code to the ticket reaching the kitchen display |
| `BPM2_kitchen_preparation` | Ticket review, preparation, quality check, delivery to the table |
| `BPM3_billing_payment` | Bill request, split bill, payment by card / wallet / cash, digital receipt |

### Entity Relationship Diagrams

| Model | Chen ERD | IE ERD |
| :--- | :--- | :--- |
| Ordering | `Chen1_ordering` | `IE1_ordering` |
| Menu, customization and inventory | `Chen2_menu_customization_inventory` | `IE2_menu_customization_inventory` |
| Billing and payment | `Chen3_billing_payment` | `IE3_billing_payment` |

Each diagram is available as **PNG** (for viewing) and **SVG** (sharp when zoomed or edited).

---

## Timeline

| Phase | Focus |
| :--- | :--- |
| Week 1 | Project planning and requirement analysis |
| Week 2 | Business process modeling |
| Week 3 | Use case diagrams and descriptions |
| Week 4 | ERD, data dictionary, and screen layouts |

Key dates: project plan uploaded Oct 9, 2026 · team presentation Nov 4, 2026 · all documents and slides Nov 11, 2026.

## References

- Dennis, A., Wixom, B. H., & Roth, R. M. (2012). *Systems Analysis and Design* (5th ed.). Wiley.
- Elmasri, R., & Navathe, S. B. (2016). *Fundamentals of Database Systems* (7th ed.). Pearson.
- Object Management Group. (2017). *Unified Modeling Language (UML)*, Version 2.5.1.
- Object Management Group. (2011). *Business Process Model and Notation (BPMN)*, Version 2.0.
