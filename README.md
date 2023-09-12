<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)


<h2>Deployment and Configuration Steps</h2>


![image](https://github.com/droderickb/configure-ad/assets/138819497/2b457581-c2e0-42bc-8fa9-1c4843143c6c)

<p>
Create two virtual machines, one as the domain control and the other as a client host. 

![image](https://github.com/droderickb/configure-ad/assets/138819497/b2b4435a-43bf-460d-95ca-c865346daeb9)

 Using the Azure cloud as the service to set up the environment. The domain control will be the server used in Windows server and have active directory installed on it. The client virtual machine will used as a user account created to join onto the domian controller.

