<h1>My Virtual Playground: Home Lab Setup Using Virtual Machines</h1>

<h2>Description</h2>
I started my learning journey in Cybersecurity on Sep 23, mainly using learning platforms such as TryHackMe and HackTheBox. I have only used the machines provided by these websites and I felt that it was very limited. That is what got me thinking about building my own Homelab for myself so that I can not only have hands-on practice on configuring the machines, but also have a safe environment for me to poke around in. I decided that creating a Homelab using Virtual Machines (VM) would be the most cost-efficient for my current learning goals. This is my write-up of creating my Homelab using VM.
<br />


<h2>System Requiremnents</h2>

<b>Host Machine Specifications</b>

| Item                               | Specifications           |
| ---------------------------------- | -------------------------|
| OS Name                            | Microsoft Windows 10 Pro |
| Version                            | 10.0.19045 Build 19045   |
| Processor                          | AMD Ryzen 5 3600 6-Core Processor|
| RAM                                | 16 GB​                    |
| C Drive Storage                    | 512 GB                   |
| D Drive Storage                    | 1 TB​                     |

<h2>Virtualization Platform Setup</h2>

<div align="left">

1. The virtualization platform I used is VMware Workstation 16 Pro

   <img src="https://i.imgur.com/yn96A8v.png" height="40%" width="40%" alt="homelab"/>

2. After downloading, I launch the installer, continue clicking next, and accepted the license agreement

   <img src="https://i.imgur.com/ifl7H5D.png" height="40%" width="40%" alt="homelab"/> 
   <img src="https://i.imgur.com/j2HRLTn.png" height="40%" width="40%" alt="homelab"/>
   <img src="https://i.imgur.com/i1WK5ai.png" height="40%" width="40%" alt="homelab"/> 
   <img src="https://i.imgur.com/Ytdhdhc.png" height="40%" width="40%" alt="homelab"/>
   <img src="https://i.imgur.com/25EqBFM.png" height="40%" width="40%" alt="homelab"/> 

3. Use Google Dorks to get the license key for Workstation, and you are done.

   <img src="https://i.imgur.com/429t5zc.png" height="40%" width="40%" alt="homelab"/>

</div>

<div align="left">

4. I will be using Kali Linux as my primary VM, as it comes pre-installed with many cybersecurity tools.

   <img src="https://i.imgur.com/A3VzPSe.png" height="40%" width="40%" alt="homelab"/>

5. After download, extract files and locate the .vmx file, right click on it to open it with VMware Workstation

   <img src="https://i.imgur.com/qVow7Uo.png" height="40%" width="40%" alt="homelab"/> 

6. Power on the virtual machine and log in using the default credentials to complete the installation.

   <img src="https://i.imgur.com/gOUJH4y.png" height="40%" width="40%" alt="homelab"/>
   <br />
   <br />
   <img src="https://i.imgur.com/9GtJFl9.png" height="40%" width="40%" alt="homelab"/>

</div>

<div align="left">

7. As for the server environment, I have decided that it will run on Ubuntu, as it is widely used and is known for its stability. (I had no idea setting up the server environment is much more complicated 😥)

   <img src="https://i.imgur.com/0kFE5p0.png" height="40%" width="40%" alt="homelab"/>

8. After downloading from the website, run VMware Workstation and select "create new VM"

   <img src="https://i.imgur.com/LZ94GC7.png" height="40%" width="40%" alt="homelab"/> 

9. Select custom, click next, and next

   <img src="https://i.imgur.com/uj7jpLO.png" height="40%" width="40%" alt="homelab"/>
   <img src="https://i.imgur.com/gPI9txs.png" height="40%" width="40%" alt="homelab"/>

10. Select installer disc image file, and choose the downloaded Ubuntu file, click next. Give the VM a name, and choose the location for the VM.

   <img src="https://i.imgur.com/mMXF6kE.png" height="40%" width="40%" alt="homelab"/>
   <img src="https://i.imgur.com/XTZIFhP.png" height="40%" width="40%" alt="homelab"/>
    
11. Leave processor configuration as default, memory and 2GB and network type as NAT.

   <img src="https://i.imgur.com/fsQjnBU.png" height="40%" width="40%" alt="homelab"/>
   <img src="https://i.imgur.com/aW9qqta.png" height="40%" width="40%" alt="homelab"/>


12. Set network type as NAT and leave the default settings for I/O and disk type.

   <img src="https://i.imgur.com/Pu5mbf8.png" height="40%" width="40%" alt="homelab"/>
   <img src="https://i.imgur.com/yPn0do7.png" height="40%" width="40%" alt="homelab"/>

13. Create new virtual disk, give it 40GB storage.

   <img src="https://i.imgur.com/VHpZvpu.png" height="40%" width="40%" alt="homelab"/>

14. Default disk file location and click finish.

   <img src="https://i.imgur.com/UKfVE9x.png" height="40%" width="40%" alt="homelab"/>
   <img src="https://i.imgur.com/ngHF9Bz.png" height="40%" width="40%" alt="homelab"/>

15. Click enter to start installing Ubuntu Server. Language will be English.

   <img src="https://i.imgur.com/wr3sCb8.png" height="40%" width="40%" alt="homelab"/>
   <img src="https://i.imgur.com/uvMEj6S.png" height="40%" width="40%" alt="homelab"/>

16. Base for installation will be Ubuntu Server.

   <img src="https://i.imgur.com/X1rkfIG.png" height="40%" width="40%" alt="homelab"/>

17. IP can be assigned manually, but we will leave it to DHCP.

   <img src="https://i.imgur.com/X1rkfIG.png" height="40%" width="40%" alt="homelab"/>

18. Select use entire disk space, and fill in the basic information and credentials for the server.

   <img src="https://i.imgur.com/X1rkfIG.png" height="40%" width="40%" alt="homelab"/> <br />
   <img src="https://i.imgur.com/X1rkfIG.png" height="40%" width="40%" alt="homelab"/>

19. Install SSH server and finish installation

   <img src="https://i.imgur.com/X1rkfIG.png" height="40%" width="40%" alt="homelab"/>

20. Enter credentials to login! 

   <img src="https://i.imgur.com/X1rkfIG.png" height="40%" width="40%" alt="homelab"/>
    
</div>

