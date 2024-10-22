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
