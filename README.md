<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket: Ticket Lifecycle — From Intake to Resolution</h1>
  
Here, I’ll walk through what happens to a support ticket from the moment it’s submitted until it’s fully resolved.  
---

## ⚙️ Tools and Environment

- **Microsoft Azure** (Virtual Machines / Compute)
- **Remote Desktop**
- **Internet Information Services (IIS)**  

---

## 💻 System Info

- **Windows 10 (21H2)**  

---

##  Overview

We’ll look at how a ticket moves through each stage in osTicket:

1. Ticket Intake  
2. Assignment & Communication  
3. Working the Issue  
4. Resolution  

---

##  Stage 1: Ticket Intake — Creating a Ticket

Start by opening **osTicket** in your browser.  


Once osTicket is open, select **“Open a New Ticket.”**  
Fill out the form as follows:

- **Email:** johnson@osTicket.com  
- **Name:** Keyana Johnson  
- **Help Topic:** Business Critical Outage  
- **Issue Summary:** Entire mobile online banking is down  
- **Details:** Customers are seeing a 404 error when visiting the online banking page  

Then click **Create Ticket**.

<p align="center">
  <img src="https://i.imgur.com/G7Ak6uI.png" width="70%" alt="Creating a new ticket"/>  
  <img src="https://i.imgur.com/UdiPc1s.png" width="70%" alt="Ticket submission form"/>
</p>

---

##  Stage 2: Assignment and Communication

Next, log in to osTicket as an **Agent** (for example, `jane.doe`, which we created in Part 2).  
From the dashboard, select the ticket created in Stage 1.

<p align="center">
  <img src="https://i.imgur.com/sDgzS36.png" width="80%" alt="Agent ticket view"/>
</p>

Now, update the ticket details:

- **Priority:** Emergency — since the banking outage affects revenue  
- **Assigned To:** Jane Doe  
- **SLA Plan:** SEV-A (Critical / Business-impacting)  
- **Department:** System Administrators  
- **Response:** “Coordinating with the SysAdmin team to bring mobile banking back online.”  

Click **Post Reply** to save your response and update the ticket status.

<p align="center">
  <img src="https://i.imgur.com/Du3kmui.png" width="80%" alt="osTicket reply example"/>  
  <img src="https://i.imgur.com/yg9TXep.png" width="80%" alt="Ticket updates"/>
</p>

---

## Stage 3: Working the Issue

Behind the scenes, Jane and the **Systems Administration Team** are investigating the outage.  
They communicate and log updates directly in the ticket so the progress is visible to everyone involved.  
This step represents the actual troubleshooting phase where the problem is being worked on internally.

---

##  Stage 4: Resolution

Once the issue is fixed, it’s time to close out the ticket properly.  
Head back to the ticket and reply to the user with an update.

**Example Response:**  
> Jerry from the System Engineering team located and reconnected a failed load balancer.  
> Mobile banking services are now restored and everything should be back online.

Set the **Ticket Status** to **Resolved**, then click **Post Reply**.  
The ticket will automatically move to the **Closed** tab.

<p align="center">
  <img src="https://i.imgur.com/et8h651.png" width="80%" alt="Ticket resolved"/>  
  <img src="https://i.imgur.com/TUo3T0Q.png" width="80%" alt="Closed ticket view"/>
</p>

---

##  Wrap-Up

And that’s it! You’ve successfully taken a support ticket from start to finish — from intake to resolution.  
.  



Pretty cool seeing it all come together! 

---

**Created by:** *Kolby Sowell*  
**Project Type:** IT Help Desk / System Administration Portfolio Project  
**Platform:** osTicket (Open Source Helpdesk Ticketing System)

