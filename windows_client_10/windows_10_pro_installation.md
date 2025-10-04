<h1>Installing and setting up Windows 10 Pro in VMware Workstation Pro</h1>
This project outlines the installation and set up of Windows10 Pro.<br />


<h2>Environments and Technologies Used</h2>

- VMware Workstation Pro (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 10 Pro

<h2>High-Level Deployment and Configuration Steps</h2>

- Install and set up Windows 10 Pro onto the VM
- Create the `User` account without a password during the installation process
- Enable the `Administrator` account
- Set a seure password for the `Administrator` account
- Delete the `User` account to avoid any user logging in with admin rights
- Download the following RSAT tools:
    - RSAT: Active Directory Certificate Services ToolsActive Directory Certificate Services Tools
    - RSAT: Active Directory Domain Services and Lightweight Directory Services Tools
    - RSAT: DHCP Server Tools
    - RSAT: DNS Server Tools
    - RSAT: Group Policy Management Tools
    - RSAT: Remote Desktop Services Tools

<br />


<h1>Deployment and Configuration Steps</h1>

## Installing and setting up Windows Pro 10
### Go to a search browser and type in the following `windows 10 bootable usb` choose the highlighed link
<p>
<img width="1668" height="946" alt="image" src="https://github.com/user-attachments/assets/5d93fa76-394d-4eaa-b692-a45aa82d8a40" />
</p>
<br />

### Scroll down to the `Create Windows 10 Installation media`, then click Download Now, once the download is complete, click on the exe file
<p>
<img width="1918" height="951" alt="image" src="https://github.com/user-attachments/assets/e82a3657-fae2-474a-9765-b79a9adff549" />
</p>
<p>
<img width="1338" height="745" alt="image" src="https://github.com/user-attachments/assets/b03bd4d8-f2ac-46ca-ad5c-7756804b6aac" />
</p>
<br />

### Accept the license terms to move forward with the installtion
<p>
<img width="997" height="859" alt="image" src="https://github.com/user-attachments/assets/4dcfd73e-a6fb-4ab3-be65-3e3334af34af" />
</p> 
<br />

### Choose the second option, this will give the option to download either a DVD, usb flash drive or a ISO file
<p>
<img width="997" height="859" alt="image" src="https://github.com/user-attachments/assets/0d8cb0c9-b120-41a0-8317-1fb7021b70e7" />
</p>
<br />

### Leave the checkbox checked, as the recommended options fit the standard installtion for the company
<p>
<img width="996" height="852" alt="image" src="https://github.com/user-attachments/assets/8a291e69-4c03-4bb1-9121-0b2d28dd79f6" />
</p>
<br />

### Choose the `ISO file` option to get the ISO file for the VM that will be created later on
<p>
<img width="994" height="853" alt="image" src="https://github.com/user-attachments/assets/4d9eb245-e72d-4807-9522-1edc95641706" />
</p>
<br />

### Choose a file path to store the ISO file
<p>
<img width="470" height="352" alt="image" src="https://github.com/user-attachments/assets/76b90de7-7a62-4c89-9e09-38f8ceda05c2" />
</p>
<br />

### Create a new VM
<p>
<img width="1918" height="1012" alt="image" src="https://github.com/user-attachments/assets/d47e4623-54c1-4326-91d5-4eae751ab043" />
</p> 
<p>
<img width="637" height="625" alt="image" src="https://github.com/user-attachments/assets/95ea9f7a-dbcf-4b91-aa1d-e320cb78a317" />
</p> 
<p>
<img width="637" height="625" alt="image" src="https://github.com/user-attachments/assets/f19d3eb7-d723-4926-a7a0-36e78843c533" />
</p> 
<br />

### Choose the Microsoft Windows operating system, along with the version as Windows 10, Click Next
<p>
<img width="634" height="622" alt="image" src="https://github.com/user-attachments/assets/61e53933-92a7-43d6-a58c-bebdd0259363" />
</p>
<br />

### Name the VM according to the company diagram, Click Next
<p>
<img width="633" height="624" alt="image" src="https://github.com/user-attachments/assets/cfc4c5f7-61c9-418e-9ff2-a122ab33e351" />
</p>
<br />

### Give the VM the proper amount of storage, and store the virtual disk in a single file, click Next
<p>
<img width="639" height="616" alt="image" src="https://github.com/user-attachments/assets/3361662e-30d8-4509-bf3a-5d95e3c6fc65" />
</p> 
<br />

### Verify the virtual hardware settings, click Finish
<p>
<img width="640" height="624" alt="image" src="https://github.com/user-attachments/assets/c9f9d75b-cf89-4b2d-8cbe-c884bed222eb" />
</p> 
<br />

### On the newly created VM, click on `Edit virtual machine settings`
<p>
<img width="1918" height="1012" alt="image" src="https://github.com/user-attachments/assets/c158c086-8c37-4e73-abb5-1348ce33ebf4" />
</p> 
<br />

### Give the proper amount of memory to the VM, I will allocate 8GB of RAM to the following VM
<p>
<img width="1117" height="691" alt="image" src="https://github.com/user-attachments/assets/fbc3930c-7d41-4bf7-a1ea-eab749e72884" />
</p> 
<br />

### Insert the ISO image to the VM, then click OK
<p>
<img width="1117" height="498" alt="image" src="https://github.com/user-attachments/assets/1644a7e9-9f79-4dc9-a730-931018152a30" />
</p>
<br />

### Power on the VM
<p>
<img width="1918" height="1012" alt="image" src="https://github.com/user-attachments/assets/4491f3de-b4f0-4c62-b7fb-6adc731ac600" />
</p>
<br />

### Based on the company standards, the language will stay as English, click Next
<p>
<img width="308" height="227" alt="image" src="https://github.com/user-attachments/assets/798f71a8-4340-4b59-9ec5-2d62600535bd" />
</p>
<br />

### Click Install Now to being the installation of the operating system
<p>
<img width="310" height="227" alt="image" src="https://github.com/user-attachments/assets/7bb03028-56b7-47ef-a06d-360bec7b6f3e" />
</p> 
<br />

### A product key is not required for the following VM based on the company
<p>
<img width="637" height="481" alt="image" src="https://github.com/user-attachments/assets/7551a74c-31e5-4bb3-944b-d222929e1230" />
</p>
<br />

### In order for the machine to be joined to the domain, the version that will be choes is Windows 10 Pro, click Next
<p>
<img width="319" height="239" alt="image" src="https://github.com/user-attachments/assets/bae4bf18-f6ca-425e-b989-933f00185935" />
</p>
<br />

### Accept the license terms, click Next
<p>
<img width="637" height="475" alt="image" src="https://github.com/user-attachments/assets/4b320e04-908d-4cb3-a702-a15e04fc7327" />
</p>
<br />

### Since this is a new virtual machine being installed, I will choose the option to install Windows only, click Next
<p>
<img width="639" height="474" alt="image" src="https://github.com/user-attachments/assets/1158f2a9-5d4a-49b0-b0d1-9072d215134f" />
</p>
<br />

### Select the driver with the storage that was added from the creation of the VM, click Next
<p>
<img width="639" height="478" alt="image" src="https://github.com/user-attachments/assets/0dcc8e4b-f5ff-451b-b256-fe3f53fceea0" />
</p>
<br />

### Select the United States as the region, click Yes
<p>
<img width="514" height="389" alt="image" src="https://github.com/user-attachments/assets/ef97c4ba-366f-444b-b922-7c9e08cd5547" />
</p>
<br />

### Select US as the keyboard layout, click Yes
<p>
<img width="514" height="386" alt="image" src="https://github.com/user-attachments/assets/a203dd2b-cd06-4941-b043-0b360595e065" />
</p>
<br />

### Click Skip
<p>
<img width="518" height="389" alt="image" src="https://github.com/user-attachments/assets/7a619cc8-8e24-4f93-a32d-30424d6a5452" />
</p>
<br />

### Select Personal Use, Click Next
<p>
<img width="1177" height="837" alt="image" src="https://github.com/user-attachments/assets/c936b899-6e50-4a74-bfb8-ac8812fd97ad" />
</p> 
<br />
<img width="1030" height="768" alt="image" src="https://github.com/user-attachments/assets/dc450db5-f9c8-4272-8975-215e86408c4a" />


### Choose `Role-based or featured-based installation` then click Next
<p>
<img width="1176" height="834" alt="image" src="https://github.com/user-attachments/assets/9df3097a-7024-4f78-8221-a5e4cfae76d5" />
</p>
<br />

### Choose `Select a Server from the server pool` then click Next
<p>
<img width="1177" height="841" alt="image" src="https://github.com/user-attachments/assets/5d2f9203-58d7-4792-b525-6d593b3d2bb0" />
</p>
<br />

### Click on the check box for `Active Directoy Domain Services`, click Add Features in the `Add Roles and Features Wizard` window, then click Next
<p>
<img width="1176" height="838" alt="image" src="https://github.com/user-attachments/assets/e7d7cc13-fab5-41d9-b135-f3c0d3d0fdcb" />
</p>
<p>
<img width="1176" height="835" alt="image" src="https://github.com/user-attachments/assets/49e1b215-18b5-4fe2-9dcd-279b0cbd9030" />
<p>
<img width="1174" height="835" alt="image" src="https://github.com/user-attachments/assets/c4f1da28-5f2f-4979-acaa-a75beeeeb90e" />
</p>
<br />

### Make sure that Group Policy Management is checked then click Next
<p>
<img width="1174" height="837" alt="image" src="https://github.com/user-attachments/assets/e9ed2933-c5bf-4be8-be24-0e9b1350d45e" />
</p>
<br />

### Click Next
<p>
<img width="1174" height="835" alt="image" src="https://github.com/user-attachments/assets/61ba355c-c34d-4aae-a1ba-a295e53ada50" />
</p>
<br />

### Click Install after review all of the Roles and Features
<p>
<img width="1171" height="835" alt="image" src="https://github.com/user-attachments/assets/9adcd166-f666-4a66-a6d0-4f32a5a85513" />
</p>


<br>
<br>


## Promoting the server as a Domain Controller
### Once the installation for AD DS has been completed click on `Promote this server to a domain controller`
<p>
<img width="1174" height="837" alt="image" src="https://github.com/user-attachments/assets/d72e8d4a-662b-4f36-ba59-915d9dc9b9ac" />
</p>
<br />

### Under `Select the deployment operation` choose `Add a forest`, then provide a domain name, in this case I will use `kevtech.com` as the domain name, then click Next
<p>
<img width="1138" height="835" alt="image" src="https://github.com/user-attachments/assets/69981208-841b-4cf2-a676-32a2c49159c1" />
</p>
<br />

### Be sure to keep the `Forest Function Level` and `Domain Function Level` set to Windows Server 2016, and enter a secure password for the domain, then click Next
<p>
<img width="1138" height="838" alt="image" src="https://github.com/user-attachments/assets/0176795b-55ea-4455-b084-93dbb2fcf9f7" />
</p>
<br />

### Click Next
<p>
<img width="1141" height="835" alt="image" src="https://github.com/user-attachments/assets/c2268666-6b27-4cd2-a72a-d68802759c2b" />
</p>
<br />

### The NetBIOS domain name will appear as the domain name without the `.com`, click Next
<p>
<img width="1146" height="847" alt="image" src="https://github.com/user-attachments/assets/845f9261-d839-40d5-880d-3d699868e242" />
</p>
<br />

### Click Next
<p>
<img width="1141" height="835" alt="image" src="https://github.com/user-attachments/assets/228e9940-d79a-429d-ab0a-81cb1558f0a1" />
</p>
<br />

### Click Next
<p>
<img width="1140" height="837" alt="image" src="https://github.com/user-attachments/assets/9d62b577-753b-4dad-9a4d-e5deec16d506" />
</p>
<br />

### Make sure all prerequisites pass, ignore the warning signs, Click Install
<p>
<img width="1138" height="838" alt="image" src="https://github.com/user-attachments/assets/ce89f1ec-25fc-4a62-999c-573e333b82f6" />
</p>
<br />

### Once the installation is complete, you will be prompted with the following message, the VM will automatically sign out in 5-10 seconds depending in Internet speed
<p>
<img src="https://github.com/user-attachments/assets/439dc6be-88ce-4525-91a6-aad4628deeb1" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Enter in the password that was created for the domain
<p>
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/8f4a994c-9b67-493b-9964-7993d8c71d54" />
</p>
<br />

### Go to Server Manager, then click on Tools, you will see all of the features for Active Directory, along with others that was installed
<p>
<img src="https://github.com/user-attachments/assets/53391199-f405-4d90-a789-9dd5f0e1b78d" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

---

# End of Project







