# SetUpHomeFolderW-NTFSPermission

<h1>Advanced Security Setting: Disable Inheritance</h1>

![image](https://github.com/user-attachments/assets/e54be792-b8d5-4de5-9a67-433e3b2c3dee)

<p>
  After creating a HR home folder directory in Explorer, I opened File and Storage Services and went to Shares.
  Then, I copied the HR home folder directory path and pasted in the custom URL path. I disabled inheritance so the HR users access to the HR home folder only.
</p>

<br>

<h1>Advanced Security Setting: Permission Entry for HRHome Directory</h1>

![image](https://github.com/user-attachments/assets/ed2de5a9-ce52-47bf-ad15-46461a1edf7c)

<p>
  I removed two principals Users(HuskyTech\Users) with Read & Execute and Users(HuskyTech\Users) with Special
  because the HR users are only ones not the users.
  
</p>

<h1>Advanced Setting: Advanced Permissions</h1>

![image](https://github.com/user-attachments/assets/8bfb5a54-b5a8-46a9-a4b6-2b6d7737d6a0)

<p>
  <ul>
    <li>Traverse Folder / execute file</li>
    <li>List Folder /read data</li>
    <li>Create folders / append data</li>
  </ul>
</p>

<h1>Properties for Multiple Items</h1>

![image](https://github.com/user-attachments/assets/08f3e038-c5d8-4614-9991-844dadebc00b)

<p>
  Selected profile where I copied and paste \\HuskyTech\HRHome\%username%
</p>

<h1>HR Users created in the explorer file</h1>

![image](https://github.com/user-attachments/assets/b4d6073c-2a13-48a8-9618-17ab0bb9977d)

<p>
  As you can see, I changed usernames and created other two folders. The new folders will have work documents store not in the old folders.
</p>

<h2>Reigstry Editor</h2>

![Screenshot from 2024-10-23 12-24-35](https://github.com/user-attachments/assets/2e72f85e-f928-43a8-b81b-07ab67075caf)



<p>
 Opened Registry editor in Windows Run command by Regedit.
  Added DC_HuskyTech as a network location showed in the register editor. 
</p>


![Screenshot from 2024-10-23 12-25-46](https://github.com/user-attachments/assets/6ff9d823-b414-4535-b8ac-1b195bc59382)


<h2>Added a Home folder directory path</h2>

<p>
  Added \\DC_HuskyTech\Personal\%username%
</p>

<h2>Windows Explorer file in This PC</h2>

![Screenshot from 2024-10-23 12-38-10](https://github.com/user-attachments/assets/e80f9662-8e69-4303-ad18-3f89636ae643)

<p>Showed the Personal network drive on the James' computer</p>

