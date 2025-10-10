<h1>Creating Users and Security Groups</h1>
This project outlines the creation of both user accounts and security groups within Active Directory<br />


<h2>Environments and Technologies Used</h2>

- Active Directory Domain Services (Active Directory Users and Computers)


<h2>Operating Systems Used </h2>

- Windows Server 2016


<h2>High-Level Deployment and Configuration Steps</h2>

- Create the following users:
    - Help Desk
    - Patty
    - Jane Foster
    - Jamie Verges
    - Eric Madson
    - Alex Bertzy
- For the user `Help Desk`, Verify that the user has admin rights
- Create the following OUs:
    - IT
    - HR
    - Engineers
- Assign `Help Desk` to the `IT` security group
- Assign `Patty`, `Jane Foster`, `Jamie Verges` to the HR OU
- Assign `Eric Madson` and `Alex Bertzy` to the Engineers OU

<br>


<h1>Actions and Observations</h1>

## Creating the user
### In Active Directory User and Computers, click on the drop down for the company domain, and click on `Users` OU
<p>
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/dba8949b-d412-418a-bff6-7a5874debb9e" />
</p>

### Right click on the `Administrator` user and choose Copy
<p>
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/3cb285ae-3ea7-4ea9-92f1-e6cea2a7e3ae" />
</p>

### Create the `Help Desk` user, then provide a secure password, since this account has admin rights, the password will never expire
<p>
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/3099bbd6-1d22-43e1-86ef-2a9e44947716" />
</p>
<p>
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/e4b6fc9f-6fd9-40d2-af2c-91d6e5a831dc" />
</p>

### Verify the user's information, Click Finish
<p>
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/8102c143-e321-4e4b-b38e-b98d6c01a282" />
</p>

### Verify that the `Help Desk` user is apart of the same groups as the `Administrator` user
<p>
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/4a7443de-e83f-4a96-a8d4-aed4620cb0ce" />
</p>
<p>
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/d8acdd8a-742f-4896-8e95-e51051317320" />
</p>

<br />

## Creating the security group
### In the USA OU, go to Users >> Right-click on the Accounting OU >> Click New > Click Group
<p>
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/0d090446-9386-413e-ab6b-c6495d9d27f3" />
</p>

### Specify the name of the group, ensure that the group type is Security
<p>
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/5a012fd7-772e-4d39-9223-40ae229c8eba" />
</p>

### Verify that the following group has been created
<p>
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/5a012fd7-772e-4d39-9223-40ae229c8eba" />
</p>


