# SetUpHomeFolderW-NTFSPermission

<h1>Disable Inheritance</h1>

![image](https://github.com/user-attachments/assets/e54be792-b8d5-4de5-9a67-433e3b2c3dee)

<p>
  After creating a HR home folder directory in Explorer, I opened File and Storage Services and went to Shares.
  Then, I copied the HR home folder directory path and pasted in the custom URL path. I disabled inheritance so the HR users access to the HR home folder only.
</p>


![image](https://github.com/user-attachments/assets/ed2de5a9-ce52-47bf-ad15-46461a1edf7c)

<p>
  I removed two principals Users(HuskyTech\Users) with Read & Execute and Users(HuskyTech\Users) with Special
  because the HR users are only ones not the users.
  
</p>

