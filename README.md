# creating-vpn
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>

- Prerequisities: brain not necessary (just need ability to read and follow instructions), computer
- Install: Proton VPN
 <br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
 
<strong> Find IP address of your computer </strong><br>
1. Copy and paste this link - https://whatismyipaddress.com/ - into your url search bar <br>
2. On this page is your IP address <br>
<img width="959" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/95fe3a32-8435-41b1-8f5f-a38d74756f1b">
<br>
3. Write the IP address down somewhere <br>
//insert screenshot of notepad with IP address
<br>

<strong> Find IP address of a Virtual Machine (VM) </strong><br>
1. Create a VM and log into it<br>
2. Copy and paste this link - https://whatismyipaddress.com/ - into the url search bar of your VM <br>
<img width="960" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/07634a41-06a9-48ef-bdc9-f98d42da35e6">
<br>
3. Write the IP address down somewhere <br>
//insert screenshot of notepad with IP address
<br>

<strong> Find IP address of a Proton VPN </strong><br>
1. Close VM and sign up for a free version of Proton VPN at this link: https://account.protonvpn.com/signup?plan=free&language=en <br>  
2. Open VM and download Proton VPN <br>
Proton donwload page: <br>
<img width="959" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/322853c1-eaa5-4ddf-b2a4-35cf54a7b7e7"> <br>
3. Click download <br>
<img width="960" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/c389bf3e-9f78-4424-a96b-05eda756f15f">
<br>
4. Click open file <br>
<img width="275" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/e6a66064-8ab2-476a-8057-22c4e087e265">
<br>
5. Setup Language page, click "OK" <br>
<img width="268" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/f09c793a-68af-4c09-b056-60ee0ab4fb31">
<br>
6. Select Start Menu Folder page, click "Next" <br>
<img width="449" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/6f4c0da3-7928-4726-9351-2593779aab01">
<br>
7. Select Additonal Tasks page, click "Next" <br>
<img width="449" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/d293f684-3f85-4664-94c5-d94ca5e0eaae">
8. Ready to Install page, click "Install" <br>
<img width="449" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/c17f949a-95ea-401a-9dbf-31bbfc0dcf48">
<br>
Proton VPN login page: <br>
<img width="450" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/4ab36bdd-4adc-453a-9388-7c3bca794450">
<br>
If this pops up after you login, click the X in the top right hand corner or click "Skip" <br>
<img width="600" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/f02b622a-c4af-4431-81b4-1c0f90b69bf3">
<br>
Click "Quick Connect" <br>
<img width="720" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/1044caf9-b0f3-451b-ba92-096091d1c942">
<br>
Click "Change server" <br>
<img width="720" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/c822f7bf-ffdc-4a60-ab92-f9d7791b85e3">
<br>
You should be in different country now
<br>
Copy and paste this link - https://whatismyipaddress.com/ - into the url search bar <br>
<img width="960" alt="image" src="https://github.com/jaysixco/creating-vpn/assets/160427311/3faacf14-611c-4341-aec3-ad52a3e15c18">
<br>
6. Write the IP address down somewhere <br>
//insert screenshot of notepad with IP address <br>
7. For fun, try browsing to different sites like Google, Disney, Amazon, and/or Netflix to see if there's anything different about it. <br>
<br>
   
<strong> Lab Cleanup (DON’T FORGET THIS)</strong>

1) Close your Remote Desktop connection <br>
   - Leave the virtual machine by clicking the underscore sign (_) in the blue bar at the top of the screen (if you hover over it for a second, it should say minimize)

3) Delete the Resource Group(s) created at the beginning of this lab <br>
   - Click the Microsoft Azure search bar and then click "Resource groups" <br>
   - This is the Resource Group page: <br>
<img width="959" alt="Resource Group page" src="https://github.com/jaysixco/monitoring-traffic-rd/assets/160427311/01b696ba-831f-4d17-9ada-54e0b1cd5bcf"> <br>
  - Right click one of the 2 names and open it in a new tab  <br>
  - Click "Delete resource group" (see screenshot below, 1)  <br>
  - Click "Copy to Clipboard" (see screenshot below, 2)  <br>
  - Paste (ctrl + v) the name in the box (see screenshot below, 3)  <br>
  - Click "Delete" (see screenshot below, 4)  <br>
  - After you follow the steps above, repeat with the other name on the Resource group page <br>
![delete steps 1 - 4](https://github.com/jaysixco/monitoring-traffic-rd/assets/160427311/95060ea7-eba8-4b5f-89bb-aa1a32a80edf)

5) Verify Resource Group Deletion <br>
  - After doing the steps above, go to the Resources Group and wait until the groups disappear. You might have to refresh a few times. <br>
  - When you see "No resource groups to display" (see screenshot), you are good to go and can close the site. <br>
![no resources groups to display](https://github.com/jaysixco/monitoring-traffic-rd/assets/160427311/9726c274-9574-4b22-824f-5d5c283fd7cd)
<br>
</p>
