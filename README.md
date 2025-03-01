# Creating Users - Group Policy and Managing Accounts
<p align="center">
<img src="https://i.imgur.com/g4LY2yK.png" width="400"/> 
</p>

<h1>Active Directory - Prerequisites and Installation</h1>
This tutorial outlines how I created users with Powershell and then went on to edit the group policy and start managing the accounts.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install Internet Information Services (IIS)
- Set up Domain Controller
- Create a Virtual Network and Subnet
- Create the Domain Controller VM's
- Log into the VM and edit the firewall

<h2>Active Directory Lab Steps</h2>

<p>
<img src="https://i.imgur.com/HtCQdID.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this image we have our code entered into Powershell that has given it orders to start generating all these different users we will be interacting with throughout the exercise.
</p>
<br />

<p>
<img src="https://i.imgur.com/UBEU4wf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here we can see in the code that all users passwords will be the same for now "Password1". This makes it easy for us to log in by simply using their username, after that we can go and edit their accounts or make changes from the admin account.
</p>
<br />

<p>
<img src="https://i.imgur.com/0sjkCpQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this simulation we wanted to make it to where a user could actually get locked out so I had to go in as the admin in grouply policy and change the account lockout settings.
