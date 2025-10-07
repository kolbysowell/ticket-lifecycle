<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket - Ticket Lifecycle: From Intake to Resolution</h1>

This project serves as **Part 3** in my osTicket tutorial series.  
In this section, I demonstrate the complete lifecycle of a helpdesk ticket — from initial submission to final resolution — within the open-source ticketing platform **osTicket**.

---

## 🧩 Technologies & Tools Utilized

- **Microsoft Azure** – Virtual Machines / Compute Resources  
- **Remote Desktop Protocol (RDP)**  
- **Internet Information Services (IIS)**  

---

## 💻 Operating System Used

- **Windows 10 (21H2)**  

---

## 🔁 Ticket Lifecycle Overview

- Ticket Intake  
- Assignment & Communication  
- Issue Resolution Process  
- Closing the Ticket  

---

## 📝 Stage 1: Ticket Intake – Creating a New Ticket

Launch **osTicket**.  
If osTicket has not yet been installed or configured, refer to:

- [Part 1 – Prerequisites & Installation](https://github.com/RoslyndWilliams/osTicket--Prerequisites-and-Installation)  
- [Part 2 – Post-Install Configuration](https://github.com/RoslyndWilliams/osTicket--Post-Install-Configuration)  

Create a new support ticket using the following details:

- **Email Address:** johnson@osTicket.com  
- **Name:** Keyana Johnson  
- **Help Topic:** Business Critical Outage  
  - **Issue Summary:** Mobile online banking system is down  
  - **Details:** Customers are receiving a 404 error when accessing the online banking portal  

<p align="center">
  <img src="https://i.imgur.com/G7Ak6uI.png" width="70%" alt="osTicket ticket creation"/>  
  <img src="https://i.imgur.com/UdiPc1s.png" width="70%" alt="osTicket help topic"/>
</p>

---

## 🧭 Stage 2: Assignment & Communication

Log in to osTicket as an **Agent** (for example, the `jane.doe` account created in the previous tutorial).  
Select the ticket submitted in Stage 1.

<p align="center">
  <img src="https://i.imgur.com/sDgzS36.png" width="80%" alt="osTicket agent view"/>
</p>

Update the ticket details as follows:

- **Priority:** Emergency (business-critical outage)  
- **Assigned To:** Jane Doe  
- **SLA Plan:** SEV-A (Severe – critical incident)  
- **Department:** System Administrators (responsible for mobile banking infrastructure)  
- **Response Message:** “Coordinating with the SysAdmin team to restore mobile banking services.”  

Select **Post Reply** to update the ticket.

<p align="center">
  <img src="https://i.imgur.com/Du3kmui.png" width="80%" alt="osTicket reply"/>  
  <img src="https://i.imgur.com/yg9TXep.png" width="80%" alt="osTicket SLA setup"/>
</p>

---

## ⚙️ Stage 3: Working the Issue

Behind the scenes, Jane collaborates with the **Systems Administration Team** to identify and fix the issue causing the outage.  
All communication and status updates can be logged directly in osTicket for visibility and documentation.

---

## ✅ Stage 4: Resolution & Ticket Closure

Once the issue has been resolved, update the end user:

**Response:**  
> Jerry from System Engineering identified and reconnected a failed load balancer.  
> Mobile banking services have been restored.

- **Ticket Status:** Resolved  
- Click **Post Reply**

The ticket will now automatically move to the **Closed** tab, marking the end of the support lifecycle.

<p align="center">
  <img src="https://i.imgur.com/et8h651.png" width="80%" alt="osTicket resolution"/>  
  <img src="https://i.imgur.com/TUo3T0Q.png" width="80%" alt="osTicket closed ticket"/>
</p>

---

## 🎉 Completion

You’ve successfully created, managed, and resolved a ticket within osTicket!  
This concludes **Part 3** of my osTicket tutorial series, covering the **full ticket lifecycle** — from intake through resolution.

---

**Author:** Kolby Sowell  
**Project Type:** IT Help Desk / System Administration Portfolio Project  
**Platform:** osTicket (Open Source Helpdesk Ticketing System)  
