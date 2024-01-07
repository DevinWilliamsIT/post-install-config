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

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
1. Firstly, navigate to Admin Panel -> Agents -> Roles and create a role, once you've created a new role give it as many permissions as you'd like, for this tutorial I named it Supreme Admin and gave it all permissions.
  (Agents assigned to this role will be able to do anything)
</p>

![image](https://github.com/DevinWilliamsIT/post-install-config/assets/155914712/b4ebb80f-b5b1-4a72-b0e8-141ea0ffd094)

<br />

<p>
2. Next navigate to Admin Panel > Agents > Departments and create a new department with the default settings. (I named the department System Administrators)
</p>

![image](https://github.com/DevinWilliamsIT/post-install-config/assets/155914712/79aec968-689f-428f-bdda-ba058f3dfeff)

<br />

<p>
3. Next navigate to Admin Panel > Agents > Teams and create a team. (For this tutorial I named the team Level II Support)
</p>

![image](https://github.com/DevinWilliamsIT/post-install-config/assets/155914712/372dcb3b-d4e5-4134-838b-332b7a8f5093)

<br />


