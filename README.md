</p>

<h1>VPNs</h1>
This walkthrough focuses on gaining familiarity with VPNs.
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used</h2>

- Windows 10</b> (21H2)

<h2>Create Virtual Machine in Azure</h2>

- Browse to https://whatismyipaddress.com/ and take note of this in a text file
<img width="1440" alt="Screenshot 2023-07-25 at 8 47 03 PM" src="https://github.com/montrequonwheeler/VPNs/assets/127397594/05b53f38-ff29-4ed4-92fd-1b01859ec434">
- Create a Resource Group. You can create the virtual machine first and the resource group will be automatically created. 
<img width="1440" alt="Screenshot 2023-07-25 at 8 52 32 PM" src="https://github.com/montrequonwheeler/VPNs/assets/127397594/21f07a43-c4c2-4f3b-a4a9-47a1aa175b51">
- Create a Windows 10 Virtual Machine in another geographic location (try a different country)
<img width="1440" alt="Screenshot 2023-07-25 at 8 54 42 PM" src="https://github.com/montrequonwheeler/VPNs/assets/127397594/eb8d4cf7-f677-40a7-8156-ecf5e8d157f5">
- Log into the VM with Remote Desktop. Copy the IP Address and input the username and password created for VM. 
<img width="1440" alt="Screenshot 2023-07-25 at 9 04 19 PM" src="https://github.com/montrequonwheeler/VPNs/assets/127397594/9ac48992-c199-4c61-9b70-528cd51d3a25">
<img width="1440" alt="Screenshot 2023-07-25 at 9 03 49 PM" src="https://github.com/montrequonwheeler/VPNs/assets/127397594/73c924d6-9a4c-4f8f-b8a5-aa6b56a9f23e">
- Browse to https://whatismyipaddress.com/ and take note of this in a text file
<img width="1440" alt="Screenshot 2023-07-25 at 9 06 41 PM" src="https://github.com/montrequonwheeler/VPNs/assets/127397594/64d3ebec-425e-4e27-9364-7c1b0e76224b">

<h2>Sign up for ProtonVPN and test the VPN connection</h2>

- On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en instead of the VM incase of not being able to understand the languages of countries the VPN is using.
- Back within your VM, download the Proton VPN client
<img width="1440" alt="Screenshot 2023-07-25 at 9 16 03 PM" src="https://github.com/montrequonwheeler/VPNs/assets/127397594/527bee4a-4eb0-4d11-9260-4bb7a67f4d83">
- Login to the VPN and choose a VPN server in yet another country (such as Japan)
<img width="1440" alt="Screenshot 2023-07-25 at 9 19 28 PM" src="https://github.com/montrequonwheeler/VPNs/assets/127397594/13f2d0a9-d9f9-44c5-a002-fa2dea952e1d">
- Browse to https://whatismyipaddress.com/  and take note of this in a text file
<img width="1440" alt="Screenshot 2023-07-27 at 2 34 28 AM" src="https://github.com/montrequonwheeler/VPNs/assets/127397594/750da4c2-70b9-4234-97cc-353ef40baf5b">
- Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different
<img width="1440" alt="Screenshot 2023-07-25 at 9 25 20 PM" src="https://github.com/montrequonwheeler/VPNs/assets/127397594/a5ef82b8-ce22-49f1-8ae2-f3bd79a41967">

<h2>Clean up Azure resources</h2>
- Delete the resource group you created in Step 2
- Ensure the resources/Resource Group has been deleted.
