<h1>Creating Users and Security Groups</h1>
This project outlines the creation of both user accounts and security groups within Active Directory<br />


<h2>Environments and Technologies Used</h2>

- Active Directory Domain Services (Active Directory Users and Computers)


<h2>Operating Systems Used </h2>

- Windows Server 2016


<h2>High-Level Deployment and Configuration Steps</h2>

- Create the user named `Help Desk` and give the user admin rights
- Verify that the user has admin rights
- Create a security group named `IT`
- Assign `Help Desk` to the `IT` security group


<br>


<h1>Actions and Observations</h1>

## Creating the user
### In Active Directory User and Computers, click on the drop down for the company domain, and click on `Users` OU
<p>
<img width="978" height="934" alt="image" src="https://github.com/user-attachments/assets/dba8949b-d412-418a-bff6-7a5874debb9e" />
</p>

### Right click on the `Administrator` user and choose Copy
<p>
<img width="844" height="846" alt="image" src="https://github.com/user-attachments/assets/3cb285ae-3ea7-4ea9-92f1-e6cea2a7e3ae" />
</p>

### Create the `Help Desk` user, then provide a secure password, since this account has admin rights, the password will never expire
<p>
<img width="651" height="562" alt="image" src="https://github.com/user-attachments/assets/3099bbd6-1d22-43e1-86ef-2a9e44947716" />
</p>
<p>
<img width="651" height="561" alt="image" src="https://github.com/user-attachments/assets/e4b6fc9f-6fd9-40d2-af2c-91d6e5a831dc" />
</p>

### Verify the user's information, Click Finish
<p>
<img width="326" height="280" alt="image" src="https://github.com/user-attachments/assets/8102c143-e321-4e4b-b38e-b98d6c01a282" />
</p>

### Verify that the `Help Desk` user is apart of the same groups as the `Administrator` user
<p>
<img width="612" height="832" alt="image" src="https://github.com/user-attachments/assets/4a7443de-e83f-4a96-a8d4-aed4620cb0ce" />
</p>
<p>
<img width="612" height="829" alt="image" src="https://github.com/user-attachments/assets/d8acdd8a-742f-4896-8e95-e51051317320" />
</p>


<br />


## Creating the security group
### In the USA OU, go to Users >> Right-click on the Accounting OU >> Click New > Click Group
<p>
<img src="https://github.com/user-attachments/assets/0d090446-9386-413e-ab6b-c6495d9d27f3" width="550" alt="Disk Sanitization Steps"/>
</p>

### Specify the name of the group, ensure that the group type is Security
<p>
<img src="https://github.com/user-attachments/assets/5a012fd7-772e-4d39-9223-40ae229c8eba" width="550" alt="Disk Sanitization Steps"/>
</p>

### Verify that the following group has been created
<p>
<img src="https://github.com/user-attachments/assets/1c97b9bb-b911-4b4f-ad08-ab8c158e1541" width="550" alt="Disk Sanitization Steps"/>
</p>

<br />

## Assiging the user to the group
### Right click on the Clerks security group, then click Properties
<p>
<img src="https://github.com/user-attachments/assets/02e3bbad-dee0-41e4-9a9d-5335567e4b98" width="550" alt="Disk Sanitization Steps"/>
</p>

### Go to the Members tab, then click Add
<p>
<img src="https://github.com/user-attachments/assets/7f5c9c74-b8e5-4b8b-8cd2-a204eb8f513a" width="550" alt="Disk Sanitization Steps"/>
</p>

### Enter the object name, in this case the user name, then click Check Names, the users full name along with their email address will appear in the object names input box, then click OK
<p>
<img src="https://github.com/user-attachments/assets/2c21d4b6-d7f6-4756-85b5-e86bb9419e04" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/20271d99-172d-44aa-8073-24b8334801a8" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click Apply
<p>
<img src="https://github.com/user-attachments/assets/df78d16b-ecba-4056-b74b-2139ecb35081" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click OK
<p>
<img src="https://github.com/user-attachments/assets/1449ef56-0dc8-49e8-8b4a-f4d431d6e68f" width="550" alt="Disk Sanitization Steps"/>
</p>

<br />

## Verify the changes
### Right click on John Doe, then click Properties
<p>
<img src="https://github.com/user-attachments/assets/de9d1306-01b4-4a40-94e9-67a141f02368" width="550" alt="Disk Sanitization Steps"/>
</p>

### Go to the Members Of tab, and verify that the Clerks security group is in the tab
<p>
<img src="https://github.com/user-attachments/assets/d58eeaa2-4617-44aa-88e4-f438e13b0f5f" width="550" alt="Disk Sanitization Steps"/>
</p>

---

<br />


# End of Project

