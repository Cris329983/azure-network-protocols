<p align="center">
<img src="https://github.com/user-attachments/assets/90003095-96fd-4400-a9cc-b8d5f3ba0439" />


</p>

<h1>Network File Shares and Permissions</h1>
In this tutorial, we will walk through the process of setting up and managing network file shares and permissions in a Windows environment.  <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- PowerShell
- File Explorer

<h2>Operating Systems Used </h2>

- Windows 10 
- Windows Server


<h2>High-Level Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/63c02b2f-4b58-4906-a770-febb9091ffbe" />

</p>
<p>
This screenshot shows a Windows desktop with four folder shortcuts, each representing different types of network file share permissions. The folders are labeled as follows:

WRITE ACCEESS – This folder has write permissions enabled, allowing users to add, modify, or delete files.

Accounting – This folder is designated for use by the accounting department, with restricted access based on user roles or groups.

No access – This folder is configured to deny all access, meaning users are unable to view or open its contents.

READ ACCESS – This folder provides read-only access, allowing users to view files but not make any changes.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/0e79f2ee-8918-4089-869f-437f00e09f2a" />

</p>
<p>This screenshot displays the sharing settings in properties for the READ ACCESS folder in a Windows environment, here I gave READ ACCESS to Domain Users I created with PowerShell, In the WRITE ACCESS Folder I gave the users read and write permissions and in the NO ACCESS folder I only gave read and write access to the Domain Admins.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
