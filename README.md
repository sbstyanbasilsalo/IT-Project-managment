# IT-Project-managment

An open-source, multi-tenant **IT & Software Agency Project Management System** designed for software development companies to centralize client portals, project files, cross-platform applications, role-based staff collaboration, and support ticketing workflows.

---

## 1. Overview & Problem Solved
Software agencies and IT departments often manage dozens or thousands of client projects simultaneously across Web, Android, and iOS platforms. Important project details frequently get scattered across chat messages, emails, design tools, and separate task boards—leading to missed client modification requests and delayed deployments.

**IT-Project-managment** solves this by providing a unified, self-hosted operational hub where every registered software company can:
* Onboard its entire management and technical team under one organization workspace.
* Maintain a centralized directory of all client projects, source/design files, deployment URLs, and pricing/package tiers.
* Bridge the gap between administrative personnel (secretaries/account managers) and IT specialists through structured ticketing and threaded internal discussions.

---

## 2. Role-Based Access Control (RBAC) & Internal Team Structure
Each registered company workspace supports granular role assignments so that every staff member has clear responsibilities and permissions within the same organization:

| Role | Responsibilities & Permissions |
| :--- | :--- |
| **IT Project Manager** | Oversees all company projects, assigns tasks across departments, monitors timelines, and approves updates prior to client delivery. |
| **Secretary / Account Manager** | Receives client modification requests (e.g., UI adjustments, website content updates, new features) and logs structured change tickets directly under the relevant project. |
| **UI/UX Designer** | Accesses project design assets, handles interface/design tickets, uploads updated mockups, and collaborates directly inside ticket threads. |
| **Database Maintenance Engineer** | Manages project databases, resolves data integrity or performance tickets, and maintains infrastructure logs. |
| **Technical Support & Developers** | Implements code changes across Web, Android, and iOS repositories, manages deployments, and closes resolved tickets. |

---

## 3. End-to-End Operational Workflow
1. **Organization & Team Onboarding:** A software agency creates its workspace and adds its management and IT staff with specific roles (IT Project Manager, UI/UX Designer, Database Maintenance, Secretary, Technical Support).
2. **Project Registration:** Each client project (Web, Android, or iOS) is added with its core documentation, design files, live deployment links, and pricing/billing details.
3. **Client Request Intake:** When a client requests a change—such as updating a webpage section or adjusting an app screen—a secretary opens the project record and submits a clear, non-technical change ticket.
4. **Threaded Staff Collaboration:** All relevant IT and management staff within the company can view the ticket, reply to one another in real time, share files, and coordinate technical execution.
5. **Resolution & Audit Trail:** Once the support or engineering team completes the update, the ticket status is updated and permanently logged in the project's version and activity history.

---

## 4. Planned System Architecture & Tech Stack
* **Backend & REST API:** Python / PHP / Node.js for multi-tenant authentication, RBAC permissions, and ticketing endpoints.
* **Web Dashboard:** Responsive HTML5, CSS3, and JavaScript portal for company administrators, secretaries, and engineers.
* **Mobile Companion Apps:** Cross-platform **Flutter** applications (Android & iOS) enabling staff to track projects, receive alerts, and reply to tickets on the go.
* **Database Layer:** **MySQL** for scalable multi-company production deployments and **SQLite** for lightweight local instances.
* **AI Agent Integration Ready:** Modular webhook and API architecture designed to connect intelligent agents for automated ticket triage, deployment status checks, and project summaries.

---

## 5. Open-Source Mission & License
**IT-Project-managment** is built as an open-source alternative to costly proprietary agency management SaaS tools. It empowers independent developers, startups, and software houses to self-host, customize, and scale their internal IT and project operations freely.

Contributions, feature proposals, and pull requests are welcome.
