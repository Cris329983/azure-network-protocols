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
<img src="https://github.com/user-attachments/assets/3bf3d64a-dc1e-485b-9604-408a6d4ab48c" />

</p>
<p>
This screenshot shows a domain user accessing "READ ACCESS" and "WRITE ACCESS." The "READ ACCESS" folder is currently empty and generates a permission error message when an action is attempted, indicating that the user only has read-only access and cannot modify or add files to this folder. The "WRITE ACCESS" folder, on the other hand, contains a text document named "New Text Document," demonstrating that the user has write permissions and can add or modify files in this folder. This setup exemplifies the difference between read-only and read-write permissions on network shared folders in an IT environment.
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/c768471e-2e86-4d54-a282-df816c91835d" />
 

</p>
<p>
This screenshot shows the creation of the accountants security group and then adding "accountants" to have read and write permissions in the accountants folder.
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/8d13d3c6-d487-4069-b3f3-e5b91306c8ca" />

 

</p>
<p>
This screenshot shows the Domain Users added as members in the Accountants Security Group.
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/4b876661-69cc-4e11-a797-29f4c08603ee" />


 

</p>
<p>
Finally in this screenshot shows that one of the domain users is able to access the Accounting folder and create a file, as it was given access to read and write as part of the accountants security group.
</p>
<br />

