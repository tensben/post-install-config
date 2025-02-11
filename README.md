<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
Congratulations, we have successfully installed and configured the osTicket system. We will start administrative work by configuring roles and permissions within the osTicket system. Roles are given permitted for certain people. Go to Admin Panel > Agents > Roles. Add a new role, enter the name of the new role. This new role is called Supreme Adim, which will have all permissions. Next, go to permission, check every box to give full access, and click on Add Role.  You should see Supreme Adim in Roles.
</p>
<br />
<p>
  
![Screenshot 2025-01-13 120511](https://github.com/user-attachments/assets/9a438e85-3ce2-438d-a6c7-0d340866f6d4)

![Screenshot 2025-01-13 120617](https://github.com/user-attachments/assets/9123a8e1-36c1-4321-955f-5e6a1f4fe22f)

![Screenshot 2025-01-13 120633](https://github.com/user-attachments/assets/6a8de8b8-9914-4b8e-b7bc-0b6866c49c0b)

![Screenshot 2025-01-13 120648](https://github.com/user-attachments/assets/bdc7c605-9b9e-40bc-bc9d-cc71a67322e3)

![Screenshot 2025-01-13 120922](https://github.com/user-attachments/assets/e1057458-e8ff-415d-bcf5-43b3e03a0136)

</p>
<p>
Agents are going to be assigned to different departments that we are creating. In the Agents tab, select Departments, and click on Add New Department. Write System Administrators or SysAdmin and hit Create. You should see SysAdmins added to the list.
</p>
<br />

<p>
  
![Screenshot 2025-01-13 121235](https://github.com/user-attachments/assets/c57f2abc-7fd0-4862-92ff-1c8c615b3af2)

![Screenshot 2025-01-13 121329](https://github.com/user-attachments/assets/8a24cef7-c840-41c4-9775-525cea8137ba)

</p>
<p>
Next, we will configure and create a new team in the Admin panel.  Teams allow you to assign and pull agents from different departments who are the best technicians in their departments. In the Admin Panel > Agents > Teams, name the team. I will name my Online Banking.
</p>
<br />

<p>
  
![Screenshot 2025-01-13 121601](https://github.com/user-attachments/assets/bfb187d7-d342-489b-bcfb-b5265e151c33)

After configuring teams, we will change the settings so anyone can create tickets. In the Admin Panel, go to Settings > User Settings in  Authentication Request and uncheck Registration Required. 

</p>
<p>

![Screenshot 2025-01-13 121711](https://github.com/user-attachments/assets/b586cb87-cf8f-4862-ac38-bad2653cb9a8)


Let's onboard some new Agents. Agents are employees who help solve tickets. They are the help desk. They are assigned within the companies. Agents provide tech support for a specific department. They may also be transferred to other departments that may need assistance.  To configure Agents, go to Admin Panel >Agents > Add New. Create at least two agents and assign them a username and password. When setting their password uncheck, send the agent a password reset email. Also, place them in the departments you created earlier. For example, select the department and role when developing new agents in Access.
</p>
<br />

<p>
  
![Screenshot 2025-01-13 122017](https://github.com/user-attachments/assets/a1a9adbe-c6de-4f70-8653-eb86b2d6795d)

![Screenshot 2025-01-13 122153](https://github.com/user-attachments/assets/9f2c05a9-5c78-453d-a8c6-03c0f7f28bd0)

![Screenshot 2025-01-13 122313](https://github.com/user-attachments/assets/7de92254-b645-4e52-bdaa-516129b160e5)

![Screenshot 2025-01-13 122357](https://github.com/user-attachments/assets/a01c213f-c6ff-47c2-b067-e41f1445d16d)

![Screenshot 2025-01-13 123533](https://github.com/user-attachments/assets/3520cd84-0c8b-421c-af4b-04364fee4da2)

</p>
<p>
Once you finish creating the Agents, let's make the users. Users are customers or internal employees who need assistance by creating tickets to explain their issues. Select the Agent Panel, then Users, and then Add New. Create one or two users.
</p>
<br />

<p>
  
![Screenshot 2025-01-13 123751](https://github.com/user-attachments/assets/518695f5-9966-42e3-ba58-c62d5e3f69c3)

![Screenshot 2025-01-13 124055](https://github.com/user-attachments/assets/8a05e7d9-16cc-4be4-9c28-953a088a1768)

![Screenshot 2025-01-13 124420](https://github.com/user-attachments/assets/0b16cb3a-bae2-4b9a-8039-64cb0af39566)

</p>
<p>
Service-level agreements (SLAs) describe the time you have to resolve tickets or complete a specific task. To configure an SLA, select Admin Panel > Manage > SLA. We will create three SLAs, each with a different grace period. For example, the SEV-A grace period is one hour. If the ticket is not completed within the hour, it will be marked overdue.
</p>
<br />

<p>
  
![Screenshot 2025-01-13 124505](https://github.com/user-attachments/assets/e48af68d-f191-4898-b806-0432035480fa)

![Screenshot 2025-01-13 124653](https://github.com/user-attachments/assets/b9e9310b-ca62-4d18-8642-34f7f4235483)

![Screenshot 2025-01-13 124803](https://github.com/user-attachments/assets/bbe32e15-d6d3-42c4-b8cd-34fcc7a71b5d)

![Screenshot 2025-01-13 124915](https://github.com/user-attachments/assets/3b70d8a3-e9e1-43da-8d68-ef45681c5bfb)

![Screenshot 2025-01-13 125004](https://github.com/user-attachments/assets/c6cfa040-e340-4e8f-9198-f5606b82d1bb)

</p>
<p>
Help Desk Topics are used when users create a ticket with a topic problem that they have. They can select topics that are given to them. To make help desk topics, go to Admin Panel > Manage > Help Topics.
</p>
<br />

<p>

![Screenshot 2025-01-13 125639](https://github.com/user-attachments/assets/08a1f53b-8863-4e7b-953f-c1af127efcb4)

![Screenshot 2025-01-13 125754](https://github.com/user-attachments/assets/a3bc4357-150c-4356-80fb-578ae6b3dee9)

![Screenshot 2025-01-13 125945](https://github.com/user-attachments/assets/c45917ae-47ed-41ff-a158-a7bfbb7b4198)

![Screenshot 2025-01-13 130106](https://github.com/user-attachments/assets/f1513de9-7ade-4704-9d71-b84954331b6d)

![Screenshot 2025-01-13 130233](https://github.com/user-attachments/assets/c74a7eed-7f24-430b-84d0-7c70314785e6)

![Screenshot 2025-01-13 130337](https://github.com/user-attachments/assets/38e16fa9-a31a-4485-bc5c-0e58f4c9b820)

![Screenshot 2025-01-13 130817](https://github.com/user-attachments/assets/a5df7f65-d3ec-4bf6-99e8-e47742c44f9f)




</p>
