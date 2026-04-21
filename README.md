# 👨‍💻 Javier Alejandro Núñez Sánchez

Computer Engineering Professional | Enterprise IT | Software Systems, Infrastructure, and Secure Architecture

I design and implement structured, reliable, and scalable technical solutions across software, networking, data engineering, and cybersecurity. My work reflects a strong engineering foundation combined with practical experience in enterprise and regulated environments.

This GitHub profile presents academic and applied projects developed under structured engineering methodologies, with emphasis on architecture, system integrity, security, and operational continuity.

---

## 🧩 Professional Profile

Computer Engineering professional with experience in enterprise incident management, public-sector digital transformation, and academic engineering initiatives across software development, database design, network infrastructure, mobile applications, and cybersecurity systems.

I have contributed to high-criticality environments requiring technical coordination, structured validation processes, and strict operational standards. My experience spans enterprise IT operations, full-stack web and mobile development, database-centered systems, network design, software architecture, and Agile and Scrum frameworks — including experience as both Tech Lead and Product Owner.

I approach engineering problems with discipline, accountability, and long-term maintainability in mind. My objective is not only to build functional systems, but to design solutions that are coherent, auditable, and scalable.

---

## 🛠️ Core Technical Competencies

**Programming and Development**
- Java, Python, C#, JavaScript, SQL
- Object-Oriented Programming and modular design
- REST API design and full-stack development

**Web Technologies**
- React 19, Node.js, Express, HTML, CSS
- JWT authentication, role-based access control
- MongoDB (Mongoose ODM), REST API architecture

**Mobile Development**
- .NET MAUI 10, C#, XAML
- Cross-platform development (Android, iOS, Windows)

**Data and Database Engineering**
- SQL Server, PostgreSQL, MongoDB, Supabase
- Relational modeling and normalization (1NF to 3NF)
- Stored procedures, triggers, views, integrity constraints
- Row-Level Security, SECURITY DEFINER functions

**Networking and Infrastructure**
- IPv4 and IPv6 implementation
- VLAN segmentation and trunking
- OSPFv2 and OSPFv3 dynamic routing
- DNS, DHCP, and VoIP services

**Architecture and Platforms**
- Microservices-oriented architecture
- Oracle Cloud Infrastructure, Azure DevOps
- Disaster Recovery (active-passive, Pacemaker, Corosync, DRBD)
- Linux administration

**Cybersecurity and Cryptography**
- Asymmetric cryptography: ECDSA-P256, RSA-OAEP 2048-bit
- Hashing and integrity: HMAC-SHA256, PBKDF2
- Biometric authentication systems (facial recognition, handwritten signature)
- Penetration testing fundamentals and DDoS resilience assessment
- Risk assessment, secure access control, and audit trail design

**Methodologies**
- Agile, Scrum, DevOps Fundamentals
- Product Ownership, backlog management, KPI tracking

**Professional Tools**
- Git and GitHub, Visual Studio, Apache NetBeans
- Cisco Packet Tracer, Postman
- Microsoft 365, Brevo API, Multer

**Languages**
- English (C1), Spanish (Native)

---

## 📂 Selected Engineering Projects

### 🎓 [Smart Campus University Platform](https://github.com/aleNu93/SmartCampusProject)
**Java | HTML | CSS | JavaScript | Azure DevOps | Scrum | Tech Lead**

A modular academic management platform developed under Agile and Scrum methodologies. The system integrates role-based access control, dynamic data dashboards, and structured academic workflows across a multi-sprint Azure DevOps delivery cycle.

As Tech Lead, I coordinated system architecture, sprint planning, development cycles, and delivery alignment with functional requirements. Focus on modularity, maintainability, and structured implementation.

---

### 🌐 [Call Center Network Topology](https://github.com/aleNu93/Call-Center-Network-Project-Mesh-Topology)
**Enterprise Networking | IPv4/IPv6 | OSPFv2/v3 | VLANs | VoIP | DNS | DHCP | IoT**

A complete enterprise network design for a multi-site call center built in Cisco Packet Tracer, integrating five network segments across a mesh topology.

Key components:
- VLAN segmentation and trunk configuration
- OSPFv2 and OSPFv3 dynamic routing
- VoIP, DNS, DHCP, and IoT device integration
- End-to-end connectivity validation and troubleshooting

Full responsibility for topology design, device configuration, and verification testing.

---

### 📱 [MOBILUX – Mobile Furniture Payment Tracker](https://github.com/aleNu93/MOBILUX)
**.NET MAUI 10 | C# | Supabase | PostgreSQL | Brevo API | Technical Lead & DB Architect**

A cross-platform mobile application (Android, iOS, Windows) for tracking financed furniture purchases — managing outstanding balances, payment history, and financial status in real time.

Key components:
- Layered architecture: .NET MAUI → Services → Supabase (PostgreSQL + Auth + Storage)
- Row-Level Security policies enforcing strict user data isolation
- SECURITY DEFINER PostgreSQL function for secure multi-table registration
- OTP-based password recovery fully independent from Supabase email system
- Automated transactional email notifications via Brevo API
- 13-screen application with custom branding, responsive layout, and multi-platform support

Led all technical and administrative responsibilities: architecture, database design, QA, branding, and documentation.

---

### 🏥 [Hospital Staff Scheduling Management Database](https://github.com/aleNu93/Hospital-Staff-Scheduling-Management-Database.git)
**SQL Server | Stored Procedures | Triggers | Views | Project Lead**

A healthcare scheduling database automating daily staff assignments, service rotations, on-call shifts, and vacation management for a 20-physician obstetrics unit across 11 service rotations.

The system enforces 9 business rules through database logic — preventing conflicting states, blocking assignments during leave periods, and protecting closed monthly records.

Responsible for project leadership, relational modeling, constraint design, stored procedure implementation, and analytical query development.

---

### 🔗 [JobBridge – Freelance Marketplace Platform](https://github.com/aleNu93/JobBridge)
**React 19 | Node.js | Express | MongoDB | JWT | Multer | Full-Stack Developer & Product Owner**

A full-stack freelance marketplace connecting small and medium businesses (PYMEs) with freelance professionals across 15 service categories.

Key components:
- JWT role-based authentication (Freelancer and PYME roles)
- Full contract lifecycle management: Requested → Accepted → In Progress → Completed/Cancelled
- Real-time messaging via HTTP polling organized by contract
- Bidirectional rating system with reviews on profiles and services
- Shopping cart with multi-service checkout and platform fee calculation
- Freelancer sales dashboards with earnings, completion rate, and average ratings
- 6-controller REST API with full CRUD, file uploads via Multer, and MongoDB Atlas

Led product ownership and Scrum delivery — managing backlog definition, KPIs, stakeholder communication, and 100% on-time delivery of all project objectives.

---

### 🛡️ [MANDATUM – Digital Delegation with Biometric Authorization](https://github.com/aleNu93/MANDATUM)
**Python | Flask | JavaScript | Web Crypto API | ECDSA-P256 | RSA-OAEP | Project Lead & Security Architect**

A full-stack web platform that digitally represents the legal concept of a special power of attorney, enabling principals to authorize third parties to perform specific actions under defined scope, validity, and revocation conditions — without credential sharing.

Key components:
- Three-factor biometric authentication: LBP facial recognition (≥72% similarity threshold), Jaccard handwritten signature grid (≥12%), color OTP via HMAC-SHA256
- ECDSA-P256 digital signatures for delegation non-repudiation
- RSA-OAEP 2048-bit encryption for cryptographic hash storage
- PBKDF2 (200,000 iterations) password hashing
- Full delegation lifecycle: create → accept → use → revoke
- Immutable cryptographically signed audit trail with timestamps
- Admin dashboard with user management and complete system logs

Led architecture, database design, security model, full-stack development, and QA across a 4-person team.

---

### ☁️ [Disaster Recovery on Oracle Cloud Infrastructure](https://github.com/aleNu93/OCI-Disaster-Recovery)
**Oracle Cloud Infrastructure | Pacemaker | Corosync | DRBD | Linux | Active-Passive Architecture**

An enterprise disaster recovery implementation on OCI for a client requiring high availability of Oracle Linux servers with automatic failover capability.

Key components:
- Two-node active-passive cluster using Pacemaker and Corosync
- Real-time block-level data replication between nodes via DRBD
- Automatic failover — passive node assumes active role without manual intervention
- SSH key-based secure remote access across all instances
- VCN configuration with public/private subnet architecture
- Full step-by-step technical manual covering setup, validation, and recovery procedures

---

### 🚗 [Parking Management System – ULACIT](https://github.com/aleNu93/Parking_Management_System)
**Python | Systems Logic | Process Automation**

A software system replacing a manual university parking control process, managing users and vehicles across multiple parking zones with improved operational oversight and traceability. Implemented approximately 90% of the system logic.

---

### 🍪 [Crumbl Cookies Sales System](https://github.com/aleNu93/Crumbl_Cookies_Sales_System)
**Java | Object-Oriented Design | Transaction Logic**

A console-based retail sales simulation applying object-oriented design principles, modular class structures, and transactional workflows. Implemented approximately 70% of the overall logic and structural design.

---

### 📄 [Translation Company Page Management Program](https://github.com/aleNu93/Translation_Company_Page_Management_Program)
**Java | Data Structures | Workflow Modeling**

A console-based document workflow simulation using stacks, queues, and lists to model structured document processing. Contributed approximately 50% of the system implementation.

---

## 🤝 Professional Contact

- **LinkedIn**: https://www.linkedin.com/in/javier-ale-nu/
- **GitHub**: https://github.com/aleNu93

---

## 📜 License

This repository is licensed under the MIT License.
