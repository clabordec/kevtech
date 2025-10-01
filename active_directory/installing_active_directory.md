## Installing and setting up Active Directory
### Within Server Manager, go to Manage >> Add Roles and Features
<p>
<img src="https://github.com/user-attachments/assets/28842a3d-154e-43de-8485-3e4d7836935b" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/ca78a244-d6c0-4d50-af1c-e5c1b2eb529c" width="550" alt="Disk Sanitization Steps"/>
</p> 

### Choose `Role-based or featured-based installation` then click Next
<p>
<img src="https://github.com/user-attachments/assets/472df778-2402-41ec-9328-9032fdff3cf4" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Choose `Select a Server from the server pool` then click Next
<p>
<img src="https://github.com/user-attachments/assets/e3de74af-56b1-4d33-92dd-ec5a65f5dccb" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Add the following `Active Directory Domain Services` Role then click Next
<p>
<img src="https://github.com/user-attachments/assets/208d19d9-3a48-4169-b262-f2b72b1543b5" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Make sure that Group Policy Management is checked then click Next
<p>
<img src="https://github.com/user-attachments/assets/baa0e613-1501-4f75-8919-36975906403e" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/46e4e047-1843-4f30-9d00-70060a26e6cd" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Install after review all of the Roles and Features
<p>
<img src="https://github.com/user-attachments/assets/6836fed2-58b6-4a7f-ad3d-d40a61a1ff59" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />


## Promoting the server as a Domain Controller
### Once the installation for AD DS has been completed click on `Promote this server to a domain controller`
<p>
<img src="https://github.com/user-attachments/assets/0460ced4-e359-4f1c-98fb-0c87307ff1ce" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Under `Select the deployment operation` choose `Add a forest`, then provide a domain name, in this case I will use `chaanyah.com` as the domain name, then click Next
<p>
<img src="https://github.com/user-attachments/assets/36f6c3b3-0903-4462-92b6-0748abc561fa" width="550" alt="Disk Sanitization Steps" />
</p>
<br />

### Be sure to keep the `Forest Function Level` and `Domain Function Level` set to Windows Server 2016, and enter a secure password for the domain, then click Next
<p>
<img src="https://github.com/user-attachments/assets/fe61dff2-8390-445e-8714-fdfb8c981039" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/67fc3d2c-4f59-4171-81a3-b8cfe23e274a" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### The NetBIOS domain name will appear as the domain name without the `.com`, click Next
<p>
<img src="https://github.com/user-attachments/assets/9d478166-6bfc-4c9e-8f02-1e3473c1f4b0" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/fea0e96f-c539-4d0d-9431-cd757565f824" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/318d9442-21fb-4364-a000-7ebf7cb8104e" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Make sure all prerequisites pass, ignore the warning signs, Click Install
<p>
<img src="https://github.com/user-attachments/assets/19f9aca7-c007-4fa1-9c63-4538671ddbf4" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Once the installation is complete, you will be prompted with the following message, the VM will automatically sign out in 5-10 seconds depending in Internet speed
<p>
<img src="https://github.com/user-attachments/assets/439dc6be-88ce-4525-91a6-aad4628deeb1" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Enter in the password that was created for the domain
<p>
<img src="https://github.com/user-attachments/assets/c98f1966-a837-4bf3-8ba5-23271779600e" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Go to Server Manager, then click on Tools, you will see all of the features for Active Directory, along with others that was installed
<p>
<img src="https://github.com/user-attachments/assets/53391199-f405-4d90-a789-9dd5f0e1b78d" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />


# End of Project
