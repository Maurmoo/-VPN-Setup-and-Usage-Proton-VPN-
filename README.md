
<p align="center">
  <img src="https://github.com/user-attachments/assets/cf7db6b2-6e72-41ac-aab4-d1d0074b20cf" alt="image" />
</p>



<h1>Azure VM Creation and VPN Testing Lab</h1>
This tutorial walks you through creating a virtual machine (VM) in Azure, connecting to it, setting up a VPN, and testing the IP address and browsing behavior. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN
- Web Browsing

<h2>Operating Systems Used</h2>

- Windows 10

<h2>List of Prerequisites</h2>

- **Step 1**: Create and Configure the Azure VM
- **Step 2**: Record IP Address from the Azure VM
- **Step 3**: Sign Up for ProtonVPN
- **Step 4**: Install ProtonVPN in the Virtual Machine
- **Step 5**: Record IP Address from the VPN Connection
- **Step 6**: Browse Websites and Test VPN Effects
- **Step 7**: Document and Submit Findings

<h2>Installation Steps</h2>

<p>
  
## Step 1: Create and Configure the Azure VM

![image](https://github.com/user-attachments/assets/40726f37-8bba-4a42-94f8-78949e41791a)


</p>
<p>
  
-  Log in to the Microsoft Azure Portal.
- Navigate to Virtual Machines and click Create to set up a new VM.
- Select the following configurations for your VM:
  - Name: **AzureVM**
  - vCPUs: **2**
  - Username: **LabUser**
  - Password: **Password1234**
  - Logged into the VM using Remote Desktop. Public IP address
- After creation, click on the VM and locate its Public IP Address.
- Use Remote Desktop to connect to the VM
</p>
<br />

## Step 2: Record IP Address from the Azure VM
![image](https://github.com/user-attachments/assets/eeeca165-534c-422e-9e58-47c6a21e28a0)

<p>
  
- Logged into the Azure VM using Remote Desktop.
- Opened a browser inside the VM and visited
     - [What is My IP Address](https://whatismyipaddress.com/).
- Recorded the IP address associated with the VM.

</p>
<br />

## Step 3: Sign Up for ProtonVPN

<p>
  
![image](https://github.com/user-attachments/assets/e35d2e5c-ed67-4f85-b1fd-259525cfbd1f)


</p>
<p>
  
- Navigate to ProtonVPN Sign-Up and sign up for a free account.
   - [ProtonVPN Sign-Up](https://account.protonvpn.com/signup?plan=free&language=en).

- Follow the instructions to confirm your email address and activate your ProtonVPN account. 


</p>
<br />

## Step 4: Install ProtonVPN in the Virtual Machine

<p>
  
![image](https://github.com/user-attachments/assets/8a118e42-d75b-48f2-ab8d-c499e1f601da)


</p>
<p>
  
- Download the ProtonVPN client from the official website.
- Open the downloaded installer and follow the steps to install ProtonVPN in your Azure VM.
- After installation, launch ProtonVPN and log in using your credentials from **Step 3**
</p>
<br />

## Step 5: Record IP Address from the VPN Connection

<p>
  
![image](https://github.com/user-attachments/assets/fdbd53af-2b04-4f4a-9577-5fbb9ceae7db)



</p>
<p>
  
- Connect to a VPN server located in a different country (e.g., Japan).
- Once connected, [What is My IP Address](https://whatismyipaddress.com/) again to observe the new IP address.
- Record the new IP address assigned by ProtonVPN. 


</p>
<br />

## Step 6: Browse Websites and Test VPN Effects

<p>
  
![image](https://github.com/user-attachments/assets/yourimage7.png)

</p>
<p>
  
- After connecting to the VPN, browsed the following websites inside the VM:
  - [Google](https://www.google.com)
  - [Amazon](https://www.amazon.com)
  - [Disney](https://www.disney.com)
- Observed changes in website content based on VPN server location (e.g., different language, region-specific content).

</p>
<br />

## Step 7: Document and Submit Findings

<p>
  
![image](https://github.com/user-attachments/assets/yourimage8.png)

</p>
<p>
  
- Documented all findings in a text file:
  - Physical machine IP address
  - Azure VM IP address
  - VPN-connected IP address
  - Observations on website behavior (e.g., language, content changes)

</p>
<br />

## Conclusion

In conclusion, setting up a Virtual Machine in Azure and using ProtonVPN for IP address manipulation helps demonstrate the effects of location on internet browsing. By following the steps, you have learned to use VPNs to test how websites change based on geographic region. This lab enhances understanding of cloud computing, VPN usage, and internet privacy.

![Azure](https://img.shields.io/badge/Azure-Cloud-blue)
