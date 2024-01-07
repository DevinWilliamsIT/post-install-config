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
1. Firstly, navigate to Admin Panel -> Agents -> Roles and create a role, once you've created a new role give it as many permissions as you'd like.
</p>
<p>Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.</p>

![image](https://github.com/DevinWilliamsIT/post-install-config/assets/155914712/b4ebb80f-b5b1-4a72-b0e8-141ea0ffd094)

<br />

<p>
2. Next navigate to Admin Panel > Agents > Departments and create a new department.
</p>


![image](https://github.com/DevinWilliamsIT/post-install-config/assets/155914712/79aec968-689f-428f-bdda-ba058f3dfeff)

<br />

<p>
3. Next navigate to Admin Panel > Agents > Teams and create a team.
</p>
<p>Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.</p>

![image](https://github.com/DevinWilliamsIT/post-install-config/assets/155914712/372dcb3b-d4e5-4134-838b-332b7a8f5093)

<br />

<p>
  4. Next we need to allow everybody to make tickets, navigate to Admin Panel -> Settings -> User Settings and make sure this box is unchecked.
</p>

![image](https://github.com/DevinWilliamsIT/post-install-config/assets/155914712/9be33c6e-b7af-47ad-9922-df6cc2c96da4)

<br />

<p>
  5. Next we have to configure agents, navigate to Admin Panel -> Agents -> Add New and add however many agents (help desk professionals) you would like.
</p>

![image](https://github.com/DevinWilliamsIT/post-install-config/assets/155914712/5a4646c8-fdd4-4ce0-a312-dff0e3794386)

<p>
  While adding new agents you can also assign their teams and permissions.
</p>

![image](https://github.com/DevinWilliamsIT/post-install-config/assets/155914712/b58122eb-4a86-4227-a82b-b385156addda)

<p>
  Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.
</p>





