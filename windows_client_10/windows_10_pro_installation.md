<h1>Installing and setting up Windows 10 Pro in VMware Workstation Pro</h1>
This project outlines the installation and set up of Windows10 Pro.<br />


<h2>Environments and Technologies Used</h2>

- VMware Workstation Pro (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 10 Pro

<h2>High-Level Deployment and Configuration Steps</h2>

- Install and set up Windows 10 Pro onto the VM
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
<img width="650" height="650" alt="image" src="https://github.com/user-attachments/assets/5d93fa76-394d-4eaa-b692-a45aa82d8a40" />
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


<br>
<br>

## Enabling the Administrator account
### After the installation has been completed, open File Explorer
<p>
<img width="510" height="388" alt="image" src="https://github.com/user-attachments/assets/4c10226d-6332-4971-b53b-f3e0077348db" />
</p>
<br />

### Right click on `This PC` then click Manage
<p>
<img width="1021" height="769" alt="image" src="https://github.com/user-attachments/assets/e539dddb-ebd8-4fe0-b7f0-f0761e9ffa8f" />
</p>
<br />

### Click on the `Local Users and Computers` drop down, click on `User`
<p>
<img width="1027" height="774" alt="image" src="https://github.com/user-attachments/assets/7b50f889-17fc-49ef-99d0-9e5b36386eb7" />
</p>
<br />

### Enable the `Administrator` account
<p>
<img width="1029" height="784" alt="image" src="https://github.com/user-attachments/assets/7ec457a7-4468-408d-bb94-10f1ea506b7b" />
</p>
<p>
<img width="1024" height="775" alt="image" src="https://github.com/user-attachments/assets/c2132e58-fc8e-495c-bdef-36c3a63fc2f5" />
</p>
<p>
<img width="1023" height="780" alt="image" src="https://github.com/user-attachments/assets/b8de5b22-2405-412e-9ce8-e8ca05cd74d3" />
</p>
<br />

### Set a password for the `Administrator` account
<p>
<img width="1030" height="778" alt="image" src="https://github.com/user-attachments/assets/2f905ae6-4fae-4e3a-98b6-88128dc44150" />
</p>
<p>
<img width="189" height="124" alt="image" src="https://github.com/user-attachments/assets/9be2b014-bf5e-48e8-a460-32995f51232a" />
</p>
<br />

### Sign out of the VM
<p>
<img width="1021" height="766" alt="image" src="https://github.com/user-attachments/assets/621ce87f-9b53-4741-b4b5-22689d526023" />
</p>


<br>
<br>


## Deleting the default User account
### Log in with the new Admin credentials
<p>
<img width="549" height="392" alt="image" src="https://github.com/user-attachments/assets/b9d1797e-2477-4826-ba09-2ebcbc5f8328" />
</p>
<br />

### Delete the default `User` account
<p>
<img width="987" height="708" alt="image" src="https://github.com/user-attachments/assets/d685dab4-35c4-4fd8-912b-72aa3ea9bfea" />
</p>
<br />


<br>
<br>


## Installing RSAT Tools
### Click on the Windows icon and type `optional features`, click on `Add or remove feature`
<p>
<img width="1026" height="772" alt="image" src="https://github.com/user-attachments/assets/ad336386-15f3-4da8-b398-058a98a92a16" />
</p>
<br />

### Click on `Add a feature`
<p>
<img width="1024" height="775" alt="image" src="https://github.com/user-attachments/assets/acb4bbe1-c27a-443c-b871-aff84b92e943" />
</p>
<br />

### Type in RSAT and install all tools provied by the company
<p>
<img width="337" height="326" alt="image" src="https://github.com/user-attachments/assets/5253d855-82c4-435e-94b7-b3c05dc01d75" />
</p>
<p>
<img width="678" height="630" alt="image" src="https://github.com/user-attachments/assets/29d18c12-b62e-4ef0-9557-53a8b7b0d7de" />
</p>
<br />

### After the installation, log out of the VM then log back in, click on the Windows icon, scroll down to `Windows Adminstrative Tools` to view the installed tools
<p>
<img width="1020" height="766" alt="image" src="https://github.com/user-attachments/assets/ea0dec89-e3cd-4ae9-aa54-596a2d482a06" />
</p>
<p>
<img width="502" height="367" alt="image" src="https://github.com/user-attachments/assets/dc5e634c-7dae-4e7c-bbe3-9ea776635171" />
</p>
<p>
<img width="1024" height="778" alt="image" src="https://github.com/user-attachments/assets/d322fd36-168c-421a-8d4e-23e188779b36" />
</p>
<br />

---

# End of Project

