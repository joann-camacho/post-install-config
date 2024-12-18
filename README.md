<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines 6 steps that cover the basics of configuring the osTicket system.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket System

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Step 1. Login Pages
- Step 2. Configure Roles, Departments & Teams
- Step 3. Allow or Require Registration to Create Tickets
- Step 4. Configure Agents (Workers)
- Step 5. Configure Users (Customers)
- Step 6. Configure SLA & Help Topics

<h2>Configuration Steps</h2>

Step 1: Login Pages
<p>

![image](https://github.com/user-attachments/assets/609d4086-936c-42ee-953e-8e119a95dace)
![image](https://github.com/user-attachments/assets/b4205a9c-c914-4748-a70b-d410b467f74d)

</p>
<p>
Admin/Analyst Login: http://localhost/osTicket/scp/login.php
  
End Users URL: http://localhost/osTicket
</p>
<br />

Step 2: Configure Roles, Departments & Teams
<p>

![image](https://github.com/user-attachments/assets/6a99deca-44e1-4a34-9612-9b5d8d100d6a)  
![image](https://github.com/user-attachments/assets/1a35c4f1-f969-45bd-9706-747ceb04fca7)
</p>
<p>
Roles: Admin Panel → Agents → Roles.

You can 'Add New Role' and configure specific 'Permissions' in this category. 

![image](https://github.com/user-attachments/assets/0b125c0d-8085-447f-a127-c0e4b5feb577)

</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/708fbccb-f44b-4e7b-8805-61b5e000777b)

</p>
<p>
Departments: Admin Panel → Agents → Departments

You can 'Add New Department' and configure specific details (dept. settings, access, add agents, etc)

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/8ec37781-c069-4ee6-859d-4e0b74d2c5b6)
  
![image](https://github.com/user-attachments/assets/dd6b4e46-aa2f-493d-ae4b-9827cfa7b89a)

</p>
<p>
Teams: Admin Panel → Agents → Teams

You can 'Add Teams' and configure specific details (add agents/ team members, change team information: active or disabled, etc.)

</p>
<br />

Step 3. Allow or Require Registration to Create Tickets
<p>

![image](https://github.com/user-attachments/assets/6938b523-aba3-4491-984e-e49c89c301d0)

</p>
<p>  
Allow Anyone to Create Tickets: Admin Panel → Settings → User Settings → UNCHECK "Unregistered users can create tickets"
  
Registration Required: Enable registration/login for ticket creation.

</p>
<br />


4. Configure Agents (Workers)

<p>

![image](https://github.com/user-attachments/assets/e10764ed-6c05-4882-8144-5f5f0dee551c)
![image](https://github.com/user-attachments/assets/1d227c1f-5708-41e5-b8d1-f62a8303985d)
![image](https://github.com/user-attachments/assets/c58d0769-c1c6-470b-bb9f-5e60687addc4)


</p>
<p>
Admin Panel → Agents → Add New Agent
  
Include the agent's username and assign a temporary password. 

Include the agent's access. Save Changes.
</p>
<br />

5. Configure Users (Customers)

<p>

![image](https://github.com/user-attachments/assets/0a312226-93d0-43d8-b4eb-b09ca8f1ec36)
![image](https://github.com/user-attachments/assets/0116abc6-53c8-4592-bd94-5004e2da0cd8)

</p>
<p>
Switch the dashboard to 'Agent Panel' on the top right of the page.

Agent Panel → Users → Add User


</p>
<br />

6. Configure SLA & Help Topics

<p>
  
![image](https://github.com/user-attachments/assets/720e675f-b123-4925-bde9-b04f673011be)
![image](https://github.com/user-attachments/assets/3285f69f-7daa-4cb5-9dee-4eeb3e4fa1d2)

</p>
<p>
  
SLA: Admin Panel → Manage → SLA (e.g., Sev-A, Sev-B, Sev-C with different grace periods)

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/c00f3250-22fc-426a-8405-179219ae20de)

</p>
<p>

Help Topics: Admin Panel → Manage → Help Topics (e.g., Business Critical Outage, Password Reset)
</p>
<br />
