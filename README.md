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
- Navigate to Admin Panel -> Agents -> Roles -> Add New Role
- Definition Tap:
    - Name Field: type in desired role, in this case it's "Supreme Admin".

<p>
<img <img width="963" height="606" alt="SupremeAdmin" src="https://github.com/user-attachments/assets/d3b42c67-940f-4eb0-916f-b4093c8fc5e0" />
</p>
      
- Permission Tap:
    - Give all permissions to Supreme Admin (Check all boxes in "Tickets", "Tasks", "Knowledgebase").
    - Click Add Role
  
<p>
<img <img width="968" height="740" alt="Tickets_Permission" src="https://github.com/user-attachments/assets/db73b494-c11f-4488-8011-caf2ee87215e" />
</p>
<p>
<img <img width="968" height="590" alt="Tasks_Permissions" src="https://github.com/user-attachments/assets/72989e7d-949d-4dbb-bdff-4a6588caa9ff" />
</p>
<p>
<img <img width="968" height="440" alt="Knowledge_Permission" src="https://github.com/user-attachments/assets/811c3525-92db-4cf9-81c9-ac3bf5b409f8" />
</p>

<br />

<h2>Adding a new Department "SystemAdmins"</h2>

- Navigate to Agents -> Departments -> Add New Department
- Name Field: type in desired department, in this case it's "SysAdmins".
- Click Create Dept
  
<p>
<img <img width="769" height="754" alt="SysAdmins" src="https://github.com/user-attachments/assets/fb8d5e52-a397-43da-85c3-062a3b63196d" />
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
    - Name, Email Address, Username for the particular agent being added.
      <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Access Tap:
     - Select Department: Department of Agent
     - Select Role: Role of Agent
       <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
       
- Permissions Tap: Check Boxs to give Agent Permissions
  <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Teams Tap:
    - Select Team: Team of Agent
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
