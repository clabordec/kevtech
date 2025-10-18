<h1>Creating Users and Security Groups</h1>

This project outlines the creation of both user accounts and security groups within Active Directory using the `Help Desk` account that has RSAT tools equipped on their machine.<br />

<h2>Environments and Technologies Used</h2>

- Active Directory Domain Services (Active Directory Users and Computers)

<h2>Operating Systems Used </h2>

- Windows Server 2016

<h2>High-Level Deployment and Configuration Steps</h2>

- Create the following OUs:
    - IT
    - HR
    - Engineers
- Create the following users:
    - Help Desk
    - Patty
    - Jane Foster
    - Jamie Verges
    - Eric Madson
    - Alex Bertzy
- For the user `Help Desk`, verify that the user has admin rights
- Assign `Help Desk` to the `IT` security group
- Assign `Patty`, `Jane Foster`, `Jamie Verges` to the HR OU
- Assign `Eric Madson` and `Alex Bertzy` to the Engineers OU

<br>

<h1>Actions and Observations</h1>

## Creating the Organizational Units (OUs)
### Within Active Directory Users and Computers, right click on the domain name, New, Organization Unit
<p>
<img width="1416" height="1018" alt="image" src="https://github.com/user-attachments/assets/829e03a7-38c5-415b-9dda-67299b8cf25d" />
</p>
<br />

### Create the IT, HR and Engineers OUs, be sure to have the `Protect container from accidental deletion` checkbox checked
<p>
<img width="328" height="280" alt="image" src="https://github.com/user-attachments/assets/c318c583-6d46-424a-9a57-3c9db67a8048" />
</p>
<p>
<img width="329" height="284" alt="image" src="https://github.com/user-attachments/assets/5918a892-c6e4-4b64-95f3-d174b4e8ab42" />
</p>
<p>
<img width="325" height="281" alt="image" src="https://github.com/user-attachments/assets/7f91e1df-ffab-4432-9197-f410d245fc8f" />
</p>
<p>
<img width="297" height="573" alt="image" src="https://github.com/user-attachments/assets/b66260dc-90d9-4161-96a3-4d3384a8d0c9" />
</p>
<br />

### Create the following users: `Help Desk`, `Patty`, `Jane Foster`, `Jamie Verges`, `Eric Madson` and `Alex Bertzy`, for the `Help Desk` user, provide a secure password, and set password to never expire, provide a password for the remaning users, but they will need to change their password once they log in
<p>
<img width="1002" height="1017" alt="image" src="https://github.com/user-attachments/assets/7461cc8f-d996-4ccc-a0b9-95b06b21bb34" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/3099bbd6-1d22-43e1-86ef-2a9e44947716" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/e4b6fc9f-6fd9-40d2-af2c-91d6e5a831dc" />
</p>
<br />

### Creating the user `Patty`
<p>
<img width="326" height="283" alt="image" src="https://github.com/user-attachments/assets/47a4c0a9-ce06-4d45-84ce-a1ce2d4d1c05" />
</p>
<p>
<img width="326" height="283" alt="image" src="https://github.com/user-attachments/assets/bc0cd0d9-3098-44b2-9eb7-d765eb842a3d" />
</p>
<p>
<img width="652" height="568" alt="image" src="https://github.com/user-attachments/assets/2d50adde-9062-4a2e-8394-b15ef34da712" />
</p>
<br />

### Creating the user `Jane Foster`
<p>
<img width="326" height="283" alt="image" src="https://github.com/user-attachments/assets/47a4c0a9-ce06-4d45-84ce-a1ce2d4d1c05" />
</p>
<p>
<img width="654" height="570" alt="image" src="https://github.com/user-attachments/assets/e89db431-ecde-44bc-9937-bac5278d0b1f" />
</p>
<p>
<img width="652" height="568" alt="image" src="https://github.com/user-attachments/assets/2d50adde-9062-4a2e-8394-b15ef34da712" />
</p>
<br />

### Creating the user `Jamie Verges`
<p>
<img width="326" height="283" alt="image" src="https://github.com/user-attachments/assets/47a4c0a9-ce06-4d45-84ce-a1ce2d4d1c05" />
</p>
<p>
<img width="654" height="570" alt="image" src="https://github.com/user-attachments/assets/e89db431-ecde-44bc-9937-bac5278d0b1f" />
</p>
<p>
<img width="652" height="568" alt="image" src="https://github.com/user-attachments/assets/2d50adde-9062-4a2e-8394-b15ef34da712" />
</p>
<br />

### Creating the user `Eric Madson`
<p>
<img width="326" height="283" alt="image" src="https://github.com/user-attachments/assets/47a4c0a9-ce06-4d45-84ce-a1ce2d4d1c05" />
</p>
<p>
<img width="654" height="570" alt="image" src="https://github.com/user-attachments/assets/e89db431-ecde-44bc-9937-bac5278d0b1f" />
</p>
<p>
<img width="652" height="568" alt="image" src="https://github.com/user-attachments/assets/2d50adde-9062-4a2e-8394-b15ef34da712" />
</p>
<br />

### Creating the user `Alex Bertzy`
<p>
<img width="326" height="283" alt="image" src="https://github.com/user-attachments/assets/47a4c0a9-ce06-4d45-84ce-a1ce2d4d1c05" />
</p>
<p>
<img width="654" height="570" alt="image" src="https://github.com/user-attachments/assets/e89db431-ecde-44bc-9937-bac5278d0b1f" />
</p>
<p>
<img width="652" height="568" alt="image" src="https://github.com/user-attachments/assets/2d50adde-9062-4a2e-8394-b15ef34da712" />
</p>
<br />

### Verify the user's information, click Finish
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/8102c143-e321-4e4b-b38e-b98d6c01a282" />
</p>
<br />

### Verify that `Help Desk` is part of the same groups as `Administrator`
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/4a7443de-e83f-4a96-a8d4-aed4620cb0ce" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/d8acdd8a-742f-4896-8e95-e51051317320" />
</p>

<br />

## Creating the Security Group
### In the USA OU, go to Users >> Right-click on the Accounting OU >> New > Group
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/0d090446-9386-413e-ab6b-c6495d9d27f3" />
</p>
<br />

### Specify the group name, ensure group type is Security
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/5a012fd7-772e-4d39-9223-40ae229c8eba" />
</p>
<br />

### Verify that the group has been created
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/5a012fd7-772e-4d39-9223-40ae229c8eba" />
</p>

<br />



