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
- Verify that the user have been created, For the user `Help Desk`, verify that the user has admin rights
- Assign `Help Desk` to the `IT` OU
- Assign `Patty`, `Jane Foster`, `Jamie Verges` to the `HR` OU
- Assign `Eric Madson` and `Alex Bertzy` to the `Engineers` OU

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

## Creating the users
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
<img width="326" height="282" alt="image" src="https://github.com/user-attachments/assets/cc6a7e15-5b4c-4c1a-ab6c-6660d093fd15" />
</p>
<p>
<img width="652" height="562" alt="image" src="https://github.com/user-attachments/assets/0dbe713a-b1b5-4ed7-abad-948f4e303121" />
</p>
<p>
<img width="654" height="565" alt="image" src="https://github.com/user-attachments/assets/13ac8a97-c4f4-4e98-a967-35101d12e4a9" />
</p>
<br />

### Creating the user `Jamie Verges`
<p>
<img width="326" height="284" alt="image" src="https://github.com/user-attachments/assets/f8389eac-ac89-403b-9e57-9a46de099c40" />
</p>
<p>
<img width="652" height="562" alt="image" src="https://github.com/user-attachments/assets/2d3233e8-43ea-466c-b7dd-d5b2e74b3242" />
</p>
<p>
<img width="649" height="565" alt="image" src="https://github.com/user-attachments/assets/7794e206-3057-4a6a-bae6-2b32cf01766e" />
</p>
<br />

### Creating the user `Eric Madson`
<p>
<img width="651" height="564" alt="image" src="https://github.com/user-attachments/assets/3779d94f-27ba-41fe-a72e-ebd026e54b74" />
</p>
<p>
<img width="652" height="562" alt="image" src="https://github.com/user-attachments/assets/2d3233e8-43ea-466c-b7dd-d5b2e74b3242" />
</p>
<p>
<img width="654" height="568" alt="image" src="https://github.com/user-attachments/assets/b8fb9a18-f432-4cf4-9dff-882e2595d860" />
</p>
<br />

### Creating the user `Alex Bertzy`
<p>
<img width="326" height="284" alt="image" src="https://github.com/user-attachments/assets/8a6f6e9c-822a-4052-ba1d-c1361bd34f94" />
</p>
<p>
<img width="652" height="562" alt="image" src="https://github.com/user-attachments/assets/2d3233e8-43ea-466c-b7dd-d5b2e74b3242" />
</p>
<p>
<img width="649" height="565" alt="image" src="https://github.com/user-attachments/assets/852a75ec-743e-4450-91c0-b900a69f3930" />
</p>
<br />

## Verifying the users
### Verify the user `Help Desk`, user should be apart of the same groups as the `Administrator`
<p>
<img width="1128" height="849" alt="image" src="https://github.com/user-attachments/assets/4aaae8c4-a256-4a36-949d-113954d022a6" />
</p>
<br />

### Verify the user `Patty`
<p>
<img width="1027" height="814" alt="image" src="https://github.com/user-attachments/assets/45f46d96-8ac1-4db3-b5a7-e3e3b8e09f74" />
</p>
<br />

### Verify the user `Jane Foster`
<p>
<img width="1099" height="829" alt="image" src="https://github.com/user-attachments/assets/ad32724d-864d-4b80-8f9b-da7f501c2e9a" />
</p>
<br />

### Verify the user `Jamie Verges`
<p>
<img width="1027" height="822" alt="image" src="https://github.com/user-attachments/assets/7adbee0b-fc4b-49e0-9452-4c083b691e58" />
</p>
<br />

### Verify the user `Eric Madson`
<p>
<img width="1015" height="819" alt="image" src="https://github.com/user-attachments/assets/72afb1c9-47dc-4ad2-9c33-13d3063423df" />
</p>
<br />

### Verify the user `Alex Bertzy`
<p>
<img width="1060" height="814" alt="image" src="https://github.com/user-attachments/assets/5c8da4e1-c49e-44f2-bf0d-d6bf276f2641" />
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






