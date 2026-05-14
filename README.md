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
<img <img width="966" height="707" alt="OnlineBanking" src="https://github.com/user-attachments/assets/733dff66-7337-4bee-9426-21af1587ca7b" />
</p>

<br />

<h2>Allowing anyone to create a ticket (Unregistered Users)</h2>

- Navigate to Settings -> Users -> Uncheck box "Require registration and login to create tickets".
- Click Save Changes
  
<p>
<img <img width="966" height="707" alt="UserSetting_UnCheckBox" src="https://github.com/user-attachments/assets/bc97053a-adf8-48d1-ae04-5c814b4ce4e7" />
</p>

<br />

<h2>Adding New Agents</h2>

- Navigate to Agents -> Agents -> Add New Agents
- Account Tap fill out:
    - Name, Email Address, Username for the particular agent being added.
      <p>
<img <img width="864" height="782" alt="JaneDoe_Agent" src="https://github.com/user-attachments/assets/01518f03-7515-4907-bce2-c09ee4cec689" />
</p>

- Access Tap:
     - Select Department: Department of Agent
     - Select Role: Role of Agent
       <p>
<img <img width="864" height="515" alt="Assign_Access" src="https://github.com/user-attachments/assets/ccabd3ac-c474-4a1c-9300-de3538acf96b" />
</p>
       
- Permissions Tap: Check Boxs to give Agent Permissions
  <p>
<img <img width="864" height="482" alt="Assign_Permissions" src="https://github.com/user-attachments/assets/368bb77a-1119-447e-9de0-41bbff7978f6" />
</p>

- Teams Tap:
    - Select Team: Team of Agent
<p>
<img <img width="876" height="416" alt="Assign_Team" src="https://github.com/user-attachments/assets/076bb566-487d-40f3-9632-65fa1f2cca36" />
</p>

- Click Create

<br />

<h2>Setting Agent's Passwords</h2>

- Navigate to Admin Panel -> Agents -> Agents -> select the Agent thats needs to Set their Password.
- Under Authentication section next to username, click "Set Password"
- Uncheck box "Send the agent a password reset email"
- Enter New Password
- Confirm New Password
- Uncheck box "Require password change at next login"
- Click Update
  
<p>
<img <img width="876" height="603" alt="SettingPassword" src="https://github.com/user-attachments/assets/327f5763-7981-477f-932e-5fb3b6004f3c" />
</p>

<br />

<h2>Adding New Users</h2>

- Navigate to Agent Panel -> Users -> Add New User
- Email Field: type user's email. 
- Name Field: type in the user's name.
- Click Add User
  
<p>
<img <img width="876" height="478" alt="Adding_Users" src="https://github.com/user-attachments/assets/7cbaa2b5-f4e5-401f-bde4-a92599aac2bc" />
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
