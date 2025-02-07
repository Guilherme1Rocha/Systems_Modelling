## Introduction

BIOGateBox (BGB) is a company specializing in the sale and implementation of the **BioBox** product, which is designed for physical access control to restricted areas. The company operates under contractual agreements with clients who require secure and automated access control solutions.

## BioBox Overview

The **BioBox** is a comprehensive service provided to contracted clients, consisting of:  
- **BGate Portals**: Physical gateways installed at the client's designated location.  
- **BGM Application**: A **Message Queue** system installed on a dedicated server.  
- **Local Network**: Connecting all BGate portals and the dedicated server using the **EtherNet/IP** industrial standard.

Clients are expected to integrate the BioBox system with their own business applications. The **BGM application** provides access to BioBox events and allows clients to send control commands. It acts as an intermediary between the client’s applications and the BGate portals.

The **BGM application** is supplied by **QUEUE**, a third-party provider.

## Governance and Management

BGB operates under a hierarchical organizational structure, governed by the **Executive Board (DEXEC)**, which consists of:  
- **Chief Executive Officer (CEO)** – Oversees the **Sales and Marketing Division (DVM)**.  
- **Chief Operations Officer (COO)** – Oversees the **Research & Development Division (DPD)** and the **Production & Quality Division (DPQ)**.  
- **Chief Financial Officer (CFO)** – Oversees the **Finance Division (DF)** and the **Human Resources Division (DRH)**.

Additional technical teams include:  
- **Research & Development Team (ERD)** – Part of the DPD, responsible for product innovation.  
- **Production Team (EPD)** – Part of the DPQ, responsible for manufacturing and installation.  
- **Quality Control Team (ECQ)** – Ensures product compliance and functionality.

### Financial and Administrative Processes
- The **DF** is responsible for invoicing clients at the end of each month and managing payments to **QUEUE**.
- All company expenses require joint authorization from the **CEO** and **CFO**.
- Employee evaluations are conducted annually in February by the **DRH** and reported to **DEXEC**.

## BGate Portal Components

Each **BGate** portal consists of the following units:  
1. **Processing Unit (UPCM)** – Runs **BSoft** software and manages communication with other units.  
2. **Power Unit (UALI)** – Converts external AC power to DC and provides battery backup.  
3. **Reading Unit (ULEI)** – Supports multiple authentication methods, including:  
   - Video camera  
   - Fingerprint scanner  
   - Barcode/QR code reader  
   - Contact chip reader  
   - RFID, Bluetooth, NFC, or other custom protocols  
4. **Control Unit (UCRL)** – Manages access control mechanisms, including:  
   - Speaker and indicator lights  
   - Sliding doors  
   - Passage detection sensors  

### Operating Modes
- **Operational Mode**: The BGate is active, controlling access based on authentication.  
- **Controlled Passage Mode**: Default mode where doors remain closed until a valid authentication event occurs.  
- **Free Passage Mode**: Doors remain open until a command is received to close them.  
- **Inactive Mode**: The unit is disabled but can still communicate with **BGM**.  
- **Shutdown Mode**: The unit is completely powered down.  

BGate status is indicated by its **light system**, which provides visual feedback based on operational conditions.

## Request Execution Process (PEP)

A **Request Execution Process (PEP)** is initiated when a potential client submits a proposal request. The process follows these steps:

1. **Sales and Marketing Division (DVM)** reviews the request for technical and legal feasibility.
2. If qualified, the **Production Team (EPD)** creates a technical plan.
3. If modifications to the BioBox are required, the **Research & Development Team (ERD)** implements improvements.
4. The **Quality Control Team (ECQ)** reviews and approves the technical plan.
5. **DVM** drafts a contract for client approval.
6. Upon contract acceptance, **EPD** installs the BioBox system.
7. **ECQ** performs final testing and certification before handing over the system to the client.

All communications between BGB and clients are managed through the **BGBCRM system**, which stores all relevant documentation.

## Acronyms

| Acronym | Description |
|---------|------------|
| **BGB** | BIOGateBox |
| **BGBCRM** | Customer Relationship Management System |
| **BGate** | Physical access control portal |
| **BGM** | Message Queue application |
| **BSoft** | BGate software |
| **CEO** | Chief Executive Officer |
| **CFO** | Chief Financial Officer |
| **COO** | Chief Operations Officer |
| **DEXEC** | Executive Board |
| **DF** | Finance Division |
| **DPD** | Research & Development Division |
| **DPQ** | Production & Quality Division |
| **DRH** | Human Resources Division |
| **DVM** | Sales and Marketing Division |
| **ECQ** | Quality Control Team |
| **EPD** | Production Team |
| **ERD** | Research & Development Team |
| **MFA** | Multi-Factor Authentication |
| **NFC** | Near Field Communication |
| **MNGAPP** | Management Application |
| **PEP** | Request Execution Process |
| **QUEUE** | Third-party provider of BGM application |
| **RFID** | Radio Frequency Identification |
| **UALI** | Power Unit |
| **UCRL** | Control Unit |
| **ULEI** | Reading Unit |
| **UPCM** | Processing Unit |

