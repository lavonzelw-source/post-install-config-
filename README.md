# post-install-config-
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the post-install configuration of the open -source help desk ticketing system osTicket.






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

Post-Install Configuration Objectives
1. Understand Panel Access: Recognize the difference between the Agent Panel and the Admin Panel.
2. Define Roles: Configure Roles to set specific permissions for agents.
3. Organize Departments: Create Departments to categorize and manage incoming tickets efficiently.
4. Build Teams: Establish Teams to group agents across multiple departments for collaborative support.
5. Adjust User Settings: Configure User Settings to control who can create or manage tickets.
6. Add Agents and Users: Register Agents (staff members) and Users (customers) in the system.
7. Set SLAs: Define Service Level Agreements (SLAs) to establish expected ticket response and resolution times.
8. Create Help Topics: Develop Help Topics to guide users in categorizing their ticket submissions accurately.

CONFIGURATION STEPS
1. ACKNOWLEDGE AGENT PANEL Vs. ADMIN. PANEL
- The Agent Panel is used by the workers to deal with the tickes vs. Admin Panel are used to manage permissions, settings, configurations etc. 
2. CONFIGURE ROLES
  - Go to Admin Panel - Agents - roles - add ne role named "Supreme Admin".
  - Establish role-based permissions to control agent access and functionality within the system.
3. CONFIGURE DEPARTMENTS
- Go to admin panel - agents - departments
- Add a new department "SysAdmins
  
4. CONFIGURE TEAMS
- Go to Admin Panel - Agents - Teams.
- Create a new team "Online Banking" - You will get agents from various departments to create special teams

7. ALLOW ANYONE TO CREATE TICKETS
- Go to Admin panel - settings - user settings - uncheck "Require Registration", Login to create tickets
- Enable Public Access - Now anyone is able to register to disable the Prerequisite that users must register before creating a ticket. 

9. CONFIGURE AGENTS
- Admin Panel - Agents - Add New Worker

11. CONFIGURE USERS
- Agent Panel - Users - Add New
  
13. CONFIGURE SLA
- Admin Panel - Manage - SLA
15. CONFIGURE HELP TOPICS
- Admin Panel - Manage - Help Topics
- Add these help topics for users to select - Equipment Request, Personal Computer issues, Business Critical Outage, Password Reset

SUMMARY & CONCLUSION
By completing the post-installation configuration, you have successfully tailored osTicket to meet your organization’s specific needs. The system is now fully prepared for use, enabling you to efficiently manage and resolve customer inquiries and support requests.

