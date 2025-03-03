<p align="center">
<img src=https://github.com/user-attachments/assets/1e9245e8-ffcf-4492-bf14-38f3c738a874 />
</p>

<h1>Setting up Roles and an SLA within osTicket.</h1>
This project goes over how to create roles and an SLA within osTicket
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10 Pro (Version 22H2)

<h2>Deployment and Configuration Steps</h2>

<p align="center">
From the Admin Panel of osTicket, navigate to the Agents Tab, and click 'Roles'. <br/>
<img src=https://github.com/user-attachments/assets/f1ef4598-3e8c-4e9f-8c91-3a42edb5de8a />
<br/>
<br/>
Click 'Add New Role', name it whatever you'd like, and head over to Permissions and give whatever permissions you'd like the role to have. Repeat as many times as you need for your organization's needs. Click 'Add Role' at the bottom once ready. <br/>
<img src=https://github.com/user-attachments/assets/52888b98-ae31-4265-a031-972222f11bf0 />
<br/>
<br/>
Still on the 'Agents' main tab, click on Departments. <br/>
<img src=https://github.com/user-attachments/assets/db911c2a-c702-4caf-a5bf-1db078f11eec />
<br/>
<br/>
Click on 'Add New Department', and fill in the information as needed. Repeat as many times as required for the amount of departments you'll need. <br/>
<img src=https://github.com/user-attachments/assets/e584a875-2191-4871-a856-98ceba74e607 />
<br/>
<br/>
You may also do the same with 'Teams' to put individual Agents in for organizational purposes to help keep various tickets organized. <br/>
<img src=https://github.com/user-attachments/assets/a1bf766b-9bd5-4ccc-af39-c4006f853b2c />
<br/>
<br/>
To allow anyone to create a ticket, navigate to the Settings Tab in the Admin panel, go to 'Users', and make sure 'Require registration and login to create tickets' is UNCHECKED. <br/>
<img src=https://github.com/user-attachments/assets/210f8327-72a1-48a0-86b3-52db5e3c4b76 />
<br/>
<br/>
To add Agents that will handle the various tickets, from the Admin panel, click on the Agents tab, then Agents, and 'Add New Agent'. Fill in the information as required, making sure to place the Agent in the required Department that they will be working in and with. <br/>
<img src=https://github.com/user-attachments/assets/30019c9f-ad57-4f4a-be97-c6390b9f03d0 />
<img src=https://github.com/user-attachments/assets/04d9d7ce-286d-4ae4-9656-6e7e10ef98ad />
<img src=https://github.com/user-attachments/assets/4cc414f5-36b3-4891-9ec9-49890ecd85d9 />
<br/>
<br/>
To create an SLA for your organization, from the Admin Panel, click on the 'Manage' tab, then 'SLA'. <br/>
<img src=https://github.com/user-attachments/assets/aad9cd5e-e741-4e91-8fb4-48fb9e2739c1 />
<br/>
<br/>
From here, click 'Add New SLA Plan', and enter in the information as needed. You can set the grace period, in hours, before a ticket will be marked as overdue, and a schedule that will be used for rendering a ticket Overdue. Repeat this process for however many SLA Plans you require. <br/>
<img src=https://github.com/user-attachments/assets/884b4fce-1283-439d-89d8-4545f409c14f />
<br/>
<br/>
Once finished, you now have a basic setup for a ticketing system!












