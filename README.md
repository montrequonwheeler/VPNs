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
- Create a Resource Group
- Create a Windows 10 Virtual Machine in another geographic location (try a different country)
- Log into the VM with Remote Desktop
- Browse to https://whatismyipaddress.com/ and take note of this in a text file

<h2>Sign up for ProtonVPN and test the VPN connection</h2>

- On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en  
- Back within your VM, download the Proton VPN client
- Login to the VPN and choose a VPN server in yet another country (such as Japan)
- Browse to https://whatismyipaddress.com/  and take note of this in a text file
- Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different

<h2>Clean up Azure resources</h2>
- Delete the resource group you created in Step 2
- Ensure the resources/Resource Group has been deleted.
