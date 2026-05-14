<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create Teams & Roles
- Configure Departments
- Configure SLA
- Staff Addition
- Create Help Topics

<h2>Configuration Steps</h2>

<h2>Adding a new role "Supreme Admin"</h2>

- Open http://localhost/osTicket/scp/login.php in a web brower, type in your username and password and login.
- Navigate to Agents -> Roles -> Add New Role
- Definition Tap:
    - Name Field: type in desired role, in this case it's "Supreme Admin".
- Permission Tap:
    - Give all permissions to Supreme Admin (Check all boxes in "Tickets", "Tasks", "Knowledgebase").
    - Click Add Role
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2>Adding a new Department "SystemAdmins"</h2>

- Navigate to Agents -> Departments -> Add New Department
- Name Field: type in desired department, in this case it's "SysAdmins".
- Click Create Dept
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2>Adding a new Team "Online Banking"</h2>

- Navigate to Agents -> Teams -> Add New Team
- Name Field: type in desired team name, in this case it's "Online Banking".
- Click Create Team
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2>Allowing anyone to create a ticket (Unregistered Users)</h2>

- Navigate to Settings -> Users -> Uncheck box "Require registration and login to create tickets".
- Click Save Changes
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2>Adding New Agents</h2>

- Navigate to Agents -> Agents -> Add New Agents
- Account Tap fill out:
    - Name, Email Address, Username and Set Password for the particular agent being added.
- Access Tap check
- Permissions Tap check
- Click Create

  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2>Adding New Users</h2>

- Navigate to Agents -> Users -> Add New User
- Name Field: type in the user name.
- Click Add User
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2>Adding Service Level Agreements (SLAs)</h2>

- Navigate to Manage -> SLA -> Add New SLA Plan
- Fill out the information in accordance to the SLA plan of choice.
- Click Add Plan
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2>Adding Help Topics</h2>

- Navigate to Manage -> Help Topics -> Add New Help Topic
- Topic Field: type in the relevant information for the topic of choice.
- Click Add Topic
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
