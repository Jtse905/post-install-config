# post-install-config
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

- Installed/setup osTicket
- Configured SQL to osTicket for database 

<h2>Configuration Steps</h2>

<p>
In this lab, we will create and configure agents, teams, departments, and permissions within osTicket. 
</p>
<br />

<p>
<img width="1190" height="1115" alt="1" src="https://github.com/user-attachments/assets/d6087b71-bbce-4fcc-9780-03c48871a828" />
</p>
<p>
We will start by logging into osTicket and creating a new role. 
</p>
<br />

<p>
<img width="1245" height="1078" alt="2" src="https://github.com/user-attachments/assets/ee2f1cd9-9846-47f0-9a98-d5a19f88fa22" />
</p>
<p>
Once we are logged in, you will be at the Admin Panel Dashboard. 
</p>
<br />

<p>
<img width="1246" height="1096" alt="3" src="https://github.com/user-attachments/assets/5af93954-c2eb-4ead-922e-1db67ccad9b1" />
</p>
<p>
Click on the "Agents" tab that is on the top bar. In the "Agents" tab, click on "Roles". 
</p>
<br />

<p>
<img width="1250" height="1075" alt="4" src="https://github.com/user-attachments/assets/1d461559-fe80-410e-94b1-2375d5483f53" />
</p>
<p>
To add a new role, click on "Add New Role" on the right side of the roles screen. 
</p>
<br />

<p>
<img width="1246" height="1145" alt="5" src="https://github.com/user-attachments/assets/9241dd57-057e-48db-b23b-ea51208c525a" />
</p>
<p>
Click the gold "Add Role" button. Here you will be able to set permissions for the new role you have created. Once configured, click the gold "Add Role" button to continue. 
</p>
<br />

<p>
<img width="1246" height="1147" alt="6" src="https://github.com/user-attachments/assets/85b02168-2623-4465-87e9-3ebf495bc361" />
</p>
<p>
Here you are able to see the new role you have created in the "Roles" list. Next, we will create a new department. 
</p>
<br />

<p>
<img width="1246" height="1147" alt="7" src="https://github.com/user-attachments/assets/038d089e-78c7-41bc-9f59-7aa3e528c8f6" />
</p>
<p>
To create a new department, click "Departments" in the "Agents" tab, then click "Add New Department". 
</p>
<br />

<p>
<img width="1250" height="1153" alt="8" src="https://github.com/user-attachments/assets/51ef3dbf-abe0-4720-bf46-1ef311e499fc" />
</p>
<p>
Here you will name your department and configure it. Once configured, click the gold "Create Dept" button at the bottom. 
</p>
<br />

<p>
<img width="1244" height="1161" alt="9" src="https://github.com/user-attachments/assets/30157f6b-be7b-4991-ba66-7f48768447bd" />
</p>
<p>
After creation, you can view the new department in the "Departments" list. Next we will create a new team. 
</p>
<br />

<p>
<img width="1258" height="570" alt="10" src="https://github.com/user-attachments/assets/94e3ee32-100f-4af2-a4d8-22eb2cbf1ed8" />
</p>
<p>
To begin creating a new team, click "Teams" in the "Agents" tab. Here, click "Add New Team". 
</p>
<br />

<p>
<img width="1245" height="510" alt="11" src="https://github.com/user-attachments/assets/3831b9d3-7502-4025-920a-8b87a5fdd173" />
</p>
<p>
For this lab we will name the new team "Online Banking". Once you name your team, click on the gold "Create Team" button at the bottom. 
</p>
<br />

<p>
<img width="1238" height="760" alt="12" src="https://github.com/user-attachments/assets/e8522303-31b2-4cac-86d2-5b3471a168e3" />
</p>
<p>
After creation, you can view the new team you have created in the "Teams" list. 
</p>
<br />

<p>
<img width="1244" height="676" alt="13" src="https://github.com/user-attachments/assets/e49875cc-e242-46c7-ade1-d43d678a3770" />
</p>
<p>
If you would like to configure extra settings, such as allowing users without an account create tickets, click the "Settings" tab at the top of osTicket. Once in the settings, go to "Users". You can adjust the "Registration Required" setting. 
</p>
<br />

<p>
<img width="969" height="728" alt="14" src="https://github.com/user-attachments/assets/90c91fd9-e8db-4603-9376-56c7a5d31102" />
</p>
<p>
Next, we will create a new Agent. To create a new Agent, click on the "Agents" tab. Once there, click on "Agents". Then click on "Add New Agent". 
</p>
<br />

<p>
<img width="1084" height="511" alt="15" src="https://github.com/user-attachments/assets/18f0ae69-c75d-4d64-8e97-49cbb57d205f" />
</p>
<p>
Fill out the Agents information. Then go to the "Access" tab next.
</p>
<br />

<p>
<img width="1109" height="1039" alt="16" src="https://github.com/user-attachments/assets/7fbb2ae8-930d-4cc9-9425-53a59f6ff724" />
</p>
<p>
Here, you are able to assign the new Agent to a department, for this lab I assigned the Agent to the Sys Admin department I created with Ultra Admin permission role I created earlier. 
</p>
<br />

<p>
<img width="1100" height="740" alt="17" src="https://github.com/user-attachments/assets/511fe57d-3ba9-4739-86ab-1180e8f64a79" />
<img width="1092" height="548" alt="18" src="https://github.com/user-attachments/assets/2aa655c7-951d-4a25-a74c-5a6ee70f7c4c" />
</p>
<p>
Once you have set the Agents access, you can also assign the Agent to a Team. In this lab, I assigned the new Agent to the Online Banking Team I created earlier in this lab. 
</p>
<br />

<p>
<img width="1030" height="474" alt="19" src="https://github.com/user-attachments/assets/175794db-8640-4559-a300-219647d3ad00" />
</p>
<p>
Here you can see the new Agent you have created in the "Agents" list. 
</p>
<br />
