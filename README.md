# SOHO Network
-- Networking project --

## Requirements
- 1 Router
- 1 Switch
- 1 Server (Active Directory)
  - DHCP, DNS
- 2 End Device Clients

## Project Description
The goal of this project is to demonstrate ability to perform network configurations on a small scale such as a home lab, providing connectivity between all the users and users being a part of one domain controller. To complete this mini project I will be using GNS3 to create the network topology and configure network devices, and Oracle VirtualBox to configure and run virtual machines, specifically for the server and end users. 

## Outline
### Configure Virtual Machines
First step is to get our virtual machines ready. This will include needing the Windows Server 2022 image file, a Windows 11 image file, and for ease of creating the project, a GNS3 image. This git repo is not targeted to help configure a virtual machine since it also differs what specs you will give your virtual machine, so I will leave links here on how to set up your virtual machine if it is your first time.

-  Windows Server iso link: https://www.microsoft.com/en-us/evalcenter/download-windows-server-2022
-  Windows 10 workstation iso: https://www.microsoft.com/en-us/software-download/windows10
-  GNS3 VM: https://gns3.com/software/download-vm

- INSTALL GNS3 VM: https://www.youtube.com/watch?v=8VQ8eTmMtjQ&t=226s
- INSTALL WINDOWS SERVER on VM: https://www.youtube.com/watch?v=oGFJ1X7o0S8
- INSTALL WINDOWS 10 WORKSTATION on VM: https://www.youtube.com/watch?v=sBzL_zoYt6o

### Import To GNS3
Once the virtual machines are created, it is time to open up GNS3 and create the virtual machines as a new template. When creating a new template, if you used Oracle Virtualbox like me, open up Oracle VirtualBox VMs and search for your windows clients and servers. Configure each of these templates in the 'Network' tab and allow GNS3 to use any configured VirtualBox adapter' 
![image](https://github.com/Noah-Inocencio/Virtual-Home-Lab/assets/133866909/7e1ef19c-134d-4c3d-97c9-30824b0f6546)

### Create topology
This simple lab will also have a simple network topology as followed by the below image...
![image](https://github.com/Noah-Inocencio/Virtual-Home-Lab/assets/133866909/2d3e588f-8ec7-4b18-8d06-06dc5b005659)

![image](https://github.com/Noah-Inocencio/Virtual-Home-Lab/assets/133866909/59b7913b-ef54-48f9-b60f-1f120abfdb8c)
