<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="Azure logo"/>
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
- **Step 2**: Record IP Address from Physical Machine
- **Step 3**: Create and Configure the Virtual Machine in Azure
- **Step 4**: Record IP Address from the Azure VM
- **Step 5**: Sign Up for ProtonVPN
- **Step 6**: Install ProtonVPN in the Virtual Machine
- **Step 7**: Record IP Address from the VPN Connection
- **Step 8**: Browse Websites and Test VPN Effects
- **Step 9**: Document and Submit Findings

<h2>Installation Steps</h2>

<p>
  
## Step 1: Create and Configure the Azure VM

![image](https://github.com/user-attachments/assets/yourimage1.png)

</p>
<p>
  
- Created a Windows 10 Virtual Machine on Azure with the following specifications:
  - Name: **AzureVM**
  - vCPUs: **2**
  - Username: **LabUser**
  - Password: **Password1234**
  - Logged into the VM using Remote Desktop. IP address: **20.106.188.26**

</p>
<br />

<p>
  
## Step 2: Record IP Address from Physical Machine
  
![image](https://github.com/user-attachments/assets/yourimage2.png)

</p>
<p>
  
- Opened the browser on the physical machine and visited [What is My IP Address](https://whatismyipaddress.com/).
- Recorded the displayed IP address in a text file.

</p>
<br />

<p>
  
## Step 3: Create and Configure the Virtual Machine in Azure
  
![image](https://github.com/user-attachments/assets/yourimage3.png)

</p>
<p>
  
- Created a new VM on Azure in a different geographic region (e.g., Japan or Central Europe).
- Configured a public IP address and ensured RDP was enabled.

</p>
<br />

## Step 4: Record IP Address from the Azure VM

<p>
  
- Logged into the Azure VM using Remote Desktop.
- Opened a browser inside the VM and visited [What is My IP Address](https://whatismyipaddress.com/).
- Recorded the IP address associated with the VM.

</p>
<br />

## Step 5: Sign Up for ProtonVPN

<p>
  
![image](https://github.com/user-attachments/assets/yourimage4.png)

</p>
<p>
  
- Signed up for the free version of ProtonVPN at [ProtonVPN Sign-Up](https://account.protonvpn.com/signup?plan=free&language=en).
- Created a ProtonVPN account and confirmed the email address.

</p>
<br />

## Step 6: Install ProtonVPN in the Virtual Machine

<p>
  
![image](https://github.com/user-attachments/assets/yourimage5.png)

</p>
<p>
  
- Downloaded and installed the ProtonVPN client inside the Azure VM.
- Logged into ProtonVPN using the credentials from Step 5.

</p>
<br />

## Step 7: Record IP Address from the VPN Connection

<p>
  
![image](https://github.com/user-attachments/assets/yourimage6.png)

</p>
<p>
  
- After connecting to a VPN server located in a different country (e.g., Japan), visited [What is My IP Address](https://whatismyipaddress.com/) again.
- Recorded the new IP address associated with the VPN server.

</p>
<br />

## Step 8: Browse Websites and Test VPN Effects

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

## Step 9: Document and Submit Findings

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
