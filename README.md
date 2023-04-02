<h1> osticket-configuration </h1> 
In this lab exercise we explore the configuration of various osTicket user roles and SLA severities. 
<br></br>
<p align="center">
<img src="https://yunohost.org/user/images/osticket_logo.svg" height="50%" width="50%" alt="osTicket Logo"/>
</p>

<h2> Environment and Technology </h2> 

- Micosoft Azure
- Windows 10 VM
- osTicket

<h2> Configuration Steps </h2>

1. Log in to osTicket with the credentials enetered when installing. Go to the Admin panel.
<p align="center">
<img src="https://i.imgur.com/0trUjFq.png" height="50%" width="50%" alt="Navigating to Admin panel."/>
</p>

2. Click Agents, Roles, Add New Role.
<p align="center">
<img src="https://i.imgur.com/LwANded.png" height="50%" width="50%" alt="Creating New os Ticket Role."/>
</p>

3. Create a new role called "Supreme Admin". Give this role all permissions.
<p align="center">
<img src="https://i.imgur.com/5T4EMfM.png" height="50%" width="50%" alt="Creating Supreme Admin Role."/>
</p>

4. Create System Admininistrator Department. Agents, Departments, Add New Department.
<p align="center">
<img src="https://i.imgur.com/0oanSOZ.png" height="50%" width="50%" alt="Creating System Administrators department."/>
</p>

5. Create two new teams; Level I and Level II Support. Agents, Teams, Add New Team.
<p align="center">
<img src="https://i.imgur.com/xi7WiKS.png" height="50%" width="50%" alt="Creating Level I and Level II Support teams."/>
</p>

6. Allow all users to create tickets. Settings, User settings, "Registration Required" box should be unchecked. 
<p align="center">
<img src="https://i.imgur.com/P4CDgHA.png" height="50%" width="50%" alt="Allowing anyone to create tickets."/>
</p>

7. Create two new support workers. Agents, Add New Agent.
<p align="center">
<img src="https://i.imgur.com/9x7kl7P.png" height="50%" width="50%" alt="Creating two new support workers."/>
</p>
<p align="center">
<img src="https://i.imgur.com/i3LBnPc.png" height="50%" width="50%" alt="Creating two new support workers."/>
</p>

8. Create two new customers (users). Users, User Directory, Add User.
<p align="center">
<img src="https://i.imgur.com/4ram2Jv.png" height="50%" width="50%" alt="Creating two new customers."/>
</p>

9. Create 3 SLA severities. Admin panel, Manage, SLA, Add New SLA Plan.
<p align="center">
<img src="https://i.imgur.com/jzc7aZO.png" height="50%" width="50%" alt="Creating a new SLA plan."/>
</p>
<p align="center">
<img src="https://i.imgur.com/9rcIaaQ.png" height="50%" width="50%" alt="Creating Sev-A."/>
</p>
<p align="center">
<img src="https://i.imgur.com/4CgjVtl.png" height="50%" width="50%" alt="Creating Sev-B."/>
</p>
<p align="center">
<img src="https://i.imgur.com/g7rKkYL.png" height="50%" width="50%" alt="Creating Sev-C."/>
</p>

10. Create the following help topics: "Business Critical Outage", "Personal Computer Issues", "Equipment Request", and "Password Reset". Admin panel, Manage, Help Topics, Add New Help Topic.
<p align="center">
<img src="https://i.imgur.com/pddZ5TA.png" height="50%" width="50%" alt="Creating a New Help Topic."/>
</p>

